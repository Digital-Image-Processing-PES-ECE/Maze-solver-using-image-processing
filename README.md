# Project Name
# Maze_Solver using Image processing
### Project Description:
#### Summary - 
The Maze Solver project demonstrates image processing techniques to detect and
trace a path in a binary maze image. Using Open-CV, the algorithm performs
thresholding, contour extraction, morphological operations, and bit wise
manipulations to identify and highlight the solution path.
#### Course concepts used - 
1. -Thresholding
2. -grayscaling
3. -contour detection
4. -dilation
5. -erosion
6. -masking    
#### Novelty - 
The project leverages morphological transformations to address maze-solving, 
ensuring robustness against noise and imperfections in the inpuimage, 
it consists of wide range on application like in natural disasters like earthquake 
where small robots can be used to rescue.   
### Contributors:
1. Yashas V(PES1UG22EC352)
2. Shreekara R Dandina(PES1UG22EC276)

### Steps:
1. Clone Repository
```git clone https://github.com/Digital-Image-Processing-PES-ECE/Maze-solver-using-image-processing.git ```

2. Install Dependencies
```pip install -r requirements.txt```

3. Run the Code
```python Maze_solver.py```

### Outputs:
## Input maze<br>
![image](https://github.com/user-attachments/assets/c2a1bffa-6cdc-4dee-83fa-1595c8a00f6c)
## Thresholding<br>
![image](https://github.com/user-attachments/assets/0e9125bb-3b4f-4159-b601-e8b3d311ab2b)
## Contour detection<br>
![image](https://github.com/user-attachments/assets/ef642636-47e9-4ab3-a956-167189e3a976)
![image](https://github.com/user-attachments/assets/cdd535c5-b6eb-44ea-8112-8f7493159cff)
## Dilation<br><br>
![image](https://github.com/user-attachments/assets/075ac21e-749d-4980-a2ea-65173a92636e)
## Erosion<br>
 ![image](https://github.com/user-attachments/assets/07ac205a-2a83-483d-a5a5-19355b7b4235)
## Masking<br>
 ![image](https://github.com/user-attachments/assets/8ac609ec-9919-4731-aac5-d3682f55adc6)
## Solved_maze<br>
![image](https://github.com/user-attachments/assets/349c5b84-a804-4814-afc9-896cfa89b8c5)


### References:
1. -OpenCV Documentation: https://docs.opencv.org
2. -Gonzalez, R. C., & Woods, R. E. (2008). Digital Image Processing.
3. -https://www.youtube.com/@Aryanverma2infoaryan
  
### Limitations and Future Work:
This program cannot solve mazes other than square or a rectangular type mazes.
In future work we can implement the code with a physical working robot.
