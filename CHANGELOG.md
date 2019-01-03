### 1. Requirements
---
OceanKTV v2 requires:
- INTEL or AMD based NAS
- QTS 4.2.x/4.3.x
- HD Station 3.0.0 or higher.

### 2. Installation
---
###### Location
//172.17.25.252/daily_build/Solution_Team/OceanKTV/v2/


### 3. Known issues
---

- [#102696, #102713, #102722](http://172.17.25.222/bugzilla/show_bug.cgi?id=102696) Limited mouse support in TV app because TV app was optimized for QNAP remote controller.
- [#104495](http://172.17.25.222/bugzilla/show_bug.cgi?id=104495) No app description in HD Station app list.
- [#103060](http://172.17.25.222/bugzilla/show_bug.cgi?id=103060) The i18n need to be improved in some countries.
- [#94041](http://172.17.25.222/bugzilla/show_bug.cgi?id=94041) An alert "cannot connect to remote server" may appear sometimes when launching TV app.
- Mic interface in some USB sound devices cannot be detected due to current kernel's limitation.
- Web app only supports IE 11, Chrome/Firefox/Safari is no problem.
- The transcode function does not support files with Dolby/DTS audio encoding (including AC3).
- **Request songs by folder is not supported.**
- **Not compatiable with current OceanV1 mobile apps, OceanV2 mobile app is coming soon.**


### v2.1.4
---
##### Server
- `Fix` [Bug [136511](http://172.17.25.222/bugzilla/show_bug.cgi?id=136511)][Bug [136570](http://172.17.25.222/bugzilla/show_bug.cgi?id=136570)] 針對新版 QTS 版本調整 OceanKTV 啟動/關閉 流程


### v2.1.3
---
##### Server
- `Feature` [Spec [17920](http://spec.qnap.com.tw/issues/17920)] 移除 Google Analytics 資料蒐集
- `Fix` [Bug [133993](http://172.17.25.222/bugzilla/show_bug.cgi?id=133993)] 匯入歌曲的視窗一片空白，無法選取來源資料夾
- `Fix` [Bug [134014](http://172.17.25.222/bugzilla/show_bug.cgi?id=134014)] 資料夾點歌的選擇資料夾，視窗裡空白無法選擇資料夾

##### TV
- `Feature` [Spec [17530](http://spec.qnap.com.tw/issues/17530)] 針對 HD Station 版本4.0.0 重新 Porting
- `Fix` [Bug [134618](http://172.17.25.222/bugzilla/show_bug.cgi?id=134618)] 修正 KTV TVPlayer 啟動流程錯誤問題
- `FIX` [BUG [135516](http://172.17.25.222/bugzilla/show_bug.cgi?id=135516)] 修正無法播放部分 YouTube 歌曲問題


### v2.1.2
---
##### Server
- `Fix` [Bug [131385](http://172.17.25.222/bugzilla/show_bug.cgi?id=131385)] 修正 OceanKTV 安裝程序無法停止問題


### v2.1.1
---
##### Server
- `Feature` [Spec [15722](http://spec.qnap.com.tw/issues/15722)] OceanKTV system log 導入至 Notification Center
- `Fix` [Bug [131711](http://172.17.25.222/bugzilla/show_bug.cgi?id=131711)] Console 大量匯入歌曲後，KTV moible fetch photo 會 crush

##### Web
- `Fix` [Bug [129696](http://172.17.25.222/bugzilla/show_bug.cgi?id=129696)] 透過分享連結新增Youtube播放清單的功能失效


### v2.1.0
---
##### Server
- `Fix` [Bug [117231](http://172.17.25.222/bugzilla/show_bug.cgi?id=117231)] 修正移除 HD Station 後會有 KTVstation 的 APP 殘留在 APPcenter
- `Fix` [Bug [118715](http://172.17.25.222/bugzilla/show_bug.cgi?id=118715)] Search showing expect result
- `Fix` [Bug [123340](http://172.17.25.222/bugzilla/show_bug.cgi?id=123340)] 插拔 USB 音效卡設定行為異常

##### Web
- `Fix` [Bug [126254](http://172.17.25.222/bugzilla/show_bug.cgi?id=126254)] KTV 2.1.0 沒辦法進入console 管理介面
- `Fix` [Bug [126402](http://172.17.25.222/bugzilla/show_bug.cgi?id=126402)] 多人團體的歌手圖片，常常人臉太小無法辨認
- `Fix` [Bug [126396](http://172.17.25.222/bugzilla/show_bug.cgi?id=126396)] 少部分歌手不會有歌手圖片
- `Feature` [Spec [13991](http://spec.qnap.com.tw/issues/13991)] 新增收尋歌曲與依資料夾點歌功能
- `Feature` [Spec [14812](http://spec.qnap.com.tw/issues/14812)] 歌手頁面顯示歌手照片
- `Enhancement` [Spec [16875](http://spec.qnap.com.tw/issues/16875)] 支援編輯歌手照片

##### TV
- `Fix` [Bug [126819](http://172.17.25.222/bugzilla/show_bug.cgi?id=126819)] player filter 進入搜尋或是設定，從 filter 結果的資料夾內回到上一層後 filter 會失效
- `Feature` [Spec [13991](http://spec.qnap.com.tw/issues/13991)] 新增依資料夾點歌與收尋功能
- `Enhancement` [Bug [126805](http://172.17.25.222/bugzilla/show_bug.cgi?id=126805)] player 首頁翻頁提示不明顯

### v2.0.14
---
##### Server
- `Feature` [Spec [16119](http://spec.qnap.com.tw/issues/16119)] revision google analytics


### v2.0.13
---
##### TV
- `Fix` [Bug [120309](http://172.17.25.222/bugzilla/show_bug.cgi?id=120309)] QTS 4.3.4 KTV player 使用中 disable KTV console，會造成 KTV player 無法正常關閉
- `Fix` [Bug [120988](http://172.17.25.222/bugzilla/show_bug.cgi?id=120988)] 修正 KTV player 關閉後產生的錯誤
- `Feature` [spec [15625](http://spec.qnap.com.tw/issues/15625)] 過場時間優化
- `Feature` [spec [15627](http://spec.qnap.com.tw/issues/15627)] 新增可啟動全螢幕延展模式播放影片的功能
##### Server
- `Fix` [Bug [120362](http://172.17.25.222/bugzilla/show_bug.cgi?id=120362)] 當 share folder 用中文命名時，底下的歌曲會無法正常撥放
- `Fix` [Bug [120986](http://172.17.25.222/bugzilla/show_bug.cgi?id=120986)] 修正 OceanKTV 權限問題
- `Fix` [Bug [122144](http://172.17.25.222/bugzilla/show_bug.cgi?id=122144)] 修正導唱切換問題


### v2.0.12
---
##### Server
- `Fix` [Bug [118800](http://172.17.25.222/bugzilla/show_bug.cgi?id=118800)] 雲端服務無法存取導致KTV無法啟動
- `Fix` [Bug [114366](http://172.17.25.222/bugzilla/show_bug.cgi?id=114366)] 早期轉檔軟體產出的部分檔案無法撥放
- `Fix` [Bug [114157](http://172.17.25.222/bugzilla/show_bug.cgi?id=114157)] 錯誤的 conf 導致 ktv 無法啟動


### v2.0.11
---
##### Server
- `Fix` [Bug [114081](http://172.17.25.222/bugzilla/show_bug.cgi?id=114081)] OceanKTV 在升上HD Station 3.2.0後無法正常使用
- `Fix` [Bug [114366](http://172.17.25.222/bugzilla/show_bug.cgi?id=114366)] 早期轉檔軟體產出的部分檔案無法撥放
- `Feature` [Spec [13795](http://spec.qnap.com.tw/issues/13795)] 支援外接顯卡
- `Feature` [Spec [14042](http://spec.qnap.com.tw/issues/14042)] 於 App Center 安裝 OceanKTV 時，能選擇安裝到哪個磁碟區(Volume)



### v2.0.10
---
##### Server
- `Fix` [Bug 108101] some v1's songbooks cannot migration to v2's playlist.
- `Fix` some songs in v1's songbook cannot migrate to v2's playlist, if that songs did not have singer info.
- `Fix` [Bug 108379] cannot store KTV database when meet special volume spec.
- `Enhancement` make song sorting more friendly.
- `Enhancement` restore user setting after reinstalling QPKG.
##### Web
- `Fix` Import: Cannot click "next" when user select the 'default' value in metadata config.
- `Fix` Import: Cannot select sub folders when folder name contains special chars.
- `Enhancement` [Bug 108103] add hover highlight on the submenu in the icon-based list pages.
- `Enhancement` reload list when click menu item (playlist & cloud playlist).
- `Enhancement` add "Delete" feature in every song-list page.
- `Enhancement` ocean search in singing mode.
- `Feature` add "manual migration" if user need to re-migrate.
##### TV
- `Enhancement` autoplay on/off as an option.
- `Enhancement` [Mantis#23300] Add video calibration in setting.


### v2.0.9
---
##### Server
- `Fix` Get song stream fail when the path contains special characters.
- `Enhancement` search api now give full song object and supports pinyin & zhuyin.
- `Enhancement` #107503, support .mov/.m4v videos.
- `Enhancement` make version number pattern consistency, will not contains ".42" or ".43" anymore.
##### TV
- `Enhancement` prompt user an readable message when cannot preview/play videos.
- `Enhancement` prompt user when mobile app is not ready.
- `Enhancement` optimize the interaction when using remote controller during song-play stage.
  - (ok) -> Menu
  - (up/down/right/left) -> Control bar


### v2.0.8 (Current Version in App Center)
---

#### Fixes

##### Web
- [#106047](http://172.17.25.222/bugzilla/show_bug.cgi?id=106047) UI crash in setting menu.
- 1st&2nd column freeze in import preview table.

##### TV
- [#106104](http://172.17.25.222/bugzilla/show_bug.cgi?id=106104) Invalid flow in screen calibration.

### v2.0.7
---

#### Fixes

##### Web
- remind user when TV app being disabled.
- improve the QTS login checking.

##### TV
- add debug tool.
- [#105945, #105946] fix paging in singertypes and langs
- will hide singertypes if no songs inside its singers

### v2.0.6
---

#### Features

- User can import songs from any folder (USB disk included), no need to rename lots of files from now on.
- User can maintain Karaoke songs' Metabase in a straightforward process.
- Search local or cloud songs getting more easily.
- Support transparent Metabase migration, migration may need several minutes according to the song count.

#### Enhancements

###### Server
- Enhance the stability.
- Performance tuning.


###### Web
- UI redesign that user can finish tasks more quickly in the current scenario (singing or management).


###### TV
- Redesign home screen, also make screen flow more logical and friendly.
- Enhance the stability.
- Performance tuning.

#### Fixes

###### Server
- [#102436](http://172.17.25.222/bugzilla/show_bug.cgi?id=102436) disable OceanKTV app in App Center shall also disable TV app.
- [#102476](http://172.17.25.222/bugzilla/show_bug.cgi?id=102476) wrong detection of "audio out" and "mic in" port map in some model.
- [#73084](http://172.17.25.222/bugzilla/show_bug.cgi?id=73084) invalid search reuslt when keyword contains special characters.


###### Web
- [#102343](http://172.17.25.222/bugzilla/show_bug.cgi?id=102343) metadata edit not work as expected.
- [#102488, #102532, #102550, #102568, #102574, #102604, #102600, #102610, #102895, #102897, #102899, #104571] UI issues.


###### TV
- [#102493](http://172.17.25.222/bugzilla/show_bug.cgi?id=102493) playing hangs when song file moved or deleted.
- [#103146](http://172.17.25.222/bugzilla/show_bug.cgi?id=103146) app hangs when press power key on remote controller.
- [#93555, #93560, #94065, #94905, #94908, #94958, #95131, #95221, #103127, #103140] unstable screen navigation and many unexpected behavior.
- [#101047](http://172.17.25.222/bugzilla/show_bug.cgi?id=101047) Audio channel will not come back to stereo.
