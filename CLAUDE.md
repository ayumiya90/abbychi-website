# CLAUDE.md — abbychi.com 個人品牌官網

## 專案概述
這是紀澄 Abby Chi 的個人品牌官網（abbychi.com），定位為「AI 社群經營 × 商業影片」領域的專業顧問品牌。網站使用 LOBO CMS，文章 HTML 採用 inline styles（CMS 相容），不使用 `<style>` 或 `<script>` 區塊。Schema JSON-LD 獨立輸出至追蹤碼欄位。

## 品牌資訊
- **品牌名稱**：Abby Chi 紀澄
- **公司名稱**：雲時代數位有限公司（Cloud Era Digital）
- **專業定位**：社群營運顧問 ｜ AI 商用影片講師
- **網站**：https://abbychi.com
- **公司網站**：https://www.uninn.com.tw

## 品牌色彩系統
| 用途 | 色碼 | 說明 |
|------|------|------|
| 主色 | `#FFB66E` | 品牌橘，用於 CTA、標題強調 |
| 輔助色 | `#FADE9E` | 淺黃，用於背景區塊 |
| 強調色 | `#EB8F80` | 珊瑚粉，用於重點標記 |
| 正文 | `#606060` | 深灰，用於內文 |
| 薄荷綠 | `#9CE1CF` | 情境用色 |
| 草地黃綠 | `#D4E5AC` | 情境用色 |
| 薰衣草紫 | `#C7ADD5` | 情境用色 |

## 文章 HTML 規範
- **必須使用 inline styles**，不可使用 `<style>` 或 `<script>` 區塊
- Schema JSON-LD 獨立輸出（放追蹤碼欄位，不放文章 HTML 裡）
- 文章色彩規範與頁尾介紹詳見品牌定位文件
- 所有文章需符合 SEO + AEO 架構

## 技術棧
- **CMS**：LOBO CMS
- **部署**：LOBO 自有主機
- **文章格式**：HTML（inline styles）
- **追蹤碼**：Google Analytics、Meta Pixel

## 常用指令
```bash
# 此 repo 主要存放靜態 HTML 文章與相關資源
# 無需 build 指令
```

## 注意事項
- 不要在客戶facing文件上使用 abbychi.com 網址
- 外部文件上公司名稱寫「雲時代數位有限公司」，不加 Uninn 前綴
- Abby 的正式署名：「紀澄 Abby Chi」
- 對外職稱：「社群營運顧問」
- 文章禁用詞：禁止使用「長出」二字
- Threads 貼文開頭禁止用假問句（如「你有沒有過這種經驗？」）

## 檔案結構說明
```
/
├── CLAUDE.md          ← 你正在看的這份文件
├── README.md          ← Repo 說明
├── articles/          ← 官網文章 HTML 檔
├── assets/            ← 圖片、CSS 等靜態資源
└── schema/            ← JSON-LD Schema 標記
```
