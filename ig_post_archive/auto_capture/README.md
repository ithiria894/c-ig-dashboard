# IG Post Auto Capture

用途：保存之後自動偵測到的新 IG post 原圖 fallback、Graph API caption、Apple Vision OCR raw text。

- `images/`：JPG 原圖 fallback。
- `posts/`：每張圖 / 每張 carousel slide 的 detail markdown。
- `index.md`：這批自動抓回來資料的總表。
- `api_media_with_captions.json`：自動抓取的 Graph API rich media payload。
- `api_metadata_snapshot.json`：這批自動抓取 post 的簡化 metadata。

OCR 來源：Apple Vision `VNRecognizeTextRequest`，語言設為 `zh-Hant`, `zh-Hans`, `ja-JP`, `en-US`。
