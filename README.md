# API_musemu
## 一、产品概述（价值主张）：
为解决博物馆出入游客存在一些安全隐患、人力资源调配不周等问题，我们团队为博物馆推出专属的小程序，也可应用在博物馆内的一些导览设备上，通过结合人脸识别技术、视频审查+语音合成技术、计算机影像技术和语音识别技术等。最大程度上解决博物馆的困扰和最大程度满足访客的需求。

## 二、使用者（博物馆）对产品的需求：

- 博物馆：
  1. 访客量多，安全性难以得到保障，再者，在刷身份证入馆的前提下，甚至有盗用身份证的情况。
（解决需求）所以这时候可以使用我们团队所提出的系统，当访客进入博物馆时，在入口处刷身份证并进行人脸验证快速入场，准确核对信息的同时，减少验票和排队的时间
  2. 游客可能会有意或无意做出一些不文明行为，需要工作人员进行一定的指导和监督。这就造成工作人员需求量大，且不一定能取到有效的效果。
  （解决需求）调用视频审查api，可以全方位并且及时的发现不文明行为，避免造成糟糕的结果，提高了工作效率。 

- 游客：
  1. 文物进行了解向工作人员进行咨询却因沟通障碍造成困扰和尴尬.通上存在障碍，有时候不懂中文想表达的深层含义，理解起来比较困难。
  （解决需求）为博物馆做的电子导览设备或者为移动端所做的小程序中调用语音识别的功能。减少应对不对国家地区人群的翻译解说成本，以及让不同国家地区的参观者可以以自己的母语的方式了解到别国博物馆的文化。
  2. 购买周边商品时，存在没有带现金、现在带不够等情况，导致访客不能购买.
  （解决需求）可以通过人脸支付功能实现无现金购物。
  3. 独自游览的时候，想要更多的了解一下喜欢的展品，可以通过拍照识别展品的方式，快速的得到该展品的相关信息。


## 三、功能说明：
  1. 人脸识别api：（验证信息）
在入闸口增加识别身份证和识别人脸同时进行。验证身份证信息与本人信息是否一致。
  2. 视频审查api+语音合成api（排查现场访客是否存在不文明行为）
针对部分游客的不文明现象，可以通过监控监测到该人的行为超过了预设值，并发出声音播报提醒游客。或者通过手机端（在小程序上）提醒该访客。
  3. 计算机影像：文物识别
通过文本分析及文本翻译，将文物中的详情以及文物上的古文和其中的意境解说出来。
  4. 语音识别：智能翻译
通过文字转语音及语音合成完成用户用语言向产品提交问题，无需手打文字。

## 四、成本效益分析：
1. 成本分析：
前期馆内规划准备及后期开发策划app所需费用为10万元。

可以借用博物馆现有监控设备进行升级，在硬件购置成本上有很大程度的降低。

API调用量视游客数量变化而变化，当游客较多时，API的调用成本更高，与此同时也能为博物馆增加更多营收。

2. 效益分析
投入使用后，每月可节省两名工作人员的负担，每月可节省3500元，app上可在第三个月投入广告，平均前三个月收益预计可达到1500，后期优化app布局，广告收益可达到3000。总体预计可在4.7个月收回成本，后期根据广告收益盈利。

减少检票和部分安检流程，能极高的提升游客的游览体验，同时节省人工成本。

通过分析不同场馆的客流量和逗留时间可以进一步得出游客更加关注的展品类别，为博物馆推出周边产品时提供建议，增加周边产品收益。
