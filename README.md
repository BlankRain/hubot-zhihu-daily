# hubot-zhihu-daily
A simple hubot script for zhihu daily

##Demo

###Using hubot-zhihu-daily with shell adapter
![](https://raw.githubusercontent.com/suosuopuo/hubot-zhihu-daily/master/terminal_demo.gif)

###Using hubot-zhihu-daily with hipchat adapter
![](https://raw.githubusercontent.com/suosuopuo/hubot-zhihu-daily/master/hipchat_demo.png)

##Installation
There are two ways to install this script.

###As a external script
First, install the script via npm

    npm install hubot-zhihu-daily --save

Then, append a name `hubot-zhihu-daily` to `external-scripts.json`

    ["hubot-zhihu-daily"]

###As a bundled script
Clone this repo, then copy the file `zhihu-daily.coffee` into directory `scripts` under your Hubot root directory.

Done.

##Commands

    hubot zhihu today
    hubot zhihu latest <count>
    hubot zhihu before yyyymmdd

###Example
####Get all the articles of today (only titles and link)

    hubot zhihu today

####Get the latest 3 articles from zhihu (with images)

    hubot zhihu latest 3

####Get all the messages posted on 2015/03/14 (only titles and link)

    hubot zhihu before 20150315

