# Python API for AirSim

This package contains Python APIs for [AirSim](https://github.com/microsoft/airsim). It is the same content found in the original repository but has been separated for simplicity.

## How to Use
See examples at [examples/car/hello_car.py](https://github.com/Microsoft/AirSim/blob/master/PythonClient/car/hello_car.py) or [examples/multirotor/hello_drone.py](https://github.com/microsoft/AirSim/blob/master/PythonClient/multirotor/hello_drone.py).

## Dependencies
This package depends on `msgpack` and would automatically install `msgpack-rpc-python` (this may need administrator/sudo prompt):
```
pip3 install msgpack-rpc-python
```

Some examples also requires opencv.

## Installation

```
pip3 install .
```

## More Info

More information on AirSim Python APIs can be found at:
https://github.com/Microsoft/AirSim/blob/master/docs/python.md


## Coodinates System

![Alt Text](./docs/coordinate_systems.png)