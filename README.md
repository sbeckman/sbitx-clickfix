# sbitx-clickfix
sBitx test software to attempt a fix for noise bursts heard when transitioning from receive to transmit.

The location for the wisdome files has been changed from the current execution directory to /home/pi/sbitx/data. This may result in a 1 minute delay the first time the program is started, while the new wisdom files are generated. The startup delay is a one time occurrence and will not happen again once the wisdom files have been generated.

08-February-2024 - a revised version of the sbitx application has been uploaded which restores the original behavior of the GUI - but unfortunately also restores the bug where the application will abort if the taskbar is not set to auto-hide and the CW keyboard is opened.

