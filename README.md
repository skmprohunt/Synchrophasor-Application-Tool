# Synchrophasor App
Operation Instructions : 
Verify the instructions of C-compiler or similar and install it if needed. To check type "mex -setup" into MATLAB Command Window.
As the app is programmed for IEEE WSC 9-bus system ensure all the phasors are being parsed as per the same.

Installation :
After downloading the file. Set the current folder to the one having the app setup.
Then click on APPS-->>Install App.
Browse and select "SynchrophasorApp.mlappinstall" form the downloaded location.
After Intallation select "SynchrophasorApp" from MyApps to run the app.

In case of the following error:
  "
  Error using icinterface/fopen (line 83)
  Unsuccessful open : Connection refused: connect
  
  Error in ICT_initialisation (line 73)
      fopen(SADF>Connection_primary);
     
  Error in SADF_run (line 58)
  ICT_initialisation();
  
  Error in run (line 86)
  evalin('caller', [script ';']);
  "
please verify the connection parameters in the settings tab of the SynchrophasorApp.
