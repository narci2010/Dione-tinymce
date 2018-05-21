# Dione-tinymce
基于tinymce网络图片上传增加了本地图片上传功能


这个功能的具体实现写在component组件里面
有两种实现方法  
    1: 选择文件后直上传然后得到网络url
    2: 用HTML5的 File API 的 FileReader 图片本地转成base64格式的url,然后将url赋值给一个img标签
两种方法的实现均在代码里面有实现


运行步骤
    --npm  install 

    --npm  run  dev
    因为用了eslint,所以代码编译的时候会有很多eslint的错误出来,不用担心 
    直接打开浏览器,访问8080端口即可 
