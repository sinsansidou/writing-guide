graph TD
    %% 親カテゴリ
    Root("<b>【親】 観光スポット名</b><br/>（記事のメインテーマ）")

    %% 子カテゴリ（3つの引き出し）
    Sub1("<b>❶【土台】 基本スペック</b><br/>（信頼を作る事実の枝）")
    Sub2("<b>❷【心臓】 見どころ・特徴</b><br/>（魅力を伝える主役の枝）")
    Sub3("<b>❸【親切】 お役立ち・補足</b><br/>（満足度を上げる配慮の枝）")

    %% 孫カテゴリ（具体的な情報の断片）
    Leaf1_1("📍 所在地・アクセス")
    Leaf1_2("🏛️ 建立・歴史背景")
    Leaf1_3("🏷️ 文化財・国宝指定")

    Leaf2_1("✨ 本尊・メイン建築")
    Leaf2_2("📸 絶景・庭園")
    Leaf2_3("写経・御朱印体験")

    Leaf3_1("🍂 季節のイベント")
    Leaf3_2("🍴 周辺グルメ情報")
    Leaf3_3("🚗 混雑回避・駐車場")

    %% 線の接続
    Root --- Sub1
    Root --- Sub2
    Root --- Sub3

    Sub1 --- Leaf1_1
    Sub1 --- Leaf1_2
    Sub1 --- Leaf1_3

    Sub2 --- Leaf2_1
    Sub2 --- Leaf2_2
    Sub2 --- Leaf2_3

    Sub3 --- Leaf3_1
    Sub3 --- Leaf3_2
    Sub3 --- Leaf3_3

    %% スタイルの設定
    style Root fill:#f9f,stroke:#333,stroke-width:2px
    style Sub1 fill:#e1f5fe,stroke:#01579b
    style Sub2 fill:#fff9c4,stroke:#fbc02d
    style Sub3 fill:#e8f5e9,stroke:#2e7d32
