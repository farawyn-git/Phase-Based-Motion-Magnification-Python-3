# Phase Based Motion Magnification Python 3

Phase based motion magnification is based on the paper written by Neal Wadhwa, Michael Rubinstein, Frédo Durand, William T. Freeman, ACM Transactions on Graphics, Volume 32, Number 4 (Proc. SIGGRAPH), 2013. Source: https://people.csail.mit.edu/mrub/papers/phasevid-siggraph13.pdf. 

The objective of this project was to adapt the code from https://github.com/jvgemert/pbMoMa in order to be able to run in Python 3
(tested in version 3.10)

### Used Modules   

  - numpy 1.24.2
  - opencv-python 4.7.0.72
  - perceptual 0.1
  - scipy 1.10.1

### Organization
 
    phasebasedMoMag.py      # Main file
    pyramid2arr.py          # Help class to convert a pyramid to a 1d array
    media/guitar.mp4        # Example video
     
You have to exchange the file filterbank.py in the following folder (could be different in your setup):

    ./venv/Lib/site-packages/perceptual

### Example video

    ./media/guitar.mp4
    
When you run the code 'python phasebasedMoMag.py' it expects an example video in the 'media' folder. Here we use the [http://people.csail.mit.edu/mrub/evm/video/guitar.mp4](guitar.mp4) video from the motion magnification website.
