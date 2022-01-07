<h1 align="center">This is a complete rewrite of NOTFLIX made to be cacheless and POSIX</h1>
<p align="center">[Original notflix by Bugswriter](https://github.com/Bugswriter/notflix)</p>

##
<p align="center">
<img src="./preview.gif" alt="Video Preview" width="500px">
</p>

## Requirements

* [webtorrent](https://webtorrent.io/) - A tool to stream torrent. `sudo npm install webtorrent -g`
* rofi (can be changed in script)
* ripgrep (can be changed in script)
* fzf (can be changed in script)

## Installation

### cURL
cURL **notflix** to your **$PATH** and give execute permissions.

```sh
$ curl -sL "https://raw.githubusercontent.com/LamprosPitsillos/notflix/master/notflix" -o ~/.local/bin/notflix
$ chmod +x ~/.local/bin/notflix
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f /usr/local/bin/notflix.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).
