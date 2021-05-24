<div dir="rtl" text-align='right'>

[لیست تسک‌های مرتبط با این فاز به صورت issue template](./issue-Phase03.md)

## آشنایی با log managment
در این فاز به یادگیری مفاهیم مرتبط با log و log managment میپردازیم و با ابزارهایی مثل elastic search  و  logstash  و kibana آشنا خواهیم شد

پس از آن با kafkaکار خواهیم کرد  و با مفاهیم producer , consumer  در کافکا آشنا خواهیم شد.

 1. در مورد مفاهیم زیر جتسجو کنید
    - لاگ چیست
    - لاگ چه اهیمیتی دارد
    - برای بررسی لاگ از چه ابزار هایی استفاده می شود؟


 1. تولید لاگ
    - انواع لاگ های معمول وساختار آن ها

 1. فایل بیت
    - فایل بیت چیست؟
    - نحوه نصب فایل بیت
    - کانفیگ کردن فایل بیت:
        - انواع ورودی فایل بیت
        - انواع خروجی فایل بیت
    - راه اندازی فایل بیت
    - عیب یابی فایل بیت
    #### پروژه بخش فایل بیت
    1. نصب فایل بیت
    1. کانفیگ فایل بیت (ورودی رو بگیر و بزن به خروجی مختلف)
    1. راه اندازی
    
    












1. بریم swift نصب کنیم :wink:
    سیستم عامل شما ubuntu 18.04 
    > :warning: حواستون باشه ورژنی که نصب میکنید حتما ussuri باشه (برای اینکار باید repository ورژن ussuri رو به apt اضافه کنید)

    مشخصات نصب:  
    نصب پراکسی با tempauth
    نصب account Contaienr v Object server
    ساخت ring با  Replication 3 برای object و ریپلیکای 1 برای اکانت کانتینر
    integrate swift with keystone
    نصب Object Expirer
    
# بیشتر بخونیم :
  - در مورد مفاهیم object storage و file storage  و block storage  مطالعه کنید. چه تفاوت های دارند؟
  - تفاوت swift  به عنوان یک  object storage   و mysql  به عنوان یک sql database و یا elastic به عنوان یک nosql در چیست ؟
  - انواع object storage  ها و block storage ها را نام ببرید. (به صورت دقیقتر  object storage systems and block storage systems)
    تفاوت ceph , swift
</div>
