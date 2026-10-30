フロントエンド・バックエンド・インフラまで、広く浅くやっています。
最近はサイネージのような「置きっぱなしで表示しておく画面」づくりにハマっていて、なくても困らないものを量産中です 💦

## 今つくっているもの

### 🖥️ [home-display](https://github.com/ynug/home-display)

Raspberry Pi とモバイルディスプレイで、カレンダー・天気・雨雲レーダー・室内の CO2 などを常時表示する情報ディスプレイ。Rust + Slint のネイティブアプリです。

| 雨雲レーダー（気象庁の実データ） | Overview（サンプルデータ） |
|---|---|
| ![雨雲レーダー](https://github.com/ynug/home-display/raw/main/docs/screenshots/radar.png) | ![Overview](https://github.com/ynug/home-display/raw/main/docs/screenshots/overview.png) |

### 🌡️ [tab5-env-monitor](https://github.com/ynug/tab5-env-monitor)

M5Stack Tab5 に自作のセンサー基板をつないで、部屋の CO2・温度・湿度・気圧を大きく表示するモニター。換気が必要なときや熱中症の危険があるときは、ずんだもんが声で知らせます。ESP-IDF + LVGL（C）。

| センサー画面 | グラフ（直近 12 時間） |
|---|---|
| ![センサー画面](https://github.com/ynug/tab5-env-monitor/raw/main/docs/images/sensor.png) | ![グラフ画面](https://github.com/ynug/tab5-env-monitor/raw/main/docs/images/graph.png) |

### 🔌 [env-sensor-board](https://github.com/ynug/env-sensor-board)

上の 2 つで使っている、CO2・温度・湿度・気圧のセンサー基板（SCD41 / SHT35 / BMP581）。EasyEDA Pro で設計して、JLCPCB で部品実装まで注文できる製造データを公開しています。
