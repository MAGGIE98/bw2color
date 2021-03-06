
# 预期目标

## 项目目标

我们的项目最终将采取前后端分离的模式，借助服务器进行发布测试、运行。

**前端**
    
    前端部分，我们采用flask框架搭建，使用bootstrap进行页面的美化工作。
  
**后端**

    后端我们将使用MySQL作为我们的管理数据库，使用Python搭建服务端，并采用tensorflow人工智能学习系统与消息队列作为保存消息的容器，从而完善后端开发。
    
    当用户通过前端访问该功能时，后端会打包一个带鉴权的API供用户使用，此时前端和客户端请求API，读取并返回json中的地址并加载图片。从而达到接收用户请求与需处理的照片并返回处理完成的图片供用户导出。
    
## 预期成果

### 项目预期成果

1. 研究报告1份（包含实验记录、设计方案、tf计算模型等）
2. 论文1篇
3. 软件著作权1项
4. 详细的软件说明文档，包括安装环境，运行，修改编译等
5. 视频若干个 分别用于展示，答辩，项目推广等
6. 网页2个 用于在线API调用，项目展示

### 结题时提供成果

训练集全部图片资源，全部源代码以及训练的模型，展示网页和视频。  
1. 训练集包括imageNet图片库资源，ins图片库资源。
2. 源代码包括dataset预处理部分，数据集清洗，tensorflow模型源代码，前端Flask框架源代码，API源代码，后端Kalfa或者RocketMQ编写的源代码，python微服务代码等。
3. 模型包括Auto Encoder预测模型，全局提示网络模型。
4. 网页包括上传页面和答辩页面。
5. 视频包括项目介绍，推广和展示等。

## 市场目标

### 项目发布情况

计费形式为服务后付费模式

黑白照片色彩还原服务按照每月（自然月）还原总量采取阶梯到达的计费方式，当月总量在哪个阶梯内则按该阶梯单价计费，识别量越大即单价越低。 
- 在线调用API报价：
    - 5万张及以下 0.0015元/张
    - 5万张以上 0.0011元/张
- 流量价格计算：
    - 内网交换流量免费
    - 公网流入流量免费
    - 公网流出0.5元/GB 免均衡负载

### 预计市场占有率

根据我项目成员的调查，目前市场上类似bw2color的处理技术还是存在的，但不同于bw2color，其他的产品的处理技术并不过关。所以对于bw2color平台的市场容量，我们十分的有信心。我们相信，在我们不断改进以及合理的推广下，我们一定会占据极大以部分市场容量。就目前的正规产品来说，并没有类似bw2color平台的一款专攻黑白照片还原技术的软件存在使用，用户最大的选择还是使用Photoshop等图片编辑软件进行手动加工处理。人工处理费时费力，对于一次性处理大量该类照片的效率也并不理想。因此，bw2color对于“打响行业第一枪”可以说是十分有优势。

### 市场容量变化趋势及前景

就目前市场而言，市场容量可以说是比较高的，保守估计可以达到85%，在接下去的逐步推广中，考虑到用户的接受程度、平台的推广力度以及同类产品的取优改进等因素，市场容量将会逐步减小。但此后，我们会针对使用量最大的群体进行专门的功能的拓展，在提高处理效率的同时，针对性的发展该平台，让市场容量稳定在65%，而根据预期，由于互联网这类产品的快速发展，市场容量将很有可能达不到预期，需要我们不断付出，我们也将根据当时的具体情况进行不断改进，让市场容量超出预期。
