# KiCad-3PDT-PCB-project
A 3PDT PCB for guitar pedals

![](./3pdt_render.png)

Hello, this is a KiCad project for a 3PDT PCB board.
This will allow a guitar pedal with a 3PDT to be wired in true bypass.

IJ = Input Jack
IN = PCB Input
LED = LED
GND = Ground connection
OUT = PCB Output
JO = Output Jack

The wire pads have a pitch of 2.54mm (0.1") to match that of common ribbon cables.

Board width is 17.5mm, height is 20.5mm.

# If you would like to order one

Click into the 3pdt_pcb_fab_files.zip file, then download that zip file.

Then you can use a board fabricator like JLCPCB and upload that zip onto their site.

If you need the files in a different format than .zip, I've included the folder unzipped `pcb_fab_files`.

Here's where to put the file on JLCPCBs website:

![](./JLCPCB_website.png)

Once you drag the .zip onto there, it'll load this page with the PCB, and lots of options for it.
You can click "PCB Qty" to change the number of boards to get. I usually leave everything else default,
except for Surface Finish - LeadFree HASL (personal preference).

![](./JLCPCB_board_page.png)

Other PCB fab sites should work very similarly.
