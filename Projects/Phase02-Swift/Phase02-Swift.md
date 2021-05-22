



<div dir="rtl" text-align='right'>

[لیست تسک‌های مرتبط با این فاز به صورت issue template](./issue-Phase02.md)

## آشنایی با object sotorage swift
    -    سرویس swift چیست؟ ورژن های مختلف آن.
    -   معماری طراحی  swift به چه شکل است؟
    - سرویس keystone چیست؟

 1. مفاهیم زیر که مرتبط با swift هستند را توضیح دهید
    - Proxy Server
    - Object Server
    - Account
    - Account
    - Account
    - Container
    - Object
    - Replicatioan & Rsync
    - Ring
    - Storage Policy
    - Middleware & Pipeline
    - TempAuth vs KeystoneAuth
    - TempUrl
    - Expirer
    - SLO & DLO
    - Recon

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
