# PrusaXL-mod-gcode
Modified gcode for the Prusa XL printer

The start.gcode can be used to replace the default start g-code for a multi-tool Prusa XL.

It starts heating the bed to the first layer bed temperature before performing a mesh bed level procedure with the tool head set to 150C.

The normal absorbing heat set is skipped, for my setup and environmental conditions this does not affect my printing but you should test this with your own setup before leaving unattended.

I experience a very quick start-up procedure and no oozing during start-up with this g-code.

Use at your own risk!
