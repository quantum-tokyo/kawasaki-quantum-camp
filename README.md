# Kawasaki Quantum Summer Camp 2024

### Day 1
- [量子コンピューティング入門](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day1/20240730_Intro.pdf)
- [量子ゲート基礎 IBM Quantum Composer](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day1/20240730_Composer.pdf)
- [Qiskit入門演習](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day1/20240730_qiskit.ipynb)

### Day 2
- 量子ハードウェア入門(解説・[コード](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day2/20240731_hardware.ipynb)・[解答例](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day2/20240731_hardware_solution.ipynb)）
- 量子テレポーテーション（[解説](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day2/20240731_2_Telepo.pdf)・[コード](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day2/20240731_teleportation.ipynb)・[解答例](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day2/20240731_teleportation_solution.ipynb)）
- 量子機械学習 ([解説](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day2/20240731_3_QML.pdf)・[コード](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day2/qml/20240731_qml.ipynb)・[解答例](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day2/qml/20240731_qml_solution.ipynb))

### Day 3
- 量子化学で薬の開発([解説](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day3/20240801_Nature.pdf)・[コード](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day3/nature/20240801_nature.ipynb)・[解答例](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day3/nature/20240801_nature_solution.ipynb))
- 量子最適化([解説](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day3/20240801_optimization.pdf)・[コード](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day3/20240801_optimization.ipynb)・[解答例](https://github.com/quantum-tokyo/kawasaki-quantum-camp/blob/main/day3/20240801_optimization_solution.ipynb))

### Day 4
- 資料なし

## Camp期間のあとにQiskitコードを動かす場合
JupyterHub環境が動かなくなりますが、以下のいずれかの方法でコードを実行することができます。
1. [Google Colabratory](https://colab.research.google.com/)    
   毎回、以下のコマンドをjupyter notebook上で最初に実行する必要があります。([参考ブログ](https://qiita.com/kifumi/private/51a5d2a420e6318f78fb))
```
!pip install qiskit qiskit[visualization] qiskit-ibm-runtime qiskit-aer
!pip install qiskit-algorithms qiskit-nature scikit-learn 
!pip install --prefer-binary pyscf
```

2. [qBraid](https://www.qbraid.com)    
   実機で実行する場合は、以下のコマンドを実行する必要があります。
```
%pip uninstall --yes simplejson
```

わからなくなったら、IBM 沼田 (kifumi@jp.ibm.com) にご連絡ください。

## 事前学習(補習教材)
- 数学の準備
    - [簡単な解説と演習問題](./vector_matrix.pdf)
    - [行列入門](https://www.mext.go.jp/content/20230828-mxt-kyoiku01_000250597_1.pdf)
- プログラミングの準備
    - [基本的なプログラミング（Python入門）](https://sites.google.com/a.ipsj.or.jp/mooc/list/C3-1)



### 
2023年のコンテンツは[こちら](https://github.com/quantum-tokyo/kawasaki-quantum-camp/tree/main/2023)    
2022年のコンテンツは[こちら](https://github.com/quantum-tokyo/kawasaki-quantum-camp/tree/main/2022)
