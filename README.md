# UpBEV-Based Drivable Region Detection (UpBEV-DRD)
***UpBEV*** is a novel representation paradigm for LiDAR data, organizing the data into a more compact style. It can not only keep part of the spatial relationship between points but also make the data processing more efficient. Especially, it can transform the 3D boundary of a drivable region into edges in a 2D image. To the best of our knowledge, this is the first work to utilize UpBEV for drivable region detection. Based on UpBEV, a complete framework for drivable region detection is proposed, which is the best-performing non-learning method on [KITTI-road-benchmark](https://www.cvlibs.net/datasets/kitti/eval_road.php) in terms of MaxF (**93.18%**) and speed (**<10ms 1core@4.0GHz**).

## 1. Features of UpBEV-DRDet
* A **complete framework of drivable region detection based on UpBEV**. Dense drivable regions can be directly generated from the UpBEV representation.
* **Accurate and Super Fast**. UpBEV-DRDet can run at more than 100Hz on a core of CPU clocked at 4.0GHz, and achieve the highest MaxF of 93.25% on the KITTI-road-benchmark.
* **Non-learning method**. UpBEV-DRDet is a non-learning method, which can be easily deployed on various platforms with different computing resources.

## 2. About this repo
### 2.1 Hope this repo can help you
If you find our repo helpful for your research, please cite our paper. Thank you!

Author and Contributor: [Hao Wen](https://scholar.google.com/citations?user=823HzfIAAAAJ&hl=zh-CN) and [Chunhua Liu](https://scholar.google.com/citations?user=7WEZSaIAAAAJ&hl=zh-CN) from EEPT Lab at CityU.

Paper: [UpBEV: Fast and Accurate LiDAR-Based Drivable Region Detection Utilizing Uniform Polar BEV](https://ieeexplore.ieee.org/document/10496244), Hao Wen, Tianci Wang, Yong Chen, and Chunhua Liu, T-IV, Regular Paper
```
@ARTICLE{10496244,
  author={Wen, Hao and Wang, Tianci and Chen, Yong and Liu, Chunhua},
  journal={IEEE Transactions on Intelligent Vehicles}, 
  title={UpBEV: Fast and Accurate LiDAR-Based Drivable Region Detection Utilizing Uniform Polar BEV}, 
  year={2024},
  volume={},
  number={},
  pages={1-11},
  keywords={bird's eye view;LiDAR-based perception;drivable region;motion planning;autonomous vehicles},
  doi={10.1109/TIV.2024.3387330}}
```

### 🚧 Code Refinement in Progress 🚧

We are currently organizing the code to make it more readable and user-friendly, aiming to present it as comprehensively as possible. Thank you for your patience and support! 💖
