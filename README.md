# mediainfo_buildpack_heroku

[![Compile](https://github.com/code-rgb/mediainfo_buildpack_heroku/actions/workflows/release.yaml/badge.svg?event=push)](https://github.com/code-rgb/mediainfo_buildpack_heroku/actions/workflows/release.yaml)

A Heroku buildpack to download latest [MediaInfo](https://mediaarea.net/en/MediaInfo) pre-compiled binary.

## Usage

-   Add the following link in your `.buildpacks` file:

```
https://github.com/code-rgb/mediainfo_buildpack_heroku.git
```

-   Or use the following command via heroku CLI:

```
heroku buildpacks:add https://github.com/code-rgb/mediainfo_buildpack_heroku.git
```
