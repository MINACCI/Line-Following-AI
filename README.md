# Line-Following-AI
This model has been built using `Keras` and the dataset can be found [here](https://drive.google.com/file/d/1VtCRG3DyGTLXUBg9CF7mN3eK1wpUdjBC/view?usp=sharing).
Each frame of the video below is processed using `opencv`. The script running in [sort_frame.ipynb](https://github.com/MINACCI/Line-Following-AI/blob/main/test/sort_frame.ipynb), sort the frame based on the angle of the tape, when the bounding box become white, the frame is saved in the corresponding folder inside the dataset. The mask applied to the source can be modulate using the `Trackbar` window.

<p align="center">
  <img src="sorting frames demo.gif" width="80%" height="80%"/>
  <br>
</p>

### Output
The model can output three values which are :
- `forward`
- `left`
- `right`

<p align="center">
  <img src="results/images/model result.png"/>
  <br>
</p>
