# Chains - Horizon Updated

- Updated all the skillchain properties to the Horizon server. This includes all of the following changes to pets:
- Corrected the SMN Blood Pact values.
- Disabled BST/SMN pet abilities that you can't skillchain.  

### Active Battle Skillchain Display.

Displays a text object containing skillchain elements resonating on current target, timer for skillchain window and a list of weapon skills that can skillchain based on the weapon you have currently equipped.

Chains is based on the skillchains addon by Ivaar for Ashita-v3. It has mostly been recoded for Ashita-v4 while maintaining the same functionality.

### Commands
The following commands may be used to adjust the window position.

    /chains visible       -- displays text box - click and drag it to desired location
    /chains move <x> <y>  -- reposition the window to the defined x, y coordinates
    /chains scale <value> -- set font scale

The following commands toggle the display information.

    /chains color   -- colorize properties and elements
    /chains pet     -- smn
    /chains weapon  -- weapon skills

### Acknowledgments
All credit goes to Ivaar for the original skillchains implementation which was used as the tempalte for how to accomplish the desired results and how to deal with some of the corner cases.

Special thanks to Atom0s and Thorny. Many of their addons are used as examples of how to accomplish various tasks.

