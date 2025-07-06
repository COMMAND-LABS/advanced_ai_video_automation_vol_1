# TLDR

Advanced A.I. Video Automation

## ToC

1 - `intro.md`
2 - `example_1.md`
3 - `example_2.md`
4 - `example_3.md`
5 - `outro.md`

## Customizing the transcription

- https://json2video.com/docs/v2/api-reference/json-syntax/element/subtitles

```sh
export JSON2VIDEO_PROJECT_ID=ttQeEoXDQ94TfWbX
export JSON2VIDEO_API_KEY=<API_KEY_HERE>
curl --location --request GET "https://api.json2video.com/v2/movies?project=$JSON2VIDEO_PROJECT_ID" \
--header "x-api-key: $JSON2VIDEO_API_KEY"
```
