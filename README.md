# GPS_Location
- Spreadsheet GPS_UBLOX_NEO_M8N_Jitter_Free_Frequencies.csv contains a list of all the frequencies that a UBLOX GPS unit can output without jitter. 

- These are the frequencies that divide evenly into the 24MHz oscillator's frequency. 

- The output frequency of UBLOX GPS units can be adjusted using UBLOX's U-Center desktop application (for Microsoft Windows). Download it from their website, launch the application and attach the GPS unit to your PC.
- Here are the steps to setup the output frequency:
- Select the COM port and Connect to the GPS
- MENU -> View -> Configure -> TP5 (Timepulse 5)
- Set Frequency & Frequency Locked to (say) 10000000 Hz
- Set Duty & Duty Locked to 50 
- Menu -> Receiver -> Save (this saves to Flash memory)



