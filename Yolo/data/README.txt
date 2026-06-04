This folder is intended to hold the EmulatorJS runtime assets required by emulator_experiment_shared.html.

To make the shared page work locally, download the EmulatorJS data files and place them here.

Recommended source:
https://cdn.emulatorjs.org/latest/data/emulator.min.zip

After downloading:
1. Extract the zip contents into this folder.
2. Ensure this folder contains loader.js, emulator.min.js, emulator.min.css, and the other runtime files.
3. Place emulator_experiment_shared.html in the same folder as this data directory.

Then your friend can open emulator_experiment_shared.html in a browser and it will try to use the local data/ loader first.
If the local data folder is missing, it will fall back to the CDN.