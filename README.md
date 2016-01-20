# Arduino-UNO-WiFi-Submission

[Arduino Uno WiFi Remote Sign-in]

My Arduino UNO WiFi project would be a remote sign in system via mobile device.

By installing an application (preferably developed for both Android and iOS systems) onto a mobile device, one can make an account to interact with the Arduino (which would host a database of numerous users and their accounts). The Arduino could see a user's account as "active" if a device with the application were within a specified range of the Arduino (say, 100 feet), and would track sign-ins, sign-outs, total time signed in, and other data based around device-to-Arduino interaction. The user's account would be "linked" to one mobile device at a time to prevent a user with more than one device from having multiple "active" instances of their account.

This project's purpose is to keep accurate track of hours signed in the workplace, at a volunteering activity, or for other sign-in-utilizing events. There is no practical way to "cheat" the system (e.g. staying signed in overnight) because it would require leaving the phone within range of the Arduino, forcing someone to stay within that range/drop off their phone or risk losing sign-in time.

As a whole, the Arduino Uno Remote Sign-in system would be more accurate and efficient than normal "punch-in" systems, and could easily replace them in the near future with proper usage.
