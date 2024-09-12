<div dir="rtl" align="right">

<h1 align="center" style="border-bottom: none">
    <b>
        <a href="https://www.nocodb.com">NocoDB </a><br>
    </b>
    ✨ جایگزین متن‌باز Airtable ✨ <br>

</h1>

<p align="center">
هر MySQL، PostgreSQL، SQL Server، SQLite و Mariadb را به یک صفحه گسترده هوشمند تبدیل کنید.
</p>

<div align="center">
 
[![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.com/github/NocoDB/NocoDB) 
[![Node version](https://img.shields.io/badge/node-%3E%3D%2014.18.0-brightgreen)](http://nodejs.org/download/)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-green.svg)](https://conventionalcommits.org)


</div>

<p align="center">
    <a href="http://www.nocodb.com"><b>وب‌سایت</b></a> •
    <a href="https://discord.gg/5RgZmkW"><b>دیسکورد</b></a> •
    <a href="https://twitter.com/nocodb"><b>توییتر</b></a> •
    <a href="https://www.reddit.com/r/NocoDB/"><b>ردیت</b></a> •
    <a href="https://docs.nocodb.com/"><b>مستندات</b></a>
</p>  


![OpenSourceAirtableAlternative](https://user-images.githubusercontent.com/5435402/133762127-e94da292-a1c3-4458-b09a-02cd5b57be53.png)

<img src="https://static.scarf.sh/a.png?x-pxid=c12a77cc-855e-4602-8a0f-614b2d0da56a" />

<p align="center">
  <a href="https://www.producthunt.com/posts/nocodb?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-nocodb" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=297536&theme=dark" alt="NocoDB - جایگزین متن‌باز Airtable | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>
</p>


# به سرعت امتحان کنید

### با استفاده از Docker
<div dir="ltr" align="left">
  
```bash

docker run -d --name nocodb -p 8080:8080 nocodb/nocodb:latest

```
</div>

نرم‌افزار NocoDB نیاز به یک پایگاه داده ورودی دارد: به [تنظیمات تولید](https://github.com/nocodb/nocodb/blob/master/README.md#production-setup) مراجعه کنید.
اگر این ورودی ارائه نشود، ما از SQLite استفاده خواهیم کرد. برای حفظ Sqlite می‌توانید `/usr/app/data/` را وارد کنید. 

  مثال:

<div dir="ltr" align="left">
  
  ```

  docker run -d -p 8080:8080 --name nocodb -v "$(pwd)"/nocodb:/usr/app/data/ nocodb/nocodb:latest

  ```
</div>




> جهت حفظ داده‌ها، می‌توانید حجم را در `/usr/app/data/` نصب کنید.

 ### با استفاده از git

<div dir="ltr" align="left">
  
```

git clone https://github.com/nocodb/nocodb-seed
cd nocodb-seed
npm install
npm start

```
</div>

### رابط کاربری گرافیکی

دسترسی به داشبورد با استفاده از: [http://localhost:8080/dashboard](http://localhost:8080/dashboard)


# به جامعه ما بپیوندید
<a href="https://discord.gg/5RgZmkW">
<img src="https://discordapp.com/api/guilds/661905455894888490/widget.png?style=banner3" alt="">
</a>
<br>
<br>

# تصاویر

![1](https://user-images.githubusercontent.com/86527202/136067515-bafd7adb-3d2e-4754-8b74-6c57d1b04f8f.png)
<br>

![2](https://user-images.githubusercontent.com/86527202/136067525-e5a1efa2-89f1-47ff-96d0-02277918a06f.png)
<br>

![5](https://user-images.githubusercontent.com/86527202/136067548-417c2c79-bd25-4285-8f00-5aed432a8f9e.png)
<br>

![6](https://user-images.githubusercontent.com/86527202/136067552-8f92faae-fb77-45bb-9623-ef0958d36d99.png)
<br>

![7](https://user-images.githubusercontent.com/86527202/136067564-16506f90-6e6c-44fb-9d51-385f68f4c815.png)
<br>

![8](https://user-images.githubusercontent.com/86527202/136067570-cced6754-014d-4d3d-95e8-419a2d4c6b61.png)
<br>

![9](https://user-images.githubusercontent.com/86527202/136067579-4709a787-8649-4d5d-8318-0f867e80a2f3.png)
<br>

![9a](https://user-images.githubusercontent.com/86527202/136067581-f6887c21-4daa-44c8-aaac-9408bb29858c.png)
<br>

![9b](https://user-images.githubusercontent.com/86527202/136067584-cfd45081-79f3-44e1-979f-1408c9f1aee5.png)
<br>

![10](https://user-images.githubusercontent.com/86527202/136067590-95ba64fd-3dfb-4d0b-9a6f-8906128f0455.png)
<br>

![11](https://user-images.githubusercontent.com/86527202/136067593-dcf7d768-4f4e-4841-8384-629a35daa356.png)
<br>

# ویژگی‌ها
### رابط صفحه گسترده غنی

- ⚡ جستجو، مرتب‌سازی، فیلتر کردن، پنهان کردن ستون‌ها به راحتی
- ⚡ ایجاد نماها: شبکه، گالری، کانبان، فرم
- ⚡ اشتراک‌گذاری نماها: عمومی یا محافظت شده با رمز عبور 
- ⚡ نماهای شخصی و قفل شده 
- ⚡ بارگذاری تصاویر به سلول‌ها (با S3، Minio، GCP، Azure، DigitalOcean، Linode، OVH، Backblaze کار می‌کند) !!
- ⚡ نقش‌ها: مالک، سازنده، ویرایشگر، نظردهنده، بیننده، نظردهنده، نقش‌های سفارشی.
- ⚡ کنترل دسترسی: کنترل دسترسی دانه‌ای حتی در سطح پایگاه داده، جدول و ستون.

### فروشگاه برنامه برای اتوماسیون گردش کار

ما ادغام‌های مختلفی را در سه دسته اصلی ارائه می‌دهیم. برای جزئیات بیشتر به <a href="https://docs.nocodb.com/setup-and-usages/app-store" target="_blank">فروشگاه برنامه</a> مراجعه کنید.

- ⚡ چت: Slack، Discord، Mattermost، Microsoft Teams، WhatsApp و غیره
- ⚡ ایمیل: AWS SES، SMTP، MailerSend و غیره
- ⚡ پیامک: Twilio
- ⚡ ذخیره‌سازی: AWS S3، Google Cloud Storage، Minio و غیره

### دسترسی به API از طریق

ما روش‌های زیر را برای اجازه دادن به کاربران برای فراخوانی اقدامات به صورت برنامه‌ای ارائه می‌دهیم. می‌توانید از یک توکن (JWT یا احراز هویت اجتماعی) برای اعتبارسنجی درخواست‌های مجوز خود به NocoDB استفاده کنید. 

- ⚡ REST API
- ⚡ NocoDB SDK

# پیکربندی پروداکشن 
نرم‌افزار NocoDB نیاز به یک پایگاه داده برای ذخیره متادیتای نماهای صفحه گسترده و پایگاه‌های داده خارجی دارد. و تنظیمات اتصال برای این پایگاه داده را می‌توان در متغیر محیطی `NC_DB` مشخص کرد. 

## Docker 


#### مثال Postgres
<div dir="ltr" align="left">

```

docker run -d -p 8080:8080 \
    -e NC_DB="pg://host:port?u=user&p=password&d=database" \
    -e NC_AUTH_JWT_SECRET="569a1821-0a93-45e8-87ab-eb857f20a010" \
    nocodb/nocodb:latest

```
</div>

## Docker Compose
<div dir="ltr" align="left">

```

git clone https://github.com/nocodb/nocodb
cd nocodb
cd docker-compose
cd pg 
docker-compose up -d

```
</div>

## متغیرهای محیطی

لطفاً به [متغیرهای محیطی](https://docs.nocodb.com/getting-started/self-hosted/environment-variables) مراجعه کنید.

# تنظیمات توسعه‌دهندگان

لطفاً به [تنظیمات توسعه‌دهندگان](https://docs.nocodb.com/engineering/development-setup) مراجعه کنید.

# مشارکت در پروژه

لطفاً به [راهنمای مشارکت](https://github.com/nocodb/nocodb/blob/master/.github/CONTRIBUTING.md) مراجعه کنید.

# چرا ما این را می‌سازیم؟
اکثر شرکت‌های اینترنتی خود را با یک صفحه گسترده یا پایگاه داده برای رفع نیازهای تجاری خود مجهز می‌کنند. صفحات گسترده توسط بیش از یک میلیارد انسان به صورت مشارکتی هر روز استفاده می‌شوند. با این حال، ما از کار کردن با سرعت‌های مشابه روی پایگاه‌های داده که ابزارهای بسیار قدرتمندتری برای محاسبات هستند، بسیار دور هستیم. تلاش‌ها برای حل این مشکل با ارائه‌های SaaS منجر به کنترل دسترسی وحشتناک، قفل فروشنده، قفل داده، تغییرات قیمت ناگهانی و مهم‌تر از همه، سقف شیشه‌ای برای آنچه در آینده ممکن است، شده است.

# ماموریت ما
ماموریت ما ارائه قدرتمندترین رابط بدون کد برای پایگاه‌های داده است که برای هر شرکت اینترنتی در جهان متن باز باشد. این نه تنها دسترسی به یک ابزار محاسباتی قدرتمند را دموکراتیزه می‌کند، بلکه ظهور بیش از یک میلیارد نفر را که توانایی‌های رادیکال برای سرهم‌بندی و ساخت روی اینترنت خواهند داشت، به همراه خواهد داشت.

</div>
