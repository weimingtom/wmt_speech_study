# wmt_speech_study
My speech recognition study, include Raspberry Pi  

## Ref  
* https://github.com/weimingtom/wmt_ai_study  

## 1. Hardware, Input Devices  

### (1.1) Seeed, ReSpeaker_2_Mics_Pi_HAT, WM8960    
* http://wiki.seeedstudio.com/cn/ReSpeaker_2_Mics_Pi_HAT/  
* https://www.yahboom.com/study/ReSpeaker_Pi  
* https://github.com/respeaker/seeed-voicecard  
* aplay -l  
* arecord -l  
* audacity  
* alsamixer  

### (1.2) Waveshare, WM8960_Audio_HAT  
http://www.waveshare.net/wiki/WM8960_Audio_HAT  
http://www.waveshare.net/wiki/WM8960_Audio_Board  

### (1.3) Waveshare, VS1003  
http://www.waveshare.net/wiki/VS1003B_MP3_Board  

### (1.4) Waveshare, Music_Shield, VS1053B    
http://www.waveshare.net/wiki/Music_Shield  

### (1.5) Seeed, Music_Shield_V2.2  
http://wiki.seeedstudio.com/cn/Music_Shield_V2.2/  
https://github.com/jdkoftinoff/jdksmidi  
https://github.com/Seeed-Studio/Music_Shield  

### (1.6) 信泰微, VS1053模块    
VS1053模块 MP3模块开发板 解码板 板载录音功能  

### (1.7) 优信 / 信泰微, 科大讯飞, XFS5152CE  

### (1.8) 信泰微, ICRoute, LD3320 / LD3321  
http://www.icroute.com  

### (1.9) waveshare, LD3320  
http://www.waveshare.net/wiki/LD3320_Board  
http://www.waveshare.net/wiki/LD3320_Board_(B)  

### (1.10) 51人工智能, 适用于树莓派 raspberrypi 2/3B+ 麦克风话筒USB免驱音质高清低噪     
(search baidupan) 树莓派麦克风教程.docx  

### (1.11) seeed, Azure IoT Edge    
https://github.com/Azure-Samples/azure-iot-starter-kits/tree/master/seeed  
https://github.com/Azure-Samples/azure-iot-starter-kits/tree/master/seeed/3-speech-recognizer/modules/speech-to-text  

## 2. Software, Raspberry Pi, Python    

### (2.1) Smart_fan.py  
https://github.com/SeeedDocument/MIC_HATv1.0_for_raspberrypi/blob/master/src/baidu_STT/Smart_fan.py  
https://console.bce.baidu.com/ai/?fromai=1#/ai/speech/overview/index  
sudo apt install mpg123  
sudo apt-get install portaudio19-dev  
(for pyaudio)  
pip install baidu-aip monotonic pyaudio  
cd src/baidu_STT  
nano Smart_Fan.py  
(for APP_ID, API_KEY, SECRET_KEY)  
python Smart_Fan.py  
http://wiki.seeedstudio.com/cn/ReSpeaker_2_Mics_Pi_HAT/  
https://www.yahboom.com/build.html?id=1790&cid=230  

## 3. SoftWare, PC  
* AutoPiano  
https://github.com/WarpPrism/AutoPiano  

## 4. Software, Raspberry Pi  
* 手把手教你做树莓派语音识别，文本变语音  
http://www.jackxiang.com/post/7637/  
https://github.com/weimingtom/wmt_rpi_study/tree/master  
