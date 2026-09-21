otomo-physical-ai/
├── README.md               # プロジェクト概要、理念、チーム紹介、ポスター連携情報
├── LICENSE                 # Apache License 2.0（GitHubで自動生成）
├── docs/                   # ドキュメント類
│   ├── ethics_guide.md     # プライバシー保護・医師法/税理士法リスク対策ルール
│   └── fieldwork_notes.md  # オートエスノグラフィー（当事者・現場観察記録の要約）
├── prompts/                # 対話シナリオ・プロンプト設計
│   ├── system_prompts.txt  # 「オトモ」のペルソナ（弱いロボット論に基づく対話設計）
│   └── qa_rag_flow.md      # 公的健康Q&Aを参照するRAGナビゲーションの設計思想
└── prototype/              # システム構成・コード（準備できたものから順次格納）
    ├── system_architecture.png  # ハード構成図（Google Home＋センサー等の連携図）
    └── app.py                   # Gradio / Streamlit等のWebモックアップコード（任意）
