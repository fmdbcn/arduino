# Instruccions per compilar la versió d'ESPurna

1. Baixat espurna-1.13.0.
2. Descomprimeix-lo en qualsevol ubicació, p.ex. C:\kk\
3. Obre des de l’Arduino IDE l’sketch C:\kk\espurna-1.13.0\code\espurna\espurna.ino
4. Compila i puja per la placa **nodeMCU**
5. Un cop pujat el firmware, obre el serial monitor, a 115200 bps i Ambdos  NL & CR.
6. Configura via serial el nou password d’administrador: `set adminPass 'psw_admin'`
7. Configura les credencials wifi ssid: `set ssid0 'nom_wifi'` password:  `set pass0 'psw_wifi'`
8. Reseteja el wifi de l’esp8266: `reset.wifi`
