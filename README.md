# bvmerger

> bvmerger = bilibili video merger

将 Bilibili App 上缓存视频中 `video.m4s` 和 `audio.m4s` 合并成 `mp4` 格式视频。

## 要求

- Go (version >= 1.16)
- ffmpeg

## 安装

```shell
go install github.com/drrrMikado/bvmerger
```

## 使用方法

```shell
bvmerger --help
```

### 参数

- ffmpeg: ffmpeg可执行文件路径 (default "ffmpeg")
- input: 输入文件路径
- output: 输出文件路径 (default "output")

### 示例

```shell
bvmerger --input ./627826691 --output output --ffmpeg ./bin/ffmpeg
```

