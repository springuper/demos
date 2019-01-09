# MSE Demo

## Step 1: Start local static server

```bash
$ cd /path/to/demos
$ npm run start
```

## Step 2: Run demos

There are two demos:

1. Basic
  This demo shows how to use MSE to append buffer to source buffer.
  Open `http://127.0.0.1:8888/basic.html` in Chrome.
2. On demand appending buffer
  This demo shows how to use MSE to dynamically append buffer to source buffer.
  For example, when the current buffer is going to run out, or the user seeks to a new position.
  Open `http://127.0.0.1:8888/ondemand.html` in Chrome.
