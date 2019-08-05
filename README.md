# [hass_tts_homely]
Vietnamese multi voice Text to speech for [Home Assistant](https://home-assistant.io/)
Extenting google transtalte for TTS function of HASS that Support Vietnamse voice from FPT speech
## Setup:
Download folder to: <config dir>/custom_components/
Edit the configuration:
Get FPT speech api: [https://console.fpt.ai](https://console.fpt.ai)
Replace the api_key in the config
Replace voice_type to change vietnamese voice
##
```
tts:  
  - platform: tts_homely      
    language: 'vi'
    api_key: 'XXXX'
    speed: '-2'
    #nam_mien_bac nu_mien_bac nu_mien_nam nu_hue
    voice_type: 'nu_mien_nam'
```
