# Assemble the basic optics module

{{BOM}}

[#1 pozidrive screwdriver]: parts/tools/pozidrive_1_screwdriver.md "{cat:tool}"
[No 2 6.5mm self tapping screws]: parts/mech/SelfTap_PoziPan_No2x6.5_SS.md "{cat:mechanic}"
[M3 nut]: parts/mech/m3_nut.md "{cat:mechanic}"
[M3x10mm cap head screw]: parts/mech/m3x10_screw.md "{cat:mechanic}"
[Raspberry Pi Camera Module v2]: parts/elect/rpi-camera-v2.md "{cat:electronic}"
[Pi camera ribbon cable]: parts/elect/rpi-camera-ribbon-cable.md "{cat:electronic}"
[Pi Camera lens tool]: parts/tools/pi_camera_lens_tool.md "{cat:tool, note: 'This should come with the [Raspberry Pi Camera Module v2].  If it is missing, you can 3D print a workaround lens remover.'}"
[Lens spacer]: models/lens-spacer.stl "{previewpage}"
[Pi Camera platform]: models/camera-platform.stl "{previewpage}"


The imaging optics for this version of the workstation consist of an the Raspberry pi camera and the lens from the camera. To create a microscope the lens is separated from the camera. This makes quite a good microscope objective with a field of view about 950μm across.

## Visually inspect the lens spacer {pagestep}

Take the [lens spacer][Lens spacer](fromstep){qty:1, cat:printedpart} and confirm that:

* It has been printed in black.
* It is dust free (You can blow air through to clean it)
* The central shaft is not obstructed by strings of plastic.

## Remove Pi Camera Lens {pagestep}

>! **Caution!**
>!
>! The camera board is static sensitive.

* Before touching the Pi Camera touch a metal earthed object. If you own one, consider wearing and anti-static strap.
* Take the [Pi Camera][Raspberry Pi Camera Module v2]{qty:1} out of the package. Make sure to **hold it only by the sides of the board**.
* Take the protective film off the lens.
* Take the [Pi Camera lens tool]{qty: 1} and place it over the lens
* Slowly unscrew the lens (About 4 full turns of the tool)
* Carefully lift off the lens.
* Save the lens and the camera, we use both this version of the microscope.

![](images/picam1.png)
![](images/picam2.png)
![](images/picam3.png)

## Push-fit the lens {pagestep}

* Place the pi camera lens on a clean surface with the side that was opposite to the camera sensor on the bottom.
* Push the lens spacer down onto the lens until it clicks into place.

![](images/lens-holder-1.png)
![](images/lens-holder-2.png)
![](images/lens-holder-3.png)

## Attach the Pi Camera {pagestep}

* Take the Pi Camera and place it ontop of the [pi camera platform][Pi Camera platform](fromstep){qty:1, cat:printedpart}.
* Place the lens spacer over the picamera
* Use four [No 2 6.5mm self tapping screws]{qty:4} to secure the three parts together using a [#1 pozidrive screwdriver]{qty:1}
* Take care to not over torque the screws.

![](images/low_cost_optics_assembly_camera.png)

## Attach the mounting screw {pagestep}

* Take an [M3 nut]{qty:1} and push it into the nut trap from the top
* Take an [M3x10mm cap head screw]{qty: 1} and screw it into the nut.
* Only screw it in a couple of turns. About 5 mm of thread should still be visible

![](images/mount-screw.png)
![](images/mount-screw-1.png)
![](images/mount-screw-2.png)

## Connect ribbon cable {pagestep}

* Take the [Pi Camera ribbon cable][Pi camera ribbon cable]{qty:1}
* Pull the catch forward on the exposed Pi Camera connector
* Insert the ribbon cable with the contacts towards the board
* Close the catch on the connector

![](images/low_cost_optics_assembly_ribbon.jpg)
![](images/low_cost_optics_assembly_ribbon_1.jpg)
![](images/low_cost_optics_assembly_ribbon_2.jpg)

Set the [complete optics module]{output, qty:1} aside in a safe place.