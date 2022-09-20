
1. 要望を書き連ねる
  - 朝におはよう，夕方にお疲れ，夜におやすみと言ってほしい
  - 話しかけたら，なんとなく会話を理解して欲しい
  - インターフェースは LINE で良い
2. 要件化して仕様を決める
  - 定型文を定期的にプッシュ型で配信できる
  - 対話文を生成し，入力によって出力を変更できる
3. 必要な技術スタックを調査する
  1. インフラ
    - Firebase
  2. サーバ
    - Cloud Function
  3. フロントエンド
    - LINE に JSON を返すだけで良いので不要
  4. 外部API
    - LINE Messaging API
    - Dialog Flow
4. 要件を満たす品質や実装コストを評価する
5. 設計する
  1. API設計
  2. DB設計
  3. ルーティング設計
  4. 画面遷移設計
  5. アーキテクチャ設計
6. 実装する
