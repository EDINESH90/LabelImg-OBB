LabelImg-OBB: An Annotation Tool for Rotated Bounding Boxes
==================================================================
LabelImg-OBB is an advanced graphical image annotation tool designed for labeling rotated rectangular regions (Oriented Bounding Boxes, or OBBs). 
It is a customized extension of the original LabelImg and its rotated variant roLabelImg, combining their core functionalities with extended format support.

The original LabelImg only supports axis-aligned bounding boxes and the roLabelImg update supports rotated boxes. 
The roLabelImg saves only in Pascal VOC .xml format with labels as <cx, cy, w, h, angle> .

LabelImg-OBB supports:

Key Features:
Label rotated rectangles with an intuitive Qt-based GUI.
Save annotations in both Pascal VOC (.xml) and YOLO (.txt) formats.
Support for two YOLO-style OBB formats:

   1.Type I – YOLO-OBB (Angle-based) -- (Total: 6 values)

                <class_name> <cx> <cy> <w> <h> <angle>         


   2.Type II – YOLO-OBB (Corner-based) -- (Total: 9 values)

                <class_id> <x1> <y1> <x2> <y2> <x3> <y3> <x4> <y4>       


Written in Python with a Qt GUI, easy to install and extend.
==========


Hotkeys
~~~~~~~

+------------+--------------------------------------------+
| Ctrl + u   | Load all of the images from a directory    |
+------------+--------------------------------------------+
| Ctrl + r   | Change the default annotation target dir   |
+------------+--------------------------------------------+
| Ctrl + s   | Save                                       |
+------------+--------------------------------------------+
| Ctrl + d   | Copy the current label and rect box        |
+------------+--------------------------------------------+
| Space      | Flag the current image as verified         |
+------------+--------------------------------------------+
| w          | Create a rect box                          |
+------------+--------------------------------------------+
| e          | Create a Rotated rect box                  |
+------------+--------------------------------------------+
| d          | Next image                                 |
+------------+--------------------------------------------+
| a          | Previous image                             |
+------------+--------------------------------------------+
| r          | Hidden/Show Rotated Rect boxes             |
+------------+--------------------------------------------+
| n          | Hidden/Show Normal Rect boxes              |
+------------+--------------------------------------------+
| del        | Delete the selected rect box               |
+------------+--------------------------------------------+
| Ctrl++     | Zoom in                                    |
+------------+--------------------------------------------+
| Ctrl--     | Zoom out                                   |
+------------+--------------------------------------------+
| ↑→↓←       | Keyboard arrows to move selected rect box  |
+------------+--------------------------------------------+
| zxcv       | Keyboard to rotate selected rect box       |
+------------+--------------------------------------------+



