<h1 style="text-align: center;">T-STAR: A Large-Scale Benchmark for Spatio-Temporal Panoptic Scene Graph Generation in Satellite Video</h1>



## 📝 TPSG Task

Given a satellite video sequence, TPSG aims to generate triplets 〈subject, relationship, object〉 with explicit temporal spans to describe dynamic geospatial scenes by jointly modeling identity-consistent instance masks and spatio-temporal relationships among panoptic scene elements.

<p align="center">
  <video src="https://github.com/user-attachments/assets/b7b6b1a1-86b4-4e0b-9189-81827e6d5242" width="98%" controls muted>
    Your browser does not support the video tag.
  </video>
</p>

<table width="98%" align="center">
  <tr>
    <td align="justify">
      <em>Illustration of spatio-temporal panoptic scene graph generation (TPSG) in satellite video.</em>
    </td>
  </tr>
</table>

## 🔖 T-STAR Dataset

We construct T-STAR, the first large-scale dataset for spatio-temporal panoptic scene graph generation (TPSG) in satellite video. It contains more than 1.1 million instance masks and over 3.8 million spatio-temporal triplets across 39 fine-grained object categories and 70 fine-grained relationship categories.

<p align="center">
  <img src="demo/scene.jpg" alt="Representative annotated scenes" width="98%"/>
</p>

<table width="98%" align="center">
  <tr>
    <td align="justify">
      <em>Representative annotated scenes from the T-STAR dataset.</em>
    </td>
  </tr>
</table>

## 🖊️ Citation

If you find this work helpful for your research, please consider giving this repo a star ⭐ and citing our papers:

```bibtex
# SGG in Large-Size Satellite Imagery
@ARTICLE{STAR,
    author={Li, Yansheng and Wang, Linlin and Wang, Tingzhu and Yang, Xue and Luo, Junwei and Wang, Qi and Deng, Youming and Wang, Wenbin and Sun, Xian and Li, Haifeng and Dang, Bo and Zhang, Yongjun and Yu, Yi and Yan, Junchi},
    journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
    title={STAR: A First-Ever Dataset and a Large-Scale Benchmark for Scene Graph Generation in Large-Size Satellite Imagery}, 
    year={2025},
    volume={47},
    number={3},
    pages={1832-1849},
    keywords={Stars;Annotations;Marine vehicles;Satellite images;Visualization;Object detection;Cognition;Benchmark testing;Complexity theory;Bridges;Large-size satellite imagery;object detection;relationship prediction;scene graph generation benchmark},
    doi={10.1109/TPAMI.2024.3508072}}

```
## Acknowledgment
Our code is based on [OpenPVSG](https://github.com/LilyDaytoy/OpenPVSG) in CVPR'23, we sincerely thank them.

<!-- ## 📃 License

This project is released under the [Apache license](LICENSE). Parts of this project contain code and models from other sources, which are subject to their respective licenses. -->
