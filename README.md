# firstcv


## 使用nginx-rtmp作为推流服务器

### 推流

1. flv 推流，flash播放

	rtmp://192.168.1.1:1935/myapp/osx
	
2. flv 推流，apple播放

	rtmp://192.168.1.1:1935/hls/osx

### 直播

1. apple直播

	http://192.168.1.1:8080/hls/osx.m3u8

2. web直播

	借助播放器即可： rtmp://192.168.1.1:1935/myapp/osx