# Homebrew Presets

## Usage

```sh
# Export existing settings
$ ./export.sh

# Import settings from repo

$ ./import.sh
```

## Notes

If you encounter this error with **Google Backup & Sync**: *"Backup and Sync has encountered a fatal error, and will now terminate."*, chances are your `~/Library/Application Support/Google` folder is owned by `root`. Change the ownership to yourself:

```sh
$ sudo chown $USER ~/Library/Application\ Support/Google
```