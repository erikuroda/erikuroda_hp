# eri-kuroda.com

個人ホームページ（Quarto製）。`main` にpushすると GitHub Actions が自動でビルドして GitHub Pages に公開されます。

## 日常の更新場所

| 更新したい内容 | 編集するファイル |
|---|---|
| News | `_content/news-ja.md` / `news-en.md`（先頭に追記） |
| 論文・発表 | `_content/publications-ja.md` / `-en.md` |
| 経歴 | `_content/career-ja.md` / `-en.md` |
| 委員歴 | `_content/committees-ja.md` / `-en.md` |
| 研究資金等 / 受賞 | `_content/funds-*.md` / `awards-*.md`（表形式） |
| Bio・トップページ | `index.qmd` / `en/index.qmd` |
| Research | `research.qmd` / `en/research.qmd` |
| CVのPDF | Google Drive上のPDFを差し替え（ページは `cv.qmd` / `en/cv.qmd`） |
| 色・デザイン | `theme.scss` |
| ナビ・サイト設定 | `_quarto.yml` |

## ローカルプレビュー

```sh
quarto preview
```

## メモ

- `cv-pdf.qmd` は `_content/cv-body.md` からPDF（`cv_erikuroda.pdf`）を自動生成する仕組み（現在サイトからは未リンク）。
- 旧サイトのソースは `~/ek_hugo`（Hugo + R blogdown、アーカイブ）。
