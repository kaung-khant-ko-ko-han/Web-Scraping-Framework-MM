# Web-Scraping-Framework-MM

ခင်ဗျားရဲ့ စာရင်းက လက်တွေ့ကျပြီး အနှစ်ချုပ်လှပါတယ်။ အခုဆောင်းပါးမှာ ခင်ဗျားပေးထားတဲ့ Tools တွေရဲ့ လတ်တလော **GitHub Star အရေအတွက်**တွေ၊ **အသုံးပြုပုံ**တွေနဲ့အတူ၊ အသေးစား၊ အလတ်စား Project တွေအတွက် စိတ်ဝင်စားဖို့ကောင်းမယ့် အခြား Link Extraction Tools တချို့ကိုလည်း ထည့်သွင်းဖော်ပြပေးလိုက်ပါတယ်။

---

### ၁။ Scrapy (အကြီးကျယ်ဆုံး Web Scraping Framework)
**GitHub Repository:** [scrapy/scrapy](https://github.com/scrapy/scrapy)  
**Star အရေအတွက်:** ⭐ **~62,000** (လက်ရှိတွင် ခန့်မှန်းခြေ 59k-62k ရှိသည်)  
**ဘာသာစကား:** Python  
**အသုံးပြုပုံ:** သင်ကိုယ်တိုင်သုံးပြီးသား `BeautifulSoup` က စာမျက်နှာတစ်ခုချင်းစီအတွက် ပိုသင့်တော်ပါတယ်။ ဒါပေမဲ့ သင်ဟာ Website ကြီးတွေ၊ Crawling လုပ်ငန်းစဉ်တွေ (link တွေလိုက်ပြီး ရှာဖွေခြင်း) လုပ်ချင်တယ်ဆိုရင်တော့ **Scrapy** က ပိုပြီး အဆင်ပြေပါတယ်။ Scrapy မှာ `LinkExtractor` ဆိုတဲ့ built-in class တစ်ခုပါရှိပြီး၊ သင့်အနေနဲ့ `scrapy.linkextractors.LinkExtractor` ကို အသုံးပြုခြင်းအားဖြင့် သင်လိုချင်တဲ့ link ပုံစံ (pattern) မျိုးကိုသာ ရွေးချယ်ထုတ်ယူနိုင်ပါတယ်။  
**လူသုံးများရခြင်း:** Python အတွက် နံပါတ်တစ် Web Scraping Framework ဖြစ်ပြီး၊ အခြား tools များနှင့်မတူဘဲ link extraction, crawling, data extraction, and exporting အားလုံးကို လုပ်ဆောင်နိုင်ပါတယ်။

### ၂။ Requests-HTML
**GitHub Repository:** [psf/requests-html](https://github.com/psf/requests-html)  
**Star အရေအတွက်:** ⭐ **~7,400**  
**ဘာသာစကား:** Python  
**အသုံးပြုပုံ:** သင်က Link တွေကို တစ်ခုတည်းသော Method (`r.html.links`) ဖြင့် ဆွဲထုတ်နိုင်ပါတယ်။ ဒါကြောင့် `BeautifulSoup` နဲ့ လုပ်ရတဲ့ `find_all('a', href=True)` ကုဒ်တွေ မလိုတော့ပါဘူး။  
**လူသုံးများရခြင်း:** `requests` နဲ့ `BeautifulSoup` ကို ပေါင်းစပ်ထားတာဖြစ်လို့ အရမ်းရိုးရှင်းပြီး လွယ်ကူပါတယ်။ သင်လို **ရိုးရိုးရှင်းရှင်း Link ထုတ်ယူဖို့အတွက် အလွန်သင့်တော်ပါတယ်**။

### ၃။ BeautifulSoup (ဂန္တဝင်နည်းလမ်း)
**GitHub Repository:** (မူရင်း Launchpad၊ GitHub mirror [wention/BeautifulSoup4](https://github.com/wention/BeautifulSoup4))  
**Star အရေအတွက်:** ⭐ **~3,500** (မူရင်း repo သေးငယ်သော်လည်း အသုံးပြုသူ အလွန်များပါသည်)  
**ဘာသာစကား:** Python  
**အသုံးပြုပုံ:** သင်သိရှိပြီးသားအတိုင်း `soup.find_all('a', href=True)` ဖြင့် link များကို တွေ့ရှိနိုင်ပါတယ်။  
**လူသုံးများရခြင်း:** ၎င်းသည် သင်လက်ရှိသုံးနေတဲ့ နည်းလမ်းဖြစ်ပြီး၊ ကမ္ဘာပေါ်တွင် **အသုံးအများဆုံး Link Scraping Template** ဖြစ်ပါတယ်။ Github ပေါ်တွင် အသေးစား Script ထောင်ပေါင်းများစွာရဲ့ အခြေခံဖြစ်ပါတယ်။

### ၄။ Selenium (Dynamic Website များအတွက်)
**GitHub Repository:** [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium)  
**Star အရေအတွက်:** ⭐ **~33,550** (လတ်တလော)  
**ဘာသာစကား:** Java / Python bindings အပါအဝင် အခြားဘာသာစကားများ  
**အသုံးပြုပုံ:** `driver.find_elements(By.TAG_NAME, "a")` ဖြင့် link အားလုံးကို ရှာဖွေနိုင်ပါတယ်။  
**လူသုံးများရခြင်း:** **JavaScript ဖြင့် Link များကို Dynamically ဖန်တီးသည့် Website များအတွက်** (ဥပမာ React, Angular) မရှိမဖြစ်လိုအပ်တဲ့ Tool ဖြစ်ပါတယ်။

### ၅။ Playwright (Microsoft မှ ခေတ်မီ Browser Automation)
**GitHub Repository:** [microsoft/playwright-python](https://github.com/microsoft/playwright-python)  
**Star အရေအတွက်:** ⭐ **~12,000**  
**ဘာသာစကား:** Python (အဓိက Project `microsoft/playwright` က TypeScript ဖြင့် ရေးသားထားပြီး Star 81k+ ရှိသည်)  
**အသုံးပြုပုံ:** `page.locator('a').all()` ဖြင့် link အားလုံးကို လွယ်ကူစွာ ထုတ်ယူနိုင်ပါတယ်။  
**လူသုံးများရခြင်း:** Selenium နှင့် အလားတူဖြစ်သော်လည်း **ပိုမိုမြန်ဆန်ပြီး ခေတ်မီသော API** ပါရှိပါတယ်။ လက်ရှိတွင် Developer အများအပြား ပြောင်းလဲအသုံးပြုလာကြသည်။

---

## 💡 အခြားမှတ်သားဖွယ် Link Extraction Repositories

### 📦 အသေးစား၊ အလတ်စား Python Script များ (Dedicated Link Extractors)

- **[Neeraj-Sihag/Website-Link-Harvester](https://github.com/Neeraj-Sihag/Website-Link-Harvester):** ⭐ 47 (ခန့်မှန်း)  
    **အထူးအင်္ဂါရပ်:** ဤ Tool သည် Selenium နှင့် BeautifulSoup ကို ပေါင်းစပ်အသုံးပြုထားပြီး၊ သင့်အား **Internal, External, Subdomain နှင့် Sitemap Link များကို ခွဲခြားသိရှိနိုင်စေပါသည်**။ ၎င်းသည် Link များကို စာရင်းပြုစုရုံသာမက အမျိုးအစားခွဲခြားပေးနိုင်သောကြောင့် ပိုမိုအဆင့်မြင့်သော Analysis အတွက် အသုံးဝင်ပါသည်။

- **[Yokran/AXcraper](https://github.com/Yokran/AXcraper):** ⭐ 24 (ခန့်မှန်း)  
    **အထူးအင်္ဂါရပ်:** **OSINT** (Open Source Intelligence) အတွက် အထူးထုတ်ထားသော Tool ဖြစ်ပြီး၊ Link များကို ထုတ်ယူရုံသာမက ၎င်း Link များမှတဆင့် Website များ၏ Screenshot များကိုပါ အလိုအလျောက်ရိုက်ယူနိုင်ပါသည်။ Bug Bounty သို့မဟုတ် လုံခြုံရေးသုတေသနအတွက် အထူးကောင်းမွန်ပါတယ်။

### 🌐 Browser Extensions (No Code Solution)

အကယ်၍ သင်သည် Python Code မရေးချင်ဘဲ Browser ပေါ်တွင် တစ်ချက်နှိပ်ရုံဖြင့် Link များကို ထုတ်ယူချင်ပါက၊ အောက်ပါ Browser Extensions များကို ထည့်သွင်းစဉ်းစားနိုင်ပါတယ်။ ၎င်းတို့သည် အများအားဖြင့် Open Source ဖြစ်ပြီး GitHub တွင် Source Code ပါရှိပါတယ်။

- **[pxlcrtiv/url-grabber-chrome-extension](https://github.com/pxlcrtiv/url-grabber-chrome-extension):** လက်ရှိ Tab သို့မဟုတ် Tabs အားလုံးမှ URL အမျိုးမျိုး (Links, Images, Videos, etc.) ကို ထုတ်ယူနိုင်ပြီး Regex ဖြင့် စစ်ထုတ်ကာ `.txt` ဖိုင်အဖြစ် Export လုပ်နိုင်ပါတယ်။
- **[skumar54uncc/LinkExtract-Tool](https://github.com/skumar54uncc/LinkExtract-Tool):** မောက်စ်ဖြင့် ဆွဲပြီး (Drag & Select) လုပ်ကာ Link များကို ကောက်ယူနိုင်ပြီး CSV ဖိုင်အဖြစ် Export လုပ်နိုင်ပါတယ်။
- **[sajadspeed/extract-copy-links](https://github.com/sajadspeed/extract-copy-links):** စာမျက်နှာပေါ်ရှိ စာသားတစ်ခုခုကို Highlight လုပ်ပြီး Right-click ချက်ချင်းဖြင့် ၎င်းနေရာရှိ Link များကို တစ်ခါတည်းကူးယူနိုင်ပါတယ်။

---

## အကျဉ်းချုပ်
ခင်ဗျားရဲ့ Colab script သည် **Requests-HTML** နှင့် **BeautifulSoup** တို့ရဲ့ ရောနှောပုံစံဖြစ်ပြီး၊ **Static Website** များအတွက် **အကောင်းဆုံး** ရွေးချယ်မှုဖြစ်ပါတယ်။

- **Dynamic Website (JavaScript-heavy):** Selenium သို့မဟုတ် Playwright ကို သုံးသင့်ပါတယ်။
- **Enterprise/Production အတွက်:** Scrapy ကို သုံးသင့်ပါတယ်။
- **No-code Solution:** အထက်ပါ Browser Extension များကို သုံးနိုင်ပါတယ်။

ခင်ဗျားရဲ့ မူရင်းစာရင်းက လုံးဝမှန်ကန်ပါတယ်။ ဤအချက်အလက်များက Link Extraction အတွက် ရှေ့ဆက်လုပ်ဆောင်ရာတွင် အထောက်အကူဖြစ်စေမယ်လို့ မျှော်လင့်ပါတယ်။


---

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
