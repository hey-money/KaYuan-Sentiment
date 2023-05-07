## ECE4010 Project
 In this assignment, We develop a sentiment analysis program upon `KaYuan Forum`.

### Dataset
- Training/Validation dataset: [simplifyweibo_4_moods](https://link.zhihu.com/?target=https%3A//pan.baidu.com/s/16c93E5x373nsGozyWevITg) (RATIO = 7:3)    
More than 360,000 posts with emotion tagging Sina Weibo, including 4 types of emotions, including about 200,000 posts of **joy**, and about 50,000 posts each of **anger**, **disgust** and **depression**.

- Testing dataset: Posts crawled from `Kayuan Fourm`  (~ 500 posts)

### Methodology:
- Embedding: [Tencent AI Lab Embedding Corpora for Chinese and English Words and Phrases](https://ai.tencent.com/ailab/nlp/en/embedding.html)

- Model: one-layer GRU with 128 hidden cells

### How to execute:

- **Training**: Execure Part A-E under `model.ipynb`.

- **Testing**: Execure Part A-D&F under `model.ipynb`.

**Note**: As the embedding vector file is too large, please refer to the Tencent link and download the file on your own. The file, named `tencent-ailab-embedding-zh-d200-v0.2.0-s.tar.gz`, should be unzipped and placed under `/vector/` folder.
