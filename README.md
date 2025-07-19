# 🇯🇵 日本株LSTM株価予測アプリ 📈

このアプリは、日本の上場株（トヨタ、ソニーなど）をLSTMとテクニカル指標（MA, RSI, MACD）で予測します。

## 機能一覧
- LSTMによる株価予測
- MA20 / RSI14 / MACD を使った分析
- 売買シグナル表示（買い/売り/様子見）
- 学習済みモデルの自動保存
- 複数銘柄対応（ポートフォリオ的表示）

## 実行方法

```bash
pip install -r requirements.txt
streamlit run app.py
```
