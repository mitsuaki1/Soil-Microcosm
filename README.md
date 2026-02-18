# Soil Microcosm
### Visualization and Programming of Soil Microbial Networks
（土壌微生物ネットワークの可視化とプログラミング）

---

## 🌱 Overview

**Soil Microcosm** is an interactive simulation project that visualizes
the hidden microbial ecosystem inside soil.  
（Soil Microcosm は、土壌内部に存在する見えない微生物生態系を可視化するインタラクティブなシミュレーションプロジェクトです。）

The simulation transitions from a macroscopic surface perspective into
a microscopic biological world, programmatically representing interactions among:  
（シミュレーションは地表のマクロな視点から微生物のミクロな世界へ移行し、以下の相互作用をプログラムによって表現します。）

- Soil particles（土壌粒子）
- Bacteria（細菌）
- Fungal networks（菌類ネットワーク）
- Plant roots（植物の根）
- Nematode predators（線虫などの捕食者）

The project explores visualization as a bridge between scientific
understanding and intuitive perception, transforming invisible ecological
processes into observable experiences.  
（本プロジェクトは、科学的理解と直感的認識をつなぐ手段として可視化を探究し、不可視の生態系プロセスを体験可能な形へ変換します。）

---

## 🎯 Purpose

Soil microorganisms form the foundation of terrestrial ecosystems,
yet their interactions occur at scales beyond human perception.  
（土壌微生物は陸上生態系の基盤ですが、その相互作用は人間の知覚を超えたスケールで起きています。）

While microscopes allow observation of individual organisms,
ecosystem-level dynamics — cooperation, competition, predation,
and nutrient exchange — remain difficult to understand intuitively.  
（顕微鏡では個体を観察できますが、協力・競争・捕食・栄養交換といった生態系レベルの動態を直感的に理解することは困難です。）

**Soil Microcosm aims to:**  
（Soil Microcosm の目的）

- Provide an intuitive understanding of microbial networks  
  （微生物ネットワークを直感的に理解できるようにする）
- Visualize ecological interactions occurring in soil environments  
  （土壌内で起きる生態学的相互作用を可視化する）
- Explore scientific expression through programming and simulation  
  （プログラミングによる科学表現を探究する）
- Translate complex biological systems into experiential visualization  
  （複雑な生物システムを体験的な可視化へ翻訳する）

---

## 🧬 Simulation Structure

The simulation consists of eight sequential scenes:  
（シミュレーションは8つの連続したシーンで構成されています。）

1. **Surface Introduction** — A macroscopic soil perspective  
   （地表導入 — マクロな土壌視点）
2. **Structure & Microhabitats** — Emergence of microbial habitats  
   （土壌構造と微生息域）
3. **Fungal–Plant Symbiosis** — Mycorrhizal relationships  
   （菌類と植物の共生）
4. **Cooperation & Competition** — Bacterial signaling behavior  
   （協力と競争、微生物コミュニケーション）
5. **Predation** — Population regulation by predators  
   （捕食関係）
6. **Nutrient Cycling** — Decomposition processes  
   （栄養循環と分解）
7. **Ecosystem Scale** — Integrated network visualization  
   （生態系スケール）
8. **Closing Sequence** — Return to macro perspective  
   （エンディング）

Camera zoom and organism populations dynamically change to represent ecological scale transitions.  
（カメラのズームと生物密度が変化し、生態系スケールの移行を表現します。）

---

## ⚙️ Technical Concept

### 1. Scale Transition (Macro → Micro)
（スケール遷移）

- Continuous zooming rather than abrupt scene changes  
  （急なシーン切替ではなく連続的なズーム）
- Depth perception created through particle density and blur  
  （粒子密度とぼかしによる奥行き表現）
- Smooth cognitive transition between ecological scales  
  （認知的に自然なスケール移動）

### 2. Scientific Realism
（科学的リアリズム）

- Avoids exaggerated organism sizes  
  （微生物サイズを誇張しない）
- Earth-toned lighting inspired by subsurface environments  
  （地中環境に基づく自然な光表現）
- Ecologically plausible population density  
  （生態学的に自然な密度）
- Motion influenced by fluid resistance concepts  
  （水膜環境を意識した運動表現）

### 3. Visualization of Invisible Processes
（不可視現象の可視化）

- Nutrient exchange represented as soft energy flow  
  （栄養交換を微細な流れとして表現）
- Quorum sensing visualized through signaling pulses  
  （クオラムセンシングをシグナルとして表現）
- Decomposition expressed via gradual transformation  
  （分解過程を段階的変化で表現）

The goal is natural plausibility rather than dramatic visual effects.  
（目的は派手さではなく自然な現実感です。）

---

## 🧪 Technologies

- HTML5 Canvas
- Vanilla JavaScript
- Procedural animation
- Particle-based simulation
- State interpolation for smooth transitions

No external frameworks or libraries are required.  
（外部フレームワークは使用していません。）

---

## ▶️ How to Run

Open the HTML file in a modern web browser:  
（HTMLファイルをブラウザで開くだけで実行できます。）

```bash
open soil-microcosm.html
```

もしくは以下をクリックしてください。
https://gemini.google.com/share/eb310dc5948f

---

## 👨 Recommended browsers

Recommended browsers
（推奨ブラウザ）

- Google Chrome
- Microsoft Edge
- Firefox

---

## 🌍 Conceptual Background

Soil is not inert matter.  
（土壌は単なる物質ではありません。）

It is a dense living network where cooperation, competition,
predation, and transformation occur continuously beneath our feet.  
（そこでは協力・競争・捕食・変化が絶えず起き続けています。）

This project treats visualization not as decoration,
but as a method for understanding complex ecological systems.  
（本プロジェクトでは可視化を装飾ではなく理解の手段として扱います。）

By simulating relationships rather than isolated organisms,
Soil Microcosm attempts to reveal ecosystem dynamics that are
normally invisible to human perception.  
（個体ではなく関係性を再現することで、通常は見えない生態系ダイナミクスを明らかにしようとしています。）

---

## 🚧 Project Status

Experimental / Research-oriented project.  
（実験的・研究志向プロジェクト）

Possible future directions include:  
（今後の展開）

- WebGL-based rendering（WebGLレンダリング）
- Agent-based ecological modeling（エージェントベース生態モデル）
- Integration of empirical microbial parameters（実測データ統合）
- AI-driven ecosystem behavior generation（AIによる生態挙動生成）
- Real-time environmental interaction models（リアルタイム環境相互作用）

---

## 🌿 Author

**mitsulab**

Organic agriculture × soil ecology × environmental design  
（有機農業 × 土壌生態学 × 環境設計）

Exploring how land systems self-organize through microbial,
hydrological, and ecological interactions.  
（微生物・水文・生態相互作用による土地システムの自己組織化を探究）

