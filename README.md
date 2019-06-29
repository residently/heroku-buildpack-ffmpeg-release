# heroku-buildpack-ffmpeg-release

A Heroku buildpack for ffmpeg that always downloads the latest [release build](http://johnvansickle.com/ffmpeg/).
Based upon https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/residently/heroku-buildpack-ffmpeg-release.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/residently/heroku-buildpack-ffmpeg-release.git
```
