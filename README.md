# gazebo-models

```bash
cd ~/.gazebo/
mkdir -p models
cd ~/.gazebo/models/
wget http://file.ncnynl.com/ros/gazebo_models.txt
wget -i gazebo_models.txt
ls model.tar.g* | xargs -n1 tar xzvf
```
