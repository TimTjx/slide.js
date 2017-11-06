# slide.js
基于jQuery的一份可配置参数易用的轮播图插件

$("").slide({
  btn:true,                 //是否添加左右按钮 true（默认）添加，flase不添加   
  autoPlay:true,            //是否自动播放 true 自动播放，false（默认）不自动播放   
  fade:"slide",             //切换效果 slide（滑动）  || fade(渐隐渐现，默认)   
  autoPlaySpeed:3000，      //自动播放时间间隔，Number类型，单位毫秒，默认：3000   
  dot:true，                //是否添加小原点，true 添加 || false(默认) 不添加   
  dotColor："#3963ec"       //小圆点颜色 #3963ec（默认）
})
