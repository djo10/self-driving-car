# Self driving car

Implementation of autonomous car in simulation environment. Self driving car - beahvioural cloning  

## Simulator
Udacity self driving car simulator : https://github.com/udacity/self-driving-car-sim
Builded simulator (executable):

    [Linux](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f0f7_simulator-linux/simulator-linux.zip)
    
    [macOs](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f290_simulator-macos/simulator-macos.zip)
    
    [Windows 32-bit](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f4b6_simulator-windows-32/simulator-windows-32.zip)
    
    [Windows 64-bit](https://d17h27t6h515a5.cloudfront.net/topher/2016/November/5831f3a4_simulator-windows-64/simulator-windows-64.zip)
    

## Usage

Used Anaconda 3

```python
# Use TensorFlow without GPU
conda env create -f environments.yml 

# Use TensorFlow with GPU
conda env create -f environment-gpu.yml

source activate car-behavioral-cloning
```

### Run autonomous driving

Start simulator, choose the Autonomous Mode 

```python
python drive.py model.h5
```

### To train the model

```python
python model.py
```

