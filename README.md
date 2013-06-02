Box1: "mixer"
=============

Bare Features:

- 2x spdif in (stereo signale verstehen reicht), galv.g.
- 1x stereo xlr out
- eth in -> arm modul, erzeugt auch audio
- => 3 stereo channels: spdif1, spdif2, arm
- alle channels koennen gleichzeitig audio anliefern. muss gemischt werden, mit von cpu einstellbaren volume (auch: off).
- gemischtes signal soll dann auch variabel regelbar und abschaltbar sein. (cpu kontrolliert wieder)
- gemischtes signal in die cpu zurueckfeeden

options:

- mehr spdif
- analog in

-----

Box2: "remote control + headphones out"
=======================================

- box2 braucht box1, aber box1 muss ohne box2 funktionieren

- drehknopf1 = volume control box1, schalter1 = mute box1, mute-led1
- drehknopf2 = volume control headphones, schalter2 = mute headphones, mute-led2
- eth in -> arm -> headphones
- headphones amp(?)

options:
- alternativ: touch(?) buttons + color lcd fuer channel select, mute


-----

Komponenten:

- ARM: RaspPi (Demo purposes), ital. ARM/Atmel Modul?
