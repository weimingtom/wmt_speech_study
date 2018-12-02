# wmt_speech_study
My speech recognition study, include Raspberry Pi

## 1. Hardware, Input Devices  

### (1.1) Seeed, ReSpeaker_2_Mics_Pi_HAT, WM8960    
* http://wiki.seeedstudio.com/cn/ReSpeaker_2_Mics_Pi_HAT/  
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

## 2. Software, python    

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
