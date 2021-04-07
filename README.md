# BERT-whitening
通过简单的向量白化来改善句向量质量，可以媲美甚至超过BERT-flow的效果。

## 介绍
- 博客：https://kexue.fm/archives/8069
- 论文：[《Whitening Sentence Representations for Better Semantics and Faster Retrieval》](https://arxiv.org/abs/2103.15316)

## 使用

- [eng](https://github.com/bojone/BERT-whitening/tree/main/eng): BERT-whitening在常见英文数据集上的测试；
- [zhn](https://github.com/bojone/BERT-whitening/tree/main/zhn): BERT-whitening在常见中文数据集上的测试。

测试环境：tensorflow 1.14 + keras 2.3.1 + bert4keras 0.10.5，如果在其他环境组合下报错，请根据错误信息自行调整代码。

## 引用
```
@article{su2021whitening,
  title={Whitening Sentence Representations for Better Semantics and Faster Retrieval},
  author={Su, Jianlin and Cao, Jiarun and Liu, Weijie and Ou, Yangyiwen},
  journal={arXiv preprint arXiv:2103.15316},
  year={2021}
}
```

## 其他

PyTorch版：https://github.com/autoliuweijie/BERT-whitening-pytorch

## 交流
QQ交流群：808623966，微信群请加机器人微信号spaces_ac_cn
