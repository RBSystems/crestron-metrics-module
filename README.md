# crestron-metrics-module
Reporting system usage via a series2/3-compatible module

### Current Simpl Windows configuration

#### MakeStringPermanent symbol
![Image of MakeStringPermanent symbol](https://raw.githubusercontent.com/byuoitav/crestron-metrics-module/master/makeStringPermanent.png)
- Size: 256d
- Signals
  - devBuilding[8]
  - devFloor[2]
  - devLatitude[11]
  - devLongitude[11]
  - devRoom[16]
  - dmpsHostName[32]
  - dmpsIp[15]
  - dmpsMACAddr[18]
  - InputLabel1[30]
  - InputLabel2[30]
  - InputLabel3[30]
  - InputLabel4[30]
  - InputLabel5[30]
  - InputLabel6[30]
  - InputLabel7[30]
  - sessionId[256]
  - volumeLevel[4]

#### Metrics symbol
![Image of Metrics symbol](https://raw.githubusercontent.com/byuoitav/crestron-metrics-module/master/metrics.png)
- Signals:
  - DIGITAL INPUTS:
    - Audio_Only_Press
    - clientConnected
    - Confirm_System_Off
    - Help_Menu_Press
    - Home_button
    - Program_Volume_Down
    - Program_Volume_Slider_Press
    - Program_Volume_Up
    - Select_AV_Jack
    - Select_Blank
    - Select_BluRay
    - Select_Device_Control_Bluray
    - Select_Device_Control_IPTV
    - Select_HDMI_Cable
    - Select_HDMI_Jack
    - Select_IPTV
    - Select_Local_Input
    - Select_PA_Control
    - Select_Remote_Input1
    - Select_Remote_Input2
    - Select_VGA_Cable
    - Startup_press
    - systemReady
  - STRING INPUTS
    - devBuilding[8]
    - devFloor[2]
    - devLatitude[11]
    - devLongitude[11]
    - devRoom[16]
    - dmpsHostName[32]
    - dmpsIp[15]
    - dmpsMACAddr[18]
    - InputLabel1[30]
    - InputLabel2[30]
    - InputLabel3[30]
    - InputLabel4[30]
    - InputLabel5[30]
    - InputLabel6[30]
    - InputLabel7[30]
    - sessionId[256]
    - volumeLevel[4]
  - BUFFER INPUTS
    - clientBuffer[100]
  - DIGITAL OUTPUTS
    - clientConnected
  - STRING OUTPUTS
    - toDevBuilding
    - toDevRoom
    - toDevFloor
    - toDevLat
    - toDevLon
    - toClientBuffer
    - storeSessionId
