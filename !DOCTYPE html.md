<!DOCTYPE html>  
<html lang=**"**ar**"** dir=**"**rtl**"**>  
<head>  
    <meta charset=**"**UTF-8**"**>  
    <meta name=**"**viewport**"** content=**"**width=device-width, initial-scale=1.0**"**>  
    <title>Respect Town - S2</title>  
    <link href=**"**https**:**//fonts.googleapis.com/css2?family=Cairo**:**wght@400;700;900&display=swap**"** rel=**"**stylesheet**"**>  
    <link rel=**"**stylesheet**"** href=**"**https**:**//cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css**"**>  
      
    <style>  
        **:**root {  
            --gold**:** #D4AF37;  
            --light-gold**:** #FFD700;  
            --dark-bg**:** #0f0f0f;  
            --glass-bg**:** rgba**(**255, 255, 255, 0.05**)**;  
        }  
  
        body {  
            margin**:** 0;  
            padding**:** 0;  
            font-family**:** **'**Cairo**'**, sans-serif;  
            background**:** radial-gradient**(**circle at top, #1a1a1a 0%, #000 100%**)**;  
            color**:** white;  
            min-height**:** 100vh;  
            display**:** flex;  
            flex-direction**:** column;  
            align-items**:** center;  
        }  
  
        /* **حاوية** **المحتوى** */  
        .container {  
            width**:** 90%;  
            max-width**:** 500px;  
            text-align**:** center;  
            padding**:** 40px 20px;  
        }  
  
        /* **الشعار** */  
        .logo-area img {  
            width**:** 150px;  
            height**:** 150px;  
            border-radius**:** 50%;  
            border**:** 3px solid var**(**--gold**)**;  
            box-shadow**:** 0 0 20px rgba**(**212, 175, 55, 0.3**)**;  
            margin-bottom**:** 20px;  
        }  
  
        h1 {  
            font-size**:** 2rem;  
            margin**:** 10px 0;  
            color**:** var**(**--gold**)**;  
            text-shadow**:** 0 2px 4px rgba**(**0,0,0,0.5**)**;  
        }  
  
        .description {  
            font-size**:** 0.95rem;  
            line-height**:** 1.8;  
            color**:** #ccc;  
            background**:** var**(**--glass-bg**)**;  
            padding**:** 20px;  
            border-radius**:** 15px;  
            backdrop-filter**:** blur**(**5px**)**;  
            border**:** 1px solid rgba**(**212, 175, 55, 0.1**)**;  
            margin-bottom**:** 30px;  
        }  
  
        /* **الأزرار** */  
        .btn-list {  
            display**:** flex;  
            flex-direction**:** column;  
            gap**:** 15px;  
        }  
  
        .btn {  
            display**:** flex;  
            align-items**:** center;  
            justify-content**:** center;  
            gap**:** 10px;  
            padding**:** 15px;  
            text-decoration**:** none;  
            color**:** white;  
            font-weight**:** bold;  
            background**:** linear-gradient**(**45deg, #1a1a1a, #2a2a2a**)**;  
            border**:** 1px solid var**(**--gold**)**;  
            border-radius**:** 50px;  
            transition**:** 0.3s;  
            cursor**:** pointer;  
        }  
  
        .btn**:**hover {  
            background**:** var**(**--gold**)**;  
            color**:** black;  
            transform**:** translateY**(**-3px**)**;  
            box-shadow**:** 0 5px 15px rgba**(**212, 175, 55, 0.4**)**;  
        }  
  
        .btn-discord {  
            background**:** #5865F2; /* **لون** **ديسكورد** **الرسمي** */  
            border**:** none;  
        }  
  
        .btn-discord**:**hover {  
            background**:** #4752c4;  
            color**:** white;  
        }  
  
        .footer {  
            margin-top**:** 40px;  
            font-size**:** 0.8rem;  
            color**:** #666;  
        }  
  
        /* **قائمة** **منبثقة** **بسيطة** **للقوانين** **أو** **المؤسسين** */  
        .modal {  
            display**:** none;  
            position**:** fixed;  
            top**:** 50%;  
            left**:** 50%;  
            transform**:** translate**(**-50%, -50%**)**;  
            background**:** #1a1a1a;  
            border**:** 2px solid var**(**--gold**)**;  
            padding**:** 20px;  
            border-radius**:** 20px;  
            z-index**:** 1000;  
            width**:** 80%;  
            max-width**:** 400px;  
        }  
    </style>  
</head>  
<body>  
  
    <div class=**"**container**"**>  
        <div class=**"**logo-area**"**>  
            <img src=**"**https**:**//i.ibb.co/VmqpZpM/image.png**"** alt=**"**Logo**"**>  
        </div>  
  
        <h1>𝐑espect - Town - 𝐒2 | 🇸🇦</h1>  
  
        <div class=**"**description**"**>  
            🏙️ <strong>Respect Town - S2</strong><br>  
            **حيث** **يلتقي** **الرقيّ** **بالأخلاق**. **مجتمع** **رقمي** **متميز** **يجمع** **بين** **التنظيم** **العالي** **والأجواء** **الأخوية**. **نهدف** **لتقديم** **تجربة** **اجتماعية** **فريدة** **قائمة** **على** **الاحترام** **المتبادل**.  
        </div>  
  
        <div class=**"**btn-list**"**>  
            <a href=**"**https**:**//discord.gg/[https://discord.gg/vFZRqXsSQ](https://discord.gg/vFZRqXsSQ)**"** class=**"**btn btn-discord**"**>  
                <i class=**"**fab fa-discord**"**></i> **سيرفر** **الديسكورد**  
            </a>  
              
            <a href=**"**#**"** class=**"**btn**"** onclick=**"**alert**('سيتم** **إضافة** **القوانين** **قريباً')"**>  
                <i class=**"**fas fa-gavel**"**></i> **القوانين**  
            </a>  
  
            <a href=**"**#**"** class=**"**btn**"** onclick=**"**alert**('المؤسسين:** **طاقم** **إدارة** **ريسبيكت** **تاون')"**>  
                <i class=**"**fas fa-users-crown**"**></i> **المؤسسين**  
            </a>  
  
            <a href=**"**#**"** class=**"**btn**"**>  
                <i class=**"**fas fa-star**"**></i> **المميزات**  
            </a>  
        </div>  
  
        <div class=**"**footer**"**>  
            &copy; 2026 Respect Town S2. All Rights Reserved.  
        </div>  
    </div>  
  
</body>  
</html>  
