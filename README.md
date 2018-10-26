# find-duplicate-movies

A small Bash script for finding duplicate movies.

## Usage

```
Usage: find-duplicate-movies [OPTION]... [FILE]...

Options:
 -h, --help     Display this help and exit.
 -v, --verbose  Enable verbose mode. This causes extra information to be written to standard output.
```

## Example

```
> find-duplicate-movies /mnt/data1/Videos /mnt/data2/Videos /mnt/data3/Videos
Collecting files in /mnt/data1/Videos ..
Collecting files in /mnt/data2/Videos ..
Collecting files in /mnt/data3/Videos ..

Finding duplicates ..
/mnt/data2/Videos/Fear.and.Loathing.in.Las.Vegas.1998.720p.BluRay.x264.mp4
/mnt/data3/Videos/Fear.and.Loathing.in.Las.Vegas.1998.1080p.BluRay.x264.mp4
```

## License

Licensed under MIT license. See [LICENSE](LICENSE) for more information.

## Authors

* Johan Gardhage