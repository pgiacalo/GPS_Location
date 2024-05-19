# GPS_Location
- Spreadsheet <b>GPS\_UBLOX\_NEO\_M8N\_Jitter\_Free\_Frequencies.csv</b> contains a list of all the frequencies that a UBLOX GPS unit can output without jitter. 

> The spreadsheet contains the frequencies that divide evenly into the 24MHz oscillator's frequency. 

- The output frequency of UBLOX GPS units can be adjusted using UBLOX's <b>U-Center</b> desktop application (for Microsoft Windows). Download it from their website, launch the application and attach the GPS unit to your PC.

- See a screen capture of the U-Center GUI screen (<b>UBLOX\_UCenter\_GUI\_Screen.jpg</b>)

- Here are the steps needed to configure the output frequency via the U-Center application:


1. Select the COM port and Connect to the GPS
2. MENU -> View -> Configure -> TP5 (Timepulse 5)
3. Set Frequency & Frequency Locked to (say) 10000000 Hz
4. Set Duty & Duty Locked to 50 
5. Menu -> Receiver -> Save (this saves to Flash memory)



