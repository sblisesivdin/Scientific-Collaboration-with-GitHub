# Experiments or Calculations

This folder is created for collecting the experiment or calculation information. For experiments it can be detailed logs and figures of the experiments. For computational studies, it can be used for collecting input and output files.

## Sample usage

Experiments or calculations can be collected as MD files and related figures or files can be collected in folders with same name

### An experimental study with Photoluminescence and AFM measurements

```
/PL
   Sample1-PL.csv
   Sample2-PL.csv
   Sample1-PL.tiff
   Sample2-PL.tiff
/AFM
   Sample1-AFM-20200510-1.gwy
   Sample1-AFM-20200511-1.gwy
   Sample1-AFM-20200511-2.gwy
   Sample2-AFM-20200510-1.gwy
PL.md
AFM.md
```

Here, PL.md and AFM.md can include details of experiments (used device, used chemicals, laser wavelength, room temperature, any problems, log, lab notebook type usage etc...)

### An computational study of DFT investigation of X material

```
/2atom_calculations
   k777-Ecut-200eV.in
   k777-Ecut-300eV.in
   k777-Ecut-400eV.in
   k777-Ecut-500eV.in
   k777-Ecut-200eV.hdf5
   k777-Ecut-300eV.hdf5
   k777-Ecut-400eV.hdf5
   k777-Ecut-500eV.hdf5
   k777-Ecut-200eV-TotalEnergy.out
   k777-Ecut-30eV-TotalEnergy.out
   k777-Ecut-400eV-TotalEnergy.out
   k777-Ecut-500eV-TotalEnergy.out
   k999-...
   
/54atom_calculations
   k999-Ecut-200eV-Type1.in
   k999-Ecut-200eV-Type2.in
   k999-Ecut-200eV-Type1.hdf5
   k999-Ecut-200eV-Type2.hdf5
   k999-Ecut-200eV-Type1-BandStructure.out
   k999-Ecut-200eV-Type1-DOS.out
   k999-Ecut-200eV-Type1-PDOS.out
   k999-Ecut-200eV-Type1-Optical.out
   k999-Ecut-200eV-Type2-BandStructure.out
   k999-Ecut-200eV-Type2-DOS.out
   k999-Ecut-200eV-Type2-PDOS.out
   k999-Ecut-200eV-Type2-Optical.out

calculation-details.md
```

As it can be seen, there is no rules for the naming of the files. The important thing is the consistency of naming. A contributer must see the the naming scheme used by others and obey that rule.
