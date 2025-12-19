# PDF to Markdown Converter

PDFファイルをセクションごとにMarkdownに変換し、図表は画像として抽出・参照を付けるWebアプリケーション

## Features (主な機能)

- PDF.js を使用した完全なPDF解析
- - セクションの自動抽出とタイトル認識
  - - Canvas APIを使用した図表の自動抽出
    - - Markdown形式への自動変換
      - - 図表への自動参照生成
        - - Markdown + 画像ファイルのZIPダウンロード
          - - モバイル対応のレスポンシブUI
           
            - ## How to Use (使い方)
           
            - 1. index.html をブラウザで開く
              2. 2. PDFファイルをアップロード（ドラッグ&ドロップ対応）
                 3. 3. 処理完了を待つ
                    4. 4. 結果をタブで確認（概要、セクション、Markdown、図表）
                       5. 5. ダウンロード（Markdownのみ、またはMarkdown+画像）
                         
                          6. ## Technology Stack (技術構成)
                         
                          7. - HTML5 + CSS3 (グラデーション、レスポンシブ)
                             - - Vanilla JavaScript (フレームワーク不使用)
                               - - PDF.js 3.11.174 (PDF解析・レンダリング)
                                 - - JSZip 3.10.1 (ZIP ファイル生成)
                                  
                                   - ## Project Structure
                                  
                                   - ```
                                     pdf-to-markdown-converter/
                                     ├── index.html          # メインアプリケーション
                                     ├── README.md           # このファイル
                                     └── images/             # 抽出された画像（ダウンロード時）
                                     ```

                                     ## Setup

                                     - ブラウザで index.html を開くだけでOK
                                     - - サーバーやインストール不要
                                       - - 完全にクライアント側で動作
                                        
                                         - ## License
                                        
                                         - MIT License
                                        
                                         - ## Author
                                        
                                         - Created for PDF document processing and Markdown conversion
