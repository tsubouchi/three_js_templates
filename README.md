# Three.js テンプレートコレクション

このリポジトリには、Three.jsを使用した様々なインタラクティブな3Dビジュアルエフェクトとアニメーションのテンプレートが含まれています。

## ディレクトリ構成

- `short/`: 短いThree.jsデモやサンプルを格納
- `slides/`: プレゼンテーション用のファイルを格納
- `caption/`: キャプション付きのデモを格納

## テンプレート一覧

### shortディレクトリ

以下のHTML単一ファイルのデモが含まれています：

- **音響エフェクト**
  - `sound_equalizer.html` - 音楽に合わせて動くグラフィックイコライザー

- **パーティクルエフェクト**
  - `interactive_particles.html` - インタラクティブなパーティクルアニメーション
  - `interactive_particles_click.html` - クリックに反応するパーティクルエフェクト
  - `smoke_clouds_particles.html` - 煙のようなパーティクルエフェクト
  - `particle_background.html` - パーティクルを使用した動的な背景効果

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
  - `decision_transition.html` - 意思決定を視覚化するトランジション効果

- **その他のビジュアル**
  - `ball_move_line.html` - 線に沿って動く球体
  - `generative_art.html` - ジェネラティブアート
  - `heart_animation.html` - ハートのアニメーション
  - `lighting_show.html` - 照明エフェクトのショー
  - `minecraft.html` - マインクラフト風のブロック表現
  - `pattern_animation.html` - パターンアニメーション
  - `popping_ball.html` - 弾むボールのアニメーション
  - `solar_system.html` - 太陽系のシミュレーション

### captionディレクトリ

キャプション付きのインタラクティブデモが含まれています：

- `caption_test.html` - キャプション機能のテストデモ

### slidesディレクトリ

プレゼンテーション用のファイルが含まれています：

- `slide.html` - Three.jsを使用したインタラクティブなプレゼンテーション

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