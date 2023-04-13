# File decompression script 📁
This script is designed to decompress different types of compressed files. Simply run the script followed by the name of the compressed file you wish to decompress, and the script will automatically select the appropriate decompression method.

## Usage
To use this script, simply run it followed by the name of the compressed file you wish to decompress. For example, if you wish to decompress a file named example.tar.gz, you would run the following command:

```sh
decompress.sh example.tar.gz
```

## Supported file types
This script supports the following file types:

- tar.bz2
- tar.gz
- bz2
- rar
- gz
- tar
- tbz2
- tgz
- zip
- Z
- 7z

If you attempt to use this script to decompress a file type that is not listed here, the script will output an error message.

## And how to turn this script into a command? 

To make this script into a command in Ubuntu GNU/Linux, you can follow these steps:

1. Create a new file in /usr/local/bin/ directory with the name of your command. For example, if you want to create a command named extract, you can use the following command:

```sh
sudo vim /usr/local/bin/extract
```
2. Copy and paste the contents of your script into this file.
3. Save and close the file.
4. Make the file executable by running the following command:

```sh
sudo chmod +x /usr/local/bin/extract
```
5. Now you can run the command extract in the terminal to execute your script.

```sh
extract file_to_extract.tar.gz
```
This will extract the contents of the file_to_extract.tar.gz archive using the appropriate decompression utility based on its file extension.
