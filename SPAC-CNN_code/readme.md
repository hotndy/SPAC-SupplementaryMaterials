This package contains the following:
computeDepth.m : estimates depth of a LF image
demo.m         : an example for computeDepth.m

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
computeDepth  :

Input  : 5D double array of size [h x w x 3 x v x u]
	 [h w 3] is spatial image size, and [v u] is angular size
Output : depth_output, 2D double array that contains 0-1

An example usage on the Wanner dataset and on our dataset is specified in demo.m

Before use, please compile the .cpp file in the mex folder.
Precompiled files for 64 bit Mac and Windows are provided, if useful.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
CONTACT:
Ting-Chun Wang (tcwang0509@berkeley.edu)

TERMS OF USE : 
Any scientific work that makes use of our code should appropriately
mention this in the text and cite our ICCV 2015 paper. For commercial
use, please contact us.

PAPER TO CITE:
Ting-Chun Wang, Alexei A. Efros, and Ravi Ramamoorthi.
Occlusion-aware depth estimation using light-field cameras. 
In Proceedings of International Conference on Computer Vision (ICCV), 2015.

BIBTEX TO CITE:
@inproceedings{wang2015occlusion,
  title={Occlusion-aware depth estimation using light-field cameras.},
  author={Wang, Ting-Chun and Efros, Alexei and Ramamoorthi, Ravi},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision (ICCV)},
  year={2015}
}

Copyright (c) 2015
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
