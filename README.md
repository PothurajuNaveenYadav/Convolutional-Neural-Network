Interpreting the Visualization
The image contains two plots:

Top Plot: "1D Binary Image (Input)"
This represents the 1D binary image as a sequence of pixel values.

Blue dots (●) represent pixel values (0 = white, 1 = black).

Example:
A 1 at index 2 means the pixel is black.
A 0 at index 3 means the pixel is white.

Bottom Plot: "Left Edge Detection Output"
This shows the edge strength at each pixel location.

Red dots (●) indicate edge responses.

The stem lines indicate the detected edges:
Positive values (1) → Left edges (0 → 1 transition)
Negative values (-1) → Right edges (1 → 0 transition)
Zero (0) → No edge detected
