# Three.js テンプレートコレクション

このリポジトリには、Three.jsを使用した様々なインタラクティブな3Dビジュアルエフェクトとアニメーションのテンプレートが含まれています。

## テンプレート一覧

`short` ディレクトリには以下のHTML単一ファイルのデモが含まれています：

- **音響エフェクト**
  - `sound_equalizer.html` - 音楽に合わせて動くグラフィックイコライザー

- **パーティクルエフェクト**
  - `interactive_particles.html` - インタラクティブなパーティクルアニメーション
  - `interactive_particles_click.html` - クリックに反応するパーティクルエフェクト
  - `smoke_clouds_particles.html` - 煙のようなパーティクルエフェクト

- **幾何学的アニメーション**
  - `spinning_square.html` - 回転する立方体のアニメーション
  - `spiral_square.html` - らせん状に動く立方体
  - `geometric_ray.html` - 幾何学的な光線エフェクト
  - `yau_geometry.html` - 複雑な幾何学的表現
  - `fractal_shader.html` - フラクタルシェーダー表現

- **特殊エフェクト**
  - `glitch_effect.html` - グリッチビジュアルエフェクト
  - `glitch_image_transitions.html` - グリッチトランジションエフェクト
  - `scanner_effect.html` - スキャナーのようなビジュアル効果
  - `lightning_effect.html` - 稲妻のエフェクト

- **その他のビジュアル**
  - `ball_move_line.html` - 線に沿って動く球体
  - `generative_art.html` - ジェネラティブアート
  - `heart_animation.html` - ハートのアニメーション
  - `lighting_show.html` - 照明エフェクトのショー
  - `minecraft.html` - マインクラフト風のブロック表現
  - `pattern_animation.html` - パターンアニメーション
  - `popping_ball.html` - 弾むボールのアニメーション
  - `solar_system.html` - 太陽系のシミュレーション

## 使用方法

各HTMLファイルは独立したデモとして機能します。ブラウザで直接開くことで実行できます：

```bash
# MacOSの場合
open short/filename.html

# Windowsの場合
start short/filename.html

# Linuxの場合
xdg-open short/filename.html
```

## 依存関係

これらのデモは以下の外部ライブラリを使用しています：

- Three.js - 3Dグラフィックスレンダリングライブラリ
- 一部のデモでは追加のThree.jsアドオンを使用

## ライセンス

このコレクションは学習と実験目的で提供されています。 