# Physician-CDSSU
這是一套基於 SMART on FHIR 標準的醫師端臨床決策儀表板系統。它包含 launch.html 負責處理 OAuth2 安全授權流程，以及核心介面 dashboard.html，利用 fhir-client.js 串接 FHIR 伺服器（如衛福部測試端點）以讀取病患個資與生理數據（血壓、血糖）。系統整合了 Chart.js 繪製健康趨勢圖，並內建簡易的 CDSS 決策輔助邏輯，能自動依據數據判讀風險（如收縮壓 > 140 跳出高血壓警示）並提供相應的醫療處置與藥物調整介面。
