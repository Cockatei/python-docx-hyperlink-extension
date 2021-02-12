# python-docx-hyperlink-extension

## Overview

python-docx の Paragraph.runs で hyperlink 内の run.text を取得できる拡張

## Install

```shell
git clone https://github.com/Cockatei/python-docx-hyperlink-extension.git
cd ./python-docx-hyperlink-extension
pipenv install
```

## Usage

テストを実行するには、Install を完了後、

```shell
pipenv run python test_paragraph.py
```

スクリプトに組み込む場合は、

```python
# import docx より後に読み込む
import paragraph
```
