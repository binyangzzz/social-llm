# social-llm
基于人情世故数据，人情世故大模型系统包括了常见人际交往中的七大领域（具体可以参考 [场景分类](test/%E5%9C%BA%E6%99%AF%E5%88%86%E7%B1%BB) 中的场景细化细节），其中大体可分为：

```
1.敬酒礼仪文化 Etiquette
  不惧碰杯，酒席桌上一条龙
2.请客礼仪文化 Hospitality
  友好地展示你的友好
3.送礼礼仪文化 Gifting
  此礼非礼，直击人心
4.送祝福 Wishes
  承包你的所有祝福语
5.如何说对话 Communication
  据说是低情商救星
6.化解"尴尬"场合 Awkwardness
  没心没肺，找回自我
7.矛盾&冲突应对 Conflict
  《能屈能伸》
```

## 目录说明

```
data/： 包括了数据集
run/： 包括了演示用前端
test/：这里存放了测试文件以及rag文本知识库
agent/： 包括了agent实现
finetune/： 包括了finetune实现
knowledges/： 包括了rag实现
```
