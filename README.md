# DSM 1121

## 📖 專案簡介
本專案主題為 **經典數據分析 - 鳶尾花 (Iris) 資料集**，涵蓋以下主題：
- 使用 K-鄰近分類演算法 (K-Nearest Neighbors, KNN)
- 鳶尾花資料集的視覺化
- 主成分分析 (PCA) 降維應用

專案步驟完整展示了數據分析流程，包括數據蒐集、預處理、建模與評估。

---

## 🗂️ 專案內容
### 1. 資料蒐集
- 透過 Kaggle API 下載數據，或直接讀取本地端 `iris.csv` 檔案。
- 簡介 Kaggle 平台功能及其使用方式。

### 2. 資料預處理
- 使用 Python 工具（`pandas`, `numpy`）檢視資料摘要。
- 缺失值處理方法：
  - 刪除缺失值
  - 補齊缺失值

### 3. 模型訓練與測試
- 實現 KNN 演算法並探討超參數（如 K 值）的影響。
- 使用 Scikit-learn 進行模型訓練與性能評估。

### 4. 資料視覺化
- 利用 Matplotlib 與 Seaborn 可視化數據分佈與分類結果。
- 實作 PCA (主成分分析) 以降維並輔助視覺化。

---

## 📋 安裝需求
- Python 版本：`3.7` 或以上
- 套件：
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `kagglehub`

### 安裝套件
請使用以下指令安裝所有依賴：
```bash
pip install -r requirements.txt

