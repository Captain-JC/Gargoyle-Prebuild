# Gargoyle-Prebuild

双面板（Luci+gargoyle-web）石像鬼固件，界面带有切换按钮，真正无缝切换

使用说明：

1）访问192.168.1.1，默认进入石像鬼界面，石像鬼界面提供luci按钮，点击即可切换到luci界面；

   同理，luci界面提供石像鬼按钮，点击切换回石像鬼界面

   注意：对于带自动完成功能的浏览器如chrome，如果无法正常访问，请清理浏览器缓存后再访问
   
2）固件名称说明

  pure版：如其名，就是纯净到极致的固件，除了石像鬼跟luci必须的功能外，啥插件都没集成
  
         注意：这里说的是插件没集成，但是一些基本的内核、库、个别功能模块(比如多拨内核)还是集成的
         
  plus版：如其名，集成一些插件，包括：
  
         SSR
         
         kms服务器
         
         .....
