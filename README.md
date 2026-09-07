# Tensorflow-and-Keras
step1:
ابتدا از کد fashion_mnist شروع کن که در داخلش با استفاده از sequential API مدل را تعریف کردم
step 2:
پس از اینکه کار با sequential API تموم شدش، سراغ کد california_housing برو تا با Functianal APi آشنا شوی 
Step 3:
در کد california_housing_subclassingAPI با استاده از subClassingAPi همان کد که با functial API زده شده رو به subclassing API تغییر داده که از انعطاف پذیری بالایی برخوردار هستش ولی keras دسترسی کاملی به مدل ندارد و توصیه میشود بیشتر از functianl API استفاده شود تا keras بتواند به شکل بهتری از مدل برسد چون در subclassing API قدم به قدم keras لایه لایه و نحوه اتصال لایه ها رو داشته باشد و در آخر لایه ها رو دریافت میکند بدون اطلاعات از نحوه اتصال آن ها ولی در Functial API به صورت لایه به لایه همراه با مدل که درحال ساخت هستش دریافت کرده و اطلاعات نحوه اتصال رو نیز دارد و در هر فدم اطلاعات رو ذخیره میکند 
** در پروژ] بهتر از نمای کلی رو با Functial API زدش یعنی قسمت ساخت مدل و در قسمت جزعیات آن مثل حلقه یا دستور شرطی داخل لایه ها رو با subclassing API زدش.
