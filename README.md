# AD³

## Overview

AD³（アドスリー）は、

「星 × 冒険 × 成長 × 出会い」

をテーマとした2DファンタジーJRPGです。

プレイヤーは星や生命に関わる力を持つ「アドバンス」として、
さまざまな世界を冒険し、仲間との出会いや戦いを通して成長していきます。

本プロジェクトでは、AD³のゲームシステムをUnityで開発しています。

---

## Project Goal

AD³の最終的なゲーム体験を実現することを目的とします。

現在は本編開発に先立ち、

**5×5マスのグリッドを利用した戦闘プロトタイプ**

「AD3_battle_plot」

を開発しています。

このプロトタイプでは、AD³の戦闘システムの基礎となる、

- グリッド移動
- ターン制
- 敵の攻撃予告
- 攻撃範囲からの回避
- 能力システム

などを段階的に実装します。

---

# Game Concept

### Theme

**星 × 冒険 × 成長 × 出会い**

### Genre

2D Fantasy JRPG

### Core Gameplay

プレイヤーはグリッド上を移動しながら敵の攻撃を回避し、
自身の能力を使って戦います。

敵の行動を予測し、攻撃範囲から逃げることが重要なゲームシステムとなります。

---

# AD³ World

AD³の世界には「ゾディアック」と呼ばれる存在と、
その力を受け継ぐ「アドバンス」が存在します。

### Zodiac

ゾディアックは世界の根幹に関わる存在であり、
黄道十二星座をモチーフとしています。

### Advanse

アドバンスはゾディアックの力を受け継ぐ存在です。

アドバンスにはそれぞれ固有の能力や人格が存在し、
物語や戦闘システムの中心となります。

---

# Battle System

現在開発中のプロトタイプでは、

- 5×5 Grid
- Player Movement
- Enemy Movement
- Turn System
- Attack Prediction
- Attack Area
- Dodge
- Game Over
- Ability System

などを実装予定です。

戦闘システムの詳細は以下を参照してください。

`Docs/BattleSystem.md`

---

# Development

## Development Environment

- Unity
- C#
- Git
- GitHub
- Codex

## Development Philosophy

AD³のゲームデザインは開発者が決定します。

AIは主に実装・コード作成・デバッグを担当します。

### Developer

- ゲームデザイン
- システム設計
- 世界観
- ストーリー
- 仕様決定
- Unity上での確認

### ChatGPT

- ゲームシステムの設計支援
- アイデア整理
- 仕様書作成
- 実装方針の検討
- Codexへの実装指示の整理

### Codex

- C#実装
- Unityプロジェクトの編集
- バグ修正
- リファクタリング
- テスト・デバッグ支援

---

# Development Status

## Current Phase

**Prototype Development**

### Battle Prototype

- [ ] Unity project setup
- [ ] 5×5 grid
- [ ] Player movement
- [ ] Enemy
- [ ] Turn system
- [ ] Attack prediction
- [ ] Attack execution
- [ ] Dodge system
- [ ] Game Over
- [ ] Restart
- [ ] Ability system

---

# Future Development

将来的には、

- AD³本編の戦闘システム
- アドバンス
- ゾディアック
- 能力システム
- 属性システム
- キャラクター
- ストーリー
- フィールド
- ダンジョン
- 音楽
- UI

などを段階的に実装します。

---

# Repository

このリポジトリはAD³のゲーム開発用リポジトリです。

ゲームの詳細仕様については `Docs/` を参照してください。
