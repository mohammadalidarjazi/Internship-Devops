<div dir="rtl" text-align='right'>

[لیست تسک‌های مرتبط با این فاز به صورت issue template](./issue-Phase03.md)

## آشنایی با log managment
در این فاز به یادگیری مفاهیم مرتبط با log و log managment میپردازیم و با ابزارهایی مثل elastic search  و  logstash  و kibana آشنا خواهیم شد

پس از آن با kafka کار خواهیم کرد  و با مفاهیم producer , consumer  در کافکا آشنا خواهیم شد.

 1. در مورد مفاهیم زیر جتسجو کنید
    - لاگ چیست
    - لاگ چه اهیمیتی دارد
    - برای بررسی لاگ از چه ابزار هایی استفاده می شود؟


 1. تولید لاگ
    - انواع لاگ های معمول وساختار آن ها

 1. elsastic search
    - elastic search چیست؟
    - نحوه نصب elastic search
    - کانفیگ کردن یک کلاستر و نود در elastic search:
        - مفهوم کلاستر و node در الستیک سرچ
        - انواع node
        - دیگر تنظیمات
    - راه اندازی elsastic search
    - عیب یابی elsastic search 
    #### پروژه elsastic seach
    1. نصب elsastic seach تک node
    1. طراحی کلاستر در محیط ویژوال
    

 1. kibana
    - kibana چیست؟
    - نحوه نصب kibana
    - کانفیگ کردن kibana:
        - اتصال به الستیک سرچ
        - تنظیم ip و port
    - راه اندازی kibana
    - عیب یابی kibana
    - مشاهده ی interface kibana
    - آشنایی با بخش های مختلف kibana و چگونگی سرچ، ساخت داشبورد و ...
    #### پروژه kibana
    1. ساخت داشبورد های مختلف با سناریو های مختلف    



 1. logstash
    - logstash چیست؟
    - نحوه نصب logstash
    - کانفیگ کردن logstash:
        - ساخت یک فایل .conf
        - ورودی های logstash
        - فیلترهای logstash(Grok)
        - خروجی های logstash
        - pipeline logstash
    - راه اندازی logstash
    - عیب یابی logstash 
    #### پروژه logstash
    1. نصب logstash
    1. ساخت یک فایل .conf
    1. یادگیری فیلتر grock
    1. نوشتن یک فیلترصحیح برای یک نمونه لاگ
    1. استفاده از دو فایل در غالب یک پایپلاین

 1. filebeat
    - filebeat چیست؟
    - نحوه نصب filebeat
    - کانفیگ کردن filebeat:
        - انواع ورودی filebeat
        - انواع خروجی filebeat
    - راه اندازی filebeat
    - عیب یابی filebeat
    #### پروژه بخش filebeat
    1. نصب filebeat
    1. کانفیگ filebeat (ورودی رو بگیر و بزن به خروجی مختلف)
    1. راه اندازی



    

# Kafka

اگر بخوایم در میانه استک یک صف داده داشته باشیم تا در صورت اتفاق غیر مترقبه به دیتا دسترسی داشته باشیم از kafka استفاده می‌شود


 1. kafka
    - kafka چیست؟
    - نحوه نصب kafka
    - کانفیگ کردن kafka:
        - مفهوم topic producer و کانسیومر و zookeeper
        - ورودی کافک
        - ساخت تاپیک، producer و consumer
        - خروجی های کافکا
    - راه اندازی کافکا
    - عیب یابی کافکا
    - مشاهده ی اینترفیس کیبانا
    - آشنایی با بخش های مختلف کیبانا و چگونگی سرچ، ساخت داشبورد و ...
    #### پروژه KAFKA
    1. راه اندازی یک کلاستر تک نود کافکا
    1. ساخت یک تاپیک پرودیوسر و کانسیومر
    1. دادن اطلاعات به تاپیک و خواندن ان 




