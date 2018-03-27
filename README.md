# config_wifi_raspberry_2_model_b
Configuracion de wifi con Nanoadaptador USB Wireless N DWA-131 E1

a) Identificando Kernel y número de Build en consola de la raspberry pi::: [uname -a]
resultado ::: Linux raspberrypi 4.1.20-v7+ #862 SMP Sat Mar 19 20:37:37 GMT 2018 armv7l GNU/Linux

En mi caso el Kernel es::: [4.1.20-v7] y el Build ::: [862]

b) Buscar el driver en la siguiente ruta, descargarlo y pegarlo en alguna ruta de tu raspberry pi:::
http://downloads.fars-robotics.net/wifi-drivers/8192eu-drivers/

El mio era el::: 8192eu-4.1.20-v7-862.tar.gz

c) Desempaquetar con el siguiente comando en consola:::
tar xzf 8192eu-4.1.20-v7-862.tar.gz

d)Instalar el driver desde consola con el siguiente comando:::
./install.sh

e) Debera salir mensaje exitoso, y reiniciar con el comando en consola::: reboot

f) Al iniciar, en la parte superior derecha debera aparecer la opcion para conectarse a redes wifi

Recursos:::
https://eu.dlink.com/es/es/products/dwa-131-wireless-n-nano-usb-adapter
https://blog.dickwyn.xyz/2015/06/28/setting-up-d-links-dwa-131-e1-nano-wi-fi-adapter-to-work-with-raspbian/
http://downloads.fars-robotics.net/wifi-drivers/8192eu-drivers/
