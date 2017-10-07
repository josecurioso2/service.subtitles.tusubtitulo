# TuSubtitulo.com provider

----------

## Table of Contents
1. [History](#history)
1. [Installation](#installation)
1. [Features](#features)
1. [Known bugs](#bugs)
1. [TODO](#todo)
1. [Contributing](#contributing)
1. [License](#license)


## History

This addon is based on previous work by m0r3 and inifinicode on the original Subtitulos.es addon and its first port to TuSubtitulo.com
If you are a bit lost let me explain:
Subtitulos.es was a very well known site where users could translate series subtitles from English to Spanish collectively. It worked incredibly well and was useful for many people and one of the main sources for Spanish subtitles sometimes taking even less than 24 hours to release a translation. All that ended (or so we thought) when the Spanish authorities threatened the owner of the page and, out of an abundance of caution, he decided to close the page.
Soon after that closure TuSubtitulo.com appeared on the radar holding all assets of Subtitulos.es such as the design and the actual files and continued with the 'legacy'
The only downside being that the new administrators didn't believe in ease of use and made it very hard to develop a similar product to the old addon (notice very hard does not mean impossible).
Fast forward to now, the previous supporters have stopped giving updates and I'm taking responsibility of this addon.


## Installation

The best way to install it is by downloading my repo and then installing it through there, that way you will get updates as soon as they go live and automatically.
    - [Repo link](https://github.com/josecurioso/repository.josecurioso.kodi/releases)

Another posibility is to install only the service (without updates) from the releases page of this repository.
    - [Release page](https://github.com/josecurioso2/service.subtitles.tusubtitulo/releases)


## Features

- Detection of incomplete subtitles (and consequent discarding)
- Scrapping every version
- I could continue but right now it is very basic


## Bugs

- Be careful with another repo overwriting the addon with a different one, this happened the first days after the release but could reappear.
- As stated in [this issue](https://github.com/josecurioso2/service.subtitles.tusubtitulo/issues/4) sometimes Kodi is not able to fullfill the dependencies of the addon. Would that be the case, you can manually download them and install from:
    - [xbmc.python 2.25.0](https://ftp.acc.umu.se/mirror/addons.superrepo.org/v7/addons/xbmc.python/xbmc.python-2.25.0.zip)
    - [script.module.beautifulsoup 4.5.3](https://ftp.heanet.ie/mirrors/xbmc/addons/krypton/script.module.beautifulsoup4/script.module.beautifulsoup4-4.5.3.zip)


## TODO

- Add rating support, TuSubtitulo doesn't offer ratings but I'll figure something out


## Contributing

First of all you can donate by going to [TuSubtitulo](http://tusubtitulo.com) and help maintain the servers needed for everything to work. The request volume of this addon to said page doesn't exceed that of a human being accessing through a web browser so your usage won't bring the servers down but collaborations are always appreciated.
There are many ways to contribute to any project, one of the best ones is to report bugs, the best practice for doing so is to attach a logfile (http://kodi.wiki/view/Log_file/Easy) and explain clearly under which circumstances the error was produced.
Another way is to submit a pull request, they are very welcome since currently I'm alone so feel free to take on a bug by yourself or add any functionality you deem necessary.


## License

This project is licensed under the GPL 2.0 License - see the [LICENSE.md](LICENSE.txt) file for details
