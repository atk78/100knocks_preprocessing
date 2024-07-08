# データサイエンス100本ノック（構造化データ加工編）

## Overview

- 一般社団法人データサイエンティスト協会が[GitHub](https://github.com/The-Japan-DataScientist-Society/100knocks-preprocess)に公開している構造化データの加工について3種類のPythonデータライブラリを用いて解答例を作成した。
- ここでは**Python**のみを取り扱っているが、本家は**Python**だけでなく、**R**と**SQL**も取り扱っているので興味がある人は本家のほうも取り組んでみてください。
- 本家はデータ成型のライブラリに`Pandas`を使用しているが、ここでは`Pandas`以外に、`Polars`および`Ibis`についての解答例も記載している。

## Requirement

- Pandas 2.2.2
- Polars 1.0.0
- scikit-learn 1.5.1
- Ibis 9.1.0
- imblearn 0.0

## Installation

ライブラリのインストールは以下の通り。（Ibsiのバックエンドはduckdb:デフォルトを利用）

```bash
pip install pandas polars scikit-learn ibis-framework
```

## Usage

`notebook`フォルダの中に各ライブラリでの解答例が入っています。

## Author

- Atsunori Kondo

## License

MITライセンスに従います。
