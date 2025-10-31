# Employee Attrition Prediction

退職者予測モデル（決定木 + Pipeline）

## 目的
社員データをもとに退職者を予測し、特徴量の影響を可視化する。

## 使用技術
- Python, pandas, scikit-learn, matplotlib
- Pipeline / ColumnTransformer
- Permutation Feature Importance

## プロジェクト構成
```bash
EmployeeAttrition/
├── data/         # 生データ・前処理後デー
├── models/       # 学習済みモデル
├── notebooks/    # 分析ノートブック
└── reports/      # グラフ画像・分析結果のまとめ
└── README.md     # このファイル
