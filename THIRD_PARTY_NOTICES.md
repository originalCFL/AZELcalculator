# 第三方服務與授權聲明

本專案的原始碼以 [MIT License](LICENSE) 授權。本檔案列出本 PWA 實際載入、快取或取用的第三方資源、來源與應保留的授權資訊。

## Open-Meteo Elevation API

- 用途：在使用者輸入座標後查詢海拔高度；Service Worker 會快取成功的 API 回應，供網路暫時不可用時使用。
- 來源：<https://api.open-meteo.com/v1/elevation>
- 來源標示：Open-Meteo（<https://open-meteo.com/>）
- 授權：Creative Commons Attribution 4.0 International（[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)）。
- 本工具的處理：將 API 回傳的高度數值四捨五入為整數公尺後顯示；未主張 Open-Meteo 或資料提供者對本工具的背書。

使用或再散布本工具所呈現或快取的 Open-Meteo 資料時，應以合理方式保留上述來源標示、CC BY 4.0 連結與處理說明。

## Google Fonts：Orbitron

- 用途：介面字型；由 Google Fonts CSS API 載入，並可能由 Service Worker 快取。
- 原始專案：<https://github.com/theleagueof/orbitron>
- 授權：SIL Open Font License 1.1（OFL-1.1）。
- Copyright 2018 The Orbitron Project Authors, with Reserved Font Name: "Orbitron".
- 授權全文：<https://github.com/google/fonts/blob/main/ofl/orbitron/OFL.txt>

## Google Fonts：Share Tech Mono

- 用途：介面字型；由 Google Fonts CSS API 載入，並可能由 Service Worker 快取。
- 授權：SIL Open Font License 1.1（OFL-1.1）。
- Copyright (c) 2012, Carrois Type Design, Ralph du Carrois (post@carrois.com, www.carrois.com), with Reserved Font Name "Share".
- 授權全文：<https://github.com/google/fonts/blob/main/ofl/sharetechmono/OFL.txt>

字型由 Google Fonts 外部服務提供，並未以字型檔形式納入本儲存庫。若日後下載、內嵌或隨本 PWA 散布字型檔，必須隨字型副本保留相應的著作權聲明與完整 SIL Open Font License 1.1；修改字型時亦須遵守其 Reserved Font Name 條款。

## 不列入第三方授權的檔案

`icon-192.png` 與 `icon-512.png` 為本專案內的本機 PWA 圖示。檔案未含可辨識的第三方著作權或來源中繼資料；若它們並非專案作者原創或已取得授權的素材，發行前仍應補上實際來源與授權資訊。

Google Maps、iOS 指北針、GitHub Pages 與 Google Forms 僅出現在介面文字、說明或外部連結中；程式並未載入其 SDK、資料或素材，因此不構成本專案散布的第三方資源。
