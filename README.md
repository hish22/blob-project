# blobify

A simple C library for working with binary blobs — memory blocks with range views and cursors for navigation.

## API

- **Block** — allocate/manage a raw byte buffer
- **Range** — a sliding, resizable window into a block
- **Cursor** — a position marker within a range
- **Blob** — combines block, range, and cursor into one object

## Build

```sh
gcc -o blobify blobify.c
```
