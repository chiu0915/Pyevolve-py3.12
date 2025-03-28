# Pyevolve (Python 3.12 Compatible Fork)

> 🇬🇧 English | 🇹🇼 [繁體中文在下方](#pyevolve-相容-python-312-的分支說明)

This is the new official Pyevolve repository.  
The documentation (HTML rendered) is still hosted at SourceForge:  
👉 http://pyevolve.sourceforge.net/0_6rc1/

[![Build Status](https://travis-ci.org/BubaVV/Pyevolve.svg?branch=master)](https://travis-ci.org/BubaVV/Pyevolve)

---

## 🔧 About This Fork

This is a **forked version** of Pyevolve with a patch for compatibility with **Python 3.10+**, especially Python 3.12.

### ✅ Fixes:
- Replaced deprecated `collections.Callable` with `collections.abc.Callable` in `FunctionSlot.py`
- Verified compatibility with Python 3.12 and Anaconda

The original repository has Issues disabled and hasn't been updated for years. This fork keeps it usable on modern environments.

---

## 📦 Installation

```bash
git clone https://github.com/chiu0915/Pyevolve.git
cd Pyevolve
pip install -e .
```

> Use the `-e` flag for editable/development mode installation.

---

## 🧪 Minimal Working Example

```python
from pyevolve import G1DBinaryString

genome = G1DBinaryString.G1DBinaryString(10)
print("Genome:", genome)
```

---

## 📜 Original Project Info

- Author: Christian S. Perone  
- Website: http://pyevolve.sourceforge.net  
- License: PSF License  
- Original GitHub: [BubaVV/Pyevolve](https://github.com/BubaVV/Pyevolve)

---

## 🙋 Feedback

Feel free to open issues on this fork if you encounter further compatibility issues.

---

# Pyevolve 相容 Python 3.12 的分支說明

這是原始 [Pyevolve](https://github.com/BubaVV/Pyevolve) 專案的 fork，用來修正 Python 3.12 不相容的問題。

> 原始專案不再維護，且 Issues 功能已關閉，因此本分支作為修正版保存與使用。

---

## 🛠️ 修改內容

- 原始碼中使用 `collections.Callable` 的地方已修改為 `collections.abc.Callable`，避免在 Python 3.10 以上版本出現 `AttributeError`
- 已確認在 Python 3.12 + Anaconda 環境中可正常執行

---

## 📥 安裝方式

```bash
git clone https://github.com/chiu0915/Pyevolve.git
cd Pyevolve
pip install -e .
```

> `-e` 是「開發模式」，可以即時反映程式碼修改。

---

## 🚀 測試範例

```python
from pyevolve import G1DBinaryString

genome = G1DBinaryString.G1DBinaryString(10)
print("Genome:", genome)
```

---

## 🧾 原專案資訊

- 作者：Christian S. Perone  
- 網站：http://pyevolve.sourceforge.net  
- 授權條款：PSF License  
- 原始 GitHub： [BubaVV/Pyevolve](https://github.com/BubaVV/Pyevolve)

---

## 📬 回報問題

若你在使用此 fork 時遇到其他相容性問題，歡迎在此 repo 開啟 issue，我會盡量回覆與更新修正。

---
