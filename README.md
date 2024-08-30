### GTA4完整版漢化 繁體中文Addon

#### 說明
2022年6月公開的GTA4完整版漢化只有簡體中文。而內附的「自定义字库字体工具」亦未能讀取繁體字型，對欲使用繁體中文遊玩的玩家構成不便。因此決定將簡體中文漢化轉換為繁體中文。<br>

#### 效果圖
<img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/Showcase_1.jpg" width="50%"><img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/Showcase_2.jpg" width="50%">
<img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/Showcase_3.jpg" width="50%"><img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/Showcase_4.jpg" width="50%">

#### 採用的開源字體
- [jf open 粉圓](https://github.com/justfont/open-huninn-font)
- [源泉圓體](https://github.com/ButTaiwan/gensen-font)

#### 更新
20240830 - v2 重新製作 (使用230704版本)<br>
20220805 - v1.1 修改部份字眼<br>
20220804 - v1 首次發佈<br>

#### 注意
請先自行備份將被覆蓋的資料和檔案，有任何損失概不負責<br>
如對翻譯文本有任何疑問，請向相闗漢化組人員查詢及回報<br>
由於簡體中文有一字多用的習慣，所以未能百分百準確轉換至繁體中文，介意者勿用<br>

<details><summary>220618舊版本步驟</summary>

1. 先到天道汉化组的[GTA4汉化导航站](https://b9348.gitee.io/#1)下載「GTA4汉化补丁20220618」<br>
2. 跟隨網頁步驟安裝完成後，下載本repo中的「GTA4_FullTran_CHT_Addon」<br>
3. 解壓縮後拖至根目錄並取代原有檔案即可<br>

#### 欲更換字體
如欲更換本檔案採用的字體，可以下載`font_cht.psd`檔再作修改。<br>
匯出透明背景png時請先隱藏「参考网格」，然後利用SparkIV修改分別位於以下三個位置的`fonts.wtd`。<br>
- Niko本篇: `GTAIV\pc\textures\`
- The Lost and Damned: `GTAIV\TLAD\pc\textures\`
- The Ballad of Gay Tony: `GTAIV\TBoGT\pc\textures\`

將`font_chs.png`的圖片匯入至該個`.wtd`內即可。
<br>
</details>

#### 230704新版本步驟
1. 先到[GTA4汉化导航站](https://b9348.pages.dev/)下載「GTA4汉化补丁2023-07-04.zip」<br>
2. 跟隨網頁步驟安裝完成後，下載本repo中的「GTA4_FullTran_CHT_Addon」<br>
3. 解壓縮後拖至根目錄並取代原有檔案即可<br>

#### 欲更換字體
如欲更換本檔案採用的字體，可以下載`font_cht.psd`檔再作修改。<br>
匯出透明背景png前請先隱藏「参考網格」圖層，後再利用OpenIV或SparkIV修改分別位於以下三個位置的`fonts_chs.wtd`。<br>
- Niko本篇: `GTAIV\pc\textures\`
- The Lost and Damned: `GTAIV\TLAD\pc\textures\`
- The Ballad of Gay Tony: `GTAIV\TBoGT\pc\textures\`

將`font_chs.png`的圖片匯入至該個`.wtd`內即可。

#### Steam Deck額外步驟
正如漢化組網站提到，需要在Steam的「內容>一般>啟動選項」中填入`WINEDLLOVERRIDES="dinput8.dll=n,b" %command% `，漢化方能生效<br>
<img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/SteamDeck_LaunchOptions.jpg" width="50%"><br>

#### Steam Deck效果圖
<img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/Showcase_SD1.jpg" width="50%"><img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/Showcase_SD2.jpg" width="50%"><br>
<img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/Showcase_SD3.jpg" width="50%"><img src="https://github.com/Megumi-B/GTA4_FullTran_CHT/raw/main/Showcase_SD4.jpg" width="50%"><br>

#### 回報
如有任何疑問、修訂等，歡迎使用Issues回報

#### 相關工具連結
OpenIV: https://openiv.com/<br>
SparkIV: https://ahmed605.github.io/SparkIV/<br>
簡轉繁: https://www.ifreesite.com/gbk-big5-gb2312-utf8.htm<br>
