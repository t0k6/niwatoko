# 要件定義書

色を暖色系にしたい

## 1. データの読み込み
- 指定された辞書データを使用してPandasデータフレームを作成する
- 日付列を適切なdatetimeデータ型に変換する

## 2. 欠損値の処理
- 欠損値を0で埋める

## 3. 累積値の計算
- 「zoltraak」と「niwatoko」の列の値を合計して「cumulative_total」列を作成する

## 4. 日本語フォントの設定
- 指定されたフォントパスを使用して日本語フォントを設定する

## 5. グラフの作成
- 「download_date」と「cumulative_total」の値をプロットする
- グラフのタイトル、軸ラベル、凡例を設定する
- X軸の目盛りを日付に設定し、45度回転させる
- グリッドを表示する

## 6. グラフの表示
- グラフを表示する