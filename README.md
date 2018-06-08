# Development Log

## This is Chia Xin Lin's development log

[Unreleased]

## 2018-06-08

## MayaAPI101

新增了 Maya API with QT 的文件。  
如何用 QMake 去產生 Visual Studio 所需要的 vcxproj。  
如何在 Maya 裡使用 QML 格式。

## 2018-06-05

### Division

更新到了 1.5.0，這個版本加上了一個新功能 - convert dds texture。  
並且重構了一部份的 code。找時間 merge 回去。  
這個功能需要 [Microsoft/DirectXTex](https://github.com/Microsoft/DirectXTex)。  
但是我不希望他轉出來的副檔名是大寫 DDS，因此有修改後重新編譯過。  
目前 Division 還尚未修正成 MAC 可以 Run 的版本。

## 2018-04-01

### Division

很久沒更新了，新的 branch : ver13 添加了一個新功能 maketx。</br>
這功能可以幫我們在產生貼圖的同時產生 tx。</br>
再繼續測試一下，一切順利的話再合併回 master。</br>

## 2018-02-09

### MayaAPI101

更新 MayaAPI101 持續優化文件的格式, 並新增 snippet 存放一些有用的 code.

## 2018-02-02

### MayaAPI101

持續更新 MayaAPI101 的文件，</br>
目前會分為三個部份 C++, .NET, Python。</br>

## 2018-02-01

### MayaAPI101

部分文件修飾了一下，</br>
新增 Maya_API_naming_conventions.md 參考了 Maya Documents，</br>
並加上一些我自己習慣用的命名法。

## 2018-01-29

### MayaAPI101

修正了一些 dotnet 的設定文件</br>
好像很少人用 .NET 寫 Maya API，我覺得很有趣，所以有時間想研究一下。

### UMPLint

將 UMPLint 更名為 `umpire` 並且第一次 Push 上了 Github。

---

## 2018-01-28

重新整理自己的 Open Source 專案。</br>

### Division

近期更新了 Photoshop 的貼圖工具 Division 到了 v1.2.0。</br>

### shaderSpace

之後有時間再來 Refactor "shaderSpace" 這個 project。</br>

### UMPLint

建立了一個新的坑 "UMPLint"，專心寫關於 Maya Production QC Tool。</br>
UMPLint 是 "Universal Maya Production Lint" 的縮寫。</br>
目標是創造一個比較全面且彈性的 QC 介面(使用 JSON )。</br>

### MyUTL

這個小工具是用來 Create & Submit 自己的 Maya Utility。</br>