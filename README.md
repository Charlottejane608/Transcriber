Guitar Notes Transcriber
=============

Basic implementation of the aubio library tool is to try and map notes played on the guitar to the top half of the guitar fretboard. The use of the base frequency identifier and the onset detector has been from the python extension of the aubio library. Any code on top of that has been to augment the use of the library to estimate where the notes are positioned on the guitar fretboard.

Implementation and Design Basics
--------------------------------

The code has been written in Python and I have tried to document it as thoroughly as possible!
You will require the python plugins Aubio, Matplotlib, and Numpy.

sudo pip install aubio

And yeah, you'll require pip (Of course)

run code as -
python pitchDetector.py audio_file_path


Credits
------------------------

Core work on the frequency note conversion to MIDI and using the Onset Detector to map these recognised notes have been done by myself and my colleague Rahul Agnihotri.

Additional credit to Sayeram Eswar for help in conceiving this project idea and helping with the final plotting of the notes using Matplotlib.

Without the help of Paul Brossier's aubio library this project would not have been possible. Thanks Paul!


Contact Info and Mailing List
-----------------------------

Sujith Sajeev (That's me) - sujithishtar3@gmail.com

Sayeram Eswar - sayeram.eswar1@gmail.com

Rahul Agnihotri- raul.agni12@gmail.com

Copyright and License Information
---------------------------------

this is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
