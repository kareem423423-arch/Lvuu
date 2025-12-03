<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع الورود والقلوب</title>
    <style>
        /* CSS للتنسيق */
        body {
            /* تعيين الخلفية الوردية */
            background-color: #ffc0cb; 
            /* إضافة تأثير الورود باستخدام صورة خلفية متكررة */
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><text x="10" y="25" font-size="20" fill="%23f4a2ad">🌸</text><text x="60" y="70" font-size="20" fill="%23f4a2ad"></text><text x="35" y="90" font-size="20" fill="%23f4a2ad">🌷</text></svg>');
            background-repeat: repeat;
            
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            font-family: 'Arial', sans-serif;
            flex-direction: column;
            text-align: center;
            position: relative; /* مهم لوضع الزر الجانبي */
        }

        /* --- تنسيق الزر الأساسي (دوسي هنا) --- */
        .main-button {
