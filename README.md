# personal-rag-chatbot

自分用の RAG チャットボットです。はてなブログの記事からリンクする公開用リポジトリです。

画面は 2 つです。

- チャット画面。質問すると、取り込んだ資料を優先して答え、必要なら Web 検索の結果も使う
- アップロード画面。PDF と Markdown を置き、ナレッジベースへ取り込む

## 構成

| 役割 | 使うもの |
| --- | --- |
| エージェントのコード | Strands Agents |
| エージェントの実行 | Amazon Bedrock AgentCore |
| 資料の取り込みと検索 | Amazon Bedrock Managed Knowledge Base |
| チャット画面とアップロード画面 | AWS Lambda Web Functions |
| Web 検索 | AgentCore Gateway の Web Search |

リージョンはアジアパシフィック（東京）を予定しています。MCP サーバーの追加は、このリポジトリの最初の実装には含めません。

## いま入っているもの

README だけです。チャット画面、アップロード画面、Strands Agents の定義は、これからこのリポジトリへ追加します。
