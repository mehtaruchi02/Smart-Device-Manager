# Smart-Device-Manager

![Smart Device Manager Application](https://github.com/mehtaruchi/Smart-Device-Manager/blob/master/screenshots/1_Screenshots.gif)

 This is a project I had developed as part of my Internship as a ___Project Trainee___ at ___Niyantras___, a Vadodara based company.

"Smart Device Manager" is an android application to configure, monitor and operate the following automation systems offered by  ___Niyantras___:
* Home automation system (Power and Curtain module)
* Water tank monitoring system
* Health monitoring system
* Automobile monitoring system
* Speaker system

******Features******

* A single application to configure, monitor and operate all the automation systems:

    * Home automation system (Power module)
       * Send information about Wi-Fi to which the system should connect.
       * Turn on or off a light appliance.

   * Water tank monitoring system
       * Configure water tank lower level, upper level and unit of measurement.
       * Monitor the current water level.

   * Health monitoring system
       * Monitor Heart beat and Blood pressure.

   * Automobile monitoring system
       * Monitor current speed, engine temperature and fuel level of automobiles.

   * Speaker system
       * Give wireless behavior to wired speakers.

* Server-driven user-interface   
     * The server sends information about actions available and the user-interface information( type of widget, hint, default values, possible values, validation criteria etc) as text data.The application parses that user-interface information to create user-interface at runtime dynamically. 
     This is useful when version conflict may arise between server and application i.e.  Server has new functionalities so now client also needs to keep making new user interfaces in order to remain in sync with server.

* Provide a choice of communication interface (Bluetooth or Wi-Fi) to communicate with the connected system.

* Connect and exchange data using Bluetooth or Wi-Fi.

* Remember device history and autoconnect. Handle connection lost and idle-channel scenarios.


