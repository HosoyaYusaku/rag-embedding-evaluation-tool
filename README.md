# RAG Embedding Evaluation Tool

A simple and interactive tool to evaluate and compare search ranking of RAG embedding models. This tool runs entirely on Google Colab.

## ✨ Features

-   **Interactive UI:** Easily upload files and run searches using `ipywidgets`.
-   **Multiple Division Methods:** Split documents by line, by fixed-size chunks, or by JSON objects.
-   **Embedding Model Comparison:** Test various OpenAI embedding models (`text-embedding-3-small`, `text-embedding-3-large`, etc.) or use simple keyword search.
-   **Instant Feedback:** Get a ranked list of search results immediately.
-   **Export Results:** Download split documents and search results as a `.txt` or `.csv` file.

## 🚀 How to Use

There are two ways to use this tool. Choose the one that fits your needs.

### Method 1: Quick Start (Open Directly in Colab)
This method is perfect for a quick test or a one-time evaluation.

1.  **Open in Colab:** Click the button below.
    
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HosoyaYusaku/rag-embedding-evaluation-tool/blob/main/rag_embedding_evaluation_tool.ipynb)

2.  **Important:** This opens a temporary notebook. To save your work, you **must** save a copy to your own Google Drive (`File` -> `Save a copy in Drive`).
3.  **Set API Key:** Add your OpenAI API key to Colab's "Secrets" manager (look for the 🔑 icon on the left) with the name `OPENAI_API_KEY`.
4.  **Run & Evaluate:** Run the cells, upload your document, and start evaluating.

### Method 2: For Customization & Repeated Use (Recommended)
This method allows you to save your changes and integrate the tool into your own workflow.

1.  **Download:** Download the notebook file (`Your-Notebook-File.ipynb`) from this repository.
2.  **Upload:** Upload the downloaded file to your own Google Drive.
3.  **Open from Drive:** Open the notebook from your Google Drive. Now, all your modifications will be saved automatically.
4.  **Set API Key:** Add your OpenAI API key to Colab's "Secrets" manager with the name `OPENAI_API_KEY`.
5.  **Run & Customize:** Run the cells and feel free to customize the code for your own projects!

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
<br>

# RAG埋め込み評価ツール

RAG（Retrieval-Augmented Generation）で利用する埋め込みモデルの検索順位を手軽に評価・比較するための、インタラクティブなツールです。すべての処理はGoogle Colab上で完結します。

## ✨ 主な機能

-   **インタラクティブなUI:** `ipywidgets`を使い、GUIで直感的にファイルアップロードや検索ができます。
-   **多様な分割方法:** 1行ごと、固定長のチャンク、JSONオブジェクト単位でのドキュメント分割に対応。
-   **埋め込みモデルの比較:** 様々なOpenAIの埋め込みモデル（`text-embedding-3-small`など）や、シンプルなキーワード検索を試せます。
-   **即時フィードバック:** 検索クエリに対して、スコア順にソートされた検索結果をすぐに確認できます。
-   **結果のエクスポート:** 分割後のドキュメントや検索結果を、`.txt`や`.csv`ファイルとしてダウンロードできます。

## 🚀 使い方

このツールの使い方は2通りあります。目的に合わせて選んでください。

### 方法1：すぐに試す（Colabで直接開く）
一度だけ試したい、手軽に評価したい場合に最適な方法です。

1.  **Colabで開く:** 下のボタンをクリックします。

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HosoyaYusaku/rag-embedding-evaluation-tool/blob/main/rag_embedding_evaluation_tool.ipynb)

2.  **重要:** この方法では一時的なノートブックが開きます。作業内容を保存するには、**必ず**ご自身のGoogleドライブにコピーを保存してください（`ファイル` > `ドライブにコピーを保存`）。
3.  **APIキーの設定:** Colabの「シークレット」機能（左側の`🔑`アイコン）で、`OPENAI_API_KEY`という名前であなたのOpenAI APIキーを登録します。
4.  **実行と評価:** セルを実行し、ファイルをアップロードして評価を開始します。

### 方法2：カスタマイズして利用する（推奨）
このツールを改造したり、ご自身のプロジェクトで繰り返し使いたい場合におすすめの方法です。

1.  **ダウンロード:** このリポジトリからノートブックファイル（`Your-Notebook-File.ipynb`）をダウンロードします。
2.  **アップロード:** ダウンロードしたファイルを、ご自身のGoogleドライブにアップロードします。
3.  **ドライブから開く:** Googleドライブからノートブックを開きます。こうすることで、加えた変更はすべて自動で保存されます。
4.  **APIキーの設定:** Colabの「シークレット」機能で、`OPENAI_API_KEY`という名前であなたのOpenAI APIキーを登録します。
5.  **実行とカスタマイズ:** セルを実行し、あなたのプロジェクトに合わせて自由にコードを改造してみてください！

## 📄 ライセンス

このプロジェクトはMITライセンスです。詳細は[LICENSE](LICENSE)ファイルをご覧ください。
