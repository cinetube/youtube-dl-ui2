<div align="center">
	<a href="https://mateffy.me/youtube-dl-ui">
		<img src="resources/screenshot.png">
	</a>
	<h1>youtube-dl-ui</h1>
	<p>
		Basic web UI for youtube-dl. Download a URL in highest quality, choosing between video or audio-only.
	</p>
</div>

<br>

## Installation
```sh
$ npm install -g youtube-dl-ui
```

## Usage
You can now start the server like you would any binary.
```sh
$ youtube-dl-ui
v1.0.3
```

### Options
```
Usage: youtube-dl-ui [options]

Options:
  -V, --version             output the version number
  -p, --port <port>         the port for the http server
  -v, --video-path <path>   path to directory where videos should be saved
  -a, --audio-path <path>   path to directory where audio should be saved
  -s, --socket-path <path>  url path the socket should connect to
  -d, --debug               enable debug mode
  -h, --help                display help for command
```

### Config
A config file for youtube-dl-ui will be created at `$HOME_DIR/.youtube-dl-ui/config`. However, options passed as command line arguments override settings in this file.

## Changelog
### Version 1.0.3
- Added CLI flag for socket path
- Added config log at startup for verification

### Version 1.0.2
- Changed HTML title

### Version 1.0.1
- Forgot to add README lol

### Version 1.0.0
- First polished release

## Authors
Lukas Mateffy – [@Capevace](https://twitter.com/capevace) – [mateffy.me](https://mateffy.me)

Distributed under the MIT license. See `LICENSE` for more information.

## Contributing
1. Fork it (<https://github.com/capevace/youtube-dl-ui/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
