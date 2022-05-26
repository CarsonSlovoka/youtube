## Build

```
git clone https://github.com/kkdai/youtube.git
cd youtube
go build ./cmd/youtubedr
```

如果想要`-o`來為執行檔更名，請切換到[cmd/youtubedr](cmd/youtubedr)資料夾
```
cd youtube/cmd/youtubedr
go build -o ydl.exe
```

## USAGE

> youtubedr.exe download https://www.youtube.com/watch?v=rFejpH_tAHM
>
> youtubedr.exe download -q medium https://www.youtube.com/watch?v=rFejpH_tAHM
>
> youtubedr.exe download -q hd1080 https://www.youtube.com/watch?v=rFejpH_tAHM
