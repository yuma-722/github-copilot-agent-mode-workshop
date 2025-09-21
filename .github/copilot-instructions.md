<!-- GitHub Copilot / AI Agent instructions for this repository -->
# Agent Instructions — github-copilot-agent-mode-workshop

Purpose: help AI coding agents be immediately productive in this repository.

- コミットルール: Agent Mode で提案する変更は、プロンプト内容と変更内容が分かる簡潔な日本語のコミットメッセージでコミットしてください（例: `agent: X のテスト追加 — prompt: Y ハンドラの単体テストを追加する`）。
- Azure 参照: Azure 関連の提案やコードを含む場合は必ず Microsoft Learn のページを参照し、ページタイトルと公式 URL を明記してください。Learn を参照せずに Azure に関する指示を作成しないでください。

Quick repo overview
- Small workshop repo; top-level files are `README.md` and license. There are no large services or build scripts. Treat changes as small, self-contained edits unless new files indicate otherwise.

How to make changes
- 小さなコミットで作業してください。各コミットにはプロンプトと変更内容が分かる簡潔な日本語メッセージを付けます。コミットメッセージのフォーマット例:
  - ``agent: <短い変更概要> — prompt: <1行のプロンプト>``
  - 例: ``agent: copilot-instructions を追加 — prompt: エージェント向け指示ファイルを生成``

Code & contribution patterns
- Keep changes minimal and focused: most exercises expect a single logical change (README, doc, or small code snippet).
- Prefer edits under `.github/`, `README.md`, or a new top-level file unless the user asks for deeper refactors.

Azure and external integrations
- When touching Azure-related code or suggestions (deploy, az CLI, ARM/Bicep, Functions, Static Web Apps), include a Microsoft Learn reference link and mention the specific Learn page title.

How to run/tests/debug
- There are no automated test or build scripts in this repo. If you add runnable code, also add minimal run instructions in the same commit (simple commands in `README.md`) so a human or CI can validate.

Examples from this repository
- `README.md`: update it when you add runnable samples or commands so humans can reproduce your changes.

Limitations
- Do not assume a particular language, framework, or CI configuration unless those files are present.

If you are unsure
- Ask the user before making large architectural changes. For small doc/code fixes follow the commit and citation rules above.

Feedback
- After making changes, ask the user: "Is this level of detail OK, or expand sections X/Y?"
