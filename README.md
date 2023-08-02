# klipper-e3s1-skrat
Configurations Klipper:
- base imprimante: Ender3-S1,
    - rails linéaires axe X et Y
    - renforts structure 
- carte BTT SKRat en remplacement de la carte originelle «défunte»
    - TMC 2209 UART
    - sensorless homing axes X et Y
    - à venir :
        - CAN bus EBB46 (tête Sprite)
- BTT UPS 24V ajouté pour palier aux micro-coupures de courant (l'imprimante est déjà derrière un onduleur)
- écran simple (BTT mini12864)

Klipper installé (MainsailOS) sur un Raspberry Pi4 (2Go), écran tactile 7" BTT
