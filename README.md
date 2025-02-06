# SPAAL v2

* Simulator of the Physical Attack Against LiDARsの略
* Spoofing AttackとLiDARのToF信号処理をシミュレーションします

# 仕組み

* ToF距離計算に用いられる光を時間-強度の1次元データとしてモデル化
* LiDARの測距ごとに反射波形とその時間の攻撃波形をシミュレート、合成波形からToFを計算

![](image/2024-05-19-14-20-00.png)

# Getting Started

1. [uv](https://docs.astral.sh/uv/)をインストール
2. `[git clone git@github.com:Keio-CSG/spaal2.git](https://github.com/Keio-CSG/spaal2-core.git)`
3. `uv run example/ahfr.py`
