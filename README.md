# marisa-chan
## これなん
ふぁぼった画像付きツイートをSlackに流すやつ

## How to use
トークンを取ってきて、所定の変数に格納してから、

```
$ python marisa-chan.py
```

## dependencies
* Python 3.x
* tweepy
  * tweepy/streaming.pyを、[このissueの回答通りに](https://github.com/tweepy/tweepy/issues/615#issuecomment-122886173)修正する必要があります
* requests

## TODO
* [x] 例外発生時のtracebackをいい感じに取得する
