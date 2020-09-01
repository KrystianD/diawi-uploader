Diawi uploader
=====

This tool is a simple utility for uploading one or more .apk or .ipa files to [Diawi](https://www.diawi.com/).

### Usage

```bash
python diawi_uploader.py [--token TOKEN] [--qr] file [file ...]
```

### Parameters

`--qr` - Shows QR code with link to Diawi page.
`--token` - Diawo API token.

### Configuration

Script requires API token which can be passed via command line or read from a config file.

Config file search paths (in order):

- `PWD/diawi_uploader.ini`
- `PWD/.diawi_uploader.ini`
- `HOME/.diawi_uploader.ini`
- `HOME/.config/diawi_uploader.ini`

### Example

```shell
python diawi_uploader.py --qr app_debug.apk
```
