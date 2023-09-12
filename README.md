# taspotify
JS script to extract color information from Spotify album covers to apply to a Tasmota RGB lamp
## Goals
- Dynamically extract 3 or more colors from the cover of currently playing spotify tracks
- Cycle through them on a Tasmota RGB lamp
- Possibly change color fading settings to ensure smooth transitions
- Written in JS, using bun
- Expressive logging and spotify integration information
- Ability to configure transitions and fade speed
- Possibly abstract connection logic to support multiple RGB bulb firmwares
- Self contained multi platform binary with OS integration (for example KDE plasmoid)
