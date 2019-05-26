# はじめに
学習、推論、評価の3点すべてimage_classification.ipynbに含まれています  
保存したモデルは容量が大きいため、リポジトリに含めていません

# データについて
NGが186個、OKが187個のデータを以下のように分割した
- train
  - OK: 100個
  - NG: 100個
- validation
  - OK: 50個
  - NG: 50個
- test
  - OK: 37個
  - NG: 36個

# 実装環境
GPUを使用するためにgoogle colaboratoryを使用した

# 実行方法
- google colaboratoryでimage_classification.ipynbを開く
- メニューバーの「ランタイム」→「ランタイムのタイプを変更」から「GPU」を選択する
- コード中の画像のパスはプロジェクトのディレクトリ名に変更する
- 上のセルから順に実行していく
