# 馬祖徒步步道 10 條秘境步道離線地圖

馬祖南竿、北竿、東引、東莒、西莒共 10 條徒步路線，提供 GPX 與 KMZ 兩種格式。

## 路線

| 島嶼 | 路線 | 里程 | GPX | KMZ |
|---|---|---:|---|---|
| 南竿 | 媽祖朝聖之旅 | 6.9 km | [GPX](public/gpx/nangan-mazu.gpx) | [KMZ](public/kmz/nangan-mazu.kmz) |
| 南竿 | 戰地景觀之旅・路線 1 | 5.3 km | [GPX](public/gpx/nangan-battlefield-1.gpx) | [KMZ](public/kmz/nangan-battlefield-1.kmz) |
| 南竿 | 戰地景觀之旅・路線 2 | 13.2 km | [GPX](public/gpx/nangan-battlefield-2.gpx) | [KMZ](public/kmz/nangan-battlefield-2.kmz) |
| 北竿 | 祈福漫步之旅 | 6.3 km | [GPX](public/gpx/beigan-blessing.gpx) | [KMZ](public/kmz/beigan-blessing.kmz) |
| 北竿 | 漁業及生態之旅・路線 1 | 4.8 km | [GPX](public/gpx/beigan-fishery-1.gpx) | [KMZ](public/kmz/beigan-fishery-1.kmz) |
| 北竿 | 漁業及生態之旅・路線 2 | 2.3 km | [GPX](public/gpx/beigan-fishery-2.gpx) | [KMZ](public/kmz/beigan-fishery-2.kmz) |
| 東引 | 地質景觀之旅・路線 1 | 6.8 km | [GPX](public/gpx/dongyin-geology-1.gpx) | [KMZ](public/kmz/dongyin-geology-1.kmz) |
| 東引 | 地質景觀之旅・路線 2 | 2.9 km | [GPX](public/gpx/dongyin-geology-2.gpx) | [KMZ](public/kmz/dongyin-geology-2.kmz) |
| 莒光 | 東莒戰地文化之旅 | 4.9 km | [GPX](public/gpx/dongju-battlefield.gpx) | [KMZ](public/kmz/dongju-battlefield.kmz) |
| 莒光 | 西莒戰地文化之旅 | 3.6 km | [GPX](public/gpx/xiju-battlefield.gpx) | [KMZ](public/kmz/xiju-battlefield.kmz) |

漁業及生態之旅・路線 1 的里程含橋仔往返大坵的海上段約 2 km。

一次下載：[全部 GPX](public/downloads/matsu-trails-gpx.zip)、[全部 KMZ](public/downloads/matsu-trails-kmz.zip)

## 手機 App

- Organic Maps（GPX、KMZ）：[iPhone](https://apps.apple.com/app/id1567437057)、[Android](https://play.google.com/store/apps/details?id=app.organicmaps)
- Hikingbook（GPX）：[iPhone](https://apps.apple.com/tw/app/id1067838748)、[Android](https://play.google.com/store/apps/details?id=net.hikingbook.hikingbook)
- OsmAnd（GPX、KMZ）：[iPhone](https://apps.apple.com/app/osmand-maps-travel-navigate/id934850257)、[Android](https://play.google.com/store/apps/details?id=net.osmand)
- Gaia GPS（GPX）：[iPhone](https://apps.apple.com/app/gaia-gps-offroad-hiking-maps/id1201979492)、[Android](https://play.google.com/store/apps/details?id=com.trailbehind.android.gaiagps.pro)
- Google 地球（KMZ）：[iPhone](https://apps.apple.com/app/google-earth/id293622097)、[Android](https://play.google.com/store/apps/details?id=com.google.earth)

路線檔只有軌跡和航點，不含底圖，請先在 App 內下載馬祖地區的離線地圖。

## 網站

`public/` 是靜態網站，沒有建置步驟，可直接部署到 Cloudflare Pages：

```bash
npx wrangler pages deploy public --project-name matsu-trails-offline-maps
```
