# x264
x264 Git mirror

example.c->main()->x264_encoder_encode()(encode a frame)->slices_write()->slice_write()(encode a slice)

### x264_encoder_encode()  
----x264_lookahead_get_frames->x264_slicetype_decide() 判断是i、p、b帧
### slice_write()
----

### h264详解 https://miaopei.github.io/2019/05/28/FFmpeg/FFmpeg%E7%9A%84H.264%E8%A7%A3%E7%A0%81%E5%99%A8%E6%BA%90%E4%BB%A3%E7%A0%81%E7%AE%80%E5%8D%95%E5%88%86%E6%9E%90/
