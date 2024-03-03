## Example Usage 1
Here is a simple example of how to use NBAnim to display an animation in a Jupyter Notebook:

```python
from nbanim import NBAnim

# List of image file paths for the frames of your animation
frames = ['path/to/frame1.png', 'path/to/frame2.png', 'path/to/frame3.png']

# Create an instance of NBAnim with the frames and optionally set the animation speed
anim = NBAnim(frames, animation_speed=0.5)
```

## Example Usage 2

```python
import glob
from nbanim import NBAnim

# List of image file paths for the frames of your animation
frames = sorted(glob.glob("~/Downloads/*png"))

# Create an instance of NBAnim with the frames and optionally set the animation speed
anim = NBAnim(frames, animation_speed=0.5)
```
