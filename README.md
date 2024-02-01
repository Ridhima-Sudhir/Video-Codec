# Video-Codec
Undergraduate Capstone Project in the field of Electronics and Communications Engineering. <br>
IEEE Paper link https://ieeexplore.ieee.org/document/9645895 <br>
A dowloaded version of our IEEE paper has been added to this repository.

Summary: <br>
I worked on this project with a team of 3 other peers.<br> A Video Codec is a software that compresses and decompresses a digital video to make the file size smaller for storage and distribution. To design an improved video codec we had to research on the current video encoding trends and compression techniques used. <br> 

My Role: I performed extensive research on the existing standards used and read throguh previous IEEE papers to arrive at the Methodology we used to design our codec. One of my teammates (Sanjana) and I implemented the DWT transform on MATLAB, while the other two implemneted the DCT transform. We spent quite some time trying to figure out which transform would give us better values as the results we obtained for the Compression Ratio and Peak Signal to Noise Ratio value were conflicting. DCT gave us a low CR but a high PSNR and vice-versa for DWT. We finally proceeded with DWT as it did not require each frame to be broken into multiple blocks which would otherwise slow down the process. <br>

Team: <br>Ridhima Sudhir - Performed research on existing best standards to arrive at the methodology used for the project. Implemented the DWT transform and performed bit shifting and Zero Tree Wavelet encoding on the 4 bands. <br>
Sanjana - Implemnted the DWT transform and worked on parallelization. <br>
Gursimran - Implement DCT transform and implemented the pragma functions on the DWT transforms in HLS. <br>
Sangeeta - Implement DCT transform  and performed bit shifting and Zero Tree Wavelet encoding on the 2 bands and worked on the Pragma functions. <br>

Softwares used: MATLAB, Simulink and HLS
