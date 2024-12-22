# SDM-Car
Dataset of paper "SDM-Car: A Dataset for Small and Dim Moving Vehicles Detection in Satellite Videos"

This dataset is being used in the 2024 "Oriental Spaceport Earth Satellite II Cup" Remote Sensing Image Intelligent Processing Algorithm Competition, Track 2 "Dim Target Detection and Tracking". At the current stage, our training set can be accessed through "[http://rsipac.whu.edu.cn](http://rsipac.whu.edu.cn)". We will publish our complete dataset and code after the competition.

More information about SDM-Car is cooming soon ...
## Download
You can now download the complete datasets directly from the links of Baidu Cloud Drive and Google Cloud Drive below:

[Baidu](https://pan.baidu.com/s/1dOJQoppE2kC_-Xuah1tT8A?pwd=46fx)  [Google](https://drive.google.com/file/d/1aK08IFIPOO_Z2Z3MqWqssqu2eRRHxdg_/view)

SDM-Car contains 99 video sequences for Moving Vehicles Detection and Tracking, of which 64 are used as training sets, 15 are used as validation sets, and 20 are used as test sets. All data were taken by Luojia-3-01 satellite, with a spatial resolution of 0.75m.

<img src="diversity.png" width = 60%>

## Data
SDM-Car contains 99 video sequences for Moving Vehicles Detection and Tracking, of which 64 are used as training sets, 15 are used as validation sets, and 20 are used as test sets. All data were taken by Luojia-3-01 satellite, with a spatial resolution of 0.75m.

<img src="diversity.png" width = 60%>

The **train**, **test**, and **validation** directories share the same structure.

The annotation file `gt.txt` contains information in the following format:

​	Each column corresponds to the following values in order:

- **Frame ID**: The index of the video frame.
- **Target ID**: A unique identifier for each target object.
- **Bounding Box x**: The x-coordinate of the top-left corner of the bounding box.
- **Bounding Box y**: The y-coordinate of the top-left corner of the bounding box.
- **Bounding Box Width**: The width of the bounding box.
- **Bounding Box Height**: The height of the bounding box.
- **Target Class**: The category of the target object, fixed as `1` to represent vehicles.
- `-1`, `-1`, `-1`: Reserved fields, consistently set to `-1`.

## Citation

If you find our work useful in your research, please consider citing:

    @ARTICLE{10746500,
      title={SDM-Car: A Dataset for Small and Dim Moving Vehicles Detection in Satellite Videos}, 
      author={Zhang, Zhen and Peng, Tao and Liao, Liang and Xiao, Jing and Wang, Mi},
      journal={IEEE Geoscience and Remote Sensing Letters}, 
      year={2024},
      publisher={IEEE}
    },
