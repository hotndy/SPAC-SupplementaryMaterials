This package contains the following:  
__derainFunction.p__: derain input rain frames  
__derain_SPAC_CNN_run.m__: an example for derain  

=================================================  
derainFunction:  
  
Input  : 4D uint8 array of size [h x w x 3 x n]
	 [h w 3] is input rain frame size, and n is the numder of frames
Output : 4D uint8 array of size [h x w x 3 x n], note the first and last 
	 two frames are empty.  
  
Please ensure that MatConvNet is properly installed before running the code.
For the .mex funtions, we regret that only precompiled files for 64 bit Mac and Windows are provided.
=================================================  

__CONTACT:__  
Chen Jie (chen.jie@ntu.edu.sg)

__TERMS OF USE:__   
Any scientific work that makes use of our code should appropriately
mention this in the text and cite our CVPR 2018 paper. 
For commercial use of a faster executable version of our code (10Hz +), please contact Dr. Soh Ling Min (sohlm@stengg.com). 

__PAPER TO CITE:__  
Jie Chen, Cheen-Hau Tan, Junhui Hou, Lap-Pui Chau, and He Li. "Robust Video Content Alignment and Compensation for Rain Removal in a CNN Framework." In Proceedings of IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018.

__BIBTEX TO CITE:__  
@inproceedings{chen2018robust,
  title={Robust Video Content Alignment and Compensation for Rain Removal in a CNN Framework.},
  author={Jie Chen, Cheen-Hau Tan, Junhui Hou, Lap-Pui Chau, and He Li},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2018}
}

Copyright (c) 2018
All rights reserved.
Redistribution and use in source and binary forms, with or without 
modification, are permitted provided that the following conditions are met:
    * Redistributions of source code must retain the above copyright 
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above copyright 
      notice, this list of conditions and the following disclaimer in 
      the documentation and/or other materials provided with the distribution      
    * Proper citation to the paper above
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" 
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE 
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR 
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF 
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN 
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE 
POSSIBILITY OF SUCH DAMAGE.
