
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>موهوب</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:black;
color:white;
overflow:hidden;
}

.feed{
height:100vh;
overflow-y:scroll;
scroll-snap-type:y mandatory;
}

.video-card{
position:relative;
height:100vh;
scroll-snap-align:start;
display:flex;
align-items:flex-end;
padding:20px;
background-size:cover;
background-position:center;
}

.overlay{
position:absolute;
top:0;
left:0;
right:0;
bottom:0;
background:linear-gradient(to top, rgba(0,0,0,.85), rgba(0,0,0,.2));
}

.content{
position:relative;
z-index:2;
width:75%;
margin-bottom:60px;
}

.username{
font-size:24px;
font-weight:bold;
margin-bottom:10px;
}

.desc{
font-size:18px;
line-height:1.6;
}

.actions{
position:absolute;
right:15px;
bottom:100px;
z-index:2;
display:flex;
flex-direction:column;
gap:18px;
align-items:center;
}

.action{
text-align:center;
font-size:14px;
}

.icon{
width:58px;
height:58px;
border-radius:50%;
background:rgba(255,255,255,.15);
display:flex;
align-items:center;
justify-content:center;
font-size:28px;
margin-bottom:5px;
backdrop-filter:blur(5px);
}

.bottom-bar{
position:fixed;
bottom:0;
width:100%;
height:70px;
background:rgba(0,0,0,.75);
display:flex;
justify-content:space-around;
align-items:center;
font-size:14px;
z-index:5;
backdrop-filter:blur(8px);
}

.plus{
background:#9333ea;
width:50px;
height:50px;
border-radius:18px;
display:flex;
align-items:center;
justify-content:center;
font-size:34px;
margin-top:-20px;
}

.live{
display:inline-block;
padding:6px 12px;
background:red;
border-radius:12px;
font-size:14px;
margin-bottom:10px;
}

</style>
</head>

<body>

<div class="feed">

<div class="video-card" style="background-image:url('https://images.unsplash.com/photo-1516280440614-37939bbacd81?q=80&w=1200&auto=format&fit=crop');">
<div class="overlay"></div>

<div class="content">
<div class="live">مباشر</div>
<div class="username">@احمد_الطرب</div>
<div class="desc">
🎤 أداء أغنية طربية كلاسيكية<br>
#غناء #طرب #موهوب
</div>
</div>

<div class="actions">
<div class="action">
<div class="icon">❤️</div>
12.5K
</div>

<div class="action">
<div class="icon">💬</div>
3.2K
</div>

<div class="action">
<div class="icon">🔁</div>
980
</div>

<div class="action">
<div class="icon">🏆</div>
تصويت
</div>
</div>
</div>


<div class="video-card" style="background-image:url('https://images.unsplash.com/photo-1501386761578-eac5c94b800a?q=80&w=1200&auto=format&fit=crop');">
<div class="overlay"></div>

<div class="content">
<div class="username">@سارة</div>
<div class="desc">
🎸 عزف جيتار مع غناء هادئ<br>
#عزف #غناء
</div>
</div>

<div class="actions">
<div class="action">
<div class="icon">❤️</div>
8.1K
</div>

<div class="action">
<div class="icon">💬</div>
1.4K
</div>

<div class="action">
<div class="icon">🔁</div>
600
</div>

<div class="action">
<div class="icon">🏆</div>
تصويت
</div>
</div>
</div>


<div class="video-card" style="background-image:url('https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f?q=80&w=1200&auto=format&fit=crop');">
<div class="overlay"></div>

<div class="content">
<div class="username">@خالد</div>
<div class="desc">
🔥 راب عربي مباشر<br>
#راب #موهبة
</div>
</div>

<div class="actions">
<div class="action">
<div class="icon">❤️</div>
15K
</div>

<div class="action">
<div class="icon">💬</div>
4K
</div>

<div class="action">
<div class="icon">🔁</div>
2K
</div>

<div class="action">
<div class="icon">🏆</div>
تصويت
</div>
</div>
</div>

</div>

<div class="bottom-bar">
<div>الرئيسية</div>
<div>اكتشف</div>
<div class="plus">+</div>
<div>مباشر</div>
<div>الحساب</div>
</div>

</body>
</html>
