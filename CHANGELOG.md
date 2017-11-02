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


### v2.1.0
---
##### Server
- `Fix` [Bug 108101] some v1's songbooks cannot migration to v2's playlist.
##### Web
- `Fix` Import: Cannot click "next" when user select the 'default' value in metadata config.
##### TV
- `Fix` cannot navigate song list when in specific "artist type".



### v2.0.11
---
##### Server
- `Fix` Some of the mpg videos that can not be played.
- `Enhancement` Support for external graphics cards.
- `Feature` Support HD Station version 3.2.0.
- `Feature` Can select the data volumn to migration the OceanKTV app.



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
