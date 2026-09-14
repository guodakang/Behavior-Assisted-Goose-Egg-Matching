<img width="678" height="268" alt="image" src="https://github.com/user-attachments/assets/b44a5344-3ae3-4d6e-bd79-3a449da4daa1" />## Two-stream motion-saliency-guided temporal VideoMAE for egg-laying straining behavior recognition in breeder geese housed in small-group natural mating cages

## ✨ Overview
Accurate individual egg-laying records are essential for reproductive performance evaluation, high-producing breeder selection, and breeding-population optimization in breeder geese. However, under **small-group housing in natural mating cages**, multiple female breeder geese share limited laying space, making egg-to-goose attribution difficult when relying only on egg location and spatial relationships.

To address this problem, this study introduces **egg-laying straining behavior** as supplementary behavioral evidence for individual egg attribution and proposes a **Two-Stream Motion Saliency-Guided Temporal VideoMAE (Two-Stream MSGT-VideoMAE)**.

The proposed framework jointly exploits:

- **RGB video** for appearance and posture representation;
- **Optical flow** for motion dynamics;
- **Motion-Guided Patch Selection (MGPS)** for emphasizing motion-salient local regions;
- **Cross-Frame Temporal Association (CFTA)** for modeling continuous temporal evolution;
- **Adaptive Dual-Modal Fusion (ADMF)** for dynamically exploiting complementary RGB and optical-flow information.

The complete framework was further integrated into a behavior-assisted egg–goose matching system and validated under real farm conditions for continuous individual egg-laying monitoring.


<img width="10083" height="3974" alt="图解摘要" src="https://github.com/user-attachments/assets/dacc6980-09a0-4c61-a75b-e9edf2280974" />

## 📂 Datasets

To access the **datasets and code** used in this study, please ensure that all files are downloaded from the following Baidu Netdisk link: 
[https://pan.baidu.com/s/1F38LGUh4Ip3_Bi1uTmkqtQ](https://pan.baidu.com/s/1zdF-gntpCQ2yL4EXGHk8pg) 
Extraction code：please email at 1395401554@qq.com

Examples of the Daytime and Night-time datasets are shown below:

<img width="4187" height="3596" alt="数据集" src="https://github.com/user-attachments/assets/cf60b226-af78-4a6e-a58f-5ae333df116c" />
A pseudocode overview of the proposed method is provided below:
<img width="518" height="646" alt="伪代码" src="https://github.com/user-attachments/assets/bd31da12-40d8-401e-af7f-06734b6a217f" />




