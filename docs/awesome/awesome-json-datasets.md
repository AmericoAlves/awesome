<div class="github-widget" data-repo="jdorfman/awesome-json-datasets"></div>
## Awesome JSON Datasets [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://www.justindorfman.com/assets/images/json.svg" align="right" width="100">](http://www.json.org/)

精选的不需要身份验证的JSON数据集的精选列表.

&gt; *月份链接：* [Foreign Exchange Rates](https://exchangeratesapi.io/)

_赞助商链接：_ [Front End Developer Jobs](https://www.bootstrapcdn.com/jobs/?utm_source=awesome-json-datasets&utm_campaign=awesome-json-datasets-sponsorship&utm_medium=referral)


## Bitcoin
* [Latest Block](https://blockchain.info/latestblock)
* [Unconfirmed Transactions](https://blockchain.info/unconfirmed-transactions?format=json)

&gt;专业提示：退房 [Cryptocurrency Market Capitalizations](https://api.coinmarketcap.com/v1/ticker/) 更多加密货币价格.

## Climate

* [Global Temperature Anomaly)](https://www.ncdc.noaa.gov/cag/time-series/global/globe/land_ocean/ytd/12/1880-2016.json) *（1880-2015 vs. 1901-2000平均值）*
* [US Annual Average Temperature and Anomaly)](https://www.ncdc.noaa.gov/cag/time-series/us/110/00/tavg/ytd/12/1895-2016.json?base_prd=true&begbaseyear=1901&endbaseyear=2000) *（1880-2015（对比1901-2000平均值）*
* [Contiguous US Annual Precipitation](https://www.ncdc.noaa.gov/cag/time-series/us/110/00/pcp/ytd/12/1895-2016.json?base_prd=true&begbaseyear=1901&endbaseyear=2000) *(1895-2015)*
* [Drought Severity Index](https://www.ncdc.noaa.gov/cag/time-series/us/110/00/pdsi/ytd/12/1895-2016.json?base_prd=true&begbaseyear=1901&endbaseyear=2000) *（Palmer for the Contiguous US，1895-2016）*

## Crime

* [DATA.POLICE.UK](https://data.police.uk/docs/)
  * [Crimes at Location](https://data.police.uk/api/crimes-at-location?date=2015-02&lat=52.629729&lng=-1.131592)
  * [Street Crime Dates](https://data.police.uk/api/crimes-street-dates)
  * [Neighbourhoods](https://data.police.uk/api/leicestershire/neighbourhoods)
  * [List of Forces](https://data.police.uk/api/forces)
* [DATA.GOV](https://www.data.gov/local/)
  * [Chicago (historical data since 2001)](https://data.cityofchicago.org/api/views/ijzp-q8t2/rows.json?accessType=DOWNLOAD)

## Currency
* [Foreign Exchange Rates](https://exchangeratesapi.io/)
  * [USD](https://exchangeratesapi.io/api/latest?base=USD)
  * [EUR](https://exchangeratesapi.io/api/latest?base=EUR)
* [VAT rates for EU](http://jsonvat.com/)

## Gaming
* [BattleField 4 Online Players](http://api.bf4stats.com/api/onlinePlayers?output=json)
* [Pokémon](https://pokeapi.co/docsv2/)
  * [Pokémon by Number](http://pokeapi.co/api/v2/pokemon/1/) *（用所需的神奇宝贝号替换“1”）*
  * [Types](http://pokeapi.co/api/v2/type/1/) *（将`1`替换为另一个数字以检索不同类型）*
  * [Abilities](http://pokeapi.co/api/v2/ability/1) *（将&#39;1`替换为另一个数字以取回不同的能力）*
* [Magic: The Gathering](http://magic.wizards.com)
  * [MTG LEA Set + Extras](https://mtgjson.com/json/LEA-x.json)
  * [MTG LEB Set + Extras](https://mtgjson.com/json/LEB-x.json)
  * [MTG ARN Set + Extras](https://mtgjson.com/json/ARN-x.json)

&gt; Protip： [https://mtgjson.com](https://mtgjson.com) 列出了更多Magic：The Gathering卡数据集，以及所有集的压缩版本.

* [Steam Player Number](https://api.steampowered.com/ISteamUserStats/GetNumberOfCurrentPlayers/v0001/?format=json&appid=0)

## GitHub API
* [Emojis](https://api.github.com/emojis)
* [Events](https://api.github.com/events)
* [Gists](https://api.github.com/gists)
* [Meta](https://api.github.com/meta)

## Government
* [Trade.gov](http://developer.trade.gov/api/trade-apis.json)
  * [Market Research Library](http://developer.trade.gov/api/market-research-library.json)
  * [Business Service Providers](http://developer.trade.gov/api/business-service-providers.json)
  * [Consumer Complaint Database](http://data.consumerfinance.gov/api/views.json)
*美国政客
  * [Current US Senators](https://www.govtrack.us/api/v2/role?current=true&role_type=senator)
  * [Current US Representatives](https://www.govtrack.us/api/v2/role?current=true&role_type=representative&limit=438)

&gt; Protip： [GovTrack](https://www.govtrack.us/) 提供了一个 [powerful API](https://www.govtrack.us/developers/api) 用于查看国会，点名和账单上的数据.

* 司法部
  * [Blog Entries](https://www.justice.gov/api/v1/blog_entries.json?amp%3Bpagesize=2)
  * [Press Releases](https://www.justice.gov/api/v1/press_releases.json?pagesize=2)
  * [Speeches](https://www.justice.gov/api/v1/speeches.json?pagesize=2)
  * [Vacancy Announcements](http://www.justice.gov/api/v1/vacancy_announcements.json?pagesize=2)
*苏格兰议会
  * [Departments](https://data.parliament.scot/api/departments)
  * [Events](https://data.parliament.scot/api/events)
  * [Government Roles](https://data.parliament.scot/api/governmentroles)
  * [Members](https://data.parliament.scot/api/members)

&gt;专业提示：你可以做**很多** [http://parliamentdata.ca/](http://parliamentdata.ca/)

*欧盟游说透明度注册
  * [Country](http://api.lobbyfacts.eu/api/1/country)
  * [Entity](http://api.lobbyfacts.eu/api/1/entity)
  * [Representative](http://api.lobbyfacts.eu/api/1/representative)
  * [Person](http://api.lobbyfacts.eu/api/1/person)
  * [Category](http://api.lobbyfacts.eu/api/1/category)
  * [Financial](http://api.lobbyfacts.eu/api/1/financial_data)
  * [Accreditation](http://api.lobbyfacts.eu/api/1/accreditation)
*印度政府
  * [State Codes](http://vocab.nic.in/rest.php/states/json)
  * [Consumer Price Index](https://data.gov.in/node/1084041/datastore/export/json)
  * [Agriculture Production](https://data.gov.in/node/135611/datastore/export/json)
  * [Number of Districts/DRDAs/Blocks/Villages](https://data.gov.in/node/100853/datastore/export/json)
  * [Gross Domestic Product at Current Prices](https://www.quandl.com/api/v1/datasets/MOSPI/GDP.json)
*澳大利亚
  * [ABC Local Stations](http://data.gov.au/geoserver/abc-local-stations/wfs?request=GetFeature&typeName=ckan_d534c0e9_a9bf_487b_ac8f_b7877a09d162&outputFormat=json)
  * [VIC Police Station Locations](http://data.gov.au/geoserver/police-station-locations/wfs?request=GetFeature&typeName=762b47b2_e706_4cab_b0c7_cf8e406aefc1&outputFormat=json)
*阿姆斯特丹
  * [Shops](http://open.datapunt.amsterdam.nl/Shoppen.json)
  * [Food and Drinks](http://open.datapunt.amsterdam.nl/EtenDrinken.json)
  * [Museums and Galleries](http://open.datapunt.amsterdam.nl/MuseaGalleries.json)

## Historical Events
*语言
  * [English](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=en)
  * [German](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=de)
  * [Italian](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=it)
  * [Spanish](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=es)
  * [Portuguese](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=pt)
  * [Catalan](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=ca)
  * [Indonesian](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=id)
  * [Romanian](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=ro)
  * [Turkish](http://www.vizgr.org/historical-events/search.php?format=json&begin_date=-3000000&end_date=20151231&lang=tr)

 &gt;专业提示：您可以在URL中更改`begin_date`和`end_date`以获取特定时间间隔内的事件.  更多的选择 [here](http://www.vizgr.org/historical-events/).

## HTTP
* [IP](http://httpbin.org/ip)
* [user-agent](http://httpbin.org/user-agent)
* [headers](http://httpbin.org/headers)
* [GET](http://httpbin.org/get)
* [gzip](http://httpbin.org/gzip)
* [deflate](http://httpbin.org/deflate)
* [cookies](http://httpbin.org/cookies)
* [stream](http://httpbin.org/stream/10)
* [delay](http://httpbin.org/delay/3)
* [cache](http://httpbin.org/cache/60) *（`60` ===`60秒`）*

&gt;专业提示：你可以做**很多** [http://httpbin.org](http://httpbin.org/).

## NASA
* [ISS Current Location](http://api.open-notify.org/iss-now.json)
* [How Many People Are In Space Right Now](http://api.open-notify.org/astros.json)
* [Earth Meteorite Landings](https://data.nasa.gov/resource/y77d-th95.json)
* [Near-Earth Asteroids and Comets](https://data.nasa.gov/resource/2vr3-k9wn.json) *（由NEOWISE发现）*

## Natural Disasters
* [Earthquakes](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_hour.geojson)

## Nobel Prize
* [Prize](http://api.nobelprize.org/v1/prize.json)
* [Laureate](http://api.nobelprize.org/v1/laureate.json)
* [Country](http://api.nobelprize.org/v1/country.json)

## Open Source Licenses
* [All](https://api.opensource.org/licenses/)
* [Copyleft](https://api.opensource.org/licenses/copyleft)
* [OSI Approved](https://api.opensource.org/licenses/osi-approved)
* [Redundant](https://api.opensource.org/licenses/redundant)
* [Permissive](https://api.opensource.org/licenses/permissive)
* [Obsolete](https://api.opensource.org/licenses/obsolete)
* [Misc](https://api.opensource.org/licenses/miscellaneous)
* [Popular](https://api.opensource.org/licenses/popular)
* [Discouraged](https://api.opensource.org/licenses/discouraged)
* [Non-reusable](https://api.opensource.org/licenses/non-reusable)
* [Special Purpose](https://api.opensource.org/licenses/special-purpose)
* [Retired](https://api.opensource.org/licenses/retired)

&gt;成为OSI会员 [here](https://opensource.org/civicrm/contribute/transact?reset=1&id=1)

## Population

*今日总人口
  * [Earth](http://api.population.io/1.0/population/World/today-and-tomorrow/?format=json)
  * [Brazil](http://api.population.io/1.0/population/Brazil/today-and-tomorrow/?format=json)
  * [France](http://api.population.io/1.0/population/France/today-and-tomorrow/?format=json)
  * [Germany](http://api.population.io/1.0/population/Germany/today-and-tomorrow/?format=json)
  * [Greece](http://api.population.io/1.0/population/Greece/today-and-tomorrow/?format=json)
  * [Italy](http://api.population.io/1.0/population/Italy/today-and-tomorrow/?format=json)
  * [Japan](http://api.population.io/1.0/population/Japan/today-and-tomorrow/?format=json)
  * [Kenya](http://api.population.io/1.0/population/Kenya/today-and-tomorrow/?format=json)
  * [Mexico](http://api.population.io/1.0/population/Mexico/today-and-tomorrow/?format=json)
  * [Poland](http://api.population.io/1.0/population/Poland/today-and-tomorrow/?format=json)
  * [India](http://api.population.io/1.0/population/India/today-and-tomorrow/?format=json)
  * [United States](http://api.population.io/1.0/population/United%20States/today-and-tomorrow/?format=json)

&gt;专业提示： [List of all Countries](http://api.population.io/1.0/countries) 追踪

*美国人口统计表（0-100岁）
    * [1950](http://api.population.io/1.0/population/1950/United%20States/?format=json)
    * [1960](http://api.population.io/1.0/population/1960/United%20States/?format=json)
    * [1970](http://api.population.io/1.0/population/1970/United%20States/?format=json)
    * [1980](http://api.population.io/1.0/population/1980/United%20States/?format=json)
    * [1990](http://api.population.io/1.0/population/1990/United%20States/?format=json)
    * [2000](http://api.population.io/1.0/population/2000/United%20States/?format=json)
    * [2010](http://api.population.io/1.0/population/2010/United%20States/?format=json)

*历史人口（自1960年以来）
  * [China](http://api.worldbank.org/countries/CHN/indicators/SP.POP.TOTL?per_page=5000&format=json)
  * [India](http://api.worldbank.org/countries/IND/indicators/SP.POP.TOTL?per_page=5000&format=json)
  * [United States](http://api.worldbank.org/countries/USA/indicators/SP.POP.TOTL?per_page=5000&format=json)

## GDP
* [USA](http://api.worldbank.org/countries/USA/indicators/NY.GDP.MKTP.CD?per_page=5000&format=json)
* [China](http://api.worldbank.org/countries/CHN/indicators/NY.GDP.MKTP.CD?per_page=5000&format=json)
* [India](http://api.worldbank.org/countries/IND/indicators/NY.GDP.MKTP.CD?per_page=5000&format=json)

&gt;专业提示：链接到国家/地区列表 [Here](http://api.worldbank.org/countries?per_page=304&format=json)

## Reddit
* [/r/all](https://www.reddit.com/r/all.json)
* [/r/AskReddit](https://www.reddit.com/r/AskReddit.json)
* [/r/funny](https://www.reddit.com/r/funny.json)
* [/r/pics](https://www.reddit.com/r/pics.json)
* [/r/todayilearned](https://www.reddit.com/r/todayilearned.json)
* [/r/announcements](https://www.reddit.com/r/announcements.json)
* [/r/worldnews](https://www.reddit.com/r/worldnews.json)
* [/r/science](https://www.reddit.com/r/science.json)
* [/r/IAmA](https://www.reddit.com/r/IAmA.json)
* [/r/videos](https://www.reddit.com/r/videos.json)
* [/r/gaming](https://www.reddit.com/r/gaming.json)
* [/r/linux](https://www.reddit.com/r/linux.json)

&gt;专业提示：您可以将`.json`附加到任何subreddit网址.

## Travel
* [Global Airfields](https://ckannet-storage.commondatastorage.googleapis.com/2014-12-13T15:15:31.729Z/airfields.json)
* [Monthly Airline Delays by Airport, 2003-2016](https://think.cs.vt.edu/corgis/json/airlines/airlines.json)
* FAA机场状态
  * [SFO](http://services.faa.gov/airport/status/SFO?format=application/json)
  * [LAX](http://services.faa.gov/airport/status/LAX?format=application/json)
  * [PHX](http://services.faa.gov/airport/status/PHX?format=application/json)
  * [JFK](http://services.faa.gov/airport/status/JFK?format=application/json)
  * [ATL](http://services.faa.gov/airport/status/ATL?format=application/json)
  * [MIA](http://services.faa.gov/airport/status/MIA?format=application/json)
  * [AUS](http://services.faa.gov/airport/status/AUS?format=application/json)
  * [BOS](http://services.faa.gov/airport/status/BOS?format=application/json)
  * [CLE](http://services.faa.gov/airport/status/CLE?format=application/json)
  * [ORD](http://services.faa.gov/airport/status/ORD?format=application/json)
  * [PDX](http://services.faa.gov/airport/status/PDX?format=application/json)
  * [SJC](http://services.faa.gov/airport/status/SJC?format=application/json)

&gt;抬头：仅适用于美国机场，不适用于国际机场.

## TV Shows

* [Mr. Robot (USA)](http://api.tvmaze.com/singlesearch/shows?q=mr-robot&embed=episodes)
* [Better Call Saul (AMC)](http://api.tvmaze.com/singlesearch/shows?q=better-call-saul&embed=episodes)
* [Homeland (Showtime)](http://api.tvmaze.com/singlesearch/shows?q=Homeland&embed=episodes)
* [Silicon Valley (HBO)](http://api.tvmaze.com/singlesearch/shows?q=silicon-valley&embed=episodes)
* [The Walking Dead (AMC)](http://api.tvmaze.com/singlesearch/shows?q=the-walking-dead&embed=episodes)
* [South Park (Comedy Central)](http://api.tvmaze.com/singlesearch/shows?q=south-park&embed=episodes)
* [Game of Thrones (HBO)](http://api.tvmaze.com/singlesearch/shows?q=game-of-thrones&embed=episodes)
* [House of Cards (Netflix)](http://api.tvmaze.com/singlesearch/shows?q=house-of-cards&embed=episodes)
* [The Big Bang Theory (CBS)](http://api.tvmaze.com/singlesearch/shows?q=big-bang-theory&embed=episodes)
* [Narcos (Netflix)](http://api.tvmaze.com/singlesearch/shows?q=narcos&embed=episodes)
* [Black Mirror (Netflix)](http://api.tvmaze.com/singlesearch/shows?q=black-mirror&embed=episodes)
* [Stranger Things (Netflix)](http://api.tvmaze.com/singlesearch/shows?q=stranger-things&embed=episodes)
* [Rick and Morty (Adult Swim)](http://api.tvmaze.com/singlesearch/shows?q=rick-&-morty&embed=episodes)
* [Westworld (HBO)](http://api.tvmaze.com/singlesearch/shows?q=westworld&embed=episodes)

 &gt;专业提示：替换未列出的节目的字段值，例如`shows？q = show-name`.  更多的选择 [here](http://www.tvmaze.com/api)

*里克和莫蒂
  * [Get all characters](https://rickandmortyapi.com/api/character/)
  * [Get a single character](https://rickandmortyapi.com/api/character/2)
  * [Filter locations](https://rickandmortyapi.com/api/location/?name=earth)
  * [Get an episode](https://rickandmortyapi.com/api/episode/12)
  * [Get multiple episodes](https://rickandmortyapi.com/api/episode/10,28)

&gt;专业提示：更多选项 [https://rickandmortyapi.com/](https://rickandmortyapi.com/)

## Movies
* [Showtime](http://showtimes.everyday.in.th/api/v2/)
  * [Current Movies in Thailand](http://showtimes.everyday.in.th/api/v2/movie/)
  * [Movie Theaters in Thailand](http://showtimes.everyday.in.th/api/v2/theater/)

## Weather
* [Los Angeles](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Los%20Angeles%2C%20CA%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Chicago](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Chicago%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [New York](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22New%20York%2C%20NY%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Miami](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Miami%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [London](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22London%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Paris](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Paris%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Berlin](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Berlin%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Rome](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Rome%2C%20it%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys%29)
* [Moscow](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Moscow%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Jerusalem](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Jerusalem%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Tokyo](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Tokyo%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Sydney](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Sydney%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)
* [Buenos Aires](https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20%28select%20woeid%20from%20geo.places%281%29%20where%20text%3D%22Buenos%20Aires%2C%20CA%22%29&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys)

&gt;专业提示：为任何位置生成URL [Yahoo Weather API](https://developer.yahoo.com/weather/)

## More Awesome Lists
* [Awesome](https://github.com/sindresorhus/awesome) *（OG名单）*
* [Help Wanted](https://github.com/fullstackla/awesome-help-wanted) *（寻求帮助的开源项目）*
* [JSON](https://github.com/burningtree/awesome-json) *（图书馆和资源）*
* [WPO](https://github.com/davidsonfellipe/awesome-wpo) *（网络性能优化）*
* [Shell](https://github.com/alebcay/awesome-shell) *（CLI框架，工具包和指南）*
* [Public APIs](https://github.com/toddmotto/public-apis) *（用于Web开发的JSON API，其中一些需要身份验证）*
* [Public Datasets](https://github.com/caesar0301/awesome-public-datasets) *（超出JSON的数据集）*
* [Style Guides](https://github.com/kciter/awesome-style-guide) *（编程语言，平台，框架）*

## Contributing
如果您想贡献，请阅读 [contribution guidelines](https://github.com/jdorfman/awesome-json-datasets/blob/master/CONTRIBUTING.md).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [MaxCDN](https://www.maxcdn.com) 已放弃对此作品的所有版权及相关或相邻权利.
