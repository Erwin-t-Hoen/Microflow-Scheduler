Name	
   Microflow Scheduler Module

 Author	   Erwin 't Hoen
 Type	   Module
 Latest Version	   1.1.1
 Package filename	   MicroflowScheduler1.1.1.mpk
 

Description
 

This module allows you to schedule events from the client.

By creating a schedule and selecting a microflow to run you can easily create and control your scheduled events from within the runtime environment.

Typical usage scenario
 

When using scheduled scheduled events and need control and visibility from the run time
When you have your app deployed and discover that you need to schedule an event more than the once a day scheduled event youo created. You can now just create a new schedule in the client and have the events trigger as often as needed without the need for a new deploy and waiting for a service window.
When a scheduled event should stop running after a certain date, you can control this from the runtime.
Features and limitations
 

Schedule events on the following interval types
Minute
Hour
Day
Week
Month
Year
Define start date and time for starting to run your events
Define stop date and time for running your events
Use multiple queues for short and long running events
Suported languages English & Dutch
One limitation is the initial availability of 5 queues, but this can be easily expanded (see readme) 
Installation
 

See the general instructions under How to Install.

Dependencies
 

Mendix 5.0.0 Environment
Mx Model Reflection v3.0 (Mx 5 version)
Configuration
 

Add the form Schedule_Overview to your navigation
Add the Configurator module permission to the correct user role(s)
Synchronize the Mx Model Reflection module
Create your schedules