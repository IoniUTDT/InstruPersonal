22/8

Voy a usar un enviroment para todas las practicas, se llama Instru

Creo un repositorio grupal con la cuenta publica es https://github.com/IoniUTDT/InstruGrupal
Cree un repo personal https://github.com/IoniUTDT/InstruPersonal

El objetivo inmediato es buscar en internet como manipular la entrada/salida de audio.

Despues de buscar un poco encontramos que lo importante parece ser tener acceso a PortAudio que es algo asi como la placa. Hay dos librerias que parece tenerlo:

PyAudio http://people.csail.mit.edu/hubert/pyaudio/
Python-sounddevice https://python-sounddevice.readthedocs.io/en/0.3.11/index.html

Vamos a tratar de usar el PyAudio

Probe usar el PyAudio y no funciona, no reconoce ningun dispositivo (17:51)

Vamos a probar al Python-sounddevice

Tampoco detecta ningun dispositivo (18:36)

Vamos a probar usar pygame como ultimo intento, sino lo pruebo en la compu de casa o en la de agus para la proxima.

26/8/18

Al final durante la clase pygame funciono en la laptop, pero tiene un mixer que solo reproduce audio pero no graba del microfono y no logramos rastrear que usaba internamente. Termino la clase y quedo pendiente solucionar el problema de comunicacion con el dispositivo. 

Hoy probe hacer lo mismo en otra laptop completamente diferente que lo unico que comparten es el sistema operativo (Linux Mint 18) y tampoco pude detectar la placa ni con PyAudio ni con SoundDevice, por lo que asumo que es un tema de compatibilidad con el operativo. En mi compu de escritorio si pudelo hacer anda inmediatamente y sin dificultades SoundDevice pero esta compu no la puedo usar para hacer mediciones por lo que no sirve como solucion definitiva. Voy a empezar a desarrollar el soft aca y mientras tanto el plan es ver si la compu de Agus corre bien el soft o sino instalar windows en una particion de mi compu mas vieja que es la que tiene entrada y salida de audio. 

27/8/18

14:45

Agus logro instalar el sounddevice en su compu y anda, yo puedo hacer los test remotos desde mi compu portatil a mi PC en casa. Si medimos con la compu de ella podemos seguir adelante.

Deberiamos juntarnos a aprender a usar Git