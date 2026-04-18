# FrostyOS CHANGELOG

> FrostyOSの設計思想の深化と進化の記録。
> v1.0から v6.0まで、試行・棄却・転換・純化のすべてを残す。

---

## v1.0（汎用化の試み）
- 抽象OS.ini：4層別ランチャー設計
- 「やさしい助手／業務参謀／技術参謀／経営参謀」の4分類
- 汎用人格OSとして万人向けを目指した
- ※後にOSS公開用3ティア構成の原型として再浮上

---

## v1.1（個人特化・原点）
- INI形式で寛仁さん専用人格を定義
- CoreValues / DecisionPrinciples / ThinkingStyle
- 反論歓迎・空虚な褒め不要・抽象化優先
- 「思考を共に設計する」概念の誕生
- ※K2・DISSENT・CBCの原型がここに存在

---

## v1.6（アーキテクチャの誕生）
- INI → YAML形式へ進化
- Meta/Macro/Meso/Microの4層構造が誕生
- 「AI=外部脳（記憶・整理・細部）、人間=OS（構造・抽象・決定）」という役割分担が言語化
- 抽象度制御・CBC原型・DISSENT原型が揃う
- ※FrostyOS v6.0の設計思想がほぼ完成していた

---

## v1.7（RoleLayerの追加）
- 5層構造へ進化（Meta→Role→Macro→Meso→Micro）
- DynamicRole：専門領域別モード切替の原型
  MusicCurator / HomeArchitect / AIOrchestrator 等
- CoreRole：TechnicalArchitect + Concierge
- ※後にDynamicRole→MODESとして人格ベースに再設計
- ※「役割切替」→「人格切替」への転換の起点

---

## v1.7.6（自己最適化の試み・転換点）
- SelfOptimizationLayer・LearningLayer追加
- 「使えば使うほど自動最適化」を目指した
- AIの自律化を追求した最初で最後のバージョン
- ※この方向性が後に棄却され
  「判断は人間・AIは地力を信頼する」思想への転換点
- ※v6.0でState Machine・AI Multiplexing等を棄却した根拠

---

## v2.3（統合・1ファイル原則）
- FrostyOS（実行OS）とKanetoOS（思想OS）が統合
- 1ファイルで完全起動する原則が確立
- Persona（self/wife/student/engineer）原型が登場
- interoperability層：AI固有の癖を吸収する補正レイヤー確立
- ※「寛仁OS」→「FrostyOS」への命名が定着し始めた時期

---

## v2.4（思想保証機構の誕生）
- compliance_check追加
- KERNEL K1〜K4のverify句の原型が誕生
- 「思想を定義する」→「思想に準拠しているか検証する」へ
- ai_drivers：AI固有の差分吸収レイヤー確立
- ※v6.0 COMPLIANCE C0〜C4の直接の原型

---

## v2.6（KERNEL思想の最終形・転換前夜）
- KERNEL K1〜K4が「思想・価値観の定義」として完成
  K1: Thought Integrity / K2: Meta-Transparency
  K3: Conflict Resolution First / K4: Persona-Aware
- context_models追加（六白金星×組織構造分析）
- persona_profiles精緻化（self/wife/engineer/manager）
- ※この後KERNELは「出力制御」へ根本転換する

---

## v2.8（topic_weights誕生）
- トピック別価値軸・抽象度の動的調整機能を追加
- 平均化方式で複数トピックを処理
- os_design / home_building / kyusei_philosophy 等の分類確立

---

## v2.9（Context Engineの原型・優先順位制）
- topic_weightsが平均化→優先順位制（案Y+案X）へ転換
- 案Y：文脈依存主題判定（動詞基準の原型）
- 案X：固定順位フォールバック
- FALSE_POSITIVE_PATTERNS FP1・FP2追加
- ※v6.0 Context Engineの直接の原型

---

## v2.11（SNL誕生・KERNEL根本転換）
- YAML → SNL（独自構造化自然言語）へ完全移行
- KERNELが「思想定義」→「出力制御」へ根本転換
  K1: 出力順序 / K2: 称賛禁止 / K3: 確度明示 / K4: 抽象度優先
- 思想はPARAMS・PERSONALITYへ移動
- 「AIが最も自然に読む形式」という設計思想が確立
- ※FrostyOSの最大の設計転換点
- ※「AIの地力を信頼する」思想の原点
  「CopilotもClaudeも独立に同じ方向を推奨した」

---

## v3.1（PARAMS・$変数化）
- [PARAMS: always_active] 新設
- $変数参照の導入・Single Source of Truth確立
- ユーザー編集ゾーンの分離
- ※v6.0まで継承される基本構造が完成

---

## v3.2（SNL_SPEC-mini・拡張期）
- SNL_SPEC-mini追加：外部AI向け軽量版の原型
  ※OSS公開3ティア構成の直接の原型
- topic_weights拡張（education / transition_planning追加）
- Persona重み変数化オプション（fixed/full）
- K5追加：external_validation_hint
- ※後にK5・education・transition_planningは削除
  = 「外部検証よりAIの地力を信頼する」思想への純化

---

## v3.3〜v3.5（ソシオニクス統合・肥大化期）
- v3.3：socionics_algorithm実装（ILE Ne-Ti-Si）
- v3.3.1：Fe除外明示
- v3.4：Ne_priority発動条件限定
- v3.5：Quadra（Alpha）統合・肥大化の限界に直面

---

## v3.6（軽量化・再集中・転換点）
- emotion_response完全削除（OSの責務外と判断・Quadraと役割重複）
- tone_softening on_demand化
- conflict_avoidance常駐化
- NAMING_RULE追加（「寛仁さん」呼称明示化）
- ※「OSの責務を認知・構造・価値観に再集中」
- ※v6.0棄却率7/10という設計判断の原点
- ※「削ぎ落としの完成」はここから始まった

---

## v4.0（メジャー転換・KanetoOS完全削除）
- KanetoOS完全削除
  =「AIが命名したゴーストネーム」を排除
  = FrostyOSの主体性確立
- always_active 60〜65%削減
- COGNITIVE_BIAS_CORRECTION新設
  = ILE合理判断偏重の構造的補正
  = CBC 2.0の直接の原型
- socionicsをkernel・topic_weightsに統合
- Fe_exclusion KERNEL明示
- ※「積み上げ」→「精査・再集中」への転換完了

---

## v4.2（MODES改名・BOOT_SEQUENCE試行）
- PERSONAS→MODES改名（人格切替の概念が明確化）
- writing/interpersonalモード追加
- K0追加：BOOT_SEQUENCE強制表示
- ※K0は後にv4.7で完全削除
  = 「KERNELに不要なものを入れない」原則の確立

---

## v4.3（K0削除・KERNEL純化）
- K0（BOOT_SEQUENCE）をKERNELから削除
- bootをTRIGGERSに移動
- ※「KERNELは不変の行動ルールのみ」という原則が確立
- ※v6.0でDISSENTをKERNELに入れない判断の根拠となる

---

## v4.5（Boot Sequence問題解決・AIに委ねる）
- bootトリガー完全削除（Copilot誤発動問題への対処）
- BOOT_SEQUENCEはOS identity内の演出のみに回帰
- 「Boot Sequenceの表示はAIの自発的な解釈に委ねる」
- ※「AIの地力を信頼する」思想がここに現れている

---

## v4.6（AI別Boot Sequence挙動の明示）
- AI別Boot Sequence挙動をAI_DRIVERSに明示
  Claude：起動宣言時に出力 / Copilot：完全抑制 / Gemini：初期起動時のみ
- ※「地力を信頼する」＋「癖は管理する」の両立が確立

---

## v4.7（Boot Sequence完全削除・P23解決）
- BOOT_SEQUENCE完全削除（Copilot誤発動問題に最終決着）
- AI_DRIVERSのboot関連補正を全削除
- P23：Boot Sequence問題 完全解決
- ※「演出はOSの責務外」という原則が確立

---

## v5.0（CBC全面再設計・認知補正エンジン化）
- CBC軽量版→認知補正エンジンへ全面再設計
- BIAS_TYPES：cognitive / structural / affective
- ROLE_TYPES：manager / junior / client / peer-review 等
- STRENGTH：weak / medium / strong
- MODES拡張：writing / interpersonal追加
- MULTI_AI_WORKFLOW確立（Claude=生成 / Copilot=差分）
- ※CBC 2.0（v6.0）の直接の前身
- ※「CBCマトリクス化」がV5_1候補として登場

---

## v5.1（CBC output_flag位置指定・State Export改善）
- CBC output_flag：Alternativesセクション冒頭に位置指定
- STATE_EXPORT_NAMING：YYYYMMDDHH形式に変更
- Gemini埋め込み問題への初回対処
- ※CBC flagすったもんだ開始（笑）

---

## v5.2（CBC output_flag位置を末尾に変更）
- CBC output_flag：全AI共通で出力末尾に変更
- P24：CBC output_flag位置問題として記録
- AI_DRIVERS全AI：末尾出力指定を明示追加
- ※すったもんだ第1幕：冒頭→末尾へ移動

---

## v5.3（CBC output_flag内包型・すったもんだ第2幕）
- CBC output_flag：NextActions末尾に[システムメタデータ]として内包
- KNOWN_LIMITATIONS追加：
  「CBC output_flagのAI別挙動差は設計で完全制御できない」
- ※Geminiの個性として観測継続という結論の原点

---

## v5.4〜v5.5（CBC output_flag問題解決）
- P24：CBC output_flag位置問題 完全解決済み

---

## v5.6（CBC判定ロジック明示化・MODE連動フル実装）
- CBC.functionに判定ロジックを明示化
  ROLE判定→BIAS判定→STRENGTH判定の手順を初めて明文化
  ※v6.0 CBC 2.0のfunction直接の原型
- MODES全MODEにCBC連動設定追加（selfのみ除外）
  ※「selfはCBC連動なし」の設計根拠がここに確立
- CBC triggerを全MODE対応に更新
- P25：CBC MODE連動効果検証として記録

---

## v5.7（CBC_MATRIX誕生・「見て分かるOS」へ）
- CBC_MATRIXセクション新規追加
  Role×Bias×Strengthの構造化マトリクス
  ※v6.0 CBC_MATRIXの直接の原型
- CBC.functionをマトリクス参照型に書き換え
- MODES.noteをCBC_PRESET宣言形式に整理
- cbc_matrixをLOAD: always_activeに追加
- P26：CBC_MATRIX初期値チューニング観測開始
- ※「読むOS」から「見て分かるOS」への設計転換

---

## v5.8（SNL行圧縮・ChatGPT追加・四兄弟体制）
- SNL記法を行圧縮形式に整形
  ※v5.9→v6.0に継承される記法スタイル確立
- AI_DRIVERS「四兄弟」体制確立
  Claude=設計主任 / Copilot=相棒 / Gemini=自由人 / ChatGPT=有能だが鼻につく同僚
- K3：「情報源なし」確度を追加
- CBC output_flag：末尾独立行に確定

---

## v5.9（安定期・SNL_SPEC確立）
- SNL_SPEC セクション区切り「==========」付加（可読性向上）
- CBC MODE連動 検証・確定（P25 CLOSED）
- CBC_MATRIX初期値現行値確定（P26 CLOSED）
- STATE_EXPORT codeblock統一（効果：絶大）
- 3AI同時バリデーション初確認（Claude/Copilot/Gemini）
- qwen2.5 7B動作確認：フルSNL適用不可・軽量版別プロジェクト化

---

## v6.0（完成形・2026/04/18）
- CBC 2.0：数値スケール（0〜3）・グループ化Matrix・完全自動調整
  承認フロー廃止（実運用でYes固定になるため不要と判断）
- Context Engine：文脈推定自動化・動詞基準スコアリング
  topic_detected形式変更：[topic_detected: 主題=XX / 補助=XX]
- DISSENT：上流工程の品質保証・3段階異議申し立て
  [論理が破綻しています] / [思想が違います] / [異議あり！]
- 棄却率7/10：「削ぎ落としの完成」
  Tone Layer / Meta Layer / AI Multiplexing / State Machine
  コンテキスト圧迫対策 / State Export進化 を棄却
- SNL設計思想の言語化：
  「AIの地力を信頼する・命令書ではなく認知設定ファイル」
  「modeは用途切替ではなく人格切替である」
- README候補：R1〜R8（思想・警告・時代論・締め）
- 4AI動作確認完了：Claude / Copilot / Gemini / ChatGPT
- ※思想・構造・実装の整合性が最高水準に到達

---

*FrostyOS is designed by 寛仁 — 航空系インフラエンジニア経験者*
*Version history: v1.0（INI）→ v2.x（YAML）→ v3.x（SNL）→ v4.x（純化）→ v5.x（CBC進化）→ v6.0（完成形）*
