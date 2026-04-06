# ESPHome
Projeto de Automação Residencial
na linha 30: coloqueio um botão para ligar a TV da sala, mas a TV tem limitações no Firmware/Hardware, não ligando por Wake-On-lan:
button:
  - platform: wake_on_lan
    name: "Ligar TV Samsung"
    target_mac_address: FC:03:9F:0F:03:BF
