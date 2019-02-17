# RAK2245-Yodiwo Gateway
ttn_gateway based on the latest SX1301 driver [lora_gateway](https://github.com/Lora-net/lora_gateway) v5.0.1 and semtech [packet_forwarder](https://github.com/Lora-net/packet_forwarder) v4.0.1  


##	Installation procedure

step1 : Download and install [Raspbian Stretch LITE](https://www.raspberrypi.org/downloads/raspbian/) 

step2 : Use command "sudo raspi-config", choose "Interfacing Options", enable spi and i2c interface

      $ sudo raspi-config

step3 : Clone the installer and start the installation

      $ git clone https://github.com/sm6uax/yodiwo-gatewayv2.git ~/yodiwo-gateway
      $ cd ~/yodiwo-gateway
      $ sudo ./install.sh

step4 : Next you will see some messages as follow. Just hit the Enter key to keep default or enter your information if you want.

      Host name [rak-gateway]:
      Latitude [0]: 
      Longitude [0]: 
      Altitude [0]: 
    
step4 : Now you have a running gateway after restart!
