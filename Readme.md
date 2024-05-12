# Zhihu Daily 2024 for Flutter Starters

👋 Hello starters, this is your first lesson on how to write an App in Flutter.

>In this course, you will learn:
>
>1. Layout
>2. Infinite Scroll
>3. Pull to Refresh
>4. Web Request (When & How)
>5. Page Router
>6. Animation

😆 Let's finish this together... 

# 📓 Lesson 1: The Goal 

🎯 The purpose of this project is to write an App called `Zhihu Daily`. You may download the original version of this App to see the result.

<div style="width=100%; display: flex; flex-direction:row; justify-content:center;gap:10px;">
<img src="/home/steven/Downloads/Screenshot_2024-05-12-22-49-33-011_com.zhihu.daily.android.jpg" alt="Screenshot_2024-05-12-22-49-33-011_com.zhihu.daily.android" style="zoom:25%;" />
<img src="/home/steven/project/zhihu_daily_2024/images/scroll.jpg" alt="scroll" style="zoom:25%;" />
<img src="/home/steven/project/zhihu_daily_2024/images/article.jpg" alt="article" style="zoom:25%;" /></div>

<div style="width=100%; display: flex; flex-direction:row; justify-content: center; font-weight: 600;">Final Result</div>

🦾 It contains three main functions:

1. 🖼️ The Sweepers image on the first page.
2. 📈 The tile list on the main page, which is grouped by date. As the user scrolls down, it will automatically refresh with new data.
3. 📰 The article preview and sharing functionality.

Now, let's implement these one by one.

Starting by analyze the Web API for this app. web api is the bridge from the back-end to the front-end (App, web page, etc.)

You can find the API document at here TODO: need url

