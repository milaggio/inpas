Install Java

sudo apt install default-jre


sudo chmod 777 service.sh

sudo ./service.sh install


В каталоге «/usr/local/bin» должны появиться ссылки на jar-файлы «dcupdater.jar»,
«dccontrol.jar», «dcconsole.jar».


java -jar dccontrol.jar


systemctl status dualconnector

systemctl start dualconnector
