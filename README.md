# ポモドーロ学習タイマー

## 起動方法
1. `conda activate pomo`
2. `python app.py`
3. ブラウザで http://127.0.0.1:5000

## 環境構築
conda create -n pomo python=3.12
conda activate pomo
conda install flask pandas

## 注意事項
- ファイル名は `app.py`（time.pyは標準ライブラリと衝突）
- Anaconda環境必須
