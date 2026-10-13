🔗 前端專案 Repository：[<前端repo名稱>](https://github.com/a0938620803-sketch/<前端repo名稱>)

# AI 智慧商品選品系統後端

（一兩句話說明專案：這個系統解決什麼問題、給誰用）

## 技術棧
- Java、Spring Boot、Gradle 多模組
- PostgreSQL（PL/pgSQL）

## 模組結構
- `ssds-api`：對外 API
- `ssds-core`：核心領域邏輯
- `ssds-infra`：基礎設施
- `ssds-ingest`：資料擷取
- `ssds-ai`：AI 相關功能
- `ssds-calibration`：校準

## 我負責的部分
- 熱度資料層（Threads／Google Trends／Instagram 擷取）
- 趨勢分析
- 風險示警中心

## 如何啟動
（複製 `.env.example` 為 `.env`、填入設定，然後執行 `./gradlew bootRun`）
