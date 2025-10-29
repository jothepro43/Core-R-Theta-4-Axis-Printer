# The Core R-Theta Printer

This is Joshua Bird's 4 axis, polar, "core-RΘ" 3D printer – an entirely new type of multi axis 3D printer designed from the ground up. 

Check out his [youtube video](https://www.youtube.com/watch?v=VEgwnhLHy3g) to see it in action!
[![Watch the video](https://github.com/user-attachments/assets/1704345d-5ec4-4803-8fbe-49bbeaa76b13)](https://www.youtube.com/watch?v=VEgwnhLHy3g)


### Slicer
A multi axis printer is pretty hopeless without a non-planar slicer, which is why He built this quick [radial slicer](https://github.com/jyjblrd/Radial_Non_Planar_Slicer) for the printer. This leverages the printer's rotating nozzle to print simple parts without supports, but there are some limitations to it which He covers in the YouTube video. He is also working on an optimization based slicer which will be able to print any object without support so stay tuned for that!

<img src="https://github.com/user-attachments/assets/190a966d-61a4-4c94-bd4a-7c1860c525db" width="500" />

### Assembly
There is a wealth of knowledge in the Discussions, Pull Requests and Issues tabs of this repo. The printer is by no means "plug and play", and there are no instructions as of yet, but the information in the discussions should help you get started. Feel free to post questions on the discussions tab.

You can view the [3d model online](https://a360.co/3VdXkRY) to see how to assemble the printer. Everything is 3D printable, however He got the extruder mount made out of metal by JLCPCB as there is quite a bit of torque on that part. He also included the gerber files to make your own PCB buildplate, but a sheet of MDF wood would also work.

### CAD Files
Huge thanks to Bolado in [Discussions](https://github.com/jyjblrd/Core-R-Theta-4-Axis-Printer/discussions/49/) from the original repository for providing a onshape file.  I was able to use that & convert it to Fusion360 file. I modified it to be usable with the materials we had. Bills of Material will be included along with Amazon links.

## Due to Fusion360's large size and it reaching Github's upload limits, I've put the rest of the files in this google drive folder [here](https://drive.google.com/drive/folders/1hgXQBZUpwzEBBKnLD_uq1bWmzUTH4E2e?usp=sharing)


Bibtex Citation:
```
@software{Bird_Core_R-Theta_Printer,
author = {Bird, Joshua},
license = {View repository for custom license.},
title = {{Core R-Theta Printer}},
url = {https://github.com/jyjblrd/Core-R-Theta-4-Axis-Printer}
}
```
