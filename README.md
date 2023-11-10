# SNDstyle

## SNDstyle.py
Plot style template for SND@LHC experiment

- `init_style()` sets the basic layout of the canvas as well as histograms.
- `writeSND(..)` adds the experiment name to the canvas.
  - `extratext` adds an extratext below the experiment name.
  - `text_in` if `TRUE`: `maintext` and `extratext` ar written within frame of the canvas, otherwise they are written on the frame border.
  - `maintext` allows to specify the experiment name. 
