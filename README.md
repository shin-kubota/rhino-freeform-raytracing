# Beans rhino-freeform-raytracing
Freeform surface ray tracing component for Grasshopper (Rhino) | Grasshopper用フリーフォームサーフェス光線追跡コンポーネント

---

## Overview

This plugin **"Beans*"** enables intuitive ray tracing in Grasshopper. Simply placing surfaces is all it takes — no complex spaghetti-like chart networks required. It is designed to make ray tracing visually straightforward, with multi-surface refraction consolidated into a single component.

"Beans" is designed for freeform lens surface design, intended to be used with a minimal number of surfaces in combination with Grasshopper's optimization tools such as Galapagos. To minimize computational load and maintain design clarity, the number of input surfaces is limited to 5. (For my research in the field of ophthalmology, five screens were sufficient.)

*The plugin name "Beans" is a nod to etymology: the word *lens* derives from the Latin for *lentil* — a legume. A playful homage to this linguistic journey from bean to optics, in the tradition of Grasshopper's plugin naming culture.

## 概要

このプラグイン **「Beans*」** は、Rhino8のGrasshopperで直感的な光線追跡を可能にします。必要なのはサーフェスを配置するだけで、複雑なスパゲッティチャートを構築する必要ありません。複数のサーフェスの屈折を単一のコンポーネントに統合することで、光線追跡を視覚的にわかりやすくするように設計されています。

「Beans」は自由曲面レンズ面の設計用に設計されており、GalapagosなどのGrasshopperの最適化ツールと組み合わせて、最小限のサーフェス数で使用することを目的としています。計算負荷を最小限に抑え、デザインの明瞭性を維持するため、入力サーフェスの数は5面に制限されています。（眼科学分野の私の研究では5つのスクリーンで十分でした）

*プラグイン名「Beans」は語源に由来しています。「lens」という単語は、マメ科植物を意味するラテン語の「lentil」に由来しています。豆から光学への言語的なユーモアのある命名として、Rhinoceros/Grasshopperのプラグイン命名文化の意思を受け継ぎました。


---

## Installation

1. Download the latest release of **Beans.gha**.
2. Make sure the file is unlocked: right click → Properties → Unblock (if visible).
3. Copy and paste it into the Grasshopper Libraries folder, usually:

```
C:\Users\<YourUser>\AppData\Roaming\Grasshopper\Libraries
```

4. Restart Rhinoceros and Grasshopper.
5. Access the component from the **Beans tab → Ray Trace**.

## インストール

1. **Beans.gha** の最新リリースをダウンロードします。
2. ファイルがロック解除されていることを確認します。右クリック → プロパティ → ブロック解除（表示されている場合）を選択します。
3. これをコピーして、GrasshopperのLibrariesフォルダ（通常は以下の場所）に貼り付けます。

```
C:\Users\<YourUser>\AppData\Roaming\Grasshopper\Libraries
```

4. Rhinoceros と Grasshopper を再起動します。
5. **Beans タブ → Ray Trace** からコンポーネントにアクセスします。

---

## Contact

[https://www.linkedin.com/in/shinkubota/](https://www.linkedin.com/in/shinkubota/)

---

## Acknowledgements

This plugin was developed based on CAD operation guidance by **Keita Murata**, further evolved by the author through inspiration from the Mosquito plugin (Carson Smuts, Food4Rhino), as part of the coursework in:

* **Digital Design Practice (FY2022, Creative Technology Course, Industrial Design)**
* **Machine Learning (FY2022, Creative Technology Course, Digital Technology, Prof. Hisashi Hayashi)**

at the **Advanced Institute of Industrial Technology (AIIT), Tokyo**.

Project repository:
[https://github.com/shin-kubota/ophthalmic-lens-design-by-Galapagos](https://github.com/shin-kubota/ophthalmic-lens-design-by-Galapagos)

This work is also conducted in association with the **Research Center for Health Design, AIIT** (Associate Professor Ken-ichi Tabei, Ph.D.).

Special thanks to **Carson Smuts (Mosquito, Food4Rhino)** for the creative inspiration.

Development was significantly accelerated with the assistance of LLM technology (**Claude by Anthropic**). What was once beyond reach in 2022 became achievable in 2026 — a testament to how rapidly AI tools have evolved.


## 謝辞

このプラグインは、工業デザイナーである**村田桂太**氏によるCAD操作実習の演習を原点とし、Mosquitoプラグイン（Carson Smuts、Food4Rhino）からヒントを得て、著者がさらに改良したものです。このプラグインは、以下の授業の一環として開発されました。

**東京都立産業技術大学院大学（AIIT）**
* **デジタルデザイン実習（2022年度、創造技術コース、産業技術研究科、村田桂太 氏）**
* **機械学習特論（2022年度、創造技術コース、産業技術研究科、教授 林久志 博士）**


研究に関するプロジェクトリポジトリ:
[https://github.com/shin-kubota/ophthalmic-lens-design-by-Galapagos](https://github.com/shin-kubota/ophthalmic-lens-design-by-Galapagos)

本研究は、**AIIT 健康デザイン研究所 **（所長 准教授 田部井 賢一 博士）の研究所での活動の一環です。

創造的なインスピレーションを与えてくださった**Carson Smuts氏（Mosquito、Food4Rhino）**に深く感謝いたします。

また、開発は、LLMテクノロジー（**Claude by Anthropic**）の支援により大幅に加速されました。2022年には不可能と思われていたことが、2026年には実現可能となりました。これは、AIツールの急速な進化によるものです。

---

## Platform

Grasshopper for Rhino 8 (Windows)

## プラットフォーム

Rhino 8 用 Grasshopper (Windows)

---

Copyright © 2026 Shin Kubota.
All rights reserved.

This software is provided free of charge for personal and academic use only.
Commercial use, redistribution, modification, reverse engineering, or derivative works 
are not permitted without explicit written permission from the author.

This software is provided "as is", without warranty of any kind.

---

👤 Author / 著者
Shin Kubota

Executive Officer & General Manager, Engineering Dept. / 執行役員 技術部長（東証プライム上場企業・医療機器メーカー）
27+ years in medical device development, production engineering & AI implementation / 27年以上の医療機器開発・生産技術・AI実装経験（眼光学・SaMD・QMS・自動化）
M.Eng. Optical Engineering, Tokyo Polytechnic University / 東京工芸大学大学院 光工学専攻 修士（工学）
M.Tech. Innovation & Design Engineering, AIIT / 東京都立産業技術大学院大学 修士（創造技術）
Collaborative Researcher, Chiba University / 千葉大学大学院 研究員
Researcher, Research Center for Health Design, AIIT / 東京都立産業技術大学院大学 健康デザイン研究所 研究員（介護予防・認知症予防・AI・IoT）
LinkedIn
