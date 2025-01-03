# FFT DeNoiser for REAPER

* A GUI version of micsthepick's fork on the REAPERDenoiser plugin:
* https://github.com/micsthepick/REAPERDenoiser/blob/main/REAPERDenoiser.jsfx

The goal of the GUI was to be clear and intuitive, and to lessen the required existing knowledge for using the plugin. I haven't made significant changes into the DSP side of the plugin.

## Usage instructions:
- Loop a section of the track that only includes noise.
- In the plugin, click "Record Noise". Click the button after a few seconds to stop recording.
- Done! You can fine tune the amount of noise reduction with the "DeNoise" knob.

## Notes:
- The Low Latency mode is low enough to allow live playback, but the quality isn't as good.
- Changing into or out of the Low Latency mode requires a new noise profile to be recorded.
- The FFT Overlap has a minor effect on the quality of the process, and a higher quality increases CPU usage a bit.

## Install instructions:
- Click on the "mrelwood_DeNoiser.jsfx" in the file list.
- Click the button "Raw" and save the resulting file on your computer.
- In REAPER go to Options > Show REAPER resource path...
- Look for the "Effects" folder, open it and and create a subfolder "mrelwood".
- Move the "mrelwood_DeNoiser.jsfx" plugin into the "mrelwood" folder you just created.
- Restart REAPER or press F5 in the plugin list for the plugin to show up in REAPER.
