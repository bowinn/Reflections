---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Bowen's Personal Page
subtitle: to record my reflections on study and experience in the way to colleges.
description: This is the meta description for this page and will help it appear in search engines
toc: true
image: /img/bowen.jpg
# hero_image: /path/to/hero-image.jpg
# hero_height: is-fullheight
show_sidebar: true
---

        <div id="time"></div>
        <script>
         setInterval(time,1000) //定时器
         function time(){ //定义方法 time
           let time = new Date();  //实例化日期对象
           let year=time.getFullYear()+"年" //获取年
           let month=time.getMonth()+1+"月" //获取月
           let day=time.getDate()+"日"      //获取日
           let h=time.getHours()+':'        //获取时
           let m=time.getMinutes()+":"      //获取分
           let s=time.getSeconds()          //获取秒
           if(s<10){                        //判定秒 是否小于10秒
              s="0"+time.getSeconds()      //小于是 在其前加0 01，02，03...
               }
          if(time.getMinutes()<10){        //判定分 是否小于10分
              m="0"+time.getMinutes()+":"  //小于是 在其前加0 01，02，03...
              }
          id.innerHTML='当前时间：'+year+month+day+h+m+s  //显示当前时间
        }
         </script>

Here is the recent updated contents......
