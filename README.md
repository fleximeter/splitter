# splitter
Automatically splits audio files in a directory to make smaller files. This is useful if you don't want to have to load an entire audio file in memory. You can optionally delete the original files.

## Optional command-line parameters:
`-f`, `--folder`: The directory to convert. Defaults to `"."`

`-n`, `--num_frames`: The maximum number of frames per file. Defaults to `44100 * 10`

`-t`, `--num-threads`: The maximum number of threads to run. If `0` (default), the program uses the same number of threads as there are processors available.

## Optional command-line flags
`-d`, `--delete`: If you provide this flag, the original files will be deleted.

`-i`, `--fade-in`: If you provide this flag, a very brief fade in / fade out will be added to the new audio files.

## License
This program is provided under the GNU GPL 3.0 license.
