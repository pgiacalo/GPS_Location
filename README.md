# GPS_Location
- Spreadsheet <b>GPS\_UBLOX\_NEO\_M8N\_Jitter\_Free\_Frequencies.csv</b> contains a list of all the frequencies that a UBLOX GPS unit can output without jitter. 

>> The spreadsheet contains the frequencies that divide evenly into the GPS Unit's 24 MHz oscillator frequency. 

- The output frequency of UBLOX GPS units can be adjusted using UBLOX's <b>U-Center</b> desktop application (for Microsoft Windows). Download it from their website, launch the application and attach the GPS unit to your PC (via USB).

- Here are the steps needed to configure the output frequency via the U-Center application:
> See the screen capture of the U-Center GUI screen (<b>UBLOX\_UCenter\_GUI\_Screen.jpg</b>)


1. Plug the GPS Unit into your PC via USB
2. Select the COM port and Connect to the GPS Unit
3. MENU -> View -> Configure -> TP5 (Timepulse 5)
4. Set Frequency & Frequency Locked to (say) 10000000 Hz
5. Set Duty & Duty Locked to 50% 
6. Menu -> Receiver -> Action -> Save Config (saves to the GPS Unit's flash memory, if available)

