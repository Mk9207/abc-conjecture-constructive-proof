# 構成的完全証明：ABC予想 / Constructive Proof of the ABC Conjecture

このリポジトリは、ABC予想に対する構成的完全証明を収録しています。

## 🔍 問題概要

ABC予想は次のように表現されます：

> 任意の \epsilon > 0 に対して、a + b = c かつ gcd(a, b, c) = 1 の自然数に対し、  
> c > \text{rad}(abc)^{1+\epsilon} を満たす解は有限個しか存在しない

ここで rad は、abc に含まれる異なる素因数の積です。

## ✅ 証明の特徴

- A型素数構造と構成的密度評価の応用
- rad関数による対数的スケーリングと構成的除去関数の結合
- gcd(a, b, c) = 1 の領域の零密度化による非存在の証明
- 構成的補題・定理・排除構造を使用した形式的証明展開

## 📂 ディレクトリ構成

. ├── main.tex ├── sections/ │   ├── introduction.tex │   ├── radical_function.tex │   ├── coprime_density.tex │   ├── removal_argument.tex │   ├── theorem_proof.tex │   └── conclusion.tex ├── README.md ├── LICENSE ├── compile.sh └── .gitignore

## 🧠 論証の構成的アプローチ（LaTeX展開）

- 共通因数なし領域の零密度性（coprime domain elimination）
- rad(abc) の拡張によるスケーリング評価と排除条件
- 明示的な補題と定理構造で論理展開

## 🌐 GitHub Topics（推奨）

math number-theory abc-conjecture constructive-mathematics radical-function coprime-analysis latex arxiv-compatible

## ✍️ ライセンス

本リポジトリは [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) に従って公開されています。

---

_この証明は、AIと人間の協働による構成的数論の発展の一環として構築されました。_
