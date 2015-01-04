Mobile Export Script for Illustrator
===

將 illustrator 的檔案根據不同大小尺寸自動輸出到對應的資料夾

原始連結請參考  
https://github.com/austynmahoney/mobile-export-scripts-illustrator

我有做一些修改  
options.artBoardClipping = false;  
原本採用整個畫布，現在將會以游標選取範圍為主

## 安裝方式

將檔案置放到對應的位置  

* Windows  

```
C:\Program Files\Adobe\Adobe Illustrator\Presets\en_US\Scripts
```
	
* Mac  

```
/Applications/Adobe Illustrator/Presets.localized/en_US/Scripts
```
  
位置僅供參考，須根據版本不同而自行變化
  
## 使用方式

1. 使用 xhdpi 維度作圖 (標準的 mdpi 的 2 倍大)
2. 選取要輸出的範圍
3. 執行 Script，勾選欲輸出的尺寸
4. 將自動建立對應的 res 資料夾

dp <-> px 互轉可參考  

* http://developer.android.com/guide/practices/screens_support.html  
* http://developer.android.com/design/style/iconography.html  
* http://pixplicity.com/dp-px-converter/