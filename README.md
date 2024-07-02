# 🌌 Dark Environment Object Detection 📸

## Purpose
Image analysis and object detection technologies play a critical role, particularly in applications such as automotive contexts. However, sensors and recognition systems often struggle in scenarios with limited visibility, such as rainy weather or darkness. This project seeks to demonstrate the capability of CNNs to accurately detect objects in images taken under low light conditions or with artificially added noise.

The study aims to advance image analysis and object detection technologies by focusing on improving accuracy in challenging environments characterized by darkness and noise distortion. Leveraging deep learning techniques, specifically CNNs, the research proposes methods to achieve robust object detection performance even in images affected by low visibility or noise.

## Target
This study primarily focuses on images captured in dark environments, aiming to enhance object detection performance under conditions of reduced visibility.
## Dark Image Exaples

### * Cat-class
<img width="125" alt="image" src="https://github.com/keikunimasa/object_detection_in_a_dark/assets/100010521/f3e85c71-1861-4b88-a8ef-8e8083318c85">
<img width="125" alt="image" src="https://github.com/keikunimasa/object_detection_in_a_dark/assets/100010521/9ae923ae-2b49-43e9-92e7-b9cadd892a55">
<img width="125" alt="image" src="https://github.com/keikunimasa/object_detection_in_a_dark/assets/100010521/dc395ade-c210-4d7d-81d0-f799c82f0a5f">


### * Dog-class
![image](https://github.com/keikunimasa/object_detection_in_a_dark/assets/100010521/766aead6-c04d-4f76-bec8-4657f360a1c7)
<img width="489" alt="image" src="https://github.com/keikunimasa/object_detection_in_a_dark/assets/100010521/25f050de-e900-428d-8999-b3d18879606a">


### * Boat-class

### * Car-class
![image](https://github.com/keikunimasa/object_detection_in_a_dark/assets/100010521/c995a804-1f50-4d26-9604-666fd2241383)



## References
This research builds upon the following foundational literature:

- Research Paper: "Revealing 'Invisible' Objects in Darkness Using Deep Learning" (January 31, 2019, AI Scholar Tech)
- Qiita Article: "Handling Dark Environment Object Detection" (TrashBoxx, Qiita)
- Lecture/Coding Exercises: Primarily referencing activities in Sections 9 and 10.

## Datasets
This study utilizes the following datasets:

- **Cifar10**: A dataset containing images of 10 common object categories, widely used for image classification and object detection tasks.
- **CBIU2019**: A dataset specialized in images captured in dark environments, suitable for research on object recognition under low light conditions.



## Implementation Strategy
In this study, we outline the following strategies to achieve object detection in dark environments:

1. **Dataset Selection**: Utilize Cifar10 and CBIU2019 datasets to prepare for a variety of scenarios.
   
2. **Target Object Categories and Evaluation**: Focus on common categories across Cifar10 and CBIU, specifically evaluating potential accuracy challenges for categories like cars and ships under low visibility conditions.

3. **Approaches for Dark Environment Object Detection**:
   - Implement object detection using pre-trained models on Cifar10.
   - Fine-tune ResNet50 on the CBIU dataset to specialize in detecting objects in darkness.
   - Explore preprocessing techniques such as edge detection algorithms to enhance model performance.

By exploring and comparing these approaches, we aim to innovate object detection technology in dark environments.

    # 🌌 暗闇における物体検知 📸

## 研究目的
本研究の目的は、画像解析および物体検知技術の進展に貢献することです。具体的には、従来の方法では困難であった暗闇やノイズが加わった環境下での物体検出精度の向上を実現することを目指しています。深層学習（CNN）を活用し、暗闇での撮影やノイズ処理された画像においても、信頼性の高い物体検知を実現する手法を提案します。

## 研究対象
本研究では、主に暗闇で撮影された画像を対象とします。具体的には、低視認性環境下での物体検出の課題に焦点を当て、その解決策を模索します。

## 関連文献
本研究の基盤となる文献として、以下の情報源を参考にしました。

- 研究論文: 「ディープラーニングを用いて暗闇の中で「見えない」オブジェクトを明らかにする」（2019年1月31日、AI Scholar Tech）

- Qiita 記事: 「暗闇での物体検知のハンドリング」（TrashBoxx氏、Qiita）

- 参考講義／コーディング演習: 主にセクション9および10で行われた内容を参照しました。

## データセット
この研究では、以下のデータセットを使用しています。

- **Cifar10**: 10種類の一般的な物体を含む画像データセット。画像の分類および物体検出に広く使用されています。

- **CBIU2019**: 暗闇で撮影された画像に特化したデータセット。低照度条件下での物体認識の研究に適しています。

## 実装計画
本研究では、以下の手法を用いて暗闇での物体検知の実現を目指します。

1. **データセットの選定**: Cifar10およびCBIU2019データセットを利用し、多様なシチュエーションに対応するための準備を行います。

2. **対象物体カテゴリの選定と評価**: Cifar10とCBIUで共通するカテゴリ [猫、犬、車（automobile）、船（boat）] を選び、特に車と船については精度低下のリスクを考慮した評価を行います。

3. **暗闇での物体検知手法の選定と実装**:
   - Cifar10で事前学習されたモデルをベースにした物体検知の実装
   - CBIUデータセットでResNet50をファインチューニングし、暗闇での特定物体検知に特化したモデルの構築
   - 画像のエッジ検出アルゴリズムを用いた事前処理を行い、その後の学習に活用する手法の検討

これらの手法を詳細に検討し、実装・評価を進めることで、暗闇での物体検知技術の革新を目指します。
