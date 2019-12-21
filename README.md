# ml_notebook
Machine Learning Notebook

### Creating the environemnt

```sh
conda create --name ml_opencv
```
which creates environemnt and generates path to it like: `/anaconda3/envs/ml_opencv`.


### Installing tools in the environemnt

 ```sh
source activate ml_opencv
pip install numpy scipy matplotlib scikit-learn jupyter pandas
pip install opencv-contrib-python
pip install dlib
 ```

### Verify the installations

```sh
python3 -c "import numpy, scipy, matplotlib, sklearn, jupyter, pandas, cv2, dlib"
```

### How to activate environemnt

```sh
# List out the environemnts
conda env list

# activate the required environment
# Unix/Linux
source activate <env_name>

# Windows
activate <env_name>
```

### Open Jupyter notebook

```sh
jupyter notebook
```



