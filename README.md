# SimpleSMSspamFilter_GUI
The GUI Version of Simple SMS Spam Filter created with DearPy GUI
<br>
<br>
This simple program labels user-provided strings as spam or not spam (ham)
<br>
You can run it easily from your own command line terminal with <b>"python Dearpy.py"</b>
<br>
<br>
<b>/finishedProject</b>
<br>
This directory contains the full version of the app.
<br>
<b>/starterFiles</b>
<br>
This directory contains only the logo, database, and functions.py
<br>
app.py is incomplete, and is only useful to you if you follow the Python Simplified tutorial on Youtube:
<br>
<br>
<br>
![DearPyGUI](https://user-images.githubusercontent.com/32107652/99757481-48d73a80-2aa4-11eb-9e11-29fdc96f6c06.jpg)
<br>
<br>
<b>Dependencies:</b>
<br>
<ul>
  <li>DearPy GUI</li>
  <li>Pandas</li>
  <li>NLTK</li>
  <li>String</li>
</ul>
<b>Database from:</b>
<br>
http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/
<br>

<br>

<br>
If you get the following error:
<br>
TypeError: function missing required argument 'pmax' (pos 4)
Exception: Error parsing DearPyGui Marvel::draw_image command on line 16
<br>
<br>
Try adjusting your draw_image function to:
<br>
draw_image("logo", "logo_spamFilter.png", [0,0], [458,192])
<br>
<br>
<b>!!! * Important Notes for Mac Users * !!!</b>
<br>
<br>
add wrap=0 to your add_text() function:
<br>
add_text("Please enter an SMS message of your choice to check if it's spam or not",
    color=[232,163,33])
<br>
<br>
