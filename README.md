Read and plot ASC or [miniSeed, xml pair] or [fullSeed, xml pair] files . The code can also be used to view free field instrument records on the AFAD site in Turkey . Python code reads a zip file containing ASC or [miniSeed, xml pair] or [fullSeed, xml pair]  files that contains three channels (Free-Field instruments have 3 channels)

This is a derivative of the Streamlit ReadV2 application posted as separate application.  

3/17/2025 Absolute trigger for autoranging was failing for earthquake records that have very low accelerations - revised for a dyanmic trigger based on 1/10 maximum absolute value.

3/29/2025 Added new file name scheme used by USGS in records from the Burma Earthquake.

3/30/2025 Changed the way v2C files read, added error catching if file names dont match standards.

4/4/2025 Changed ADRS spectra to be a vertical arrangement rather than horizontal to avoid titles overlapping.  Also implemented a logspace interval for spectra.

5/26/2025 Added ROTD50 spectra and associated ASI computation (with polar gragh plotted against azimuth angles).

5/30/2025 Added Arais Intensity Computation.   Added SI and DSI computation.

6/1/2025 Animation of displacements in 3D added.

Try out at https://appreadv2-8tcju9gckv5rnfcrja59nj.streamlit.app/
