# nextcloudcli
Nextcloud bash script for upload and download

#### Features:
- Interactive upload and download to or from your nextcloud host
- Simple saved login session (Stored in $HOME/.nextcloud_session)

#### How to:

```bash
wget https://raw.githubusercontent.com/Keyz078/nextcloudcli/refs/heads/main/nextcloudcli
chmod +x nextcloudcli
./nextcloudcli
```

#### Help

```bash
===== Nextcloud CLI Help =====
Navigation:
  cd <number>       - Change directory using the directory number shown in the list
                     Example: cd 1
  cd ..             - Go back to previous directory
  cd / or cd ~      - Jump directly to root directory

File Operations:
  <number(s)>       - Select one or more files by their numbers for download/upload
                     Example (download mode): 3
                     Example (multiple): 3 5 7
  <filename(s)>     - Enter one or more filenames to upload in upload mode
                     Example (upload mode): file1.txt file2.jpg

Menu Options:
  0                 - Return to the main menu
  help              - Show this help guide

Tips:
 - Directories are marked as [DIR], files as [FILE].
 - Use spaces to select multiple items (files or directories).
 - Upload mode accepts local files (absolute or relative path).
   Example: file.txt   ./Download/a.txt   /home/user/file.jpg
 - Download mode only works with files, not directories.
```

#### P.S:
For dev environments or self-hosted Nextcloud use only
