# subs-downloader
Subtitle Downloader v. 0.34.3 2013-01-27

Enigma2 plugin which downloads subtitle to Your movie written in Python.

Homepage:  http://code.google.com/p/subs-downloader/ - Due to Google Code services termination I have moved my project to github.
This repo contains last plugin version which is also source code.
At 25-05-2020 I have no plans for furure updates and maintain.

Developer: Dawid "SileliS" Bańkowski

ver 0.34.3:
- support for DMnapi v. 1.28.0,
- more languages supported,
- install unrar, libmediainfo, libzen for ONLY for mipsel.

ver 0.34.0:
- Napisy24pl works after changes on server,

ver 0.33.4:

- FileManager (delete, copy, move, rename files),
- support for UTF-16LE subtitle codepage,
- fix in saveSubtitleasSRT - don't make greenscreen if chardetOutputTranslation doesn't recognice subtitle codepage,
- fix in convert_subtitle_to_movie - don't make greenscreen if subtitle format isn't detected,
- fix for Portuguese(Brazil) language for OpenSubtile,
- fix in MusicExplorer class audioplayer should work again.

ver 0.31.0
- fixed threading - now plugin starts faster.

ver 0.30.8
- "0" key skin show/hide,
- movie resume time support (cuts file support),
- animated commertial banner.

ver 0.28.7 
- git repository corrections (Subtitulos bringed back to git IPK).

ver 0.28.6:
- Itasa subtitle server support,
- setServerAvailableSubtitles_for_Napisy24 optimization should work little faster,
- setServerAvailableSubtitles_for_PERISCOPE optimization should work little faster,
- setServerAvailableSubtitles_for_XBMC_SUBTITLES optimization should work little faster,
- correction in Napisy.Me class,
- localConvertionSublist optimization should work little faster,
- fixed greenscreen in NapiProject module when subtitles are not found.

ver 0.27.0:
- Napisy.me subtitle server support,
- required memory optimization,
- subtitle conversion function improved,
- subtitle and movie matching function added (experimental),
- changes in CONTROL file depends (python-html added).

ver 0.24.7:
- makefile.am correction.

ver 0.24.6:
- fixed SubtitleDatabase.py,
- fixed XBMC_search.py,
- function guessFileData implemented to Napisy24 search by movei name method.

ver 0.24.3:
- christmass banner removed.

ver 0.24.2:
- Subtitlous subtitle server support.

ver 0.23.2:
- some correction in IPK so it should work on OpenPLI and other CVS,
- gzip.py and zilezip.py deleted from plugin to Python libs.

ver 0.23.0:
- BierDopje subtitle server support,
- plugin skin generator more flexible,
- server logo display method more flexible,
- 3rd subtitle language added,
- fixes in module impoert so requires less memory,
- added support for XBMC Subtitles.

ver 0.21.5:
- improved OnlineContent installation (Screen.Ipkg library),
- restart GUI prompt after OnlineContent installation,
- changes in IPK file,
- christmass edition ;-).

ver 0.21.3:
- Napisy24.py subtitle server support,
- plugin autopudate,
- chardetOutputTranslation function outside of SubsDownloaderApplication class,
- some correction in IPK file.

ver 0.19.1:
- fixed bug in myFileList,
- fixes in localConvertionSublist works better,
- YELLOW button in ConfigurationMenu downloads and install libmediainfo.

ver 0.17.9:
- long TXT key makes local subtitle convertion,
- HELP key display plugin about,
- INFO key display file/dir info,
- mod and 3gp movie file support added,
- changed FileList widget class from FileList to DreamExploereII myFileList (long file names are displied correctly),
- fixed closing Subs Downloader during playing movie bug,
- fixed corrupted subtitle file chars reading,
- fixed error subtitle_codepage detection when server returns no subtitle.

ver 0.16.2:
- two different Subs Dowanloader avaliable:
    Subs Downloader (without libmediainfo) - support for RIFF and MKV videofiles)
    after upgrade (libmediainfo.so installation) Subs Downloader (with libmediainfo) (support for any movies),
- mov, mp4 and any other supported by Enigma2 movies Frame Per Second indicator detection avaliable,
- config menu display fix,

ver 0.13.3:
- corrected handling of media pattern filter = "no" error in return_media_kind function,
- implemented utf-8-sig file code page convertion (subtitle convertion is little faster),
- possibility to add/remove Subs Downloader execution from BlueButton menu,
- any2srt converion less sensitive on MLP2, TMP, MDVD, SUB2 subtilte errors.

ver 0.12.7:
- small fixes of errors detected in 0.12.6 version.

ver. 0.12.6:
- enable/disable media pastern filter,
- enable/disable last FileList path save,
- left/right key = page up/down both in FileList and SubsList,
- extended MMI (comunication errors and other are described as MessageBox 

ver. 0.12.1:
- Pythin-zlib library added to IPK depends,
- some correction of IPK's controll file,
- small code fixes.

ver. 0.12a:
- basic file mbrowser,
- handle OpenSubtile server,
- handle NapiProjekt server,
- play movie, picture, audio, some system files.
