# 作るもの
1. 自家製Notion Q&A
→NotionQ&Aが調子悪いから、LlamaIndexでNotionを読み込んで、自家製NotionQ&AをGeminiを使って作る。GraphRAGも組み合わせたい

2. 授業資料RAG
→図表を解析できる方法を調べて、図表込みで答えてくれるRAGシステム作り。

3. (モデルのファインチューニング、RLHF。)←LLM講座でやったようなこと。ただ、手作業が多くて時間の関係上、今回は省略。

# 使用モデル
Gemini→無料で使えるから。なるべくGeminiで行きたい。無理ならGPT-4o mini
HuggingFaceから、ホーダチさんとかサイバーエージェントの日本語チューニングLlama3.1も使えたら嬉しいな

# 使用技術
LlamaIndex, LangChain, GraphRAG

# 目的
LLM学習ロードマップの学習成果として、勉強したことを用いてアウトプットを出したい。
LlamaIndex, LangChainを組み合わせたRAG botはもちろん、そこに論文や文献を読んで得た知識を使ってカスタマイズして精度向上させたい。
→pdfの図表も解析できるRAG、GraphRAGとか。
