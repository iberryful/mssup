# mssup
A command line app for meituan object bucket

##Usage
Usage: mssup [OPTIONS] FILE_NAME

  A simple tool to upload file to meituan object bucket. Please set
  environment variables MSS_KEY and MSS_SECRET first.

Options:
  -b, --bucket TEXT         butket name
  -t, --expires_in INTEGER  expire time
  --help                    Show this message and exit.


set environment variable before use.

```shell
export MSS_KEY=YOUR_MSS_ACCESS_KEY
export MSS_SECRET=YOUR_MSS_ACCESS_SECRET
```

##example
mssup hello_world.py

