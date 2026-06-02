# Web-Scraping-Framework-MM

GitHub ပေါ်မှာ Link Extractor အနေနဲ့ တိုက်ရိုက်ဖြစ်စေ၊ Web Scraping Project တွေရဲ့ အစိတ်အပိုင်းအနေနဲ့ဖြစ်စေ လူသုံးအများဆုံး Public Repository တွေနဲ့ Tools တွေကို အောက်ပါအတိုင်း စာရင်းပြုစုပေးလိုက်ပါတယ်။ ဤစာရင်းတွင် "Link ဆွဲထုတ်ခြင်း" ဆိုသည်မှာ သင် Colab မှာ လုပ်ခဲ့သည့် `<a href>` tag များကို ရှာဖွေထုတ်ယူသည့် လုပ်ဆောင်ချက်ကို အခြေခံထားပါသည်။

---

### ၁။ Scrapy (အကြီးကျယ်ဆုံး Web Scraping Framework)
**GitHub:** `scrapy/scrapy` (⭐ ~52k)  
**ဘာကြောင့်လူသုံးများလဲ:** Python ၏ နံပါတ် ၁ Web Scraping Framework ဖြစ်ပြီး `LinkExtractor` ဆိုသည့် built-in class ပါဝင်ပါသည်။ ဤ class သည် link များကို အလိုအလျောက်ဆွဲထုတ်ပေးရုံသာမက filter လုပ်ခြင်း၊ follow လုပ်ခြင်းတို့ပါ လုပ်ဆောင်နိုင်ပြီး Web Crawling လုပ်ငန်းစဉ်အတွက် အသင့်တော်ဆုံးဖြစ်သည်။  
**သုံးပုံ:** `scrapy.linkextractors.LinkExtractor` ကို အသုံးပြုပြီး မိမိလိုချင်သော pattern နှင့် ကိုက်ညီသည့် link များကို စစ်ထုတ်နိုင်သည်။

### ၂။ Requests-HTML
**GitHub:** `psf/requests-html` (⭐ ~13k)  
**ဘာကြောင့်လူသုံးများလဲ:** `requests` နှင့် `BeautifulSoup` ကို ပိုမိုလွယ်ကူအောင် ပေါင်းစပ်ထားသည့် Python library တစ်ခုဖြစ်သည်။ `page.links` ဆိုသည့် method တစ်ခုတည်းဖြင့် စာမျက်နှာပေါ်ရှိ link အားလုံးကို တစ်ကြောင်းတည်းဖြင့် ဆွဲထုတ်နိုင်သောကြောင့် ရိုးရှင်းသော link extraction အတွက် အလွန်အသုံးများသည်။  
**သုံးပုံ:** `r.html.links` ဟုခေါ်ရုံဖြင့် link စာရင်း (set) ကိုရရှိသည်။

### ၃။ BeautifulSoup + Requests (အခြေခံ စံနမူနာ)
**GitHub:** Official repo (Launchpad) / GitHub mirror `wention/BeautifulSoup4`  
**ဘာကြောင့်လူသုံးများလဲ:** သင်အသုံးပြုခဲ့သည့် နည်းလမ်းဖြစ်ပြီး ကမ္ဘာပေါ်တွင် အသုံးအများဆုံး link scraping အတွက် **template** ဖြစ်သည်။ GitHub ပေါ်တွင် `find_all('a', href=True)` ကိုသုံးထားသော script ငယ်ပေါင်း သောင်းချီရှိသည်။ တရားဝင် repo တစ်ခုတည်းထက် tutorial များနှင့် gist များတွင် ပျံ့နှံ့နေသည့် ပုံစံဖြစ်သည်။  

### ၄။ Selenium (Dynamic Website များအတွက်)
**GitHub:** `SeleniumHQ/selenium` (⭐ ~30k)  
**ဘာကြောင့်လူသုံးများလဲ:** JavaScript ဖြင့် link များကို dynamically ဖန်တီးသည့် website များ (React, Angular) အတွက် မရှိမဖြစ် tool ဖြစ်သည်။ Browser တစ်ခုကို အလိုအလျောက်ထိန်းချုပ်ပြီး link များကို ရှာဖွေနိုင်သောကြောင့် သာမန် `requests` ဖြင့် မရသော link များကို ဆွဲထုတ်ရာတွင် ထိပ်တန်းရွေးချယ်မှုဖြစ်သည်။  
**သုံးပုံ:** `driver.find_elements(By.TAG_NAME, "a")`

### ၅။ Playwright (Microsoft မှ ခေတ်မီသော Browser Automation)
**GitHub:** `microsoft/playwright-python` (⭐ ~12k)  
**ဘာကြောင့်လူသုံးများလဲ:** Selenium နှင့် အလားတူဖြစ်သော်လည်း ပိုမိုမြန်ဆန်၍ ခေတ်မီသော API ပါဝင်သည်။ Link extraction အတွက် `page.locator('a').all()` ဖြင့် link အားလုံးကို အလွယ်တကူဆွဲထုတ်နိုင်သည်။ လက်ရှိတွင် developer များစွာ ပြောင်းလဲအသုံးပြုလာကြသည်။  

---

### 💡 အခြား မှတ်သားဖွယ် Repository ငယ်များနှင့် Tools များ
- **link-extractor (PyPI package):** GitHub တွင် `python-link-extractor` ဟူသော ရိုးရှင်းသည့် repo အနည်းငယ်ရှိပြီး သတ်မှတ်ထားသော URL မှ link များကို တစ်ကြောင်းတည်းဖြင့် ဆွဲထုတ်ပေးသည်။ (ကြယ်ပွင့် ရာဂဏန်းခန့်သာရှိသော်လည်း beginner project အဖြစ် လေ့လာရန် ကောင်းသည်။)
- **Link Grabber (browser extension):** GitHub တွင် source code ထုတ်ပေးထားသော Firefox/Chrome extension များဖြစ်သည်။ (ဥပမာ - `link-grabber`) ၎င်းတို့ကိုသုံးပါက Python code မလိုဘဲ click တစ်ချက်ဖြင့် link အားလုံးကို CSV ထုတ်နိုင်သည်။

---

**အကျဉ်းချုပ်**  
သင် Colab မှာ ရေးခဲ့သည့် code သည် အထက်ဖော်ပြပါ **Requests-HTML နှင့် BeautifulSoup တွဲသုံးနည်း** ၏ ဂန္တဝင်ပုံစံအတိုင်းဖြစ်ပြီး ကမ္ဘာပေါ်တွင် အသုံးအများဆုံး link scraping template ဖြစ်ပါသည်။ ပိုမိုကြီးမားသော project များ သို့မဟုတ် dynamic site များအတွက်ဆိုလျှင် **Scrapy** သို့မဟုတ် **Selenium/Playwright** ကို developer အများစုက အားထားအသုံးပြုကြပါသည်။
