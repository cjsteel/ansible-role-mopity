# output-mopidyctl-config-run-001.md

```shell
Running "/usr/bin/mopidy --config /usr/share/mopidy/conf.d:/etc/mopidy/mopidy.conf config" as user mopidy
[core]
cache_dir = /var/cache/mopidy
config_dir = /etc/mopidy
data_dir = /var/lib/mopidy
max_tracklist_length = 10000
restore_state = false

[logging]
color = true
console_format = %(levelname)-8s %(message)s
debug_format = %(levelname)-8s %(asctime)s [%(process)d:%(threadName)s] %(name)s\n  %(message)s
debug_file = /var/log/mopidy/mopidy-debug.log
config_file = /etc/mopidy/logging.conf

[audio]
mixer = software
mixer_volume = 
output = autoaudiosink
buffer_time = 

[proxy]
scheme = 
hostname = 
port = 
username = 
password = 

[mpd]
enabled = true
hostname = 127.0.0.1
port = 6600
password = 
max_connections = 20
connection_timeout = 60
zeroconf = Mopidy MPD server on $hostname
command_blacklist = 
  listall
  listallinfo
default_playlist_scheme = m3u

[http]
enabled = true
hostname = 127.0.0.1
port = 6680
static_dir =
zeroconf = Mopidy HTTP server on $hostname

[stream]
enabled = true
protocols = 
  http
  https
  mms
  rtmp
  rtmps
  rtsp
metadata_blacklist = 
timeout = 5000

[m3u]
enabled = true
base_dir =
default_encoding = latin-1
default_extension = .m3u8
playlists_dir = /var/lib/mopidy/playlists

[softwaremixer]
enabled = true

[file]
enabled = true
media_dirs = 
  $XDG_MUSIC_DIR|Music
  ~/|Home
excluded_file_extensions = 
  .jpg
  .jpeg
show_dotfiles = false
follow_symlinks = false
metadata_timeout = 1000

[local]
enabled = true
library = json
media_dir = /var/lib/mopidy/media
scan_timeout = 1000
scan_flush_threshold = 100
scan_follow_symlinks = false
excluded_file_extensions = 
  .directory
  .html
  .jpeg
  .jpg
  .log
  .nfo
  .png
  .txt

```
