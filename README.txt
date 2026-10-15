7 Tesla fMRI Point-Light Display Experiment Dataset
---------------------------------


This study employed an event-related design within a parallel-group, double-blind, randomized controlled trial. Sixty-three healthy male participants received either 1 mg of Lorazepam or a placebo. During scanning, participants performed a detection task involving dynamic point-light displays that depicted social interactions. They were instructed to observe the stimuli and press a response button whenever a neutral social interaction was presented.

The task included six experimental conditions:

- happy females
- happy males
- angry females
- angry males
- neutral females
- scrambled motion

Each trial began with a fixation cross of variable duration (0.5 to 3.5 seconds, mean: 2 seconds), followed by a stimulus from one of the experimental conditions, presented in random order. The task was completed in two identical consecutive runs, each consisting of 18 presentations per condition, totaling 216 trials. Each trial lasted 3.35 seconds.

The scanning session included preparatory steps, the acquisition of phase and magnitude field map images, high-resolution T1-weighted structural images, and the two functional task runs. The total scanning time was approximately 60 minutes.



fMRI SPECS:
Scanner: 7 Tesla whole-body MRI (Siemens), with a 32-channel head coil.
Functional imaging:
Sequence: T2*-weighted EPI
TR / TE / Flip Angle: 1900 ms / 22 ms / 13°
Slices: 88 sagittal slices, 1.7 mm thick, 40% slice gap
Field of View (FOV): 204 mm
Field map: Used to correct distortions from magnetic field inhomogeneities
TR / TE1 / TE2 / Flip Angle: 400 ms / 5.19 ms / 7.65 ms / 60°
Slices: 37 sagittal, 3.2 mm thick, 25% slice gap
Structural imaging:
Sequence: T1-weighted 3D MPSAGE
TR / TE / Flip Angle: 2500 ms / 2.91 ms / 7°
Slices: 256 sagittal, 0.6 mm thick, 20% slice gap
FOV: 256 mm
Shim: up to 3rd order to reduce magnetic field inhomogeneities (adjusting the magnetic field)


BIDS structure:
  Organized per BIDS v1.0.4 
  sub-XXX/anat  – T1w structural scans  
  sub-XXX/func  – Task-PLDs runs + events 
  sub-XXX/fmap  – Fieldmaps for distortion correction


