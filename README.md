# Phase-Based-Motion-Magnification-Python-3.10
Phase based motion magnification based on https://github.com/jvgemert/pbMoMa
adapted for python 3.10


### Used Modules   

  - numpy 1.24.2
  - openvc-python 4.7.0.72
  - perceptual 0.1
  - scipy 1.10.1

### Organization
 
    phasebasedMoMag.py      # Main file
    pyramid2arr.py          # Help class to convert a pyramid to a 1d array
    media/guitar.mp4        # Example video
     
### Example video

    ./media/guitar.mp4
    
When you run the code 'python phasebasedMoMag.py' it expects an example video in the 'media' folder. Here we use the [http://people.csail.mit.edu/mrub/evm/video/guitar.mp4](guitar.mp4) video from the motion magnification website.
