# ZiraForStarCitizen
A Custom Voice Attack Profile developed for use with the game Star Citizen.

VERSION 1:

  Creation of Profile: "SC-Pilot"
  
    Profile focuses on implementing basic voice activated controls for pilots
    
    Also introduces some minor intelligence for tracking ship status
    
  Preflight checks added:
  
    1)Landing gear
    
    2)Cockpit HUD mode
    
Run These Preflight Checks Everytime You Change Ships:

  1) Say "Run preflight checks"
  
  2) After Zira asks say either "landing gear active" or "landing gear inactive" to tell Zira the status of the gear
  
  3) After she asks her next question say either "combat mode active" or "scan mode active" to tell Zira which view mode the Cockpit is   in, by default Ships will start with combat mode.
  
  To setup the keybindings:
  
    1) Place the xml file beginning with the word "layout" in your Mappings folder. By default it is located at this path: 
    
    C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER\Controls\Mappings
    
    2) Go in game and under Options on the main menu, go to "Keybindings" then "Advanced Control Customizations" at the bottom of the screen. Select "Control Profiles" located at the lower right of the screen. Look for the entry labeled "Zira_VA_Mappings" select it and load the profile.
