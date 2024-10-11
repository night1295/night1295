<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت خدمات تدوین و طراحی</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f7fa; /* آبی آسمانی */
            margin: 0;
            padding: 20px;
            direction: rtl;
        }
        h1 {
            font-size: 36px;
            font-weight: bold;
            color: #007bb2; /* آبی */
            text-align: center;
        }
        .package {
            background-color: #ffffff;
            border: 1px solid #b0e0e6; /* رنگ مرز */
            padding: 20px;
            margin: 20px 0;
            text-align: center;
            border-radius: 10px;
        }
        .package h2 {
            font-size: 28px;
            margin-bottom: 10px;
            font-weight: bold;
            color: #007bb2; /* آبی */
        }
        .package ul {
            list-style-type: none;
            padding: 0;
            font-size: 20px;
            font-weight: bold;
            display: none;
        }
        .buy-button {
            background-color: #007bb2; /* آبی */
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 20px;
            position: relative;
        }
        .buy-button:hover {
            background-color: #005f8a; /* تیره‌تر */
        }
        .resum {
            margin-top: 40px;
            font-size: 20px;
            text-align: center;
        }
        .link {
            display: block;
            margin-top: 20px;
            font-size: 20px;
            color: #007bb2; /* آبی */
            text-decoration: none;
        }
        .link:hover {
            text-decoration: underline;
        }
        .sticker {
            position: absolute;
            right: -10px;
            top: -10px;
            font-size: 24px;
            display: none;
            transition: opacity 1s;
        }
        .large-text {
            font-size: 30px;
            font-weight: bold;
        }
        .tariff {
            font-size: 28px;
            font-weight: bold;
            margin-top: 10px;
        }
        .payment-info {
            display: none;
            margin-top: 20px;
            font-size: 22px;
        }
        .payment-button {
            display: none;
            margin-top: 20px;
            background-color: #007bb2; /* آبی */
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 20px;
        }
        .payment-button:hover {
            background-color: #005f8a; /* تیره‌تر */
        }
    </style>
</head>
<body>

<h1>خدمات تدوین و طراحی</h1>

<div class="package">
    <h2>پکیج اقتصادی</h2>
    <ul id="economy-services">
        <li>لوگو موشن</li>
        <li>استوری موشن</li>
        <li>تدوین ریلز</li>
        <li>کاور پست</li>
        <li>ادیت تیک‌تاکی</li>
    </ul>
    <button class="buy-button" onclick="toggleSticker('economy')">💸 خرید این پکیج
        <span class="sticker" id="economy-sticker">💸💸💸💸💸</span>
    </button>
    <div id="continue-economy" style="display: none;">
        <button class="buy-button" onclick="showPaymentInfo('economy')">ادامه</button>
    </div>
    <div class="payment-info" id="payment-economy">
        <p>شماره کارت: 6277601356857639</p>
        <p>قیمت محصول: 8 میلیون تومان</p>
        <p>رسید را به این آیدی تلگرام ارسال کنید: @pov_night</p>
        <a class="payment-button" href="https://www.zarinpal.com/" target="_blank">پرداخت با زرین‌پال</a>
    </div>
</div>

<div class="package">
    <h2>پکیج وی آی پی</h2>
    <ul id="vip-services">
        <li>استوری موشن سطح بسیار بالا</li>
        <li>ادیت ریلز با سطح حرفه‌ای</li>
        <li>ادیت تیک‌تاکی برای ماشین و محل کار</li>
        <li>ساخت لوگو با کیفیت بسیار عالی</li>
        <li>کاور پست با بهترین فونت و امکانات</li>
    </ul>
    <button class="buy-button" onclick="toggleSticker('vip')">💸 خرید این پکیج
        <span class="sticker" id="vip-sticker">💸💸💸💸💸💸💸💸💸</span>
    </button>
    <div id="continue-vip" style="display: none;">
        <button class="buy-button" onclick="showPaymentInfo('vip')">ادامه</button>
    </div>
    <div class="payment-info" id="payment-vip">
        <p>شماره کارت: 6277601356857639</p>
        <p>قیمت محصول: 15 میلیون تومان</p>
        <p>رسید را به این آیدی تلگرام ارسال کنید: @pov_night</p>
        <a class="payment-button" href="https://www.zarinpal.com/" target="_blank">پرداخت با زرین‌پال</a>
    </div>
</div>

<div class="resum">
    <h3 class="large-text">رزومه</h3>
    <p class="large-text">من در دوره‌هایی مانند گوت پلاس و دوره‌ی لیویلگیم شرکت کرده‌ام. سه سال است که در این حوزه فعالیت می‌کنم.</p>
    <p class="large-text">به برنامه‌ی افتر افکت تسلط کامل دارم و پروژه‌های متنوعی را انجام داده‌ام.</p>
    <p class="large-text">هدف من همیشه ارائه بهترین کیفیت در کارهایم بوده و از چالش‌های جدید خوشحال می‌شوم.</p>
    
    <p class="tariff">تعرفه:</p>
    <p class="large-text">من ابتکاری هستم، 14 سالمه و در شیراز زندگی می‌کنم.</p>
    <a class="link" href="https://night.com" target="_blank">به سایت ما مراجعه کنید</a> <!-- لینک به سایت -->
</div>

<a class="link" href="https://www.instagram.com/night_edit3/profilecard/?igsh=MWRubmhjOG5jeXY3dA==">برای دیدن نمونه کارهای بیشتر روی این لینک کلیک کنید</a>
<a class="link" href="tel:09178932870">تماس با ما: 09178932870</a> <!-- لینک تماس با شماره -->

<script>
    function toggleSticker(type) {
        const sticker = document.getElementById(`${type}-sticker`);
        const services = document.getElementById(`${type}-services`);
        sticker.style.display = 'inline';
        services.style.display = 'block';

        if (type === 'economy') {
            document.getElementById('continue-economy').style.display = 'block';
        } else if (type === 'vip') {
            document.getElementById('continue-vip').style.display = 'block';
        }

        setTimeout(() => {
            sticker.style.opacity = '0';
            setTimeout(() => {
                sticker.style.display = 'none';
                sticker.style.opacity = '1';
            }, 1000);
        }, 3000);
    }

    function showPaymentInfo(type) {
        document.getElementById(`payment-${type}`).style.display = 'block';
        document.querySelector(`#payment-${type} .payment-button`).style.display = 'inline';
    }
</script>

</body>
</html>
- 👋 Hi, I’m @night1295
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
night1295/night1295 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
