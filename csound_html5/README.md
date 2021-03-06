# Csound with HTML5

## License

This software is licensed under the terms of the GNU Lesser General Public
License, which is the same license as used for Csound.

## Introduction

CHSound is a bare-bones "front end" for editing and performing Csound pieces
that contain an embedded Web page. This page can be used to provide a highly
customizable user interface for Csound pieces, to generate Csound scores
using JavaScript, and to interface with all the myriad capabilities of HTML5,
including for example animated 3-dimensional graphics (WebGL).

The CSD file can contain a standard Web page, which appears as an <html>
element in the file. When this page is loaded in the browser tab of the
application, the running instance of Csound is accessible as a "csound"
object in the JavaScript context of the page. This object implements many of
the important methods of the Csound API. Although all of these methods are
asynchronous, methods that normally return values accept an additional
completion callback that will be called with the return value of the method
when it becomes available.

The JavaScript API methods and names are otherwise roughly the same as found
in CsoundQt, Csound for Android, csound.node, and Csound for PNaCl.

This project requires a recent version of the Qt SDK with QtWebEngine support.
The only external dependency is a recent version of Csound. CHSound should
build and run on Windows, Linux, and OS X.
