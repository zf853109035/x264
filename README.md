# x264
x264 Git mirror

example.c->main()->x264_encoder_encode()(encode a frame)->slices_write()->slice_write()(encode a slice)

### x264_encoder_encode()  
----x264_lookahead_get_frames->x264_slicetype_decide() 判断是i、p、b帧
### slice_write()
----
