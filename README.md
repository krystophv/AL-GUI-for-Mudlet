# AL-GUI-for-Mudlet

Excited to share with you the work of a Mudlet UI for Accursed Lands:
- telnet://mud.accursed-lands.com:8000 or you can use a browser to
- http://mud.accursed-lands.com:7878

![Ongoing version 1.x releases page](https://github.com/Accursed-Lands-MUD/AL-GUI-for-Mudlet/releases); please see the chat in our discord for updates - https://discord.gg/yZ6uNSM

Enjoy!

![image](https://user-images.githubusercontent.com/59232016/202618690-db7d87c3-3f9d-4bfd-94cd-5dc0f3edf19b.png)


# Features
- Mud enabled GA by default so functions like isPrompt() work.
- Sends IAC GA at the end of every prompt and when done sending data.
- Mapping scripts for both the wilderness and in points of interest.
 - (Pending) Includes the map of the newbie training area
  - Method to be determined:  MMP or via downloadFile() + loadMap().
- Interface tracks player vital stats, player combat styles and inventory
- Tabbed chat included as well for MUD channels.
- This page and its releases are updated regularily and using the GMCP extension that Mudlet makes use of.

# Installing

After creating a Mudlet profile to connect to Accursed Lands, add the package by:

1.    Downloading a release of this package (the .mpackage file) from the [releases page](https://github.com/Accursed-Lands-MUD/AL-GUI-for-Mudlet/releases)
2.    Open the Package Manager in Mudlet
- If present, uninstall the generic-mapper package. It may conflict with the one provided here.

  <img src="https://user-images.githubusercontent.com/59232016/202616813-7b79b6d0-9510-4ba9-a0e1-7b3c5b769b4b.png" width="200" />

- Select the alui_<version>.mpackage file downloaded in step 1 for installation

  <img src="https://user-images.githubusercontent.com/59232016/202617253-70fa4f6e-8cc3-4d9d-a08f-66cd551e85bd.png" width="200" />


3.    Restart Mudlet and reconnect. The UI will populate fully once you log in with your account.
- Perform commands such as info, inventory, look, style and survey.


# Version 2 mock up for where this is going:
![image](https://user-images.githubusercontent.com/59232016/202612971-754f0c50-549e-4b5b-86d5-d1bd703c49a7.png)
