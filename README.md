# shelly_pm_mini_gen3_pull_power_homeassistant
Pull Shelly Power through REST API in HomeAssistant

The Shelly HomeAssistant plugin only pulls power values, if the difference to the last measurement is big enough. However this might not be ideal in some cases.
This sensor allows you to pull the data through the rest API every second.

NOTE: To use this it is necessary to disable authentification on the Shelly. 

1. Add the above code to your configuration.yaml file in HomeAssistant.
2. Change the IP-Address to the IP of your Shelly.
3. Save the file and restart HomeAssistant.
4. The new sensor should now be available.
