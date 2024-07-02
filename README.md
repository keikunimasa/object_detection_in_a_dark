# 🌌 Dark Environment Object Detection 📸

## Purpose
Image analysis and object detection technologies are crucial, especially in contexts like automotive applications. However, sensors and recognition systems often falter in scenarios with low visibility such as rainy weather or darkness. This project aims to demonstrate that CNNs can accurately detect objects in images taken in darkness or artificially noise-added conditions.

## Target
The focus is primarily on scenarios where images are captured in dark environments.

## References
- Research Paper: [Revealing "Invisible" Objects in Darkness Using Deep Learning](https://ai-scholar.tech/articles/machine-learning/ai-dark-69) (January 31, 2019)

- Qiita Article: [Handling Dark Environment Object Detection](https://qiita.com/TrashBoxx/items/2d441e46643f73c0ca19)

- Lecture/Coding Exercises: Section 9, 10

## Implementation Strategy

1. **Dataset**: Utilize Cifar10 and CBIU2019 datasets for analysis.
   
2. **Object Categories**: Focus on common categories across Cifar10 and CBIU, namely [cat, dog, Car(=automobile), Ship(=Boat)]. Separate validation for Car and Ship due to potential lower accuracy.

3. **Approaches for Dark Environment Object Detection**:
   - Detection using pre-trained models on Cifar10.
   - Fine-tuning ResNet50 on CBIU datasets.
   - Preprocessing with edge detection algorithms before training.

Experiment with the above approaches and compare results.

    



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

## 実装計画
本研究では、以下の手法を用いて暗闇での物体検知の実現を目指します。

1. **データセットの選定**: Cifar10およびCBIU2019データセットを利用し、多様なシチュエーションに対応するための準備を行います。

2. **対象物体カテゴリの選定と評価**: Cifar10とCBIUで共通するカテゴリ [猫、犬、車（automobile）、船（boat）] を選び、特に車と船については精度低下のリスクを考慮した評価を行います。

3. **暗闇での物体検知手法の選定と実装**:
   - Cifar10で事前学習されたモデルをベースにした物体検知の実装
   - CBIUデータセットでResNet50をファインチューニングし、暗闇での特定物体検知に特化したモデルの構築
   - 画像のエッジ検出アルゴリズムを用いた事前処理を行い、その後の学習に活用する手法の検討

これらの手法を詳細に検討し、実装・評価を進めることで、暗闇での物体検知技術の革新を目指します。
