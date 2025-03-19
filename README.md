# Stock_tool
# 專案說明

## myStrategy.py

回傳交易動作：`buy` 或 `sell`。  
其中的參數會透過 `bestParamByExhaustiveSearch.py` 進行最佳化。

---

## bestParamByExhaustiveSearch.py

此腳本透過窮舉搜尋（Exhaustive Search）來取得最佳參數。  
取得最佳參數後，你可以將它們套用到 `myStrategy.py` 進行評估。

**使用方式：**
```bash
python bestParamByExhaustiveSearch.py 0050.csv
python rrEstimate.py 0050.csv

### 如何使用
1. **安裝/下載專案**：將此儲存庫 `git clone` 或下載到本地。
2. **準備資料**：確保你的 CSV 檔案（如 `0050.csv`）已經放在專案目錄中。
3. **執行腳本**：依照上方說明，先用 `bestParamByExhaustiveSearch.py` 找到最佳參數，再執行 `rrEstimate.py` 或 `myStrategy.py` 進行模擬交易。
