# 自用娱乐，出事概不负责

# 说明

1、使用的jd_Scripts脚本，感谢原作者。    
2、只保留了签到、农场、种豆得豆，其它脚本都删除了。    
3、不带助力码，不会给任何人助力。    
4、本人小白一个，看不懂jd_Scripts中大神写的代码，只会简单的使用。    

# 使用

1、下载代码，终端执行`npm install`    
2、将你的`pt_key=;pt_pin=;`放在`.env`文件的`JD_COOKIE`中    
3、其它环境变量自行往`.env`中添加，例如`PUSH_PLUS_TOKEN`推送    
4、终端执行`node .\jd_task.js`会执行全部任务（签到、农场、种豆）    

# 脚本说明
1、终端执行`node .\jd_bean_home.js`会执行签到任务     
2、终端执行`node .\jd_jrsign.js`会执行金融签到任务    
3、终端执行`node .\jd_fruit.js`会执行农场任务    
4、终端执行`node .\jd_plantBean.js`会执行种豆得豆任务    