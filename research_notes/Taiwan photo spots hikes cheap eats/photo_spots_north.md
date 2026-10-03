# Photo Spots in Northern Taiwan (Taipei, New Taipei, Keelung, Yilan, Taoyuan, Hsinchu, Miaoli) — data for a trip-planner app

> **Research method note for the report writer:** Wikipedia, Wikidata, OpenStreetMap and taiwanobsessed.com were **blocked by the network egress proxy** during this research (both direct API calls and page fetches failed with EGRESS_BLOCKED). So:
> - **No coordinate in these notes was checked against Wikipedia/Wikidata/OSM.** The lat/lon values come from the researcher's background knowledge, rounded to ~3 decimals (about ±100–500 m). They are labelled **"approx., unverified"** and must be geocoded before the app ships. Rows marked "low confidence" may be off by more than 1 km.
> - Wikimedia Commons file URLs listed as "verified" appeared as live pages in search results restricted to commons.wikimedia.org. They were not opened, so the licence and exact framing were not checked.
> - MRT exit numbers are "verified" only where a source states them. All others say "unverified".
> - Research date: 2026-10-03.

## 1. Master list of spots: names, location, approximate coordinates

### Takeaway
There are 34 candidate spots: 19 iconic and 15 hidden gems. They cover Taipei (9), New Taipei (11), Keelung (3), Yilan (4), Taoyuan (4), Hsinchu (1) and Miaoli (2). Every name and district is well established. All coordinates still need geocoding (see method note).

### Cited Findings
Table (EN name | 中文 | city/district | approx. lat, lon (UNVERIFIED) | type)

| # | English name | Traditional Chinese | City / District | Approx. lat, lon (unverified) | Type |
|---|---|---|---|---|---|
| 1 | Taipei 101 (and Observatory) | 台北101 | Taipei / Xinyi | 25.0340, 121.5645 | Iconic |
| 2 | Elephant Mountain (Xiangshan) – Six Giant Rocks viewpoint | 象山 (六巨石) | Taipei / Xinyi | 25.0273, 121.5765 | Iconic |
| 3 | Chiang Kai-shek Memorial Hall & Liberty Square | 中正紀念堂 / 自由廣場 | Taipei / Zhongzheng | 25.0346, 121.5218 | Iconic |
| 4 | Longshan Temple (Mengjia) | 艋舺龍山寺 | Taipei / Wanhua | 25.0371, 121.4999 | Iconic |
| 5 | Dihua Street / Dadaocheng | 迪化街 / 大稻埕 | Taipei / Datong | 25.0565, 121.5100 | Iconic |
| 6 | Ximending | 西門町 | Taipei / Wanhua | 25.0421, 121.5076 | Iconic |
| 7 | Beitou Thermal Valley (Hell Valley) + Beitou Public Library | 北投地熱谷 / 北投圖書館 | Taipei / Beitou | 25.1378, 121.5113 | Iconic |
| 8 | Yangmingshan: Qingtiangang Grassland | 擎天崗 | Taipei / Shilin | 25.1665, 121.5745 | Iconic |
| 9 | Yangmingshan: Zhuzihu calla lily fields | 竹子湖 | Taipei / Beitou | 25.1665, 121.5385 (low confidence) | Seasonal gem |
| 10 | Maokong Gondola & tea fields | 貓空纜車 | Taipei / Wenshan | 24.9686, 121.5885 (Maokong Station) | Iconic |
| 11 | Tamsui Fisherman's Wharf (Lover's Bridge) sunset | 淡水漁人碼頭 (情人橋) | New Taipei / Tamsui | 25.1830, 121.4110 | Iconic |
| 12 | Fort San Domingo | 淡水紅毛城 | New Taipei / Tamsui | 25.1755, 121.4329 | Iconic |
| 13 | Jiufen Old Street / Shuqi Road (A-Mei Teahouse) | 九份老街 / 豎崎路 (阿妹茶樓) | New Taipei / Ruifang | 25.1095, 121.8445 | Iconic |
| 14 | Jinguashi: Gold Museum / Gold Ecological Park | 金瓜石 黃金博物館 | New Taipei / Ruifang | 25.1077, 121.8573 | Iconic |
| 15 | Golden Waterfall | 黃金瀑布 | New Taipei / Ruifang | 25.1172, 121.8640 (low confidence) | Iconic |
| 16 | Yin Yang Sea (Yinyang Sea viewing platform) | 陰陽海 | New Taipei / Ruifang | 25.1224, 121.8640 (low confidence) | Iconic |
| 17 | Shifen Old Street (sky lanterns on the tracks) | 十分老街 | New Taipei / Pingxi | 25.0418, 121.7754 | Iconic |
| 18 | Shifen Waterfall | 十分瀑布 | New Taipei / Pingxi | 25.0477, 121.7870 | Iconic |
| 19 | Houtong Cat Village | 猴硐貓村 | New Taipei / Ruifang | 25.0874, 121.8274 | Iconic / quirky |
| 20 | Sandiaoling Waterfall Trail | 三貂嶺瀑布群步道 | New Taipei / Ruifang | 25.0590, 121.8226 (Sandiaoling Stn) | Hidden gem |
| 21 | Yehliu Geopark (Queen's Head) | 野柳地質公園 (女王頭) | New Taipei / Wanli | 25.2063, 121.6900 | Iconic |
| 22 | Bitou Cape (Bitoujiao) Trail | 鼻頭角步道 | New Taipei / Ruifang | 25.1290, 121.9200 (low confidence) | Hidden gem |
| 23 | Laomei Green Reef | 老梅綠石槽 | New Taipei / Shimen | 25.2900, 121.5390 (low confidence) | Seasonal gem |
| 24 | Zhishanyan Huiji Temple / hill (Shilin) | 芝山岩 惠濟宮 | Taipei / Shilin | 25.1040, 121.5320 (low confidence) | Hidden gem |
| 25 | Wangyou Valley (Badouzi) | 望幽谷 (八斗子) | Keelung / Zhongzheng | 25.1435, 121.7988 (low confidence) | Hidden gem |
| 26 | Keelung Miaokou Night Market (lantern rows) | 基隆廟口夜市 | Keelung / Ren'ai | 25.1282, 121.7432 | Iconic |
| 27 | Heping Island Geopark | 和平島地質公園 | Keelung / Zhongzheng | 25.1597, 121.7650 (low confidence) | Hidden gem |
| 28 | Lanyang Museum | 蘭陽博物館 | Yilan / Toucheng | 24.8689, 121.8323 | Hidden gem / architecture |
| 29 | Taipingshan National Forest Recreation Area (Bong Bong Train, Cuifeng Lake) | 太平山國家森林遊樂區 (蹦蹦車 / 翠峰湖) | Yilan / Datong | 24.4960, 121.5320 (low confidence) | Hidden gem |
| 30 | Mingchi National Forest Recreation Area | 明池國家森林遊樂區 | Yilan / Datong | 24.6502, 121.4740 (low confidence) | Hidden gem |
| 31 | Shimen (Shihmen) Reservoir | 石門水庫 | Taoyuan / Daxi–Longtan | 24.8115, 121.2450 (low confidence) | Hidden gem |
| 32 | Daxi Old Street | 大溪老街 | Taoyuan / Daxi | 24.8830, 121.2870 (low confidence) | Hidden gem |
| 33 | Lalashan (giant cypress trees) & Smangus | 拉拉山 / 司馬庫斯 | Taoyuan / Fuxing; Hsinchu / Jianshi | Lalashan ~24.712, 121.430; Smangus ~24.580, 121.340 (both low confidence) | Remote gem |
| 34 | Neiwan Old Street & Neiwan Line | 內灣老街 / 內灣線 | Hsinchu County / Hengshan | 24.7050, 121.1830 (low confidence) | Hidden gem |
| 35 | Shitoushan (Lion's Head Mountain) temples | 獅頭山 | Miaoli / Nanzhuang–Sanwan (border with Hsinchu Emei) | 24.620, 120.975 (low confidence) | Hidden gem |
| 36 | Shengxing Station & Longteng Bridge ruins (Old Mountain Line) | 勝興車站 / 龍騰斷橋 | Miaoli / Sanyi | Shengxing ~24.388, 120.772; Longteng ~24.362, 120.774 (low confidence) | Hidden gem |

(36 rows. Rows 9, 24, 27 and 35 are the most optional if the app wants a tighter list of about 30.)

- Shuqi Road (豎崎路) is in Jiufen, New Taipei City — [Wikimedia Commons search result](https://commons.wikimedia.org/wiki/File:Jioufen_Shuchi_Street_Banner.jpg)
- Bitou Cape (鼻頭角) is one of the three major capes on the north coast, in Ruifang District, New Taipei — [AllTrails / search summary](https://www.alltrails.com/trail/taiwan/new-taipei-city/bitou-cape-coastal-loop); [newtaipei.travel](https://newtaipei.travel/en/attractions/detail/402842)
- Wangyou Valley (望幽谷) is on Badou Street, Zhongzheng District, Keelung, near Badouzi fishing village — [Trip.com moments](https://www.trip.com/moments/poi-wangyougu-13505943/); [Tourism Administration](https://eng.taiwan.net.tw/m1.aspx?sNo=0002105&id=C100_378)
- Lanyang Museum is in Toucheng Township, Yilan, next to Wushigang. It was designed by Kris Yao and opened 16 Oct 2010 — [TravelKing](https://www.travelking.com.tw/eng/tourguide/scenery104761.html); [Commons category](https://commons.wikimedia.org/wiki/Category:Lanyang_Museum)
- Shimen Reservoir straddles Daxi, Longtan and Fuxing districts of Taoyuan — [TravelKing](https://www.travelking.com.tw/eng/tourguide/taoyuan/shihmen-reservoir.html)
- Lalashan is reached via Provincial Highway 7 (Northern Cross-Island Highway), which starts in Daxi — [Taiwan Everything](https://taiwaneverything.cc/2021/09/27/lalashan/)

### Inferences
- Exact pins matter more for some spots than others. For trail-type spots (Bitou Cape, Wangyou Valley, Sandiaoling, Elephant Mountain), the app should pin the **trailhead or transit stop**, not the summit. For Yehliu, pin the park entrance; the Queen's Head is roughly 500 m inside.

### Gaps
- **No coordinate verified** (Wikipedia, Wikidata and OSM were blocked). Recommend batch geocoding from Wikidata. Likely QIDs or articles exist for Taipei 101, CKS Memorial Hall, Longshan Temple, Jiufen, Jinguashi, Yehliu, Bitou Cape, Shifen Waterfall, Houtong, Lanyang Museum, Taiping Mountain, Maokong Gondola and Xiangshan (Taipei); English Wikipedia articles titled "Bitou Cape", "Maokong Gondola", "Taiping Mountain", "Xiangshan, Taipei" and "Chiang Kai-shek Memorial Hall" appeared in search results.
- Smangus, Lalashan and Shitoushan pins are especially uncertain.

## 2. Why each spot is photogenic, the classic shot, and best time and season

### Takeaway
The highest-value timed shots are:
- **Elephant Mountain at dusk:** 18:00–18:45 in summer; sunset is ~17:15 in December.
- **Jiufen at blue hour:** lanterns lit.
- **Laomei Green Reef:** low tide in April.
- **Zhuzihu calla lilies:** mid-March to mid-April.
- **Yangmingshan silvergrass:** October–December, peak November.
- **Yehliu Night Tours:** late June to mid-July 2026.

### Cited Findings
**Taipei**
- **Elephant Mountain:** a 184 m peak directly behind Xinyi, a free viewpoint about 20 minutes up. The classic shot is the Taipei 101 skyline from the Six Giant Rocks; Chaoran Pavilion higher up is less crowded. The dusk window (about 18:00–18:45 in summer, ~30–45 min) is when 101's lights come on as the sky changes colour. Sunset ranges from ~17:15 (Dec) to ~19:00 (Jun). Weekday evenings are quieter — [taipeitourism.org](https://www.taipeitourism.org/elephant-mountain-taipei-hike/); [taipei-escape.com](https://www.taipei-escape.com/guides/elephant-mountain-hike/)
- **Taipei 101 Observatory:** floors 88F, 89F and 91F; the 101F open-air deck costs extra (see section 3) — [KKday blog](https://www.kkday.com/en/blog/98733/taipei-101); [official ticket page](https://www.taipei-101.com.tw/en/observatory/ticket)
- **CKS Memorial Hall:** "one of the most photographed and most visited free attractions in Taipei." The classic shot is the Liberty Square gate (自由廣場) framing the white hall.
  - The changing of the guard moved in 2024 from inside the hall to Liberty Square / Democracy Boulevard outdoors. It runs hourly 09:00–17:00 and lasts ~10–15 min.
  - The grounds are open 05:00–midnight.
  - [taipeitourism.org](https://www.taipeitourism.org/chiang-kai-shek-memorial-hall/); [search summary incl. Taipei Travel Geek](https://www.taipeitravelgeek.com/chiang-kai-shek-memorial-hall)
- **Yangmingshan, Zhuzihu (竹子湖):** famous for calla lilies and hydrangeas. Callas start in January and peak mid-March to mid-April; 80–90% of Taiwan's calla lilies are grown here — [Taiwan Obsessed via search](https://www.taiwanobsessed.com/yangmingshan-national-park/); [travel.taipei TAIPEI Quarterly](https://www.travel.taipei/en/pictorial/article/57703)
- **Yangmingshan, Qingtiangang (擎天崗):** rolling grassland where water buffalo are almost always visible. Silvergrass runs October–December, peaking in November, at Xiaoyoukeng, Qixingshan, Qingtiangang and Lengshuikeng — [Taiwan Obsessed (via search)](https://www.taiwanobsessed.com/qingtiangang-grassland-taipei/)
- **Beitou Thermal Valley:** a steaming jade-coloured hot-spring pool. Free, 09:00–18:00, closed Mondays — [Taiwanderers / search summary](https://taiwanderers.com/beitou-thermal-valley-taipei/); [travel.taipei](https://www.travel.taipei/en/attraction/details/536). Note: travel.taipei announced a revamped "Beitou Geothermal Valley Park" opening free "from July 20th". The year was not visible in the snippet — [travel.taipei news](https://www.travel.taipei/en/news/details/37639)
- **Maokong:** the Maokong Gondola is the main draw (glass-floor "Eyes" cabins, tea fields, night views) — [Taipei City Gov FAQ](https://english.gov.taipei/News_Content.aspx?n=A0EDC3930FBE7EFC&sms=5B794C46F3CDE718&s=79465BE90315C332)

**New Taipei: Jiufen, Jinguashi, Pingxi, north coast**
- **Jiufen:** red lanterns on the Shuqi Road stairs (classic dusk/blue-hour shot) — [Commons: Lanterns in Jiufeng](https://commons.wikimedia.org/wiki/File:Lanterns_in_Jiufeng.jpg)
- **Yin Yang Sea:** two-tone sea, listed among Jinguashi's highlights. A viewing platform is served by Taipei Bus — [taipeibus.fontour.com](https://taipeibus.fontour.com/en/spots/65); [wefuntaiwan](https://wefuntaiwan.com/jinguashi/)
- **Yehliu Queen's Head:**
  - The neck circumference has thinned from ~220 cm in the 1990s to 116.59 cm (Oct 2024 measurement), roughly 1 cm per year.
  - A Taipei Tech reinforcement project has cut the weathering rate on treated rocks to about 1/10 of untreated rocks.
  - Classic shot: the Queen's Head profile, usually with a queue. Go at opening time to beat tour buses.
  - [Taiwan Merch guide](https://taiwanmerch.co/culture/yehliu-geopark-taiwan-guide/); [newtaipei.travel](https://newtaipei.travel/en/attractions/detail/111495)
- **Yehliu night event:** "2026 Times of Rocks in Yehliu – A Night-time Visit to the Queen's Head" ran **28 June – 12 July 2026, 18:30–21:00**. It is a ticketed night tour with the Queen's Head illuminated; discounted tickets went on sale 1 June. The event started in 2018 — [Tourism Administration events](https://eng.taiwan.net.tw/m1.aspx?sNo=0002019&lid=081749); [MerXWire](https://merxwire.com/30098/2026-yehliu-night-tours-see-the-queens-head-illuminated-at-night-open-june-28-discounted-tickets-on-sale-june-1/); [North Coast NSA](https://www.northguan-nsa.gov.tw/user/article.aspx?Lang=2&SNo=04008941)
- **Bitou Cape:** 3.5 km coastal trail (2–3 h) with two branches, one to the lighthouse and one through a valley. The drone shot of the cape looks like a "battleship", making it the north coast's most popular drone spot (check local drone rules) — [mstravelsolo](https://www.mstravelsolo.com/bitoujiao-trail/); [Taiwan Obsessed (via search)](https://www.taiwanobsessed.com/bitoujiao-trail/)
- **Laomei Green Reef:**
  - Rows of volcanic-rock troughs covered in bright green algae.
  - Best March–May, greenest in **April**. Go on a sunny day at **low tide**; low-tide times vary daily.
  - Hot weather kills the algae early.
  - [hoponworld](https://hoponworld.com/laomei-green-reef/); [unlockingtaiwan](https://unlockingtaiwan.com/laomei-green-reef/); [Josh Ellis Photography](https://www.goteamjosh.com/blog/laomei)
- **Sandiaoling:** three large waterfalls above the Keelung River on the Pingxi Line. The hike can continue to Houtong — [AllTrails](https://www.alltrails.com/trail/taiwan/new-taipei-city/sandiaoling-waterfalls-trail); [goteamjosh](https://www.goteamjosh.com/blog/sandiaoling-)

**Keelung**
- **Wangyou Valley:** V-shaped grassy valley sloping to the sea, with Keelung Islet in view. The iconic shot is the white staircase descending into the valley. There is almost no shade, so go late afternoon or evening for soft light and sunset. The ~1.7 km easy trail takes about 1 h — [Trip.com moments](https://www.trip.com/moments/poi-wangyougu-13505943/); [taiwantrailsandtales](https://taiwantrailsandtales.com/2023/05/20/wangyou-valley-trail/)

**Yilan**
- **Lanyang Museum:** Kris Yao's slanted, cuesta-shaped building beside Wushigang lagoon. Reflection shots work best — [TravelKing](https://www.travelking.com.tw/eng/tourguide/scenery104761.html)
- **Taipingshan:** the 1 km heritage "Bong Bong" train (~20 min), the Jianqing Huaigu Trail (moss and misty forest) and Cuifeng Lake, Taiwan's largest alpine lake, about 30 min drive beyond the village — [Trip.com](https://sg.trip.com/travel-guide/attraction/yilan/bong-bong-train-taipingshan-station-136724614/); [Taiwan Hikes](https://www.taiwanhikes.com/blog-posts/jancing-trail-taipingshan.html)

**Taoyuan**
- **Shimen Reservoir:** Pinglin Park is the best vantage point for the spillway discharge and is popular for wedding photos and stargazing — [Trip.com / TravelKing summary](https://www.travelking.com.tw/eng/tourguide/taoyuan/shihmen-reservoir.html)

### Inferences
- These best-time rules are based on general knowledge, not cited, and should be presented as tips rather than facts:
  - Jiufen: blue hour, weekday.
  - Yehliu: opening time.
  - Shifen: dusk, when the lantern launches are backlit.
  - Tamsui: sunset.
  - Mingchi: early-morning mist.
  - Taipingshan: autumn maples (Oct–Nov) and sea of clouds.
  - Neiwan: firefly season April–May.
  - Longteng Bridge: tung blossom ("May snow") April–May.
  - Daxi: weekday mornings.
  - Smangus and Lalashan: peach blossom and peach season.
- A seasonal calendar view in the app would be valuable:
  - Jan–Apr: Zhuzihu calla lilies.
  - Feb–Mar: cherry blossoms. Yangmingshan Flower Festival and Lalashan, not cited here.
  - Mar–May: Laomei.
  - Apr–May: tung blossom in Miaoli/Hsinchu (uncited).
  - Jun–Jul: Yehliu night tours.
  - Oct–Dec: silvergrass.
  - Nov: Taipingshan maples (uncited).

### Gaps
- No sources were found for photo tips at Zhishanyan, Shitoushan, Neiwan, Smangus, Mingchi, Heping Island, Dihua Street, Ximending, Tamsui or Fort San Domingo. Searches returned nothing specific, and Taiwan Obsessed pages could not be fetched.
- Cherry blossom timing (Yangmingshan, Lalashan, Wuling and others) was not researched.

## 3. Public transport, fees, opening hours, closed days

### Takeaway
Most city spots are free and on the MRT. The north-coast and gold-mining spots use buses 1062, 965, 856 and 891 from Taipei or Ruifang. Yilan, Taoyuan, Hsinchu and Miaoli mountain spots need intercity buses or tours. Only these MRT exit numbers are source-confirmed: **Xiangshan Exit 2** (Elephant Mountain) and **Zhongxiao Fuxing** as the 1062 bus origin (exit number not confirmed).

### Cited Findings
- **Elephant Mountain:** MRT Red Line to **Xiangshan Station, Exit 2**, then a 10–15 min flat walk through Xiangshan Park to the trailhead by Lingyun Temple. Free, no reservation. Allow 1.5–2 h round trip from the MRT — [taipeitourism.org](https://www.taipeitourism.org/elephant-mountain-taipei-hike/); [taipei-escape.com](https://www.taipei-escape.com/guides/elephant-mountain-hike/)
- **Taipei 101 Observatory:**
  - Standard ticket **NT$600** for 88F/89F/91F.
  - "Skyline 460" combined ticket ~**NT$980**, or **NT$380 add-on** for the 101F outdoor deck. Another source lists a premium guided Skyline460 at **NT$3,000**. These figures conflict; verify on the official page.
  - Children under 115 cm or under 6 are free.
  - [KKday blog](https://www.kkday.com/en/blog/98733/taipei-101); [official ticket page](https://www.taipei-101.com.tw/en/observatory/ticket); [Taipei Travel Geek](https://www.taipeitravelgeek.com/taipei-101)
- **CKS Memorial Hall:** free. Grounds open 05:00–24:00. Guard change hourly 09:00–17:00 outdoors — [taipeitourism.org](https://www.taipeitourism.org/chiang-kai-shek-memorial-hall/)
- **Beitou Thermal Valley:** free, 09:00–18:00, **closed Mondays** — [Taiwanderers (via search)](https://taiwanderers.com/beitou-thermal-valley-taipei/)
- **Yangmingshan:** park shuttle **108** is a one-way loop. Stops: Yangmingshan bus station → Visitor Center → Yangming Shuwu → Zhuzihu → Qixingshan → Xiaoyoukeng → Lengshuikeng → Qingtiangang → Lengshuikeng → Songyuan → Jyuansih Waterfall → bus station. Bus S9 (from MRT Beitou) also appears in traveller forums — [Taiwan Obsessed (via search)](https://www.taiwanobsessed.com/taipei-to-yangmingshan/); [Tripadvisor forum](https://www.tripadvisor.com/ShowTopic-g293913-i9546-k3602655-Yangmingshan_by_bus_S9-Taipei.html)
- **Jiufen / Jinguashi:**
  - **Bus 1062** from Zhongxiao Fuxing MRT is the easiest route from Taipei.
  - **Bus 965** passes Beimen MRT and goes to Ruifang, Jiufen and Jinguashi. The Taiwan Tourist Shuttle brands it the "965 Jiufen–Jinguashi route".
  - From the Gold Museum to the Golden Waterfall: buses **826, 856 or 891**.
  - [Nick Kembel](https://www.nickkembel.com/taipei-to-jiufen-to-shifen/); [mstravelsolo](https://www.mstravelsolo.com/jiufen-from-taipei/); [amazingjiufen.tw](https://amazingjiufen.tw/en/); [Gold Museum transport](https://www.gep-en.ntpc.gov.tw/xmdoc/cont?xsmsid=0G274607184480542936)
- **Gold Museum (Jinguashi):**
  - **NT$80** general admission. Free for New Taipei residents, seniors 65+, children 12 and under, and domestic full-time students.
  - Hours: weekdays 09:30–17:00; weekends and national holidays 09:30–18:00.
  - **Closed the first Monday of each month** (open if it is a national holiday), plus Lunar New Year's Eve and Day and typhoon days off.
  - [Gold Museum official, Opening Hours](https://www.gep-en.ntpc.gov.tw/xmdoc/cont?xsmsid=0G274606722488077919)
- **Bitou Cape:** reachable on Taiwan Tourist Shuttle **856** (the Huangguan Fulong line), which links to Jiufen. Trail is 3.5 km, 2–3 h — [mstravelsolo](https://www.mstravelsolo.com/bitoujiao-trail/)
- **Wangyou Valley:** TRA train to Keelung Station, then **Keelung City Bus 103** to the Badouzi stop. Free — [Trip.com moments](https://www.trip.com/moments/poi-wangyougu-13505943/)
- **Sandiaoling and Houtong:** TRA to Sandiaoling Station (Pingxi Line junction). The waterfall hike can end at Houtong — [Pingxi Line guide, Wandering Wheatleys](https://wanderingwheatleys.com/pingxi-line-train-taipei-day-trip-taiwan/); [AllTrails](https://www.alltrails.com/trail/taiwan/new-taipei-city/sandiaoling-waterfalls-trail)
- **Laomei Green Reef:** free, open coast. Check tide tables — [unlockingtaiwan](https://unlockingtaiwan.com/laomei-green-reef/)
- **Lanyang Museum (Toucheng, Yilan):**
  - Thursday–Tuesday 09:00–17:00, ticket sales until 16:30.
  - **Closed every Wednesday** (open on national holidays), plus Lunar New Year's Eve and Day.
  - Adult **NT$100**, student NT$50, group NT$80.
  - [TravelKing](https://www.travelking.com.tw/eng/tourguide/scenery104761.html); [Lanyang Museum FAQ](https://www.lym.gov.tw/en/audience-service/faq/)
- **Taipingshan:** Bong Bong Train adult return **NT$180**. Tickets are sold on-site only, from 07:00 for same-day rides; trains run ~07:30–16:00 — [Trip.com](https://sg.trip.com/travel-guide/attraction/yilan/bong-bong-train-taipingshan-station-136724614/). Joint tickets with Lanyang Museum are sold on Taipei Fun Pass — [Taipei Fun Pass](https://funpass.travel.taipei/tour/gNMq)
- **Daxi and Shimen Reservoir:** **Taoyuan Bus 5096/5098** to Daxi (~40 min, ~NT$55), then **5098** to Shimen Reservoir (~20 min, ~NT$25). There is also a Taiwan Tourist Shuttle "Shimen Reservoir Line", and Taoyuan Bus from Zhongli East Station — [relaygo.pro](https://relaygo.pro/en/guide/taoyuan-daxi); [TravelKing](https://www.travelking.com.tw/eng/tourguide/taoyuan/shihmen-reservoir.html)

### Inferences
- Commonly cited but **UNVERIFIED** MRT exits (from general knowledge; not confirmed in this research):
  - CKS Memorial Hall Station Exit 5
  - Longshan Temple Station Exit 1
  - Ximen Station Exit 6
  - Taipei 101/World Trade Center Station Exit 4
  - Xinbeitou Station for Thermal Valley (no exit needed; it is the terminus)
  - Zhongxiao Fuxing Exit 1 for bus 1062
  - Tamsui terminus for Tamsui and Fisherman's Wharf (bus or ferry)
  - Shifen and Pingxi: TRA Pingxi Line, transfer at Ruifang.
- Remote spots (Smangus, Lalashan, Mingchi, Taipingshan, Cuifeng Lake) are realistically tour or self-drive only for first-time visitors. The app should flag them as "advanced/1-day+".

### Gaps
- **No cited data** was found on:
  - Entry fees or hours for Yehliu Geopark (believed ~NT$120 adult; unverified), Fort San Domingo, Longshan Temple, Taipingshan main admission, Mingchi, Shimen Reservoir and Lalashan.
  - Maokong Gondola fares.
  - Shitoushan, Neiwan and Smangus transport, beyond general knowledge that Neiwan is the terminus of the TRA Neiwan Line from Hsinchu.
  - Smangus visitor rules.
- Bus 108 frequency and fare, and the exact Tamsui ferry, were not verified.

## 4. Sample photo links (Wikimedia Commons / Wikipedia / tourism pages)

### Takeaway
Specific Commons **File:** pages were found for 8 spots. For the rest, the best available link is a Commons **Category:** page, an English Wikipedia article title, or an official tourism page.

### Cited Findings
Specific Commons file pages (seen as live pages in commons.wikimedia.org search results):
- Elephant Mountain night skyline (Jan 2017): https://commons.wikimedia.org/wiki/File:Taipeh,_Taiwan_Skyline_vom_Elephant_Mountain.jpg
- Taipei 101: https://commons.wikimedia.org/wiki/File:Taipei_101_(from_ground_level).jpg (also https://commons.wikimedia.org/wiki/File:Taipei_101.JPG)
- Jiufen lanterns: https://commons.wikimedia.org/wiki/File:Lanterns_in_Jiufeng.jpg
- Jiufen overview: https://commons.wikimedia.org/wiki/File:Mountain_Village_of_Jiufen_08.23_(II).jpg ; https://commons.wikimedia.org/wiki/File:180124_Jiufen,_Taiwan_%E4%B9%9D%E4%BB%BD.jpg
- Jiufen Shuqi Street lanterns banner. A panoramic strip of 1,800×257 px from 2006, so a poor thumbnail: https://commons.wikimedia.org/wiki/File:Jioufen_Shuchi_Street_Banner.jpg
- Yehliu Queen's Head: https://commons.wikimedia.org/wiki/File:Queen's_head,_Yehliu_Geopark,_Taiwan_-_%E9%87%8E%E6%9F%B3%E5%9C%B0%E8%B3%AA%E5%85%AC%E5%9C%92,_%E5%8F%B0%E6%B9%BE_(11353535854).jpg
- Shifen Waterfall: https://commons.wikimedia.org/wiki/File:Shifen_Waterfall_2019.jpg
- Houtong cats: https://commons.wikimedia.org/wiki/File:Houtong_cats10.JPG
- Lanyang Museum: https://commons.wikimedia.org/wiki/File:%E5%AE%9C%E8%98%AD_%E8%98%AD%E9%99%BD%E5%8D%9A%E7%89%A9%E9%A4%A8_I-lan_LanYang_Museum_Taiwan.jpg

Commons category pages (fallback galleries):
- https://commons.wikimedia.org/wiki/Category:Mount_Elephant_(Taipei)
- https://commons.wikimedia.org/wiki/Category:Views_from_Mount_Elephant_(Taipei)
- https://commons.wikimedia.org/wiki/Category:Jiufen_Old_Street
- https://commons.wikimedia.org/wiki/Category:Jioufen
- https://commons.wikimedia.org/wiki/Category:Yehliu
- https://commons.wikimedia.org/wiki/Category:Queen's_head_(Yehliu)
- https://commons.wikimedia.org/wiki/Category:Shifen_Waterfall
- https://commons.wikimedia.org/wiki/Category:Lanyang_Museum

English Wikipedia articles seen in search results (URL confirmed; lead image not checked):
- Chiang Kai-shek Memorial Hall — https://en.wikipedia.org/wiki/Chiang_Kai-shek_Memorial_Hall
- Bitou Cape — https://en.wikipedia.org/wiki/Bitou_Cape
- Maokong Gondola — https://en.wikipedia.org/wiki/Maokong_Gondola
- Taiping Mountain — https://en.wikipedia.org/wiki/Taiping_Mountain
- Taiping Mountain Forest Railway — https://en.wikipedia.org/wiki/Taiping_Mountain_Forest_Railway
- Xiangshan, Taipei — https://en.wikipedia.org/wiki/Xiangshan,_Taipei
- Sandiaoling railway station — https://en.wikipedia.org/wiki/Sandiaoling_railway_station

Official tourism pages with photos:
- Beitou Geothermal Valley: https://www.travel.taipei/en/attraction/details/536
- Yehliu Geopark: https://newtaipei.travel/en/attractions/detail/111495
- Bitoujiao Trail: https://newtaipei.travel/en/attractions/detail/402842
- Badouzi / Wangyou Valley: https://eng.taiwan.net.tw/m1.aspx?sNo=0002105&id=C100_378
- Yin Yang Sea: https://taipeibus.fontour.com/en/spots/65
- Bong Bong Train (Forestry): https://recreation.forest.gov.tw/EN/Forestry/FR?typ_id=0100041
- Zhuzihu (agri-tourism): https://ezgo.ardswc.gov.tw/en/tour/1260/

### Inferences
- For an app, Commons file pages are the safest (freely licensed). Category pages are good for a "more photos" link. Before shipping, a script should call the Commons API (`prop=imageinfo&iiprop=url|extmetadata`) to get the thumbnail URL and licence/attribution, which this research could not do.

### Gaps
- No specific Commons **file** found for:
  - Taipei: CKS Hall, Longshan, Dihua, Ximending, Beitou, Qingtiangang, Zhuzihu, Maokong, Zhishanyan.
  - New Taipei: Tamsui, Fort San Domingo, Golden Waterfall, Yin Yang Sea, Shifen Old Street, Sandiaoling, Bitou Cape, Laomei.
  - Keelung: Wangyou Valley, Miaokou, Heping Island.
  - Yilan and further south: Taipingshan, Mingchi, Shimen, Daxi, Lalashan, Smangus, Neiwan, Shitoushan, Shengxing/Longteng.
- These files very likely exist on Commons but could not be verified, because commons.wikimedia.org was reachable only through search snippets.

## 5. Current closures and changes, 2025–2026

### Takeaway
As of October 2026, nothing iconic is permanently closed. Flag these:
- The Maokong Gondola has recurring maintenance shutdowns.
- Taipingshan was partially closed March–April 2026 and has had typhoon-damage history.
- The Sandiaoling trail was reported closed or overgrown in May 2026.
- The Xiaowulai Skywalk closed April–June 2026.
- The Queen's Head is eroding but still standing, with reinforcement under way.

### Cited Findings
- **Maokong Gondola:**
  - 2026 suspensions: **20–24 April 2026** (cable trimming on Section 2, Corner Station 2 to Maokong) and **8–28 June 2026** (annual major maintenance). Resumed 25 April and 29 June — [CNA via washinmura](https://aeo.washinmura.jp/ai/cna/en/news/2026-04-13-taipei-maokong-gondola-to-suspend-operat); [Taipei Times, 2 Jun 2026](https://www.taipeitimes.com/News/taiwan/archives/2026/06/02/2003858415)
  - The 2025 annual maintenance was 16–30 June — [Focus Taiwan](https://focustaiwan.tw/society/202506110022)
  - Pattern: an annual shutdown of 2–3 weeks around May–June, plus regular weekly Monday closures (Monday closure from general knowledge; unverified here).
- **Yehliu Queen's Head:** still standing and viewable. The neck was 116.59 cm in Oct 2024. Reinforcement is slowing erosion but not stopping it — [Taiwan Merch](https://taiwanmerch.co/culture/yehliu-geopark-taiwan-guide/). The 2026 Night Tours ran 28 Jun – 12 Jul 2026 — [Tourism Administration](https://eng.taiwan.net.tw/m1.aspx?sNo=0002019&lid=081749)
- **Taipingshan:**
  - **3 March – 30 April 2026:** the recreation area was partially closed for construction. Only Jiuzhize Hot Springs stayed open; the Bong Bong Train, Cuifeng Lake and their trails were closed — [search summary of Trip.com/KKday listings](https://www.kkday.com/en/product/100467-yilan-taipingshan-national-forest-recreation-area-admission-ticket-taiwan). Secondary source; verify with the Forestry and Nature Conservation Agency.
  - Earlier, Typhoon Gaemi (Kemi) damage collapsed parts of the Bong Bong Train route. Reports describe partial road reopening and the train running only about 1 km. A published May 2026 maintenance schedule (12 and 26 May) implies the train was operating by May 2026 — [search summary of Trip.com / forest.gov.tw](https://tps.forest.gov.tw/TPSWeb/wSite/ct?xItem=3679&amp=&ctNode=352&amp=&mp=2)
  - The Jianqing Huaigu Trail now ends after ~900 m; the rest was destroyed by a typhoon and will not be rebuilt — [search summary; Taiwan Obsessed / Taiwan Hikes](https://www.taiwanhikes.com/blog-posts/jancing-trail-taipingshan.html)
- **Sandiaoling Waterfall Trail:** AllTrails reviews from April–May 2026 report the trail **marked closed in May 2026**, with the final ~0.8 km unmaintained, overgrown and slippery — [AllTrails](https://www.alltrails.com/trail/taiwan/new-taipei-city/sandiaoling-waterfalls-trail). These are user-generated reports, not official. Note: the trail also had a long official closure before reopening in 2023–24 (not cited here).
- **Xiaowulai (Little Wulai) Skywalk (Taoyuan, Fuxing):** scheduled to close **7 April 2026** for bridge renovation, expected to reopen **1 July 2026** — [search summary from Lalashan/Taoyuan travel listings](https://www.travelking.com.tw/eng/tourguide/scenery23.html). Secondary; reopening not confirmed.
- **CKS Memorial Hall:** the guard ceremony moved outdoors to Liberty Square in 2024 — [taipeitourism.org](https://www.taipeitourism.org/chiang-kai-shek-memorial-hall/)

### Inferences
- The app should treat these as "check before you go" items with a status field and last-verified date: Maokong (annual maintenance), Taipingshan (typhoon road status), Sandiaoling, Lalashan and Smangus (Highway 7 and county road landslides), and Yehliu Night Tours (annual, summer only).

### Gaps
- No 2026 official confirmation found for:
  - Whether Taipingshan fully reopened after 30 April 2026.
  - Current Northern Cross-Island Highway (Hwy 7) status to Lalashan and Mingchi.
  - Smangus road access.
  - Whether the Xiaowulai Skywalk reopened on 1 July 2026.
- No status checks were done for Jiufen, Shifen sky-lantern rules, Laomei access, or Heping Island Park (which has had renovation phases).
- The Beitou Geothermal Valley Park revamp date is unclear (the travel.taipei news item lacked a visible year).

## 6. Verification of suggested hidden gems

### Takeaway
Sources confirm these as real, photogenic and reachable: Sandiaoling (status caveat), Bitou Cape, Houtong, Taipingshan (status caveat), Lanyang Museum, Shimen Reservoir, Laomei Green Reef, Wangyou Valley, Daxi and Lalashan. Mingchi, Zhishanyan, Smangus, Neiwan and Shitoushan are well-known places but had **no supporting detail** in this research.

### Cited Findings
- **Sandiaoling:** three waterfalls on the Pingxi Line; connects to Houtong. Status caveat for May 2026 — [AllTrails](https://www.alltrails.com/trail/taiwan/new-taipei-city/sandiaoling-waterfalls-trail)
- **Bitou Cape:** 3.5 km trail, lighthouse, "battleship" drone view; Tourist Shuttle 856 — [mstravelsolo](https://www.mstravelsolo.com/bitoujiao-trail/); [newtaipei.travel](https://newtaipei.travel/en/attractions/detail/402842)
- **Houtong:** "cat village", reached via the Sandiaoling hike or the train — [AllTrails summary](https://www.alltrails.com/trail/taiwan/new-taipei-city/sandiaoling-waterfalls-trail); [Commons file](https://commons.wikimedia.org/wiki/File:Houtong_cats10.JPG)
- **Laomei Green Reef:** algae season Feb/Mar–May, best in April at low tide — [hoponworld](https://hoponworld.com/laomei-green-reef/)
- **Wangyou Valley:** easy 1.7 km trail, white stairs shot, bus 103 — [Trip.com](https://www.trip.com/moments/poi-wangyougu-13505943/); [Tourism Administration](https://eng.taiwan.net.tw/m1.aspx?sNo=0002105&id=C100_378)
- **Lanyang Museum:** open Thursday–Tuesday, NT$100 — [TravelKing](https://www.travelking.com.tw/eng/tourguide/scenery104761.html)
- **Taipingshan:** Bong Bong Train NT$180; status caveats — [Trip.com](https://sg.trip.com/travel-guide/attraction/yilan/bong-bong-train-taipingshan-station-136724614/)
- **Shimen Reservoir:** Pinglin Park spillway viewpoint; bus 5098 — [TravelKing](https://www.travelking.com.tw/eng/tourguide/taoyuan/shihmen-reservoir.html); [relaygo](https://relaygo.pro/en/guide/taoyuan-daxi)
- **Lalashan:** sacred giant tree trail via Highway 7 — [taiwantrailsandtales](https://taiwantrailsandtales.com/2025/08/30/lalashan-sacred-trees/); [Taiwan Everything](https://taiwaneverything.cc/2021/09/27/lalashan/)

### Inferences
- For a *first-time* visitor app, prioritise the hidden gems reachable by rail or city bus: Wangyou Valley, Bitou Cape, Houtong, Laomei (seasonal), Lanyang Museum, Daxi and Neiwan. Tag the mountain sites (Taipingshan, Mingchi, Lalashan, Smangus) as "needs tour/car, check road status".

### Gaps
- Zhishanyan, Mingchi, Smangus, Neiwan, Shitoushan, Shengxing/Longteng Bridge and Heping Island are not backed by any source fetched or seen in this research; their inclusion relies on general knowledge. The report writer should present them with lighter detail or mark them "details unverified".
