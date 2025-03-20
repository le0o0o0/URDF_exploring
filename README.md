# Project name: URDF EXPLORING

<img src="https://placehold.co/900x300?text=Picture%20illustrating%20the%20project"> 

👨‍💻 **Students:** Léo Thévenet, Florian Roy

## 📄 This project in short

Concevoir un robot en 3D sur Fusion360 et générer un package exploitable sur gazebo et Rviz


## 🚀 Quickstart
### Install instructions

Our project requires a working Fusion360 to URDF Plugin installed from https://github.com/dheena2k2/fusion2urdf-ros2

### Launch instructions

First Download the files 
Place the fusion2urdf-ros2 in in your ros2_ws

Go in your Ros2 workspace
```bash
cd ~/model_ws/
colcon build
```
Open a new terminal

```bash
cd ~/model_ws/
source install/setup.bash
ros2 launch (whatever your robot_name is)_description display.launch.py
```

If you want to simulate your robot on gazebo, just run
```bash
ros2 launch (whatever your robot_name is)_description gazebo.launch.py
```

## 📚 References and bibliography
This project is based on the following sources:
- Tutorial A: https://github.com/dheena2k2/fusion2urdf-ros2
- Tutorial B : https://docs.ros.org/en/jazzy/Tutorials/Intermediate/URDF/Exporting-an-URDF-File.html
...

