1.nedēļa 21.-28. aprilis.

plāns.
izveidot durvju zvanu kas būs savienot ar raspberry pi un nodods ienākošās ziņas tālāk uz web saitu kur tu varēsi to redzēt jebkurā vietā kur tu būtu.

Darba plāns.

izveidot kodu python durvju zvanam.

izveidot web saiti.

izveidot prototipu durvju zvanam un savienot ar raspberry.

savienot visus kopā lai strādātu un funkcionetu secīgi.


pa šīm brīvdienām esmu izveidojis kodu durvju zvanam :

import RPi.GPIO as GPIO

from time import sleep

GPIO.setmode(GPIO.BCM)

GPIO.setup(18, GPIO.IN, pull_up_down=GPIO.PUD_UP)

while True:

input_state = GPIO.input(18)

if input_state == False:

print ("The button works!")

sleep(0.1)



1-15 maijam

komanda:Mtiss 
komandas nosaukums-zvans
saja projekta velos izveidot zvanu ar raspberry palidzibu kas spetu dot majas ipasniekam zinu , kad pie durvim kads zvana
un velas tikt ieksa. si doma man piesaistija jo uzskatu ka tas ir vajadzigs katrai majai. tas palidzetu cilvekiem kuri iezi celo ,strada darza vie citas iestades un vienkarsi kurliem cilvekiem.
mans plans: izveidot durvu zvanu kas nosutitu zinu uz telefona aplikaciju.

![Untitled.png](Untitled.png)

![hatsApp Image 2019-05-15 at 21.53.44.jpeg](hatsApp Image 2019-05-15 at 21.53.44.jpeg)
