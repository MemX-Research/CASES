# CASES

This repository contains the CASES dataset described in the paper "CASES: A Cognition-Aware Smart Eyewear System for
Understanding
How People Read".

If you use this dataset in your work, please cite our paper:

```
@article{qi2023cases,
  title={CASES: A Cognition-Aware Smart Eyewear System for Understanding How People Read},
  author={Qi, Xiangyao and Lu, Qi and Pan, Wentao and Zhao, Yingying and Zhu, Rui and Dong, Mingzhi and Chang, Yuhu and Lv, Qin and Dick, Robert P and Yang, Fan and others},
  journal={Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies},
  volume={7},
  number={3},
  pages={1--31},
  year={2023},
  publisher={ACM New York, NY, USA}
}

@article{chang2021memx,
  title={MemX: An Attention-Aware Smart Eyewear System for Personalized Moment Auto-capture},
  author={Chang, Yuhu and Zhao, Yingying and Dong, Mingzhi and Wang, Yujiang and Lu, Yutian and Lv, Qin and Dick, Robert P and Lu, Tun and Gu, Ning and Shang, Li},
  journal={Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies},
  volume={5},
  number={2},
  pages={1--23},
  year={2021},
  publisher={ACM New York, NY, USA}
}
```

## Dataset

This data was collected in an e-reading context, and includes 5 native English speakers and 20 participants who speak
English as a second language.A detailed description of the CASES dataset is given in Section 5 of the paper.

The dataset can be downloaded [here](https://drive.google.com/drive/folders/1AZmL1YhUU49ZOmCJKxqWsQUVFIW5nedo).

## Data Format

The CASES dataset has 3 files. Each file is named "x_level_feature", where x is the granularity of the features.

Follows are the brief description of each file.

**word_level_feature.csv**: This CSV file contains the word-level representative visual features,such as reading
times,fixation duration,number of fixations.It also contains annotations about word understading.

**sentence_level_feature.csv**: This CSV file contains sentence-level representative visual features, including dwell
time, saccade times, forward saccade times, and backward saccade times, and all of them normalized by sentence length.It
also contains annotations about
mind wandering and sentence understanding.

**cnn_level_feature.csv**: This CSV file contains the feature that used as the input of Visual+.

