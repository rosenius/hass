### Lokal repo för hass, mm.

Detta är en lokal repo jag gjort för att säkra upp min Hass-installation samt att fixa till så att det blir enklare att fixa till när något blir fel eller ändras plötsligt.

### Home Assistant

Ip: 192.168.1.172
Port: 8123 (lokalt) 443 (externt) 

### Node-red

Ip: 192.168.1.172
Port: 1880

### Mqtt (mosquttio)

Ip: 192.168.1.172
Port: 1884

Lokala data (på virtuella maskinen)
/var/lib/docker/volumes/mosquitto_config/_data

Plats för passwd (docker)
/etc/mosquitto/passwd
(kommando för ny användare mosquitto_passwd -c /etc/mosquitto/passwd (användarnamn)


### Portainer

Ip: 192.168.1.172
Port: 9000