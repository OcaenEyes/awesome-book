<div class="github-widget" data-repo="likedan/Awesome-CoreML-Models"></div>


<!--
标题：很棒的核心 ML 模型
描述：Core ML 格式的机器学习模型精选列表.
作者：李克丹
-->
<p align="center">
<img src="https://raw.githubusercontent.com/likedan/Awesome-CoreML-Models/master/images/coreml.png" width="329" height="295"/>
</p>


从 iOS 11 开始，苹果发布了 Core ML 框架，帮助开发者将机器学习模型集成到应用程序中. [The official documentation](https://developer.apple.com/documentation/coreml)

我们以 Core ML 格式提供了最大的机器学习模型集合，以帮助 iOS、macOS、tvOS 和 watchOS 开发人员尝试机器学习技术.

如果您已经转换了 Core ML 模型，请随时提交 [pull request](https://github.com/likedan/Awesome-CoreML-Models/compare).

最近，我们添加了可视化工具. 这是一个 [Netron](https://lutzroeder.github.io/Netron).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## Models

## Image - Metadata/Text
*以图像数据作为输入并输出有关图像的有用信息的模型.*
 * **TextDetection** - 使用 Vision 内置模型实时检测文本.  [下载]() | [Demo](https://github.com/tucan9389/TextDetection-CoreML) | [Reference](https://developer.apple.com/documentation/vision)
* **照片评估** - 使用 Core ML 和 Metal 进行照片评估. [Download](https://github.com/yulingtianxia/PhotoAssessment/blob/master/PhotoAssessment-Sample/Sources/NIMANasnet.mlmodel) | [Demo](https://github.com/yulingtianxia/PhotoAssessment) | [Reference](https://arxiv.org/abs/1709.05424)
* **PoseEstimation** - 根据手机图片估计人体姿势. [Download](https://github.com/edvardHua/PoseEstimationForMobile/tree/master/release) | [Demo](https://github.com/tucan9389/PoseEstimation-CoreML) | [Reference](https://github.com/edvardHua/PoseEstimationForMobile)
* **MobileNet** - 检测图像中存在的主要对象. [Download](https://github.com/hollance/MobileNet-CoreML/raw/master/MobileNet.mlmodel) | [Demo](https://github.com/hollance/MobileNet-CoreML) | [Reference](https://arxiv.org/abs/1704.04861)
* **Places CNN** - 从卧室、森林、海岸等 205 个类别中检测图像场景. [Download](https://github.com/hollance/MobileNet-CoreML/raw/master/MobileNet.mlmodel) | [Demo](https://github.com/chenyi1989/CoreMLDemo) | [Reference](http://places.csail.mit.edu/index.html)
* **Inception v3** - 检测图像中存在的主要对象. [Download](https://github.com/yulingtianxia/Core-ML-Sample/blob/master/CoreMLSample/Inceptionv3.mlmodel) | [Demo](https://github.com/yulingtianxia/Core-ML-Sample/) | [Reference](https://arxiv.org/abs/1512.00567)
* **ResNet50** - 检测图像中存在的主要对象. [Download](https://github.com/ytakzk/CoreML-samples/blob/master/CoreML-samples/Resnet50.mlmodel) | [Demo](https://github.com/ytakzk/CoreML-samples) | [Reference](https://arxiv.org/abs/1512.03385)
* **VGG16** - 检测图像中存在的主要对象. [Download](https://docs-assets.developer.apple.com/coreml/models/VGG16.mlmodel) | [Demo](https://github.com/alaphao/CoreMLExample) | [Reference](https://arxiv.org/abs/1409.1556)
* **汽车识别** - 预测汽车的品牌和型号. [Download](https://github.com/likedan/Core-ML-Car-Recognition/blob/master/Convert/CarRecognition.mlmodel) | [Demo](https://github.com/ytakzk/CoreML-samples) | [Reference](http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/index.html)
* **YOLO** - 识别给定图像中的对象是什么以及它们在图像中的位置. [Download](https://github.com/hollance/YOLO-CoreML-MPSNNGraph/blob/master/TinyYOLO-CoreML/TinyYOLO-CoreML/TinyYOLO.mlmodel) | [Demo](https://github.com/hollance/YOLO-CoreML-MPSNNGraph) | [Reference](http://machinethink.net/blog/object-detection-with-yolo)
* **AgeNet** - 从一个人的肖像预测一个人的年龄. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6mT1J3T1BEeWx4TWc/view?usp=sharing) | [Demo](https://github.com/cocoa-ai/FacesVisionDemo) | [Reference](http://www.openu.ac.il/home/hassner/projects/cnn_agegender/)
* **GenderNet** - 从一个人的肖像预测一个人的性别. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6mYkNsZHlyc2ZuaFk/view?usp=sharing) | [Demo](https://github.com/cocoa-ai/FacesVisionDemo) | [Reference](http://www.openu.ac.il/home/hassner/projects/cnn_agegender/)
* **MNIST** - 从图像中预测手写（绘制）数字. [Download](https://github.com/ph1ps/MNIST-CoreML/raw/master/MNISTPrediction/MNIST.mlmodel) | [Demo](https://github.com/ph1ps/MNIST-CoreML) | [Reference](http://yann.lecun.com/exdb/mnist/)
* **EmotionNet** - 从一个人的肖像预测一个人的情绪. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6mTlYtRGdXNFlpWDQ/view?usp=sharing) | [Demo](https://github.com/cocoa-ai/FacesVisionDemo) | [Reference](http://www.openu.ac.il/home/hassner/projects/cnn_emotions/)
* **SentimentVision** - 从图像中预测积极或消极的情绪. [Download](https://drive.google.com/open?id=0B1ghKa_MYL6mZ0dITW5uZlgyNTg) | [Demo](https://github.com/cocoa-ai/SentimentVisionDemo) | [Reference](http://www.sciencedirect.com/science/article/pii/S0262885617300355?via%3Dihub)
* **Food101** - 从图像中预测食物的类型. [Download](https://drive.google.com/open?id=0B5TjkH3njRqnVjBPZGRZbkNITjA) | [Demo](https://github.com/ph1ps/Food101-CoreML) | [Reference](http://visiir.lip6.fr/explore)
* **Oxford102** - 从图像中检测花朵的类型. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6meDBHT2NaZGxkNzQ/view?usp=sharing) | [Demo](https://github.com/cocoa-ai/FlowersVisionDemo) | [Reference](http://jimgoo.com/flower-power/)
* **FlickrStyle** - 检测图像的艺术风格. [Download](https://drive.google.com/file/d/0B1ghKa_MYL6meDBHT2NaZGxkNzQ/view?usp=sharing) | [Demo](https://github.com/cocoa-ai/StylesVisionDemo) | [Reference](http://sergeykarayev.com/files/1311.3715v3.pdf)
* **RN1015k500** - 预测拍摄照片的位置. [Download](https://s3.amazonaws.com/aws-bigdata-blog/artifacts/RN1015k500/RN1015k500.mlmodel) | [Demo](https://github.com/awslabs/MXNet2CoreML_iOS_sample_app) | [Reference](https://aws.amazon.com/blogs/ai/estimating-the-location-of-images-using-mxnet-and-multimedia-commons-dataset-on-aws-ec2)
* **裸体** - 将图像分类为 NSFW（裸体）或 SFW（非裸体）
 [Download](https://drive.google.com/open?id=0B5TjkH3njRqncDJpdDB1Tkl2S2s) | [Demo](https://github.com/ph1ps/Nudity-CoreML) | [Reference](https://github.com/yahoo/open_nsfw)
 * **TextRecognition (ML Kit)** - 使用 ML Kit 内置模型实时识别文本.  [下载]() | [Demo](https://github.com/tucan9389/TextRecognition-MLKit) | [Reference](https://firebase.google.com/docs/ml-kit/ios/recognize-text)
* **图像分割** - 将相机帧或图像的像素分割为一组预定义的类. [Download](https://developer.apple.com/machine-learning/models/) | [Demo](https://github.com/tucan9389/ImageSegmentation-CoreML) | [Reference](https://github.com/tensorflow/models/tree/master/research/deeplab)
* **DepthPrediction** - 预测单个图像的深度. [Download](https://developer.apple.com/machine-learning/models/) | [Demo](https://github.com/tucan9389/DepthPrediction-CoreML) | [Reference](https://github.com/iro-cp/FCRN-DepthPrediction)

## Image - Image
*转换图像的模型.*
* **HED** - 从彩色图像中检测嵌套边缘. [Download](https://github.com/s1ddok/HED-CoreML/blob/master/HED-CoreML/Models/HED_so.mlmodel) | [Demo](https://github.com/s1ddok/HED-CoreML) | [Reference](http://dl.acm.org/citation.cfm?id=2654889)
* **AnimeScale2x** - 处理双三次比例的动漫风格艺术品 [Download](https://github.com/imxieyi/waifu2x-ios/blob/master/waifu2x/models/anime_noise0_model.mlmodel) | [Demo](https://github.com/imxieyi/waifu2x-ios) | [Reference](https://arxiv.org/abs/1501.00092)

## Text - Metadata/Text
*处理文本数据的模型*
* **情绪极性** - 从句子中预测积极或消极情绪. [Download](https://github.com/cocoa-ai/SentimentCoreMLDemo/raw/master/SentimentPolarity/Resources/SentimentPolarity.mlmodel) | [Demo](https://github.com/cocoa-ai/SentimentCoreMLDemo) | [Reference](http://boston.lti.cs.cmu.edu/classes/95-865-K/HW/HW3/)
* **文档分类** - 将新闻文章分为 5 个类别之一. [Download](https://github.com/toddkramer/DocumentClassifier/blob/master/Sources/DocumentClassification.mlmodel) | [Demo](https://github.com/toddkramer/DocumentClassifier) | [Reference](https://github.com/toddkramer/DocumentClassifier/)
* **iMessage 垃圾邮件检测** - 检测邮件是否为垃圾邮件. [Download](https://github.com/gkswamy98/imessage-spam-detection/blob/master/MessageClassifier.mlmodel) | [Demo](https://github.com/gkswamy98/imessage-spam-detection/tree/master) | [Reference](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)
* **NamesDT** - 使用 DecisionTreeClassifier 进行性别分类 [Download](https://github.com/cocoa-ai/NamesCoreMLDemo/blob/master/Names/Resources/NamesDT.mlmodel) | [Demo](https://github.com/cocoa-ai/NamesCoreMLDemo) | [Reference](http://nlpforhackers.io/)
* **性格检测** - 根据用户文档（句子）预测性格. [Download](https://github.com/novinfard/profiler-sentiment-analysis/tree/master/ios_app/ProfilerSA/ML%20Models) | [Demo](https://github.com/novinfard/profiler-sentiment-analysis/) | [Reference](https://github.com/novinfard/profiler-sentiment-analysis/blob/master/dissertation-v6.pdf)
* **用于问答的 BERT** - 用于问答的 BERT 的 Swift Core ML 3 实现 [Download](https://github.com/huggingface/swift-coreml-transformers/blob/master/Resources/BERTSQUADFP16.mlmodel) | [Demo](https://github.com/huggingface/swift-coreml-transformers#-bert) | [Reference](https://github.com/huggingface/pytorch-transformers#run_squadpy-fine-tuning-on-squad-for-question-answering)
* **GPT-2** - OpenAI GPT-2 文本生成（Core ML 3） [Download](https://github.com/huggingface/swift-coreml-transformers/blob/master/Resources/gpt2-512.mlmodel) | [Demo](https://github.com/huggingface/swift-coreml-transformers#-gpt-2) | [Reference](https://github.com/huggingface/pytorch-transformers)
## Miscellaneous
* **Exermote** - 当 iPhone 佩戴在右上臂时预测锻炼情况. [Download](https://github.com/Lausbert/Exermote/tree/master/ExermoteInference) | [Demo](https://github.com/Lausbert/Exermote/tree/master/ExermoteInference) | [Reference](http://lausbert.com/2017/08/03/exermote/)
* **GestureAI** - 根据给定位置和流派推荐艺术家. [Download](https://goo.gl/avdMjD) | [Demo](https://github.com/akimach/GestureAI-CoreML-iOS) | [Reference](https://github.com/akimach/GestureAI-iOS/tree/master/GestureAI)
* **艺术家推荐** - 根据给定地点和流派推荐艺术家. [Download](https://github.com/agnosticdev/Blog-Examples/blob/master/UsingCoreMLtoCreateASongRecommendationEngine/Artist.mlmodel)  |  [演示]() | [Reference](https://www.agnosticdev.com/blog-entry/python/using-scikit-learn-and-coreml-create-music-recommendation-engine)
* **ChordSuggester** - 根据输入的和弦进行预测最可能的下一个和弦. [Download](https://github.com/carlosmbe/Mac-CoreML-Chord-Suggester/blob/main/MLChordSuggester.mlpackage.zip) | [Demo](https://github.com/carlosmbe/Mac-CoreML-Chord-Suggester/tree/main) | [Reference](https://medium.com/@huanlui/chordsuggester-i-3a1261d4ea9e)



## Visualization Tools
*帮助可视化 CoreML 模型的工具*
* [Netron](https://lutzroeder.github.io/Netron)

## Supported formats
*可转换为 Core ML 的模型格式列表及示例*
* [Caffe](https://apple.github.io/coremltools/generated/coremltools.converters.caffe.convert.html)
* [Keras](https://apple.github.io/coremltools/generated/coremltools.converters.keras.convert.html)
* [XGBoost](https://apple.github.io/coremltools/generated/coremltools.converters.xgboost.convert.html)
* [Scikit-learn](https://apple.github.io/coremltools/generated/coremltools.converters.sklearn.convert.html)
* [MXNet](https://aws.amazon.com/blogs/ai/bring-machine-learning-to-ios-apps-using-apache-mxnet-and-apple-core-ml/)
* [LibSVM](https://apple.github.io/coremltools/generated/coremltools.converters.libsvm.convert.html)
* [Torch7](https://github.com/prisma-ai/torch2coreml)

## The Gold
*可转换为 Core ML 的机器学习模型集合*

* [Caffe Model Zoo](https://github.com/BVLC/caffe/wiki/Model-Zoo) - Caffe 格式的大模型列表.
* [TensorFlow Models](https://github.com/tensorflow/models) - TensorFlow 模型.
* [TensorFlow Slim Models](https://github.com/tensorflow/models/tree/master/research/slim/README.md) - TensorFlow 模型的另一个集合.
* [MXNet Model Zoo](https://mxnet.incubator.apache.org/model_zoo/) - MXNet 模型的集合.

 *可以转换为 Core ML 的个人机器学习模型. 我们将在转换后不断调整列表.*
* [LaMem](https://github.com/MiyainNYC/Visual-Memorability-through-Caffe) 对图片的记忆力进行评分.
* [ILGnet](https://github.com/BestiVictory/ILGnet) 图像的审美评价.
* [Colorization](https://github.com/richzhang/colorization) 使用深度神经网络自动着色.
* [Illustration2Vec](https://github.com/rezoo/illustration2vec) 估计一组标签并从给定插图中提取语义特征向量.
* [CTPN](https://github.com/tianzhi0549/CTPN) 检测自然图像中的文本.
* [Image Analogy](https://github.com/msracver/Deep-Image-Analogy) 查找两个输入图像之间具有语义意义的密集对应关系.
* [iLID](https://github.com/twerkmeister/iLID) 自动口语识别.
* [Fashion Detection](https://github.com/liuziwei7/fashion-detection) 从图像中检测布料.
* [Saliency](https://github.com/imatge-upc/saliency-2016-cvpr) 传统上，图像中显着区域的预测是通过手工制作的特征来解决的.
* [Face Detection](https://github.com/DolotovEvgeniy/DeepPyramid) 从图像中检测人脸.
* [mtcnn](https://github.com/CongWeilin/mtcnn-caffe) 联合面部检测和对齐.
* [deephorizon](https://github.com/scottworkman/deephorizon) 单图像地平线估计.

## Contributing and License
* [See the guide](https://github.com/likedan/Awesome-CoreML-Models/blob/master/.github/CONTRIBUTING.md)
 * 根据 MIT 许可分发. 请参阅许可证了解更多信息.
