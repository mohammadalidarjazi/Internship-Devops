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
    یک موتور جستجو مبتنی بر پایگاه داده غیر رابطه ای است که در لاگ منیجمنت به عنوان انباره داده برای ذخیره و جستجو لاگ ها بکار برده میشود
    - elastic search چیست؟
    - نحوه نصب elastic search
    - کانفیگ کردن یک کلاستر و نود در elastic search:
        - مفهوم کلاستر و node در الستیک سرچ
        - انواع node
        - دیگر تنظیمات
    - راه اندازی elsastic search
    - عیب یابی elsastic search 
  

 1. kibana
     ابزاری است که برای مدیریت، پایش، جستجو و ویژالایز کردن الستیک سرج استفاده میشود
    - kibana چیست؟
    - نحوه نصب kibana
    - کانفیگ کردن kibana:
        - اتصال به الستیک سرچ
        - تنظیم ip و port
    - راه اندازی kibana
    - عیب یابی kibana
    - مشاهده ی interface kibana
    - آشنایی با بخش های مختلف kibana و چگونگی سرچ، ساخت داشبورد و ...
  


 1. logstash
     یک ابزار ETL است که در پشته لاگ منیجمنت برای پردازش لاگ ها استفاده می شود
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
   
 1. filebeat
     یک ابزار جمع آوری لاگ است.
    - filebeat چیست؟
    - نحوه نصب filebeat
    - کانفیگ کردن filebeat:
        - انواع ورودی filebeat
        - انواع خروجی filebeat
    - راه اندازی filebeat
    - عیب یابی filebeat

# Kafka

کافکا یک ابزار مدیریت صف است که از آن می توان در پشته مدیریت لاگ برای افزایش پایداری استفاده کرد

 1. kafka
    - kafka چیست؟
    - نحوه نصب kafka
    - کانفیگ کردن kafka:
        - مفهوم topic producer و consumer و zookeeper
        - ورودی kafka
        - ساخت topic producer و consumer
        - خروجی های kafka
    - راه اندازی kafka
    - عیب یابی kafka


