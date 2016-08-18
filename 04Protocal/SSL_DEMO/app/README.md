First you inpress you own WIFI SSID and key to the defination "SSID" and "PASSWORD", int the file "ESP8266_RTOS_SDK\openssl_demo\include\user_config.h"

If you want to test the openSSL client demo:
1. you should use the defination "#define DEMO_CLIENT" int the file "ESP8266_RTOS_SDK\openssl_demo\programs\openssl_demo.c". 
2. you should load the firmware
3. you can see it will download the "www.baidu.com" main page and print the context
    
IF you want to test the openSSL client demo: 
1. You should not use the defination "#define DEMO_CLIENT" int the file "ESP8266_RTOS_SDK\openssl_demo\programs\openssl_demo.c".
2. You should load the firmware and start your IE of microsoft. 
3. You should input the context of "https://192.168.17.128", the IP of your module may not be 192.168.17.128, you should input your module's IP
4. You may see that it shows the website is not able to be trusted, that you should select that "go on visit it"
5. You should wait for a moment until your see the "hello word" in your IE page