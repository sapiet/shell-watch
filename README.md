# Shell watch function

## Usage

`watch.sh <your_command> <sleep_duration>`

## Example

Run `./watch.sh "cat watch.sh" 1` to watch for the script content every second

Output:
```
Wed Oct 16 15:09:25 CEST 2019
#!/bin/bash

while :;
  do
  clear
  date
  $1
  sleep $2
done
```
