# CC-Hat (yet another riser)

This is my take on a lid riser for the Centauri Carbon.

I started this design using the one-piece step file for the vented riser by JesusFreak, and while there isn't very much left of the original geometry of that riser, I'm calling this a remix of JesusFreak's awesome design.

### Changes From the OG

* Reduced height to 27.5 MM.
* No vent. The riser is designed so that the lid can be slid back or forward for venting.

### Important Things to Know Before Printing

* All holes were sized for M3 and M4 threaded inserts. I have provided step files, so the holes can be resized if you prefer not to use threaded inserts (though I recommend using them for the 8 M4 screws for the glass guides).
* All holes other than the 8 glass guide holes are completely optional. Other than the guides, the parts fit together with dovetail joints which should be entirely sufficient to hold the riser together while in place on the printer.
* The dovetail joints were designed with **zero tolerance**. This makes for a perfect tight, but not too tight, fit when I print them on my printer using my slicer settings. I would strongly suggest that you print the provided test joint to ensure that these joints will work for you before printing the whole shebang. Adjust the tolerance if needed.
* The parts called plates are provided for locking the joints. These are optional. The holes are sized for M3 inserts. Resize the holes if you want to self tap screws into the plastic.
* **The thumbscrews are intended to be printed in 95A TPU**. TPU gives good friction and it would be impossible to break the glass by over-tightening the screw.
* The inside holes are meant for hooks/clamps for holding an LED strip. I use a strip with an adhesive backing and don't use these holes for anything, there are example clamp models provided.

### Other Info

The guides should allow the glass to be lifted enough for the handle screws to clear the riser frame for inserting the glass or the glass can be inserted from the rear. There is a spacer meant to go between the guide and the frame. This allows for tighter or looser horizontal tolerance between the glass and the guides. The provided spacer model is 2.1 MM thick. You will need to print 8 of these.

There is an optional glass guide without the threaded hole if you only want to use a single thumbscrew or no thumbscrews. I like using two thumbscrews, as it makes it easy to safely remove the whole riser with the glass in place (just make sure the screws are locked down first).

There is an optional rear brace provided for the inside rear dovetail joint. This part is optional, and really is overkill if you are using the rear plate part, but it's there if you want.

### Print Materials and Settings

Use whatever you want for the frame and guides. PLA or PETG should be fine.

As stated above, I recommend 95A TPU for the thumbscrews. I haven't tried other materials. The purpose of the screws is to hold the glass in place when closed or when open for venting. You could adjust the spacers to achieve enough friction between the glass and the guides to keep the glass in place. I have not tested this.

The front part of the frame must be printed at 45 degrees on a 256 x 256 build plate. I change the sparse infill direction to 0 and the solid infill to 90 to compensate.

I used Orca Slicer's 0.20 MM Strength preset with gyroid for the frame, which I printed in Voxel PLA.

I used the 0.16 MM Optimal preset with gyroid infill for the guides, which were also printed in Voxel PLA.

I used the 0.16 MM Optimal preset with gyroid infill for the thumbscrews, which were printed in Polymaker 95A TPU.

I use scarf joint seam, nearest for my seam settings and I can't even tell where the seams are, but use whatever you prefer.

### Required Extras

* 8 M4 x 12 MM button head screws. Socket cap may be okay, as well, but you might want to use a washer.
* 8 M4 threaded inserts (or resize the holes for self-tapping).
* Optionally, 7 M3 x 8 MM counter-sink socket head screws and M3 inserts (or resize the holes for self-tapping).
* 2 M4 screws and inserts if you want the rear joint brace, but this part isn't really recommended if you are using the three plates that go under the joints.
