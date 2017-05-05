# Deep Coding Baselines by Task
Baseline papers about deep coding ordered by task, date. For each paper there is a permanent link, which is either to Arxiv.org or to a mirror of the original paper in this repository.
# Table of Contents
1. [Dialogue](#dialog)

	1.1. [Datasets](#data-dialog)
	
	1.2. [Dieversity](#dieversity)
	
2. [Code Generation](#code-gen)

	2.1. [Datasets](#data-codegen)

3. [Code Completion](#code-complete)

	3.1. [Datasets](#data-codecompl)

## Dialog
### Datasets
|No|Title|Paper|Blog|Code|
|---|---|---|---|---|
|1|[Ubuntu Dialogue Corpus](https://drive.google.com/open?id=0B_bZck-ksdkpVEtVc1R6Y01HMWM)|[arxiv](https://arxiv.org/abs/1506.08909)|[Tutorial:chatbot-retrieval](http://www.wildml.com/2016/07/deep-learning-for-chatbots-2-retrieval-based-model-tensorflow/)|[corpus collector](https://github.com/npow/ubottu)<br/> [corpus collector v2](https://github.com/rkadlec/ubuntu-ranking-dataset-creator)<br/> [chatbot-retrieval](https://github.com/dennybritz/chatbot-retrieval)|
|2|[OpenSubtitle](https://s3.amazonaws.com/opennmt-trainingdata/opensub_qa_en.tgz)|[arxiv](https://arxiv.org/pdf/1506.05869v3.pdf) | [Tutorial](http://forum.opennmt.net/t/english-chatbot-model-with-opennmt/184)<br/> [opensubtitle website](http://opus.lingfil.uu.se/OpenSubtitles.php)||
|3|[Twitter Corpus](http://homes.cs.washington.edu/~aritter/twitter_chat/)| [pdf](http://www.aclweb.org/anthology/N10-1020)|  |[corpus collector](https://github.com/bwbaugh/twitter-corpus)|

### Diversity

|No|Title|Paper|Data|Code|Blog|Labels|
|---|---|---|---|---|---|---|---|---|
|1| Random Predictor | | | | | | 
|2| TF-IDF Predictor | | | | | |
|3| Dual Encoder LSTM | [SigDial_2015](https://arxiv.org/abs/1506.08909)| [ubuntu corpus](https://drive.google.com/open?id=0B_bZck-ksdkpVEtVc1R6Y01HMWM) | [chatbot-retrieval](https://github.com/dennybritz/chatbot-retrieval)|[tutorial](http://www.wildml.com/2016/07/deep-learning-for-chatbots-2-retrieval-based-model-tensorflow/)| |
|4| Smart Reply: Automated Response Suggestion for Email | [KDD_2016](https://github.com/DeepSE/DeepCodingBaselines/raw/master/papers/smart-reply.pdf)| Gmail Data | | [paper notes](https://gist.github.com/shagunsodhani/da411f15b71ed6a664f9d5ac46409b42)| * | 
|5| A Hierarchical Latent Variable Encoder-Decoder Model for Generating Dialogues | [AAAI_2017](https://github.com/DeepSE/DeepCodingBaselines/raw/master/papers/!2017AAAI-A-Hierarchical-Latent-Variable-Encoder-Decoder-Model-for-Generating-Dialogues.pdf) | |[github](https://github.com/julianser/hed-dlg-truncated) | _None_ | |
|6| Latent Variable Dialogue Models and their Diversity | EACL_2017   |  |  | _None_ |  |
|7| Generating Long and Diverse Responses with Neural Conversation Models | ICLR_2017  | |  | _None_ |  |
|8| Diverse Beam Search:Decoding Diverse Solutions from Neural Sequence Models | 2016 |  |  | _None_ |  |

