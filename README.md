# UBIK
Using the Web Speech API and Web MIDI API for an accessible MIDI mapper with spoken parameters.

This forms some of my initial research for my PhD thesis, Designing Interfaces For Visual Impairments.

What is UBIK? 

I first created this as an accessible way of quickly generating some sliders to test current MIDI projects and control some hardware. I then combined this with the Web Speech API to read out params when sending MIDI.

In a nutshell this project allows you to create control groups and populate them with sliders and toggle buttons for sending MIDI data. Each control populates with a learn button to quickly map any MIDI controller. When adding sliders you can map the visable output and spoken feedback to any value to match the param being controlled.

I have added full customisation of the interface including font size and styles, page and element colours, focus size and slider style. There are 10 different styles of slider available. 

Full support for screen readers, including a custom tour of the interface highlighting all functions.

Save and load your controller layouts, within each layout patches can be saved for the current control positions. When loading all controls send MIDI CC value. Added so I could save preset patches for some old hardware without SYSEX.

Send Program Change messages.

I recomend Google Chrome or Microsoft Edge as they have the best support of the API's in this project.
