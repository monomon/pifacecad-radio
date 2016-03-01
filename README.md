# pifacecad-radio

My version of the [pifacecad radio](https://github.com/piface/pifacecad).

Differences from the original:
* Different set of stations
* Command-line arguments of mplayer take double instead of single slash. Likely due to platform differences...
* Update bottom row of the lcd with the standard output of the mplayer process. This is useful both as status information and for debugging.
* move call to play in main to after all listeners have been initialized
