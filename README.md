# SEUMLD

SEUMLD: Southeast University Multimodal Lie Detection Dataset

## Abstract:

To address the lack of Chinese-context-based lie detection datasets in current research, we have developed ***SEUMLD***, **the first publicly available multimodal lie detection dataset based on Chinese conversations**. SEUMLD includes data from three modalities: **video**, **audio**, and **electrocardiogram (ECG)** signals, as illustrated in Figure 1. To effectively motivate participants to lie, we designed **simulated crime** and **interrogation** experimental paradigms, as shown in Figure 2. By capturing participants' multimodal signals during the simulated interrogation process, SEUMLD collects data from 76 participants who have long been immersed in a Chinese language environment, resulting in a total of 3,224 conversation segments. The dataset offers both **coarse-grained** annotations for identifying whether a participant is lying in a full-length conversation and **fine-grained** annotations that provide precise segmentation of each conversation.

<img src="SEUMLD.png" alt="image-20241218095520013" style="zoom:30%;" />

## Dataset files:

The **Original** folder contains the raw interrogation data for video, audio, and ECG (organized by participant IDs), as well as files for cross-validation data splits.

The **Preprocess** folder contains the video and audio data segmented at a fine-grained level (named using participant IDs and question numbers).

The **Labels** folder includes coarse-grained lie detection experiment label files, fine-grained lie detection experiment label files, and timestamps indicating the start of the interrogation in the ECG signals.

The **Questions** folder contains the details of the 46 questions asked during the interrogation, along with their corresponding question types.

## Application:

**If you want to apply for this database, please download the license and follow the introduction.**

## Reference:
Xu Xiaolin， Zheng Wenming， Lian Hailun， Li Sunan， Liu Jiateng， Liu Anbang， Lu Cheng， Zong Yuan， Liang Zongbao. 2025. Multimodal lie detection dataset based on Chinese dialogue. Journal of Image and Graphics， 30(8):2729-2742 DOI： 10.11834/jig.240571.
徐啸林， 郑文明， 连海伦， 李溯南， 刘佳腾， 刘安邦， 路成， 宗源， 梁宗保. 2025. 基于中文对话的多模态谎言检测数据集. 中国图象图形学报， 30(8):2729-2742 DOI： 10.11834/jig.240571.

## BibTex:
@article{xu2025multimodal,
  title={Multimodal lie detection dataset based on Chinese dialogue},
  author={Xu, Xiaolin and Zheng, Wenming and Lian, Hailun and Li, Sunan and Liu, Jiateng and Liu, Anbang and Lu, Cheng and Zong, Yuan and Liang, Zongbao},
  journal={Journal of Image and Graphics},
  volume={30},
  number={8},
  pages={2729--2742},
  year={2025}
}


