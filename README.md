# RGB-YUV
 视频RGB转YUV格式

Y''= 0.299*R'' + 0.587*G'' + 0.114*B''

U''= -0.147*R'' - 0.289*G'' + 0.436*B'' = 0.492*(B''- Y'')

V''= 0.615*R'' - 0.515*G'' - 0.100*B'' = 0.877*(R''- Y'')

 
 48bit宽数据的视频转模块
 延时为8个clock，不使用乘法器
 
 工程还缺少一个延时模块，延时数据用，很简单的模块，自己写就好
 
 
--@--Young--@--
