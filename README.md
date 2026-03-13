# [TPAMI 2025] DyCrowd: Towards Dynamic Crowd Reconstruction from a Large-scene Video

**[Hao Wen](#)**<sup>💡</sup>, **[Hongbo Kang](https://khb1698.github.io/)**<sup>💡</sup>, **[Jian Ma](https://majian8.github.io/)**, **[Jing Huang](#)**, **[Yuanwang Yang](https://yywqwq.github.io/)**, **[Haozhe Lin](https://www.bnrist.tsinghua.edu.cn/info/1193/3604.htm)**, **[Yu-Kun Lai](https://yukunlai.github.io/)**, **[Kun Li](http://cic.tju.edu.cn/faculty/likun/)**<sup>🌟</sup>

💡Equal Contribution, 🌟Corresponding Author

📄 **[Paper](https://arxiv.org/abs/2508.12644)** | 🌍 **[Project Page](https://cic.tju.edu.cn/faculty/likun/projects/DyCrowd/index.html)** | 💻 **[Code](https://github.com/KHB1698/DyCrowd)** (Coming Soon) | 📂 **[Datasets](#)**

![DyCrowd Framework Overview](assets/fig1.png)

---

## 🎯 Key Features

- The first framework for spatio-temporally consistent 3D reconstruction (pose/position/shape) of hundreds of people from large-scene video
- **Coarse-to-fine group-guided motion optimization** for occlusion-robust crowd reconstruction
- **VAE-based human motion prior** for temporal stability and short-term occlusion recovery
- **Asynchronous Motion Consistency (AMC) loss** to resolve temporal desynchronization and recover long-term occluded motion
- **VirtualCrowd dataset** - a new benchmark with 8 validation videos, 60-200 people, 931 sequences, and 186,200 poses with full 2D/3D annotations

---

## 📊 Dataset: VirtualCrowd

We construct VirtualCrowd, which includes:
- Eight 8K validation videos (60–200 people; 931 sequences; 186,200 poses with 2D/3D annotations)
- Comprehensive annotations for evaluating dynamic crowd reconstruction from large-scene videos

**Requesting the Dataset:** Please contact [hbkang@tju.edu.cn](mailto:hbkang@tju.edu.cn) to request access to the VirtualCrowd dataset.

---

## 📖 Citation

If you find our work useful, please consider citing:

```bibtex
@article{wen2025dycrowd,
  author = {Hao Wen, Hongbo Kang, Jian Ma, Jing Huang, Yuanwang Yang, Haozhe Lin, Yu-Kun Lai and Kun Li},
  title = {DyCrowd: Towards Dynamic Crowd Reconstruction from a Large-scene Video},
  journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year={2025}
}
```

