# makegif
Shell script &amp; Automator service for creating animated GIFs from videos

## Installation:
- `makegif` depends on `ffmpeg`
- the Automator service requires `makegif` being on your `PATH` via `source $HOME/.bash_profile`

## Usage:
### Shell script:
```
makegif [--fps fps] [--width width] [--height height] [--colors max_colors] source_file ...
```
### Automator service:
The service can operate on sets of movie files. 
