# CCTV
Repository of CCTV, IP Camera, and other camera/device information.

## Stream Profiles

### Amcrest
rtsp://[username]:password@IPaddress:554/cam/realmonitor?channel=1&subtype=0

### Axis
rtsp://ip-addr/axis-media/media.amp
rtsp://xxx.xxx.xxx.xxx/mpeg4/media.amp
rtsp://xxx.xxx.xxx.xxx:554/axis-media/media.amp
rtsp://xxx.xxx.xxx.xxx/axis-media/media.amp?camera=2 (stream 2 / View Area 2 H.264)

### Canon
(VB-M42) http://username:password@XXX.XXX.XXX.XXX/-wvhttp-01-/video.cgi

### Dahua
rtsp://<username>:<password>@<ip>:<port>/cam/realmonitor?channel=<channelNo>&subtype=<typeNo>

<ip> – the IP address of the IP Camera.
<port> – the default port is 554. It can be omitted.
<channelNo> – the channel number. It starts from 1.
<typeNo> – the stream type. The <typeNo> of main stream is 0, extra stream 1 is 1, extra stream 2 is 2.


### Foscam
rtsp://testuser:foscam@192.168.1.11:88/videoMain
rtsp://testuser:foscam@192.168.1.11:88/videoSub

### Lorex
See Dahua

### Panasonic
rtsp://192.168.0.253:port//nphMpeg4/g726-640×48

rtsp://192.168.0.253/nphMpeg4/g726-640×480

rtsp://192.168.0.253/nphMpeg4/nil-320×240

rtsp://192.168.0.253/MediaInput/h264

rtsp://192.168.0.253/nphMpeg4/g726-640x

rtsp://192.168.0.253/MediaInput/mpeg4

