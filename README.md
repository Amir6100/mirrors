# Features:

## From This Repo
- Fully non-credit repo (For protect repo from ban etc.)
- Some more trackers
- Supports all yandex links like yandex.com.tr, yandex.com.ru
- Better YTDL Playlist naming: `"%(playlist_title)s %(playlist_index)s.%(n_entries)s %(title)s.%(ext)s"`
- Update all python packages before start bot (optional)
- Custom finished & unfinished string. (You can get from [1](https://coolsymbol.com/) [2](https://changaco.oy.lc/unicode-progress-bars/) [3](https://text-symbols.com/) or leave empty for default)
- More respectful to user
- Show thumbnail
- Speedtest with picture
- Removed all username cc's. Never trust a username.
- WayBack Machine Archiver
- VirusTotal File / URL / Hash Scanner (api required)
- Delete file / folder from drive with replying message
- Better file captions. Now writing full path instead of only filename. Before: `Antalya.pdf` After: `Manisa/Antalya.pdf`
- File Hasher: `MD5`, `SHA1`, `SHA224`, `SHA256`, `SHA512`, `SHA384`
- URL Shortener
- MediaInfo (To use, add `RUN apt install mediainfo -y` into your deployer Dockerfile. Do not ask me.)
- Heroku Usage (To use fill `HEROKU_API_KEY` `HEROKU_APP_NAME`)
- Dyno Restarter / Killer (To use fill `HEROKU_API_KEY` `HEROKU_APP_NAME`)
  - Usage: `/restart dyno`. This will update your bot to latest version, re-set your configs with your new values.
  - Usage: `/restart kill`. This will kill your app for save dyno hours.
- AntiSpam Protections:
  - SpamWatch AntiSpam: Fill `SPAMWATCH_ANTISPAM_API` variable.
  - Combot AntiSpam (CAS): Set `COMBOT_CAS_ANTISPAM` to `True`
  - Userge AntiSpam: Fill `USERGE_ANTISPAM_API` variable.
  - IntelliVoid AntiSpam (AI): Set `INTELLIVOID_ANTISPAM` to `True`
- More Shorteners:
  - Not required signup: `v.gd`, `da.gd`, `is.gd`, `ttm.sh`, `clck.ru`, `chilp.it`, `osdb`, `owly`
  - Required signup: `shorte.st`, `bc.vc`, `pubiza`, `linkvertise`, `bit.ly`, `post`, `cutt.ly`, `adf.ly`, `shortcm`, `tinycc`, `tinyurl`, `ouo.io`
  - bc.vc sample api: `"2dgdg5f1fgag7cg6f0622&uid=45634"`
  - pubiza sample api: `"hsdfgCgdgrsdfgsfgfgsdgLsfgXef mainstream"`. Split api key and ad type with a space. Genel içerik için: `mainstream` Yetişkin içerik için: `adult` İçerik Kilidi için: `content_locker`
  - adfly sample api: `"hsdfgCgdgrsdfgsfgfgsdgLsfgXef 51515155"` Split api key and user id with a space.
  - shortcm sample api: `"hsdfgCgdgrsdfgsfgfgsdgLsfgXef abcdotcom"` Split api key and domain with a space.
  - tinycc sample api: `"hsdfgCgdgrsdfgsfgfgsdgLsfgXef tinyccusername"` Split api key and username with a space.
## From Other Repositories
- qBittorrent
- Select files from Torrent before downloading using qbittorrent
- Leech (splitting, thumbnail for each user, setting as document or as media for each user)
- Size limiting for Torrent/Direct, Zip/Unzip, Mega and Clone
- Stop duplicates for all tasks except yt-dlp tasks
- Zip/Unzip G-Drive links
- Counting files/folders from Google Drive link
- View Link button, extra button to open file index link in broswer instead of direct download
- Status Pages for unlimited tasks
- Clone status
- Search in multiple Drive folder/TeamDrive
- Recursive Search (only with `root` or TeamDrive ID, folder ids will be listed with non-recursive method)
- Multi-Search by token.pickle if exists
- Extract rar, zip and 7z splits with or without password
- Zip file/folder with or without password
- Use Token.pickle if file not found with Service Account for all Gdrive functions
- Random Service Account at startup
- Mirror/Leech/Watch/Clone/Count/Del by reply
- YT-DLP quality buttons
- Search for torrents with Torrent Search API or with variable plugins using qBittorrent search engine
- Docker image support for `linux/amd64, linux/arm64, linux/arm/v7, linux/arm/v6` (**Note**: Use `anasty17/mltb-oracle:latest` for oracle or if u faced problem with arm64 docker run)
- Update bot at startup and with restart command using `UPSTREAM_REPO`
- Clone/Zip/Unzip/Count from gdtot links (main script from [Yusuf](https://github.com/oxosec)) and delete first cloned file from main drive or TeamDrive
- Qbittorrent seed until reaching specific ratio or time
- Rss feed and filter. Based on this repository [rss-chan](https://github.com/hyPnOtICDo0g/rss-chan)
- Save leech settings including thumbnails in database
- Many bugs have been fixed
- Mirror direct download links, Torrent, and Telegram files to Google Drive
- Mirror Mega.nz links to Google Drive (If you have non-premium Mega account, it will limit download to 5GB per 6 hours)
- Copy files from someone's Drive to your Drive (Using Autorclone)
- Download/Upload progress, Speeds and ETAs
- Mirror all yt-dlp supported links
- Docker support
- Uploading to Team Drive
- Index Link support
- Service Account support
- Delete files from Drive
- Shortener support
- Speedtest
- Multiple Trackers support
- Shell and Executor
- Sudo with or without Database
- Custom Filename* (Only for direct links, Telegram files and yt-dlp. Not for Mega links, Gdrive links or Torrents)
- Extract or Compress password protected files.
- Extract these filetypes and uploads to Google Drive
  > ZIP, RAR, TAR, 7z, ISO, WIM, CAB, GZIP, BZIP2, APM, ARJ, CHM, CPIO, CramFS, DEB, DMG, FAT, HFS, LZH, LZMA, LZMA2, MBR, MSI, MSLZ, NSIS, NTFS, RPM, SquashFS, UDF, VHD, XAR, Z, tar.xz

- Direct links Supported:
  >letsupload.io, hxfile.co, anonfiles.com, bayfiles.com, antfiles, fembed.com, fembed.net, femax20.com, layarkacaxxi.icu, fcdn.stream, sbplay.org, naniplay.com, naniplay.nanime.in, naniplay.nanime.biz, sbembed.com, streamtape.com, streamsb.net, feurl.com, pixeldrain.com, racaty.net, 1fichier.com, 1drv.ms (Only works for file not folder or business account), uptobox.com (Uptobox account must be premium), solidfiles.com

# How to deploy?
