# PC-8001 Semi-Graphic Editor

**Browser-based semi-graphic editor for the NEC PC-8001 home computer.**  
No install, no dependencies — open the HTML file and start drawing.

**[Open Editor](https://gikonekos.github.io/pc8001-semigfx-editor/pc8001-semigfx-editor.html)**  |  **[Manual](https://gikonekos.github.io/pc8001-semigfx-editor/pc8001-semigfx-editor-manual.html)**

---

## Screenshot

![PC-8001 Semi-Graphic Editor screenshot](img/screenshot.png)

---

## Features

- **PC-8001 semi-graphic editing** — character range `0xA0`–`0xBF`, 2×3 sub-pixels per cell
- **8-color support** — includes color attribute data
- **Browser-based editor** — works entirely in a single HTML file
- **Z80 ASM export** — `DB` format output
- **PNG export** — native sub-pixel resolution output
- **Selection export** — export only the selected region
- **Live ASM preview** — follows the cursor in real time
- **Image import** — converts PNG, JPEG, and other browser-supported images
- **Undo / Redo**
- **Zoom**
- **Keyboard shortcuts**
- **Real hardware aware** — warns when color attribute changes exceed the PC-8001 per-row limit

> **Note:** This is an authoring tool, not a strict hardware emulator.  
> It warns about color attribute limits, but does not forcibly restrict editing.

> **Note:** Exported files are saved to your browser's default download folder.  
> The save destination cannot be selected due to browser security restrictions.

---

## Usage

Clone the repository:

    git clone https://github.com/gikonekos/pc8001-semigfx-editor.git

Open `pc8001-semigfx-editor.html` in any modern browser. No server required.

Or use the hosted version directly:

`https://gikonekos.github.io/pc8001-semigfx-editor/pc8001-semigfx-editor.html`

---

## Files

| File | Description |
|------|-------------|
| `pc8001-semigfx-editor.html` | Editor application |
| `pc8001-semigfx-editor-manual.html` | Specification & user manual (EN/JP) |
| `README.md` | This file |
| `LICENSE` | MIT license |

---

## Changelog

| Version | Date | Changes |
|---------|------|---------|
| v1.3 | 2026-04-02 | Manual presentation refined; no major functional changes |
| v1.0 | 2026-04-02 | Initial release |

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

---

# PC-8001 セミグラフィックエディタ

**NEC PC-8001 用ブラウザベースのセミグラフィックエディタ。**  
インストール不要・外部依存なし。HTML ファイルを開くだけで動作します。

**[エディタを開く](https://gikonekos.github.io/pc8001-semigfx-editor/pc8001-semigfx-editor.html)**  |  **[マニュアル](https://gikonekos.github.io/pc8001-semigfx-editor/pc8001-semigfx-editor-manual.html)**

---

## スクリーンショット

![PC-8001 Semi-Graphic Editor screenshot](img/screenshot.png)

---

## 機能一覧

- **PC-8001 セミグラ編集対応** — 文字コード `0xA0`–`0xBF`、1セル 2×3 サブピクセル
- **8色対応** — カラーアトリビュートを含む
- **ブラウザベース** — 単一 HTML ファイルで動作
- **Z80 ASM 出力** — `DB` 形式で出力
- **PNG 出力** — サブピクセル等倍で出力
- **選択範囲出力** — 選択領域のみ出力可能
- **リアルタイム ASM プレビュー** — カーソル追従
- **画像読み込み** — PNG / JPEG などを変換
- **Undo / Redo**
- **ズーム**
- **キーボードショートカット**
- **実機制約を考慮** — 1行あたりの色変更回数制限超過を警告表示

> **注:** このツールは制作支援用であり、厳密なハードウェアエミュレータではありません。  
> 色変更回数制限は警告表示のみで、編集自体は制限しません。

> **注:** 出力ファイルはブラウザの既定ダウンロードフォルダへ保存されます。  
> ブラウザのセキュリティ制約により保存先は選択できません。

---

## 使い方

レポジトリを取得：

    git clone https://github.com/gikonekos/pc8001-semigfx-editor.git

`pc8001-semigfx-editor.html` をモダンブラウザで開いてください。サーバー不要です。

または GitHub Pages を直接使用できます：

`https://gikonekos.github.io/pc8001-semigfx-editor/pc8001-semigfx-editor.html`

---

## ファイル構成

| ファイル | 内容 |
|----------|------|
| `pc8001-semigfx-editor.html` | エディタ本体 |
| `pc8001-semigfx-editor-manual.html` | 仕様書・利用マニュアル（日英） |
| `README.md` | このファイル |
| `LICENSE` | MITライセンス |

---

## 更新履歴

| バージョン | 日付 | 変更内容 |
|------------|------|----------|
| v1.3 | 2026-04-02 | マニュアルの見せ方を調整、機能面の大きな変更なし |
| v1.0 | 2026-04-02 | 初期リリース |

---

## ライセンス

MIT License — 詳細は [LICENSE](LICENSE) をご覧ください。
