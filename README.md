# meteor-spectrum
Analysis of meteor spectra with windows GUI.

Requires previous calibration of camera, lens and grating combination. Input: video file containing meteor spectrum. Video is converted to video frames. A background image is computed and subtracted from the meteor images. Meteor images are transformed to orthographic projection in order to linearize spectra. These spectra are registered and added. After correcting tilt and slant the 2-D spectra are converted to 1-D spectra by adding rows. These raw spectra are calibrated using known meteor lines for calibration. The result can be plotted.

<b> Update:</b> 

This version runs with Python 3.7. For newer versions of Python some statements are outdated. An updated version of the repository is here:
https://github.com/meteorspectroscopy/meteor-spectrum-calibration
The new version also contains the camera calibration, previoously contained in:
https://github.com/meteorspectroscopy/calibrate-spectrum

Calibration page:
<img src= https://github.com/meteorspectroscopy/meteor-spectrum/blob/master/doc/m_spec%20calibration.PNG>

Result: calibrated meteor spectrum as file wavelength vs. intensity .dat
<img src= https://github.com/meteorspectroscopy/meteor-spectrum/blob/master/doc/m_spec%20plot%20spectrum.PNG>

For a description of the processing see: https://meteorspectroscopy.org/2020/03/27/meteor-spectra-analysis-new-version/
or the manual in the doc folder.

Further information about the theoretical background can be found at https://meteorspectroscopy.org/

