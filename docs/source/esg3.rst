ESG3 Encoder & Sync Generator
=========================================

.. figure:: lzxart/Encoder/LZX12HPEncoderFrontpanelColorGraphicDark.png
   :height: 600
   :alt: ESG3 Encoder & Sync Generator frontpanel

   Frontpanel

   +-----------------------+-----------------------+-----------------------+-----------------------+
   | Potentiometer         | Description           | Range                 | Center                |
   +=======================+=======================+=======================+=======================+
   | P1                    | Red Contrast          | 0x to 4x              | 1x                    |
   +-----------------------+-----------------------+-----------------------+-----------------------+
   | P2                    | Green Contrast        | 0x to 4x              | 1x                    |
   +-----------------------+-----------------------+-----------------------+-----------------------+
   | P3                    | Blue Contrast         | 0x to 4x              | 1x                    |
   +-----------------------+-----------------------+-----------------------+-----------------------+
   | P4                    | Red Brightness        | -1V to +1V            | 0V                    |
   +-----------------------+-----------------------+-----------------------+-----------------------+
   | P5                    | Green Brightness      | -1V to +1V            | 0V                    |
   +-----------------------+-----------------------+-----------------------+-----------------------+
   | P6                    | Blue Brightness       | -1V to +1V            | 0V                    |
   +-----------------------+-----------------------+-----------------------+-----------------------+
   
   +-----------------------+-----------------------+-----------------------+-----------------------+-----------------------+
   | 3 Position Toggle     | Description           | Up                    | Center                | Down                  |
   +=======================+=======================+=======================+=======================+=======================+
   | S1                    | Red Function          | Invert                | Enable                | Mute                  |
   +-----------------------+-----------------------+-----------------------+-----------------------+-----------------------+
   | S2                    | Green Function        | Invert                | Enable                | Mute                  |
   +-----------------------+-----------------------+-----------------------+-----------------------+-----------------------+
   | S3                    | Blue Function         | Invert                | Enable                | Mute                  |
   +-----------------------+-----------------------+-----------------------+-----------------------+-----------------------+

.. graphviz::
    :name: sphinx.ext.graphviz
    :caption: Sphinx and GraphViz Data Flow
    :alt: How Sphinx and GraphViz Render the Final Document
    :align: center

     digraph "sphinx-ext-graphviz" {
         size="6,4";
         rankdir="LR";
         graph [fontname="Verdana", fontsize="12"];
         node [fontname="Verdana", fontsize="12"];
         edge [fontname="Sans", fontsize="9"];

         sphinx [label="Sphinx", shape="component",
                   href="https://www.sphinx-doc.org/",
                   target="_blank"];
         dot [label="GraphViz", shape="component",
              href="https://www.graphviz.org/",
              target="_blank"];
         docs [label="Docs (.rst)", shape="folder",
               fillcolor=green, style=filled];
         svg_file [label="SVG Image", shape="note", fontcolor=white,
                 fillcolor="#3333ff", style=filled];
         html_files [label="HTML Files", shape="folder",
              fillcolor=yellow, style=filled];

         docs -> sphinx [label=" parse "];
         sphinx -> dot [label=" call ", style=dashed, arrowhead=none];
         dot -> svg_file [label=" draw "];
         sphinx -> html_files [label=" render "];
         svg_file -> html_files [style=dashed];
     }
   
:HP: 12
:Power Consumption +12V: 200mA

DIP Switch Settings
-------------------------

+------------+--------------+
| Format     | Setting      |
+============+==============+
| NTSC       | 0000xxxx     | 
+------------+--------------+
| PAL        | 1000xxxx     | 
+------------+--------------+
| 486p5994   | 0100xxxx     | 
+------------+--------------+
| 576p50     | 1100xxxx     | 
+------------+--------------+
| 1080i5994  | 0010xxxx     | 
+------------+--------------+
| 1080i60    | 1010xxxx     | 
+------------+--------------+
| 720p5994   | 0110xxxx     | 
+------------+--------------+
| 720p60     | 1110xxxx     | 
+------------+--------------+
| 1080i50    | 0001xxxx     | 
+------------+--------------+
| 1080p2398  | 1001xxxx     | 
+------------+--------------+
| 720p50     | 0101xxxx     | 
+------------+--------------+
| 1080p2997  | 1101xxxx     | 
+------------+--------------+
| 1080p24    | 0011xxxx     | 
+------------+--------------+
| 1080p25    | 1011xxxx     | 
+------------+--------------+
| 1080p30    | 0111xxxx     | 
+------------+--------------+
| RGB Out    | xxxxxxx1     | 
+------------+--------------+
| YPbPr Out  | xxxxxxx0     | 
+------------+--------------+
