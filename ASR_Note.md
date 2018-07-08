# 语音识别软件
## 语音识别技术
### 语音识别分类
**根据对说话人的依赖程度，分为：**
- 特定人语音识别（SD）：只能辨认特定使用者的语音，训练→使用。
- 非特定人语音识别（SI）：可辨认任何人的语音，无须训练。
**根据对说话方式的要求，分为：**
- 孤立词识别：每次只能识别单个词汇。
- 连续语音识别：用者以正常语速说话，即可识别其中的语句。

语音识别系统的模型通常由**声学模型**和**语言模型**两部分组成，分别对应于**语音到音节概率**的计算和**音节到字概率**的计算。
### HMM原理
[HMM学习最佳范例一：介绍 | 我爱自然语言处理](http://www.52nlp.cn/hmm-learn-best-practices-one-introduction)

## 科大讯飞
目前科大讯飞开放平台提供以下与语音相关的产品和服务：
- 语音合成
	- 在线语音合成
	- 离线语音合成
- 语音识别
	- 语音听写
	- 语音转写
	- 实时语音转写
	- 语音唤醒
	- 离线命令词识别
- 语音扩展
	- 语音评测
	- 机器翻译
	- 语义理解
- 语音硬件
	- 双麦克风阵列
	- 六麦环形阵列
	- 语音合成芯片
	- xTTS-C离线语音合成
	- 离线识别模块
- 模式识别
	- 人脸识别
	- 声纹识别

开放平台地址：[讯飞开放平台-以语音交互为核心的人工智能开放平台](https://www.xfyun.cn/?ch=bdpp)

语音听写接口文档：[语音听写 · 科大讯飞REST_API开发指南](https://doc.xfyun.cn/rest_api/%E8%AF%AD%E9%9F%B3%E5%90%AC%E5%86%99.html)
## CMU-Sphinx
[语音识别的基础知识与CMUsphinx介绍 - sunfoot - 博客园](https://www.cnblogs.com/qiuhong/articles/3661546.html)
Sphinx是由美国卡内基梅隆大学开发的**大词汇量、非特定人、连续英语语音识别**系统。一个连续语音识别系统大致可分为四个部分：
- 特征提取
- 声学模型训练
- 语言模型训练
- 解码器

## 开源语音识别软件对比
[横评：五款免费开源的语音识别工具 | 雷锋网](https://www.leiphone.com/news/201703/RccQRMCqbgxnFFS3.html)