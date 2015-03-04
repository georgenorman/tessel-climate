

=======================================================================
Tessel Climate Module Test Project
=======================================================================


---------------------------------------------------------
app.js:
  A simple test of the Tessel Climate module.
---------------------------------------------------------

# runs app using default settings from ./config/config.json
tessel run app/app.js --listen all

# runs app using overriding settings from config
tessel run app/app.js --listen all climatePort=A refreshRate=2000

# runs app using overriding settings from config
tessel run app/app.js climatePort=A refreshRate=1000


To exit, click the config button on the Tessel.

