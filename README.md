# My-Terminal-Setup
My-Terminal-Setup

// This file was initially generated by Windows Terminal 1.6.10571.0
// It should still be usable in newer versions, but newer versions might have additional
// settings, help text, or changes that you will not see unless you clear this file
// and let us generate a new one for you.

// To view the default settings, hold "alt" while clicking on the "Settings" button.
// For documentation on these settings, see: https://aka.ms/terminal-documentation
{
    "$schema": "https://aka.ms/terminal-profiles-schema",

    "defaultProfile": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",

    // You can add more global application settings here.
    // To learn more about global settings, visit https://aka.ms/terminal-global-settings

    // If enabled, selections are automatically copied to your clipboard.
    "copyOnSelect": false,

    // If enabled, formatted data is also copied to your clipboard
    "copyFormatting": false,

    // A profile specifies a command to execute paired with information about how it should look and feel.
    // Each one of them will appear in the 'New Tab' dropdown,
    //   and can be invoked from the commandline with `wt.exe -p xxx`
    // To learn more about profiles, visit https://aka.ms/terminal-profile-settings
    "profiles":
    {
        "defaults":
        {
            "fontFace": "Consolas"
            // Put settings here that you want to apply to all profiles.
        },
        "list":
        [
            {
                // Make changes here to the cmd.exe profile.
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "name": "CMD Lord",
                "commandline": "cmd.exe",
                "hidden": false,
                "colorScheme": "CMD-Lord",
                "fontFace": "Cascadia Code",
                "icon": "C:\\Users\\lexro\\OneDrive\\Pictures\\kali_Icon.png",
                "backgroundImage": "C:\\Users\\lexro\\OneDrive\\Pictures\\percentage.gif",
                "backgroundImageOpacity": 0.4,
                "useAcrylic": true,
                "acrylicOpacity": 0.1,
                "cursorShape": "doubleUnderscore",
                "cursorColor": "#ed4e04"  
                
            },
            {
                // Make changes here to the powershell.exe profile.
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "name": "Windows PowerShell",
                "commandline": "powershell.exe",
                "hidden": false,
                "fontFace": "Cascadia Code",
                "colorScheme": "Campbell",
                "background": "#473D5E",
                "cursorShape": "vintage",
                "cursorColor": "#f00",
                "useAcrylic": true,
                "acrylicOpacity": 0.2,
                "backgroundImage": "C:\\Users\\lexro\\OneDrive\\Pictures\\geometry.jpg"
            },

            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "hidden": false,
                "name": "Azure Cloud Shell",
                "fontFace": "Cascadia Code",
                "source": "Windows.Terminal.Azure",
                "colorScheme": "Campbell",
                "icon": "C:\\Users\\lexro\\OneDrive\\Pictures\\kali_Icon.png",
                "backgroundImage": "C:\\Users\\lexro\\OneDrive\\Pictures\\kali.jpg",
                "startingDirectory": "C:\\Users\\lexro",
                "background": "#473D5E",
                "cursorShape": "vintage",
                "cursorColor": "#f00",
                "acrylicOpacity": 0.2
            },
            {
                "guid": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",
                "hidden": false,
                "name": "Ubunto-Retro",
                "fontSize": 11,
                "source": "Windows.Terminal.Wsl",
                "colorScheme": "Ubunto-Retro",
                "fontFace": "Cascadia Code",
                "icon": "C:\\Users\\lexro\\OneDrive\\Pictures\\kali_Icon.png",
                "backgroundImage": "C:\\Users\\lexro\\OneDrive\\Pictures\\percentage.gif",
                "startingDirectory": "C:\\Users\\lexro\\",
                "useAcrylic": true,
                "acrylicOpacity": 0.1,
                "cursorShape": "doubleUnderscore",
                "cursorColor": "#c70303"  
                
            },
            {
                "guid": "{46ca431a-3a87-5fb3-83cd-11ececc031d2}",
                "hidden": false,
                "name": "kali",
                "colorScheme": "Frost",
                "icon": "C:\\Users\\lexro\\OneDrive\\Pictures\\kali_Icon.png",
                "backgroundImage": "C:\\Users\\lexro\\OneDrive\\Pictures\\kali.jpg",
                "source": "Windows.Terminal.Wsl",
                "cursorShape": "doubleUnderscore",
                "foreground": "#c70303" 
            },
            {
                "guid": "{55ca431a-3a87-5fb3-83cd-11ececc031d2}",
                "hidden": false,
                "icon": "C:\\Users\\lexro\\OneDrive\\Pictures\\kali_Icon.png",
                "backgroundImage": "C:\\Users\\lexro\\OneDrive\\Pictures\\kali.jpg",
                "name": "Win-KeX",
                "commandline": "wsl -d kali-linux kex --sl --wtstart -s",
                "startingDirectory" : "//wsl$/kali-linux/home/<kali user>"
        },
        ]
    },

    // Add custom color schemes to this array.
    // To learn more about color schemes, visit https://aka.ms/terminal-color-schemes
    "schemes": [{
        "name": "Ubunto-Retro",
        "background" : "#FFFFFF",
        "black" : "#070ff7",
        "blue" : "#17b2ff",
        "brightBlack" : "#3e6303",
        "brightBlue" : "#045bfd",
        "brightCyan" : "#13A8C0",
        "brightGreen" : "#f79706",
        "brightPurple" : "#ff000d",
        "brightRed" : "#ba0000",
        "brightWhite" : "#fc0cfc",
        "brightYellow" : "#06d853",
        "cyan" : "#00d9ff",
        "foreground" : "#db1111",
        "green" : "#ff0000",
        "purple" : "#991070",
        "red" : "#8D0C0C",
        "white" : "#6E386E",
        "yellow" : "#991070"
    },
    {
        "name" : "Frost",
        "background" : "#FFFFFF",
        "black" : "#070ff7",
        "blue" : "#17b2ff",
        "brightBlack" : "#3e6303",
        "brightBlue" : "#045bfd",
        "brightCyan" : "#13A8C0",
        "brightGreen" : "#f79706",
        "brightPurple" : "#ff000d",
        "brightRed" : "#ba0000",
        "brightWhite" : "#fc0cfc",
        "brightYellow" : "#06d853",
        "cyan" : "#00d9ff",
        "foreground" : "#db1111",
        "green" : "#ff0000",
        "purple" : "#991070",
        "red" : "#8D0C0C",
        "white" : "#6E386E",
        "yellow" : "#991070"
    },
    {
        "name": "CMD-Lord",
        "background": "#663535",
        "black": "#013f01",
        "blue": "#0bb4d1", //Shadded path
        "brightBlack": "#6b0505",
        "brightBlue": "#459983", //Path
        "brightCyan": "#4b4e4a", // 'path'
        "brightGreen": "#0425e2", // '' * path
        "brightPurple": "#3fe615",
        "brightRed": "#b6b4b1",
        "brightWhite": "#b4e7b4",
        "brightYellow": "#0051ff",
        "cyan": "#00aeff",
        "foreground": "#0ff7e0", // results display
        "green": "#383131",
        "purple": "#03a7ff",
        "red": "#e100ff",
        "white": "#cbe9cb",
        "yellow": "#00ff88"
    },
    
  

],

    // Add custom actions and keybindings to this array.
    // To unbind a key combination from your defaults.json, set the command to "unbound".
    // To learn more about actions and keybindings, visit https://aka.ms/terminal-keybindings
    "actions":
    [
        // Copy and paste are bound to Ctrl+Shift+C and Ctrl+Shift+V in your defaults.json.
        // These two lines additionally bind them to Ctrl+C and Ctrl+V.
        // To learn more about selection, visit https://aka.ms/terminal-selection
        { "command": {"action": "copy", "singleLine": false }, "keys": "ctrl+c" },
        { "command": "paste", "keys": "ctrl+v" },

        // Press Ctrl+Shift+F to open the search box
        { "command": "find", "keys": "ctrl+shift+f" },

        // Press Alt+Shift+D to open a new pane.
        // - "split": "auto" makes this pane open in the direction that provides the most surface area.
        // - "splitMode": "duplicate" makes the new pane use the focused pane's profile.
        // To learn more about panes, visit https://aka.ms/terminal-panes
        { "command": { "action": "splitPane", "split": "auto", "splitMode": "duplicate" }, "keys": "alt+shift+d" }
    ]
}
