# TLDR

Welcome to Advanced A.I. Video Automation Vol. 1

## ToC

1. Check out `chapters/intro.md`
2. Check out `chapters/example_1.md`
3. Check out `chapters/example_2.md`
4. Check out `chapters/example_3.md`

## Customizing the transcription

- https://json2video.com/docs/v2/api-reference/json-syntax/element/subtitles

```sh
export JSON2VIDEO_PROJECT_ID=ttQeEoXDQ94TfWbX
export JSON2VIDEO_API_KEY=<API_KEY_HERE>
curl --location --request GET "https://api.json2video.com/v2/movies?project=$JSON2VIDEO_PROJECT_ID" \
--header "x-api-key: $JSON2VIDEO_API_KEY"
```
