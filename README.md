# Csound Goodies

This Web site contains various resources for using Csound. These resources include examples, a playable version of the Csound reference manual, and Lisp code written by [Drew Krause](http://www.drew-krause.com/) that can be used for algorithmic composition with Csound.

## Playable version of the Csound Reference Manual

The following link will take you to an online version of the Csound Reference Manual. It contains examples that will play right in your browser. You can even edit the examples and play them again hear the results of your changes. Currently this is supported only in desktop versions of Google's Chrome browser.

https://gogins.github.io/csound/html/indexframes.html

Not all examples are playable at this time. Only csd based examples (not orc based) that output stereo audio, and do not use file-based resources (such as sample soundfiles) or network-based resources (e.g. OSC does not work), are currently working.

## Playable Sample Pieces

This repository contains samples of integrating HTML5 capabilities with Csound, where the PNaCl build of Csound is used, so that Csound itself does not need to be installed. These examples should play on version 31 or later of 
Google's Chrome browser for OS X, Windows, or Linux. Click on the links below to play the examples. If you don't hear anything at first, make sure Csound has finished loading, and play with the sliders, particularly the output level slider.

https://gogins.github.io/csound/PNaCl_Csound_01_Introduction.html

https://gogins.github.io/csound/PNaCl_Csound_02_Instrument_Controls.html

https://gogins.github.io/csound/PNaCl_Csound_03_Style_Sheet.html

https://gogins.github.io/csound/CompileCsdText.html

I performed this piece for the 2016 New York City Electroacoustic Music Festival: https://gogins.github.io/csound/Scrims_pnacl.html

## Playing With the Examples

If you want to see what happens when you edit these examples, or if you want to use them as a basis for your own works, clone this repository on your computer using the <b>Clone or download</b> button on this page. Make sure Python is installed. Then go to the root directory of this repository and run ```webserver.cmd``` on Windows or ```webserver.sh``` on Linux to run a local Web server. Open Chrome, and navigate to http://localhost:8080. You can then find and run the examples. Edit the examples or create your own pieces using a regular text editor, and refresh the browser to see your changes in action.

## Other Sample Pieces

The examples in this category are not necessarily playable, as they may depend on resources not available in the Web browser. They are included here to show how to use various features of Silencio and/or Csound.

I performed this piece for the 2016 New York City Electroacoustic Music Festival. It is an example of the use of the new parametric Lindenmayer system class along with chord transformations:
<a href="https://www.dropbox.com/s/nkcubcw3jwe3nqt/Sevier.6.html" type="text/plain"><b>Sevier</b></a>. In order to view the code, either download the file, or right-click to view the frame source.

Here is a variant of Sevier reworked for PNaCl:
https://gogins.github.io/csound/Lindenmayer_Example_pnacl.html

## Nudruz

This archive of Lisp code from [Drew Krause](http://www.drew-krause.com/) is hosted with his permission. The code has been lightly edited to make it more usable with Steel Bank Common Lisp and the current version of Csound. Drew's code also is licensed under the terms of the GNU Lesser General Public License.
