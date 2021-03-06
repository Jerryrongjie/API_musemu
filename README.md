# API_musemu

|   产品名字  |  博物馆导览APP   |
| --- | --- |
|    文件状态 | 基本完成  |
|    文件主人 | 叶荣杰  |
|    文件设计者 |  叶荣杰  |

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
![产品架构图](https://github.com/Jerryrongjie/API_musemu/blob/master/%E5%8E%9F%E5%9E%8B%E5%9B%BE/%E5%8D%9A%E7%89%A9%E9%A6%86%E5%AF%BC%E8%A7%88app.jpg)

  1. 人脸识别api：（验证信息）
在入闸口增加识别身份证和识别人脸同时进行。验证身份证信息与本人信息是否一致。

![入门检测功能](https://github.com/Jerryrongjie/API_musemu/blob/master/%E5%8E%9F%E5%9E%8B%E5%9B%BE/1_1_%E5%85%A5%E9%97%A8%E6%A3%80%E6%B5%8B.jpg)

  2. 视频审查api+语音合成api（排查现场访客是否存在不文明行为）
针对部分游客的不文明现象，可以通过监控监测到该人的行为超过了预设值，并发出声音播报提醒游客。或者通过手机端（在小程序上）提醒该访客。

![安全检测](https://github.com/Jerryrongjie/API_musemu/blob/master/%E5%8E%9F%E5%9E%8B%E5%9B%BE/1_2_%E5%8F%8A%E6%97%B6%E6%8F%90%E9%86%92.jpg)

  3. 计算机影像：文物识别
通过文本分析及文本翻译，将文物中的详情以及文物上的古文和其中的意境解说出来。

![展品识别](https://github.com/Jerryrongjie/API_musemu/blob/master/%E5%8E%9F%E5%9E%8B%E5%9B%BE/1_3_%E8%AE%A1%E7%AE%97%E6%9C%BA%E8%A7%86%E8%A7%89.jpg)

  4. 语音识别：智能翻译
通过文字转语音及语音合成完成用户用语言向产品提交问题，无需手打文字。

![语音助手](https://github.com/Jerryrongjie/API_musemu/blob/master/%E5%8E%9F%E5%9E%8B%E5%9B%BE/1_4_%E8%AF%AD%E9%9F%B3%E5%8A%A9%E6%89%8B.jpg)


### 原型文档 已上传至 Github Pages [链接](https://jerryrongjie.github.io/API_musemu/)




## 四、成本效益分析：
1. 成本分析：
前期馆内规划准备及后期开发策划app所需费用为10万元。

可以借用博物馆现有监控设备进行升级，在硬件购置成本上有很大程度的降低。

API调用量视游客数量变化而变化，当游客较多时，API的调用成本更高，与此同时也能为博物馆增加更多营收。

2. 效益分析
投入使用后，每月可节省两名工作人员的负担，每月可节省3500元，app上可在第三个月投入广告，平均前三个月收益预计可达到1500，后期优化app布局，广告收益可达到3000。总体预计可在4.7个月收回成本，后期根据广告收益盈利。

减少检票和部分安检流程，能极高的提升游客的游览体验，同时节省人工成本。

通过分析不同场馆的客流量和逗留时间可以进一步得出游客更加关注的展品类别，为博物馆推出周边产品时提供建议，增加周边产品收益。


---
## PRD 价值主张设计 15%
### PRD1.加值宣言 3%
加值宣言：
1. 人脸识别能够大大的降低人工检票的时间和人工成本，也可以极大的提高游客的体验，缩短排队时间。
2. 视频审查+语音合成，帮助管理人员第一时间提醒游客的不文明行为，减少了他们的工作负担，也提高了展品安全性。
3. 计算机视觉，降低讲解人员的工作负担，也可以在人流量较多的时候满足游客了解展品的需求，提高满意度。
4. 无障碍设计，帮助残障人士提高游览体验。

### PRD2.核心价值 3%
核心价值宣言：解放游客，让观展无拘无束。

### PRD3.核心价值与用户痛点 3%
用户痛点宣言：
  1. 减少游客的束缚，不需要处处被工作人员关注。
  2. 提高游览体验，人多人少都可以自主游览。
  3. 无障碍设计，让残障人士得到应有的服务。

### PRD4.人工智能概率性与用户痛点 3%
AI概率性考量：
1. 计算机视觉的准确率约为94%，在软件调试时要严格审查说明文本和展品的对应性。
2. 语言合成文本也需要人工提前检验，以防部分文学古籍中与现代不同的字词读音的错误解读。

### PRD5.需求列表与人工智能API加值 3%

需求 | 加值
--- | --- 
博物馆高峰时期人流量太多，排队太长。 | 人脸识别搭配身份证刷卡，减少排队时间。
讲解员无法同时使用多种语言，为所有人讲解 | 语音合成，帮助游客了解展品故事。
人流量多时，安检巡查变得更加困难 | 视频审查&语音合成，及时提醒游客文明参观。
残障人士游馆体验差，无法了解全面的信息 | 语音助手帮助残障人士解决困难。


## API 完整示例代码 [链接](https://github.com/Jerryrongjie/API_musemu/blob/master/_musemu.ipynb)

- Azure 人脸识别
  - 输入：人脸图像url
  - 输出：人脸识别信息

```
import requests
from IPython.display import HTML
import matplotlib.pyplot as plt
from PIL import Image
from matplotlib import patches
from io import BytesIO


subscription_key = 'YourSubscriptionKey' # 改成自己的Key
assert subscription_key
face_api_url = 'https://face-jerry.cognitiveservices.azure.com/face/v1.0/detect' # 改成自己的站点


headers = { 'Ocp-Apim-Subscription-Key': subscription_key }
    
params = {
    'returnFaceId': 'true',
    'returnFaceLandmarks': 'false',
    'returnFaceAttributes': 'age,gender,headPose,smile,facialHair,glasses,emotion,hair,makeup,occlusion,accessories,blur,exposure,noise',
}

def annotate_image(image_url):
    response = requests.post(face_api_url, params=params, headers=headers, json={"url": image_url})
    faces = response.json()

    image_file = BytesIO(requests.get(image_url).content)
    image = Image.open(image_file)

    plt.figure(figsize=(8,8))
    ax = plt.imshow(image, alpha=0.6)
    for face in faces:
        fr = face["faceRectangle"]
        fa = face["faceAttributes"]
        origin = (fr["left"], fr["top"])
        p = patches.Rectangle(origin, fr["width"], \
                              fr["height"], fill=False, linewidth=2, color='b')
        ax.axes.add_patch(p)
        plt.text(origin[0], origin[1], "%s, %d"%(fa["gender"].capitalize(), fa["age"]), \
                 fontsize=20, weight="bold", va="bottom")
    plt.axis("off")
    
annotate_image("https://how-old.net/Images/faces2/main007.jpg")
```
- Azure 计算机视觉
  - 输入： 图像url
  - 输出： 图像描述
  
```
import http.client, urllib.request, urllib.parse, urllib.error, base64
import requests
import json

headers = {
    # Request headers
    'Content-Type': 'application/json',
    'Ocp-Apim-Subscription-Key': 'YourSubscriptionKey', # 改成自己的key
}

params = urllib.parse.urlencode({
    # Request parameters
    'visualFeatures': 'Description',
    'language': 'zh',
})

url = 'https://xxx/vision/v2.0/analyze' # 改成自己的站点
image_url = 'https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1578645908953&di=46e321d21c2277d40e9c1897a3b38b21&imgtype=0&src=http%3A%2F%2F5b0988e595225.cdn.sohucs.com%2Fq_70%2Cc_zoom%2Cw_640%2Fimages%2F20180621%2Fbb1ecbe5854a4bbab310fee4811e2be5.jpeg' # 可以修改图片的地址

response = requests.post(url, params=params, headers=headers, json={"url": image_url})
vison = response.json()

print(vison)
```

- Azure 语音合成

  - 输入： 文本
  - 输出： 音频文件（wav格式）

```
import azure.cognitiveservices.speech as speechsdk

# Creates an instance of a speech config with specified subscription key and service region.
# Replace with your own subscription key and service region (e.g., "westus").
speech_key, service_region = "YourSubscriptionKey", "eastasia"  # 你的key 和站点
speech_config = speechsdk.SpeechConfig(subscription=speech_key, region=service_region)

# Creates an audio configuration that points to an audio file.
# Replace with your own audio filename.
audio_filename = "helloworld.wav"  # 文件名称
audio_output = speechsdk.AudioOutputConfig(filename=audio_filename)

# Creates a synthesizer with the given settings
speech_synthesizer = speechsdk.SpeechSynthesizer(speech_config=speech_config, audio_config=audio_output)

# Synthesizes the text to speech.
# Replace with your own text.
text = "Hello world!"  
result = speech_synthesizer.speak_text_async(text).get()

# Checks result.
if result.reason == speechsdk.ResultReason.SynthesizingAudioCompleted:
    print("Speech synthesized to [{}] for text [{}]".format(audio_filename, text))
elif result.reason == speechsdk.ResultReason.Canceled:
    cancellation_details = result.cancellation_details
    print("Speech synthesis canceled: {}".format(cancellation_details.reason))
    if cancellation_details.reason == speechsdk.CancellationReason.Error:
        if cancellation_details.error_details:
            print("Error details: {}".format(cancellation_details.error_details))
    print("Did you update the subscription info?")
```
