```mermaid
flowchart TD
    A(("案件の種"))
    A --> node_2
    node_2 --> node_3
    node_3 --> node_1
    A --> node_4
    node_4 --> node_1
    node_4 --> node_5
    node_4 --> node_6
    node_3 --> node_7
    node_3 --> node_8
    node_8 --> node_9
    node_8 --> node_10
    node_3 --> node_11
    node_11 --> node_12
    node_12 --> node_11
    node_1 --> node_13
    node_13 --> node_14
    node_1 --> node_15
    node_1 --> node_16
    node_1 --> node_17
    node_14 --> node_18
    node_18 --> node_19
    node_15 --> node_19
    node_16 --> node_19
    node_17 --> node_19
    node_19 --> node_20
    node_19 --> node_21
    node_19 --> node_22
    node_20 --> node_23
    node_23 --> node_24
    node_19 --> node_25
    node_21 --> node_26
    node_26 --> node_27
    node_26 --> node_28
    node_27 --> node_29
    node_27 --> node_30
    node_27 --> node_31
    node_30 --> node_32
    node_32 --> node_33
    node_33 --> node_32
    node_30 --> node_34
    node_31 --> node_34
    node_34 --> node_35
    node_34 --> node_36
    node_34 --> node_37
    node_35 --> node_38
    node_35 --> node_39
    node_39 --> node_40
    node_34 --> node_41
    node_41 --> node_42
    node_2["要件概要"]
    style node_2 fill:#6699CC
    node_3(("実現可用性の確認"))
    node_4["ビジネス価値の確認"]
    node_5["リーンキャンバス"]
    node_1(("プロジェクト名（英名や略称も）を決める"))
    style node_5 fill:#6699CC
    node_6["カスタマージャーニー"]
    style node_6 fill:#6699CC
    node_7["技術スタックの選定"]
    node_8["外部連携の整理"]
    node_9["データフロー"]
    style node_9 fill:#6699CC
    node_10["連携方式"]
    style node_10 fill:#6699CC
    node_11["全体概要図の作成"]
    style node_11 fill:#6699CC
    node_12["技術的スパイク"]
    node_13["関係者のスクラム理解推進"]
    node_14["プロダクトオーナーの工数確保"]
    node_15["社内Wikiツール準備"]
    node_16["プロジェクト管理ツール準備"]
    node_17["社内チャットツール準備"]
    node_18["スクラムイベントのスケジュール作成"]
    subgraph スプリント0
        node_19(("スプリント０"))
        node_20["インセプションデッキの作成"]
        style node_20 fill:#6699CC
        node_21["ワーキングアグリーメントの作成"]
        node_22["完了条件の定義"]
        node_23["ステークホルダの特定"]
        node_24["プロジェクト参加工数や役割の調整"]
        node_25["チームビルディング"]
        node_26["ユーザーストーリーマッピングの作成"]
        node_27["プロダクトバックログの作成"]
        node_28["ユーザーのペルソナ設定"]
        node_29["完了条件、着手可能条件の明確化"]
        node_30["MVPの定義"]
        node_31["優先順位付け"]
    end
    node_32["リリース計画"]
    node_33["他ベンダとの調整"]
    subgraph テックスプリント0
        node_34(("テックスプリント０"))
        node_35["最低限のアーキテクチャ設計"]
        node_36["コーディング規約"]
        node_37["ブランチ戦略"]
        node_38["ブランクプロジェクト作成"]
        node_39["Gitリポジトリ準備"]
    end
        node_40["CI/CDパイプライン準備"]
        node_41["スプリント計画"]
        node_42(("スプリント１"))
    style node_21 fill:#6699CC
    style node_26 fill:#6699CC
    style node_27 fill:#6699CC
    style node_30 fill:#6699CC
    style node_35 fill:#6699CC
    style node_36 fill:#6699CC
    style node_32 fill:#6699CC
    style node_38 fill:#CC9966
    style node_39 fill:#CC9966
    style node_40 fill:#CC9966
````
