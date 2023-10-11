# Mydaq Potentiostatic Sytem
A potentiostatic system. This repository includes LabVIEW virtual instruments and 3D models for 3D printing of electrochemical cell containers.

## 3D model descriptions
All 3D models were constructed using Freecad, to this date they are yet compatible with Freecad version 0.21. STL versions are included, since they are more universal.

The file `CellBody.FCStd` contains the 3D model for an electrochemical cell container, reference electrode should be inserted from above in such a way that it doesn't touch the working electrode, working electrode is fixed from below using the screw included in the `Screw.FCDtd` file. Counter electrode should be rested carefully in the diagonal stand. Some modifications may be needed to match every electrode shape. An o-ring should stay between the container and the working electrode to prevent any leaking from this union.

If the cell container is 3D printed, using very high fill percentages could reduce the risk of fluid leakages, but more importantly, the thickness of the outer layers can reduce this potential problem by increasing the parallelism between each layer and thus reducing the gaps produced by crossed filament lines. A setting of 4 outer 0.4 mm lines for the outer layers in Prusa Slicer seemed to be more than enough.
