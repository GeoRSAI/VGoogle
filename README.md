# VGoogle
A remote sensing image dataset constructed from the Google World Imagery using the V-RSIR tool. 

<b>Author</b>: Dongyang Hou

## Data description

VGoogle dataset covers 38 classes (see Table 1) and contains a total of 59,404 images. Each class contains at least 1500 images with spatial resolutions ranging from 0.07 m to 9.555 m. Each class contains at least 1500 images with spatial resolutions ranging from 0.07 m to 9.555 m. Figure 1 represents the spatial distribution of the VGoogle dataset. Without affecting the data accuracy, the team converted the original dataset from RGBA four-channel to RGB three-channel and converted the images from tiff format to jpg format on December 14, 2021, reducing the dataset storage space from 8.70 GB to 2.66 GB.

### Fig. 1 Spatial distribution of images from the VGoogle

![image-20230328130111559](https://github.com/GeoRSAI/VGoogle/blob/master/figures/spatial_distribution.png)

### Table 1 Class name

| Class                | Code | Class             | Code | Class                       | Code |
| -------------------- | ---- | ----------------- | ---- | --------------------------- | ---- |
| airplane             | 0    | forest            | 14   | runway                      | 28   |
| baseball  field      | 1    | freeway           | 15   | runway  marking             | 29   |
| basketball  court    | 2    | golf  course      | 16   | shipping  yard              | 30   |
| beach                | 3    | harbor            | 17   | solar  panel                | 31   |
| bridge               | 4    | intersection      | 18   | sparse  residential         | 32   |
| cemetery             | 5    | mobile  home park | 19   | storage  tank               | 33   |
| chaparral            | 6    | nursing  home     | 20   | swimming  pool              | 34   |
| christmas  tree farm | 7    | oil  gas field    | 21   | tennis  court               | 35   |
| closed  road         | 8    | oil  well         | 22   | transformer  station        | 36   |
| coastal  mansion     | 9    | overpass          | 23   | wastewater  treatment plant | 37   |
| crosswalk            | 10   | parking  lot      | 24   |                             |      |
| dense  residential   | 11   | parking  space    | 25   |                             |      |
| ferry  terminal      | 12   | railway           | 26   |                             |      |
| football  field      | 13   | river             | 27   |                             |      |

## Download link
Download dataset from the following link: (We recommend using the compressed version.)
- [Compressed version (code is `lv9i`)](https://pan.baidu.com/s/1OLImdhJpOtwNgQYiDYJGqA)
- [Uncompressed version (code is `og5s`)](https://pan.baidu.com/s/1_kBTYg8gg9nyv0Ci3zXMdA)

## License
This dataset is for scientific research use only and should not be used commercially. When using it, please cite the following references. 

[1] Hou Dongyang; Miao Zelang; Xing Huaqiao*; Wu Hao*; V-RSIR: an Open Access Web-based Image Annotation Tool for Remote Sensing Image Retrieval, IEEE Access. 2019, 7: 83852-83862.

[2] Hou Dongyang; Miao Zelang; Xing Huaqiao*; Wu Hao*; Two Novel Benchmark Datasets from ArcGIS and Bing World Imagery for Remote Sensing Image Retrieval, International Journal of Remote Sensing. 2021, 42(1): 240-258. doi: 10.1080/01431161.2020.1804090.
