<div dir="rtl">
    <h1>خروجی‌ها</h1>
    <p><span style="color: #999999;">دسته‌های جدید از بیت‌کوین که تو تراکنش ساخته شدن.</span></p>
    <h2>فهرست</h2>
        <hr>
    <ul>
        <li>
            <p><a href="#1">تراکنش 1 – یه تراکنش ساده</a></p>
        </li>
        <li>
            <p><a href="#2">تراکنش 2 – استفاده از خروجی به عنوان ورودی</a></p>
        </li>
        <li>
            <p><a href="#3">تراکنش 3 – کارمزدهای تراکنش</a></p>
        </li>
    </ul>
    <hr>
    <hr>
    <p><strong>سیستم تراکنش بیت‌کوین در بر گیرنده‌ی فرستادن و دریافت دسته‌هایی از بیت‌کوین است که به نام خروجی می‌شناسیم</strong>.</p>
    <br><br>
    <p>می‌شه یه چیزایی فهمید؛ ولی تنها راهی که بفهمیم چی به چیه اینه که  به چندتا مثال نگاه کنیم.</p>
    <br>
    <h2 id="1">تراکنش 1 – یه تراکنش ساده</h2>
    <p>بذار داستان تراکنش رو با تولد یه دسته بیت‌کوین جدید شروع کنیم...
    </p>
    <p>
    فرض کن یه استخراج کننده‌ی بیت‌کوینی، بر اساس کاری که انجام دادی موفق شدی یه بلوک از تراکنش‌ها رو حل کنی و یه دسته بیت‌کوینِ 25تایی رو بدست آورده‌ای.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/00-generation-transaction.png"><br><br>
    <p style="color: #999999; text-align: center; ">هر استخراج‌کننده‌‌ای (ماینر) آدرس خودش رو بالای هر بلوک قرار می‌ده که اگه موفق به حل بلوک بشه پاداش بیت‌کوین به این آدرس فرستاده بشه. به این تراکنش می‌گیم تراکنشِ ساخت.
    </p>
    <p>پس وضعیت فعلی آدرس بیت‌کوین تو این شد:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/01-transaction1-before.png"><br><br>
    <p>به طور طبیعی می‌خوای جشن بگیری و نوشیدنی‌ای بر بدن بزنی.
    </p>
    <blockquote>
     شایدم پولت اضافه بیاد و هوس از دست دادنش
        به سرت زد و ریختی تو سایت‌های پانزی و اسکم !
    </blockquote>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/01-beer.png"><br><br>
    <p> اولین چیزی که به ذهنت می‌رسه اینه که 1 دونه از اون دسته 25تایی بیت‌کوین رو برداری و خرج نوشیدنی رو بدی، منطقیه، ولی تراکنش اینطوری کار نمی‌کنه.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/01-transaction1-chip.png"><br><br>
    <p>بجاش باید 
    <strong>کل دسته‌ی 25 بیت‌کوین</strong>
     رو تو تراکنش بفرستیم.</p>
    <p>اما برای اینکه مطمئن باشیم کل 25 بیت‌کوین رو نمی‌خوایم برای پرداخت قیمت 1 بیت‌کوین خرج کنیم. 
    <strong>دسته رو تقسیم می‌کنیم</strong>
     به 2 مقصد مجزا:</p>
    <ol>
        <li>(پرداخت)نوشیدنی‌فروشی</li>
        <li>باز به آدرس خودمون (باقی پول)</li>
    </ol>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/01-transaction1.png">
    <p style="color: #999999; text-align: center; ">به دسته‌های تازه ساخته شده می‌گیم خروجی.</p>
    <br><br>
    <p>درسته اینجا در ظاهر یه لقمه رو دور سر خودمون چرخوندیم ولی در نهایت نتیجه یکسانه 
    </p>
    <blockquote>
        <p> دلیل اینکه به این صورت این تراکنش‌ها انجام می‌گیره اینه که از چشم‌انداز برنامه‌نویسی، ساده‌تر و امن‌تره.</p>
    </blockquote>
    <p>
بگذریم! در شکل زیر می‌بینیم که آدرس‌های بیت‌کوین بعد از تراکنش  به چه شکل درمیان:
    </p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/01-transaction1-after.png"><br><br>
    <p style="color: #999999; text-align: center; "> نوشیدنی‌فروشی، یه دسته جدید 1 بیت‌کوینی داره، به خودمونم دسته 24 بیت‌کوینی فرستادیم. اون دسته‌ی 25تایی الان دیگه مصرف شده رفته.</p>
    <p>پس درسته که بنظر میاد 1 بیت‌کوین رو از حسابمون برداشتیم و به یه آدرس دیگه فرستادیم... ولی الان می‌دونیم واقعا چی شد.</p>
    <br>
    <blockquote>
    <h4 id="">خلاصه:</h4>
    <p>سازوکار تراکنش بیت‌کوین اینطور طراحی شده:</p>
    <ol>
        <li>برداشتن یک خروجی (دسته بیت‌کوین) که از قبل وجود داره</li><br>
        <li>ایجاد کردن خروجی‌ها (دسته‌ها) با مقدار جدید</li><br>
        <li>فرستادن این دسته‌های جدید به آدرس‌ها</li>
    </ol>
    </blockquote>
    <br>
    <h2 id="2">
        تراکنش 2 – استفاده از خروجی به عنوان ورودی
    </h2>
    <p> از این به بعد بجای استفاده از کلمه‌ی «دسته» از «خروجی» استفاده می‌کنیم. </p>
    <p>چند روز گذشته و نوشیدنی‌فروشی‌ای که مشتریش بودیم، با توجه به آدرسش، نونش تو روغن بوده:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/02-transaction2-before.png">
    <br><br>
    <p>اما همانطور که می‌دونیم، نوشیدنی از رو درخت در نمیاد، پس نوشیدنی‌فروشمون الان دنبال خرید دستگاه نوشیدنی‌ساز جدیده.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/02-beer-machine.png"><br><br>
    <p>چه نوشیدنی‌ساز دوست داشتنی‌ای، با قیمت مفت 4.2 بیت‌کوین.
    </p><p>بخریمش.</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/02-transaction2.png">
    <p style="color: #999999; text-align: center; ">ساخت تراکنش برای دستگاه نوشیدنی‌ساز. </p><br><br>
    <p> فکر کنم یه خرده شکلش رو شاخ و دم دار کشیدم، ولی خب توضیحش سخت نیست:</p>
    <ol>
        <li>نوشیدنی‌فروشی یه خروجی (دسته) نداره که تنهایی کل 
        <strong>4.2</strong>
         قیمت دستگاه ( مقدار بیت‌کوین) رو پوشش بده. پس باید یه مشت دسته رو کنار هم بگذاریم که در نهایت جمعش از 4.2 بیت‌کوین بیشتر بشه.</li><br>
        <li>زمانی که ما یه تراکنش رو می‌سازیم، خروجی‌هایی که برمی‌داریم که خرج کنیم رو می‌گیم «ورودی» تراکنش.</li>
        <br>
        <blockquote> وقتی یه خروجی رو تو تراکنش استفاده می‌کنی بطور موقت بهش  می‌گن «ورودی» .</blockquote>
        <br>
        <li>نوشیدنی‌فروشی، با مجموع ورودی
         <strong>4.5</strong>
         ، دو خروجی جدید 
         <strong>4.2</strong>
          و 
          <strong>0.3</strong>
           ایجاد می‌کنه.</li>
    </ol>
    <p>بعد از این تراکنش، وضع آدرس نوشیدنی‌فروشی اینطوریه:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/02-transaction2-after.png"><br><br>
    <p>دوباره توجه کن که خروجی‌هایی که به عنوان ورودی ازشون استفاده کردیم
    <strong> خرج شدن!</strong>
     و دیگه نمی‌شه ازشون استفاده کرد.</p>
    <p>ولی هنوز اون خروجی‌های هنوز
    <strong> «خرج نشده»</strong> 
    قابل استفاده‌اند. بهشون می‌گیم خروجی تراکنش‌های خرج نشده (UTXOs).</p>
    <br><strong>مقدار کل تعداد بیت‌کوین‌های داخل یه حساب برابر هست با مجموع کل UTXOs ‌های حساب.</strong>
    <br>
    <blockquote>
    <p> خروجی‌های [1] + [2] + [0.5] + [1] رو برای ورودی تراکنش انتخاب کردیم. اما  تا زمانی که روی هم رفته بیشتر از مقداری باشن که می‌خواهیم بفرستیم، هر ترکیبی بخوایم می‌تونیم از این خروجی‌ها (یا به زبون بهتر ورودی‌ها) انتخاب کنیم!</p>
    <p dir="ltr">
        [1] + [3] + [0.5] = 4.5 <br><br> [3] + [2] = 5 <br><br> [1] + [3] + [0.5] + [2] + [1] = 7.5
    </p>
    <p>همه اینها شدنی‌اند، خودت می‌تونی باقی پول هر ترکیب رو حساب کنی.</p>
    </blockquote>
        <br>
    <h2 id="3">تراکنش 3 – کارمزدهای تراکنش</h2>
    <p>عه، راستی! تو دوتا تراکنش قبلی کارمزد تراکنش نذاشتیم.</p>
    <p>بدون کارمزد تراکنش،اینکه تراکنش‌هات برن تو بلوک طول می‌کشه، کارمزد، نقشش اینه که به تراکنشت اولویت بده.</p>
    <blockquote>
    کارمزد تراکنش زمان استخراج بلوک به جیب استخراج‌کننده می‌ره، پس کارمزد انگیزه‌ایه که به استخراج‌کننده‌ می‌دی که
     تراکنش رو داخل بلوکی که استخراج می‌کنه بزاره.
     </blockquote>
     <br>
<blockquote>
زمانی که این متن نوشته شده اینطوری بود که چون بلوک‌ها پر پر نمی‌شد، استخراج‌کننده‌ها مرامی تراکنش بی‌کارمزد هم بعضی وقت‌ها تو بلوکشون می‌ذاشتن. الان دیگه این خبرا نیست و تراکنش بی‌کارمزد نه تو بلوک قرار می‌گیره، نه حتی تو شبکه پخش می‌شه و به‌دست استخراج‌کننده می‌رسه.
</blockquote>
<br>
    <p>فرض کن تراکنش آخری رو تو شبکه نفرستادیم، بیا یه کارمزد بهش اضافه کنیم:</p>
    <br><br><img style="display: block; margin-left: auto; margin-right: auto;" src="./beginners/guide/outputs/03-transaction2-fee.png"><br><br>
    <p>پس خروجیِ کارمزد تراکنش چی شد؟! خروجی کارمزدی درکار نیست ولی به <strong>اندازه‌ی خروجی‌ها</strong> دقت کن.</p>
    <b><strong>مجموع خروجی‌ها کمتر از مجموع ورودی‌هاست، یعنی مقداری بیت‌کوین مونده که مصرف نشده. این مقدار «باقی مونده» کارمزد تراکنشه.</strong></p>
    <blockquote>
    مبلغ باقی‌مونده‌ی تراکنش (ورودی‌ها – خروجی‌ها) همیشه توسط استخراج‌کننده‌ برداشته می‌شه، پس اگه یه تراکنش دستی ایجاد کنی و فراموش کنی داخلش یه خروجی برای باقی پولت بذاری، استخراج‌کننده‌ اون باقی پول (هرچقدر که باشه) رو برای
        خودش برمی‌داره.</blockquote>
    <p><a href="https://learnmeabitcoin.com/beginners/outputs">منبع</a></p>
    <p>و اینجا آخر این قسمته!</p>
    <p>شاد زی..</p>
</div>
