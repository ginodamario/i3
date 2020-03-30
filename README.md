# i3

My configuration for the i3wm using Ubuntu 18.04


- Install **redshift** for blue light filter
    
      sudo apt install redshift

- Install **lxappearance** to get gtk fonts and theme

      sudo apt install lxappearance
    

- Install **compton** to allow transparency and fix screen tearing
    
      sudo apt install compton 
      # Edit or create ~/.config/compton.conf 
      # put this in 
      backend = "glx"; 
      glx-no-stencil = true; 
      paint-on-overlay = true; 
      vsync = "opengl-swc";
      
- Install **i3blocks**
      
      sudo apt install i3blocks
      
- Install **arandr**. This configures the displays
    - Open and "Save As" once you configure the display like you want.
    - Open the file and copy the xrandr command to the ~/.config/i3/config file.

            sudo apt install arandr
            
- Install **pavucontrol** to control volume
    
            sudo apt install pavucontrol
      
 - Install font awesome from here: https://github.com/FortAwesome/Font-Awesome/releases
Unzip zip file and copy .ttf files to ~/.fonts
 
- Put this repo in ~/.config/i3 after install i3

    sudo apt install i3
    
- Use **xset** to set power management stuff like screensaver timeout
