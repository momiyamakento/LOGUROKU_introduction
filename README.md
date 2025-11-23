# LOGROKU – Introduction

「日記 × すごろく」で、自己理解と意思決定力を育てるアプリ  
Still Developing / Flutter × Firebase

---

## 📌 サービス概要
LOGROKU は、毎日の生活を記録した「日記」を自動で **すごろく化** し、  
楽しく自己理解を深められる成長支援アプリです。

パーソナルAI全盛の未来で失われつつある  
「自分で考える習慣」を取り戻すことを目的としています。

---

## 🎯 背景（課題）
スライドより引用：

- AI の提案に従い続けると、思考機会が減少し意思決定力が低下する  
- 判断基準を持てず、流されやすくなる  
（p4–5） :contentReference[oaicite:5]{index=5}

➡ LOGROKU は、日記・振り返り・比較を通じて「自分の軸」を育てます。

---

## 🧪 ユーザーの変化
Before  
- AIの提案をそのまま受け入れがち  
- 自分の判断に自信がない  

After（LOGROKU使用後）  
- 自分を客観視でき、自己理解が向上  
- AIに流されず、自分の軸で意思決定できる  
（p11） :contentReference[oaicite:6]{index=6}

---

## 🎮 主な機能（開発中）
- 日記をすごろく形式に自動変換  
- マスを進めながら日記を振り返る体験  
- 友達の日記と比較し、新しい視点を得る  
（p8–9）  
- AI分析による簡易スコアリング（構想）

---

## 🧩 使用技術
- Flutter / Dart  
- Firebase Authentication / Firestore  
- Cloud Functions  
- Riverpod  
- Python（分析）  
- Figma（UI/UX設計）

---

## 👤 私の担当範囲
- UI/UX デザイン（Figmaで画面・UXフロー作成）  
- Firestore のスキーマ設計  
- Firebase Authentication の導入  
- 日記→すごろく変換ロジックの一部  
- PM / スプリント管理（WBS・仕様調整）  

---

## 🏛 アーキテクチャ
（画像推奨）

Flutter  
↓  
Firebase Auth  
↓  
Cloud Firestore  
↓  
Cloud Functions（すごろく生成処理）

---

## 🎨 UIイメージ（プロトタイプ）
（Figma のスクショを貼る）

---

## 🔗 関連資料
- 成果発表スライド（ver1.0） （ファイル）  
- 本番レポジトリ（Private）  
- 企画書 / UX資料（任意）  
