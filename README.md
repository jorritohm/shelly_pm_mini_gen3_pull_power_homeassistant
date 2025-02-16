# shelly_pm_mini_gen3_pull_power_homeassistant
Pull Shelly Power through REST API in HomeAssistant

By default, a Shelly device only pushes updates to Home Assistant when the difference from the last measurement is significant enough. However, this behavior may not be ideal in some cases.  
This sensor setup allows you to fetch data from the device every second using the REST API, ensuring up-to-date values at all times.

NOTE: To use this it is necessary to disable authentification on the Shelly. 

1. Add the above code to your configuration.yaml file in Home Assistant.
2. Change the IP-Address to the IP of your Shelly.
3. Save the file and restart HomeA ssistant.
4. The new sensor should now be available.
