# HSOD-BIT (V1)

HSOD-BIT (V1), a large-scale dataset for hyperspectral saliency object detection, has been released. The improved version, HOSD-BIT (V2), which has more data and more comprehensive challenges, has been produced and will be released soon.

## Papaer

The paper "DMSSN: Distilled Mixed Spectral-Spatial Network for Hyperspectral Salient Object Detection" has been published and can be viewed at https://ieeexplore.ieee.org/abstract/document/10475351.

## Dataset

#### Description:

HSOD-BIT is the first large-scale, high-quality benchmark dataset for hyperspectral salient object detection, aimed at leveraging the advantages of spectral information to achieve higher precision in salient object detection tasks. Addressing the data requirements of contemporary deep learning models, this dataset provides pixel-level manual annotations for 319 hyperspectral data cubes and generates corresponding pseudo-color images. Each data cube contains 200 bands covering spectral information from visible light to near-infrared bands, with a spatial resolution of up to 1240×1680 pixels. In addition to conventional scenes, this dataset also specifically gathers challenging data to reflect the complexity of the real world, such as similar background interference, uneven lighting, overexposure, and other challenging scenarios. This further enhances the practicality and evaluation capabilities of the dataset.

![1714354809442](C:\Users\24790\AppData\Roaming\Typora\typora-user-images\1714354809442.png)

#### Download:

**Download link:** <https://pan.baidu.com/s/1AsdnO2-nadxTaq9_9Mo3Eg?pwd=tftf>

**Extraction code:** tftf

## Code

The proposed DMSSN method is implemented based on pytorch, and the code has been open source. For details, please see <https://github.com/q2479036243/DMSSN>.

## Citation

If you use this benchmark in your research, please cite this project.

```
@article{qin2024dmssn,
  title={DMSSN: Distilled Mixed Spectral-Spatial Network for Hyperspectral Salient Object Detection},
  author={Qin, Haolin and Xu, Tingfa and Liu, Peifu and Xu, Jingxuan and Li, Jianan},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2024},
  publisher={IEEE}
}
```
