# MFT_DATASETS
The resources of MFT series datasets.

<div align="center">
<img src="assets/MFT_samples.png" width="900"/>
</div>

Contact: vranlee@cau.edu.cn and weiranli@u.nus.edu. Any questions or discussion are welcome!

-----

## Updates
+ [2025.02.27] We update the BrackishMOT-M4FT dataset which is utilized in M^4FT.
+ [2024.07.23] Thanks for your attention! We have initialized this repo, and 4 clips of the MFT_DATASET (VER.24) is released now.

## Baseline Performance

### State-of-the-art Methods Comparsion on MFT Dataset (VER.24)

Method  | Paradigm | IMT ↑ | Method  | Paradigm | IMT ↑ | Method  | Paradigm | IMT ↑ |
---------|----------|--------|---------|----------|--------|---------|----------|--------|
SORT   | SDE | 1.67 |   TransCenter   | TranF | 0.45 | CenterTrack   | JDE | 0.54 |
DeepSORT   | SDE | 1.09 |  TrackFormer   | TranF | 0.46 | FairMOT   | JDE | 1.55 |
Trackor   | SDE |  0.85  | **TFMFT**  | **TranF** | **1.22** | CMFTNet   | JDE | 1.70 |
ByteTrack   | SDE | 0.83 | | | | **P2PMFT**$^\dagger$   | **JDE** | **3.20** |
**QDTrack**   | **SDE** | **1.68** | | | | **P2PMFT**   | **JDE** | **1.74** |
OC-SORT   | SDE | 1.01 |

* **P2PMFT**$^\dagger$ incorporates the PMNet-Light backbone. 
* **TranF** refers to Transformer architecture.

## Download
The datasets can be downloaded here:   

+  **(New)** **BrackishMOT-M4FT.zip [[GoogleDrive]](https://drive.google.com/drive/folders/1wZiD702m6Nyje58PzWBT5jEKm4Mt1E9B?usp=drive_link) [[BaiduYun: evbh]](https://pan.baidu.com/s/1t5Eg8honnc4UX4AT1NxNpw?pwd=evbh)**
+  **MFT24_Samples.tar [[BaiduYun: 5ic5]](https://pan.baidu.com/s/1NDpHi9f1BK_qLpglpWjvxQ?pwd=5ic5)**
+  **OptMFT_Samples.tar.gz: [[Onedrive]](https://1drv.ms/u/s!AiAYwd6-_n-fmmDxKUh81f5nylZv?e=61bjeO) [[BaiduYun: hfg1]](https://pan.baidu.com/s/1-R3kyzkm8iNNKD7AIombNg)**

+ Using the ***gen_data_path_sample.py*** to generate the training json files.

## Citation
We are still preparing a large dataset for MFT (will be updated in this repo), which will include the video clips of this version. You can look up our other repos for MFT resources: [**\[M4FT\]**](https://github.com/vranlee/M-4-FT) [**\[P2PMFT\]**](https://github.com/vranlee/P2PMFT/) [**\[CMFTNet\]**](https://github.com/vranlee/CMFTNet/) [**\[TFMFT\]**](https://github.com/vranlee/TFMFT/).
