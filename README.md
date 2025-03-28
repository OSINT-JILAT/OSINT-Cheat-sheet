# OSINT CHEAT SHEET - List OSINT Tools

[![Github Badge](https://img.shields.io/badge/-Jieyab89-black?style=flat&logo=github&logoColor=white&link=https://github.com/Jieyab89/)](https://github.com/Jieyab89)

Contains a list of OSINT tools, OSINT tips, datasets, Maltego transform and others. There are free and paid tools you can use and owner is not responsible, only for knowledge or educational purposes. Sorry if some of the resources have closed the service or error owner doesn't always check what's going on with the resources here, thank you

# EXIF TOOL COMMAND

#Exif tag name and data type

> Artist                                        string
>
> Author                                        string
>
> Caption                                       string
>
> Categories                                    string
>
> Collections                                   string
>
> DateTime                                      date
>
> DPP                                           lang-alt
>
> EditStatus                                    string
>
> FixtureIdentifier                             string
>
> Keywords                                      string
>
> Notes                                         string
>
> ObjectCycle                                   string
>
> OriginatingProgram                            string
>
> Rating                                        real
>
> Rawrppused                                    boolean
>
> ReleaseDate                                   string
>
> ReleaseTime                                   string
>
> RPP                                           lang-alt
>
> Snapshots                                     string
>
> Tagged                                        boolean

More : man exiftool (Run on your terminal)

Site :

- [Exiftool](https://exiftool.org/)
- [List tagname](https://exiftool.org/TagNames/)
- [List tagnme 2](https://metacpan.org/dist/Image-ExifTool/view/lib/Image/ExifTool/TagNames.pod)
- [List tagname 3](https://manpages.org/imageexiftooltagnames/3)

#Write metadata

- exiftool -tagname="string" file
>
>example : exiftool -Author="Bayu" test.txt
>

you can add multiple tag and multiple file

#Delete metadata

- exiftool -tagname="" file
>
>example : exiftool -Author="" test.txt
>

#Delete mass metadata

- exiftool -all="" file
>
>example : exiftool -all="" file
>

#Usage : man exiftool or read documentation exiftool.org

> Not there are tag no writetable, make sure tagname can write
>

#!Note

> Use fresh file, if your file has been compressed or edit metadata you got a default metadata
> You can use xmp format for edit, write and delete metadata
> Check the documentation


# SOCMINT  

- [Instagram](https://github.com/Datalux/Osintgram)
Be carefull using this tool
- [Tinfoleak](https://github.com/vaguileradiaz/tinfoleak)
- [SOCMINT tool](https://osint.support/chrome-extensions/2019/09/29/osint-socmint-tooling.html)
- [Graph Search](http://socmint.tools/graph.htm)

# Collection Dataset

- [Kaggle](https://www.kaggle.com/)
- [AWS open data](https://registry.opendata.aws/)
- [Open Network](http://www.opendatanetwork.com/)
- [WHO Data](https://www.who.int/data/gho/)

# Forums

- [Bellingcat Discord](https://discord.com/invite/nTaNPmz)
- [Independent OSINT](https://discord.com/invite/2DGJ2EC)
- [OSINT.Team](https://osint.team)
- [Seccodeid](https://forum.seccodeid.com/category/osint)
- [/r/OSINT](https://www.reddit.com/r/OSINT)
- [TraceLabs Slack](https://discord.gg/tracelabs)

# General Search

- [ASK](http://www.ask.com)
- [Baidu](http://www.baidu.com)
- [DuckDuckGo](https://duckduckgo.com)
- [Yandex](https://www.yandex.com)
- [Infospace](http://www.infospace.com)

# Meta Search

- [100SearchEngines](https://www.100searchengines.com)
- [Bing vs. Google](http://bvsg.org)
- [DADgogo](http://dadgogo.com)
- [Etools](http://www.etools.ch)
- [WebCrawler](http://www.webcrawler.com)

# Code Search

- [Chromium Code Search](https://source.chromium.org/chromium)
- [Android Code Search](https://cs.android.com)
- [Code Finder](http://codefinder.org)
- [CodeSeek](https://www.codeseek.co)
- [Debian Code Search](http://codesearch.debian.net)
- [Scala](https://www.programcreek.com/scala)
- [SearchCode](https://searchcode.com)
- [SourceCodeOnline](http://www.sourcecodeonline.com)
- [Woboq](https://code.woboq.org)

# Competitive Programming

- [Hackerrank](https://www.hackerrank.com/)
- [Code chef](https://www.codechef.com/)
- [Code war](https://www.codewars.com/)

# File & FTP

- [Archie](http://archie.icm.edu.pl/archie_eng.html)
- [4shared](https://www.4shared.com)
- [FileSearching](http://www.filesearching.com)
- [File chef](https://www.filechef.com)
- [Global File Search](http://globalfilesearch.com)
- [Search Shared](https://www.searchshared.info)
- [MMNT](http://www.mmnt.ru)

# Social Media Search and Monitoring

- [Awario](https://awario.com)
- [Brand24](https://brand24.com)
- [Samdesk](https://www.samdesk.io)
- [Social Links](https://www.mtg-bi.com)
- [Social Searcher](https://www.social-searcher.com/)
- [Social Analyzer](https://github.com/qeeqbox/social-analyzer)

# Social Media Management and Content Discovery

- [Buffer](https://buffer.com)
- [Coosto](https://www.coosto.com)
- [Revive Social](https://revive.social)
- [Social Analyzer](https://github.com/qeeqbox/social-analyzer)

# Web Intelligence

- [Better Whois](http://www.betterwhois.com)
- [DNS History](http://dnshistory.org)
- [DNS Spy](https://dnsspy.io)
- [DNS Checker](https://dnschecker.org)
- [HackerTarget](https://hackertarget.com/ip-tools)
- [Shodan](https://www.shodan.io)
- [Wappalyzer](https://www.wappalyzer.com/)
- [Sudomy](https://github.com/screetsec/Sudomy)
- [Testssl](https://testssl.sh/)
- [Nmap](https://nmap.org/)
- [builtwith](https://builtwith.com/)
- [VirusTotal](https://www.virustotal.com/gui/)
- [Nessus](https://www.tenable.com/products/nessus)
- [Nikto](https://cirt.net/Nikto2)
- [Webshag](https://github.com/wereallfeds/webshag)
- [wayback machine](https://archive.org/web/)
- [Farsight DNSDB Transforms for Maltego](https://www.maltego.com/transform-hub/farsight-dnsdb/)
- [Web Screnshhot Maltego Transforms](https://github.com/TURROKS/Maltego_Web2Screenshot)
- [Nuclei](https://github.com/projectdiscovery/nuclei)

# Analysing URLs

- [Unfurl](https://github.com/obsidianforensics/unfurl)
- [VirusTotal](https://www.virustotal.com/gui/home/upload)
- [Archive Org](https://archive.org/web/)
- [Iplocation](https://iplocation.io/website-link-analyzer)
- [Smallseotools](https://smallseotools.com/website-link-analyzer-tool/)
- [Abuse IP](https://www.abuseipdb.com/)
- [Check Phish](https://checkphish.ai/)
- [Radar By Cloudflare](https://radar.cloudflare.com/)
- [Is it Phishing](https://isitphishing.org/)
- [Kaspersky](https://opentip.kaspersky.com/)
- [PolySwarm](https://polyswarm.network/)
- [Threat Miner](https://www.threatminer.org/)

# Researching Cyber Threats

- [Apility.io](https://apility.io)
- [Alien Vault](https://otx.alienvault.com)
- [AutoShun](https://www.autoshun.org)
- [Blacklist Check Tool](http://www.blchecktool.com)
- [Censys](https://censys.io)
- [CVE Details](https://www.cvedetails.com)
- [IBM X-Force Exchange](https://exchange.xforce.ibmcloud.com)
- [JoeSandbox Cloud](https://www.joesandbox.com)
- [Is It Hacked?](http://www.isithacked.com)
- [Is It Phishing](https://isitphishing.org)
- [Kaspersky Threat](https://opentip.kaspersky.com)
- [Malware Domain List](http://www.malwaredomainlist.com/mdl.php)
- [Malware URL Website](https://www.malwareurl.com/listing-urls.php)
- [Quttera](https://quttera.com)
- [Virus total](https://www.virustotal.com/gui/home/upload)
- [Virus Share](https://virusshare.com)
- [Web Cookies Scanner](https://webcookies.org)
- [Yara](https://yara.readthedocs.io/en/stable/)
- [Spiderfoot](https://www.spiderfoot.net/)
- [NVD](https://nvd.nist.gov/search)
- [Seclist](https://seclists.org/fulldisclosure/)
- [CVE Mitre](https://cve.mitre.org/cve/search_cve_list.html)
- [Malicious Check](https://forum.seccodeid.com/d/phishing-email-analysis-tools)
- [Email Header Analysis](https://mxtoolbox.com/EmailHeaders.aspx)
- [Url Scan]( https://urlscan.io/ )
- [AnyRun](https://any.run/)
- [Hybrid Analysis](https://www.hybrid-analysis.com/)
- [VMRay Sandbox](https://www.vmray.com/)
- [Browser Sandbox](https://www.browserling.com/)
- [Fillter Bypass](https://www.filterbypass.me/id)
- [Abuse IP DB](https://www.abuseipdb.com/)
- [Talos CTI](https://www.talosintelligence.com/)
- [Phishing Analysis Tool](https://www.phishtool.com/)
- [Phish Verification System](https://phishtank.org/)
- [PolySwarm](https://www.maltego.com/transform-hub/polyswarm/)
- [ThreatCrowd](https://www.maltego.com/transform-hub/threatcrowd/)
- [HYAS Insight](https://www.maltego.com/transform-hub/hyas-insight/)
- [Phishstats](https://phishstats.info/)
- [GitGuardian](https://www.gitguardian.com/monitor-public-github-for-secrets)
- [Rescure](https://rescure.me/feeds.html)
- [Kaspersky](https://opentip.kaspersky.com/)
- [PolySwarm](https://polyswarm.network/)
- [Darkfeed](https://darkfeed.io/)

# IoT Search Engines

- [LeakIX](https://leakix.net)
- [Binary Edge](https://www.binaryedge.io)
- [Shodan](https://www.shodan.io)
- [Shodan Filters](https://github.com/T43cr0wl3r/shodan-filters)
- [Shodan Scripts](https://github.com/random-robbie/My-Shodan-Scripts)

# IP Addresses

- [Whats my ip](https://whatismyipaddress.com/)
This tools can show your ip address isp provider
- [Ip 2 location](https://www.ip2location.com/)
This tools can show your ip address isp provider and geo location  

# Wireless Network

- [Wigle](https://www.wigle.net/)
Maps and database of 802.11 wireless networks, with statistics, submitted by wardrivers, netstumblers, and
net huggers
- [Fing Net Scan](https://www.fing.com/)
- [Wifianalyzer](https://www.wifianalyzer.info/)
- [Signalmonitoring](https://signalmonitoring.com/)
- [Angry Ip](https://angryip.org/)
- [Advanced ip scanner](https://www.advanced-ip-scanner.com/)
- [Wifimap](https://www.wifimap.io/)
- [Fon](https://fon.com/maps/)
- [SolarWInds](https://www.solarwinds.com/network-performance-monitor/use-cases/wifi-monitor)

# SOC & Threat Hunting

- [Alien Vault](https://otx.alienvault.com/)
- [Exploit db](https://www.exploit-db.com/)
- [AT&T](https://cybersecurity.att.com/resource-center#content_analyst-reports)
- [Yara](https://yara.readthedocs.io/en/stable/)
- [Virustotal](https://www.virustotal.com/gui/home/upload)
- [Joesandbox](https://www.joesandbox.com/#windows)
- [Spiderfoot](https://www.spiderfoot.net/)
- [Open CTI](https://github.com/OpenCTI-Platform/opencti)
- [Solarwinds](https://www.solarwinds.com/)
- [VMware Carbon Black Endpoint](https://www.vmware.com/products/carbon-black-cloud-endpoint.html)
- [Insightidr](https://www.rapid7.com/products/insightidr/)
- [MISP](https://www.misp-project.org/)
- [NVD](https://nvd.nist.gov/search)
- [Seclist](https://seclists.org/fulldisclosure/)
- [CVE Mitre](https://cve.mitre.org/cve/search_cve_list.html)
- [Whois Record](https://centralops.net/co/)
- [Abuse IP DB](https://www.abuseipdb.com/)
- [Talos CTI](https://www.talosintelligence.com/)
- [Darkfeed](https://darkfeed.io/)

Tips

You can find the file hash or other threat indicator

# Dorking

Dorking is a wonderful thing, you can use this technique to search for anything such as index of a website, looking for live online camera server and other specifics, as for dorking commands that you can do for example

1. intitle: Search for specific titles
2. inurl: Search for specific urls or paths
3. intext: Search for specific words or contects
4. filetype: Search for files
5. site: Search from a specified target
6. Wildcard or symbol * (star) Find all web pages, for example: seccodeid*
7. Define:term Search for all things with specified terms, example define:seccodeid
8. cache page Take a snapshot of an indexed page. Google uses this to find the right page for the query you're looking for. Website or target specifically
9. allintext: Searches for specific text contained on a web page
10. allinurl: Find various keywords in a URL
11. allintitle: Restricts results to those containing all terms specified in a title
12. link: List of web pages that have links to the specified URL
13. (|) Pipe. This is a logical operator, | "tips" will show all the sites which contain either, or both words
14. (+) Used to concatenate words, useful to detect pages that use more than one specific key
15. (-) Minus operator avoids showing results that contain certain words, e.g. security -trails will show pages that use "security" in their text, but not those that have the word "trails"

example
> intext:"hacking" site:seccodeid.com
> site:www.github.com ext:doc | ext:docx | ext:odt | ext:rtf | ext:sxw | ext:psw | ext:ppt | ext:pptx | ext:pps | ext:csv  

# Google Advanced Search Tools

- [Advanced google search](https://www.google.com/advanced_search)
- [Google Scholar](https://scholar.google.com)
- [Google Alerts](https://www.google.com/alerts)
- [Google Search History](https://myactivity.google.com/myactivity)

# Other Search Engines

- [us.searchboth.net](http://us.searchboth.net)
- [Archive.org](http://www.arhive.org)
- [Yandex](Yandex.com)
- [Pastebin](http://www.pastebin.com)
- [Topix.com](http://www.topix.com)
- [search.carrot2.org/stable/search](http://search.carrot2.org/stable/search)
- [Shodan](https://www.shodan.io/)
- [Piratebays](https://thepiratebays.com/)
- [Onesearch](https://www.onesearch.com/)
- [Searchencrypt](https://www.searchencrypt.com/home)
- [Duckgo](https://duckduckgo.com/)
- [Waymore](https://forum.seccodeid.com/d/waymore-find-way-more-from-the-wayback-machine)

# Internet Archive

- [Wayback Machine](https://web.archive.org/)
- [Intelligence X](https://intelx.io/)
- [Openlibrary](https://openlibrary.org/)
- [Archive Fo](https://archive.fo/)
- [UKWA](https://www.webarchive.org.uk/ukwa/)
- [Archive today](https://archive.vn/)
- [Waymore](https://forum.seccodeid.com/d/waymore-find-way-more-from-the-wayback-machine)

# Data Breached OSINT

- [Dehashed](https://www.dehashed.com/)
- [Haveibeenpwned](https://haveibeenpwned.com/)
- [Intelligence X](https://intelx.io/)
- [Wiki Leaks](https://wikileaks.org/)
- [DDO Secrets](https://ddosecrets.com/wiki/Distributed_Denial_of_Secrets)
- [Breached](https://breached.to/) Availabe on Darkweb
- [Dark Tracer](https://darktracer.com/)

# Crack Jurnals

- [SCI HUB](https://sci-hub.hkvisa.net/)
This domain will always change

# Search Jurnals

- [Libgen](https://libgen.is/)
- [Ieee](https://ieeexplore.ieee.org/Xplore/home.jsp)
- [Sciencedirect](https://www.sciencedirect.com/)
- [Sinta](https://sinta.kemdikbud.go.id/)
- [Scopus](https://www.scopus.com/)
- [Onesearch ID](https://onesearch.id/)

# Blogs Search Engine

- [Google Blog](www.google.com/blogsearch)
- [technorati](www.technorati.com)
- [omgili.com](http://omgili.com/)

# Darkweb Search Engines

- [Thehiddenwiki](http://thehiddenwiki.org)
- [Onion Link](http://www.onion.link)
- [MEMEX](https://memex.garden/)
- [Onion](https://onion.cab)
- [Onion city](https://onion.city/)
- [Ahmia](https://ahmia.fi/)
- [TorBot](https://github.com/DedSecInside/TorBot)
- [Darkfeed](https://darkfeed.io/)

# Tracking Website Changes

- [Changedetection](http://www.changedetection.com)
- [Followthatpage](http://www.followthatpage.com)

# Company Reconnaissance Sites (Passive)

- [whois](http://www.whois.net)
- [Netcraft](http://www.netcraft.com)
- [Hunter](https://hunter.io/)
- [SignalHire](https://www.signalhire.com/)

# People Searching

- [spokeo](http://www.spokeo.com)
- [123people](http://www.123people.com)
- [peepdb](http://www.peepdb.com)
- [reversegeni](http://www.reversegenie.com/plate.php)
- [PDDIKTI](https://pddikti.kemdikbud.go.id/)
- [SINTA](https://sinta.kemdikbud.go.id/)
- [Social Searcher](https://www.social-searcher.com/)
- [Pimeyes](https://pimeyes.com/en)
- [Rocketreach](https://rocketreach.co/)
- [SignalHire](https://www.signalhire.com/)

# Phone Numbers

- [argali](http://www.argali.com)
- [ciddb](http://www.ciddb.com/index.php)
- [cellrevealer](http://www.cellrevealer.com)
- [spydialer](http://www.spydialer.com)
- [Twilio](https://www.twilio.com/lookup)
- [Reverse lookup](https://www.reversephonelookup.com/)
- [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga)
- [Sync](https://sync.me/)
- [National cell](https://www.nationalcellulardirectory.com/)
- [Getcontact](https://www.getcontact.com/id/)
- [Moriarty-Project](https://github.com/AzizKpln/Moriarty-Project)
- [Get Contact](https://www.getcontact.com/en/)
- [True Caller](https://www.truecaller.com/)
- [Cell Id Lookup](https://www.reskrim.com/cek.php)
- [Device Info](https://www.deviceinfo.me/)
- [Cell Finder](https://cellidfinder.com/)
- [Unkownphone](https://www.unknownphone.com/)
- [Whocallsme](https://whocallsme.com/)
- [elenchitelefonici](https://www.elenchitelefonici.it/)
- [nationalcellulardirectory](https://www.nationalcellulardirectory.com/)
- [phonebooks](https://www.phonebooks.com/)
- [International Phone Directories](https://www.thisnumber.com/)
- [PhoneInfoga](https://demo.phoneinfoga.crvx.fr/#/)
- [Spy Dialer](https://spydialer.com/)
- [Phone Validator](https://www.phonevalidator.com/)
- [Fone finder](https://www.fonefinder.net/)
- [411 reverse phone](https://www.411.com/reverse-phone)
- [Number guru](https://www.numberguru.com/)
- [Zaba reverse phone](https://www.zabasearch.com/reverse-phone-lookup/)
- [FullContact](https://www.maltego.com/transform-hub/full-contact/)
- [HLR Lookup](https://www.hlrlookup.com/)
- [Ceebydith HLR Lookup](https://ceebydith.com/cek-hlr-lokasi-hp.html)
- [Free HLR](https://www.free-hlr.com/)
- [HLR Lookup API](https://www.hlr-lookups.com/)
- [Maltego Phone Search](https://www.maltego.com/transform-hub/phonesearch/)
- [SignalHire](https://www.signalhire.com/)
- [Emobiletracker](https://www.emobiletracker.com/)
- [OpenCNAM](https://docs.maltego.com/support/solutions/articles/15000045282-maltego-opencnam-transforms)
- [Fullcontact](https://www.fullcontact.com/)

# Public Records

- [Public Record](http://publicrecords.searchsystems.net)
- [Fam Watchdog](http://Familywatchdog.us)
- [Crime Reports](http://www.crimereports.com)

# Finding Usernames

- [Namechk](http://www.namechk.com)
- [Knowem](http://www.knowem.com)
- [Nexfil](https://github.com/thewhiteh4t/nexfil)
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [Instantusername](https://instantusername.com/#/)
- [Snitch](http://snitch.name/)
- [Checkusernames](https://checkusernames.com/)
- [Maigret](https://github.com/soxoj/maigret)

# Social Networks

- [Facebook](https://facebook.com/livemap)
- [Facebook lookup id](https://lookup-id.com/#)
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [Socialsearcher Users](https://www.social-searcher.com/)
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [Nexfil](https://github.com/thewhiteh4t/nexfil)
- [Googlesocialsearch](https://www.social-searcher.com/google-social-search/)
- [Google Social Network Transforms](https://www.maltego.com/transform-hub/google-programmable-search-engine-transforms/)
- [FullContact](https://www.maltego.com/transform-hub/full-contact/)
- [maigret](https://github.com/soxoj/maigret)

# Google Queries for Facebook

> Group Search: site:facebook.com inurl:group
>
> Group Wall Posts Search: site:facebook.com inurl:wall
>
> Pages Search: site:facebook.com inurl:pages
>
> Public Profiles: allinurl: people ‘‘name’’ site:facebook.com
>

# Facebook Query Language (FQL)

- [Findmyfbid](http://www.findmyfbid.com/)

> Photos By - https://www.facebook.com/search/taget_id/photos-by
>  
> Photos Liked - https://www.facebook.com/search/taget_id/photos-liked
>  
> Photos Of - https://www.facebook.com/search/taget_id/photos-of
>  
> Comments - https://www.facebook.com/search/taget_id/photos-commented
>  
> Friends - https://www.facebook.com/search/taget_id/friends
>  
> Videos Tagged - https://www.facebook.com/search/taget_id/videos
>  
> Videos By - https://www.facebook.com/search/taget_id/videos-by
>  
> Videos Liked - https://www.facebook.com/search/taget_id/videos-liked
>  
> Videos Commented - https://www.facebook.com/search/taget_id/videos-commented
>  
> Events Attended - https://www.facebook.com/search/taget_id/events-joined
>  
> Relatives - https://www.facebook.com/search/taget_id/relatives
>  

or you can use dork for spesific example

> id <this id facebook> site:facebook.com
>  
> page site: facebook.com
>
> id <this id facebook> site:facebook.com *
>
> page site: facebook.com *
>

# The Ultimate Facebook Investigation Tool

- [Intel Technique](https://inteltechniques.com/osint/facebook.html)
- [DumpItBlue](http://le-tools.com/DumpItBlue.html)
- [Fanpage Karma](http://www.fanpagekarma.com)
- [Facebook Search](http://search.fb.com/)
- [Fb-sleep-stats](https://github.com/sqren/fb-sleep-stats)
- [Lookup-ID.com](https://lookup-id.com)
- [SearchIsBack](https://searchisback.com)
- [Wolfram Alpha Facebook Report](http://www.wolframalpha.com/input/?i=facebook+report)

# Instagram

- [Hashtagify](http://hashtagify.me)
- [Iconosquare](http://iconosquare.com)
- [Picodash](https://www.picodash.com)
- [Toutatis](https://github.com/megadose/toutatis)
- [SearchMyBio](https://www.searchmy.bio/)
- [Dumpor](https://dumpor.com/)
- [Hookgram](https://hookgram.com/)

# Pinterest

- [Pingroupie](http://pingroupie.com)

# Twitter

- [search.twitter.com](https://twitter.com/search-home)
- [twitter advanced](https://www.twitter.com/search-advanced)
- [twitter who_to_follow](https://www.twitter.com/who_to_follow)
- [Backtweets](http://backtweets.com) BackTweets is a Twitter analytics tool that allows users to search through a Tweet archive.
- [First Tweet](http://ctrlq.org/first)
- [Foller.me](http://foller.me)
- [Followerwonk](http://followerwonk.com)
- [GeoSocial Footprint](http://geosocialfootprint.com)
- [Gigatweeter](http://gigatweeter.com)
- [Harvard TweetMap](http://worldmap.harvard.edu/tweetmap)
- [Hashtagify](http://hashtagify.me)
- [Hashtags.org](http://www.hashtags.org)
- [MyTweetAlerts](https://www.mytweetalerts.com/) A tool to create custom email alerts based on Twitter search.
- [OneMillionTweetMap](http://onemilliontweetmap.com)
- [SnapBird](http://snapbird.org)
- [Social Bearing](http://www.socialbearing.com)
- [Social Rank First Follower](http://socialrank.com/firstfollower)
- [Spoonbill](http://spoonbill.io)
- [Tagdef](https://tagdef.com)
- [TeachingPrivacy](http://app.teachingprivacy.com)
- [Tinfoleak](https://tinfoleak.com)
- [Trends24](http://trends24.in)
- [TrendsMap](http://trendsmap.com)
- [Ttrends](https://ttrends.co)
- [twbirthday](http://twbirthday.com)
- [TwChat](http://twchat.com)
- [tweepsect](http://tweepsect.com)
- [TweetArchivist](http://www.tweetarchivist.com)
- [TweetDeck](https://www.tweetdeck.com)
- [Tweeten](http://tweeten.xyz)
- [TweetMap](http://mapd.csail.mit.edu/tweetmap)
- [TweetMap](http://worldmap.harvard.edu/tweetmap)
- [TweetPsych](http://tweetpsych.com)
- [Tweetreach](http://tweetreach.com)
- [TweetStats](http://www.tweetstats.com)
- [TweetTunnel](http://tweettunnel.com)
- [Twellow](http://www.twellow.com)
- [Tweriod](http://www.tweriod.com)
- [Twiangulate](http://www.twiangulate.com)
- [Twilert](http://www.twilert.com)
- [Twipho](http://www.twipho.net)
- [Twitonomy](http://www.twitonomy.com)
- [TwitRSS](https://twitrss.me)
- [Twitter Advanced Search](https://twitter.com/search-advanced?lang=en)
- [Twitter Audit](https://www.twitteraudit.com)
- [Twitter Chat Schedule](http://tweetreports.com/twitter-chat-schedule)
- [Twitter Counter](http://twittercounter.com)
- [Twitterfall](http://twitterfall.com)
- [Twitter Search](http://search.twitter.com)
- [TWUBS Twitter Chat](http://twubs.com/twitter-chats)
- [Schedule Warble](https://warble.co)
- [Twint](https://github.com/twintproject/twint)

# Twitter Search Engines

- [tweetpaths](http://www.tweetpaths.com)
- [allmytweets](http://www.allmytweets.com)
- [Twimemachine](https://www.twimemachine.com)
- [inteltechniques](http://inteltechniques.com/osint/twitter.html)

# LinkedIn

Google queries for LinkedIn
> Public Profiles: site:linkedin.com inurl:pub
>  
> Updated Profiles: site:linkedin.com inurl:updates
>  
> Company Profiles: site:linkedin.com inurl:companies
>  

- [LinkedInDumper](https://github.com/l4rm4nd/LinkedInDumper)

# MySpace

Google queries for MySpace

> Profiles: site: myspace.com inurl:profile
>  
> Blogs: site:myspace.com inurl:blogs
>  
> Videos: site:myspace.com inurl:vids
>  
> Jobs: site:myspace.com inurl:jobs
>  
> Videos: site:myspace.com ‘‘TARGET NAME’’ ‘‘videos’’
>  
> Comments: site:myspace.com ‘‘TARGET NAME’’ ‘‘comments’’
>  
> Friends: site:myspace.com ‘‘TARGET NAME’’ ‘‘friends’’
>  

# Tiktok

- [tiktok-hashtag-analysis](https://github.com/bellingcat/tiktok-hashtag-analysis)

# Social Network Search Engines

- [socialmention](http://www.socialmention.com)

# Monitoring & Alerting

- [Pastebin Alerts](http://pastebin.com/u/alerts)
- [HaveIBeenPwned](http://www.haveIbeenpwned.com)
- [breachorclear](http://breachorclear.jesterscourt.cc)

# EXIF Analysis

- [regex](http://regex.info/exif.cgi)
- [FindExif](http://www.findexif.com)
- [metapicz](http://metapicz.com)
- [imageforensic](http://www.imageforensic.org)
- [metapicz](http://metapicz.com)
- [jimpl](https://jimpl.com/)
- [pic2map](https://www.pic2map.com/)

# Documents

- [Metashield Analyzer](https://metashieldanalyzer.elevenpaths.com/)
- [foca](https://github.com/ElevenPaths/FOCA)
- [Psbdmp](https://psbdmp.ws/)
- [Find PDF Doc](http://www.findpdfdoc.com/)

# Email Tracing

- [ip-adress](http://www.ip-adress.com/trace_email/)
- [whatismyipaddress](http://www.whatismyipaddress.com/trace-email)
- [hunter](https://hunter.io/)
- [email-checker](https://email-checker.net/)
- [verifyemailaddress](https://www.verifyemailaddress.org/)
- [SignalHire](https://www.signalhire.com/)
- [Holehe](https://github.com/megadose/holehe)
- [Holehe Maltego Transforms](https://github.com/megadose/holehe-maltego)
- [Spokeo](https://www.spokeo.com/email-search)
- [Mx Toolbox - Header Email](https://mxtoolbox.com/EmailHeaders.aspx)
- [getnotify](http://www.getnotify.com)

# IoT – Internet of Things

- [Cameraftp](https://www.cameraftp.com/cameraftp/publish/publishedcameras.aspx)
- [Earthcam](https://www.earthcam.com/)
- [Insecam](http://Insecam.org)
- [Shodan](https://Shodan.io)

# Shodan Query Options

> https://pen-testing.sans.org/blog/2015/12/08/effective-shodan-searches
>  
> https://danielmiessler.com/study/shodan/#gs.VBVsyo0
>  

# Capturing Information

- [DownloadHelper](https://www.downloadhelper.net/)
Firefox plugin that will assist in downloading all media from a website
- [Exif Viewer](https://addons.mozilla.org/en-US/firefox/addon/exif-viewer/)
- [HTTrack](https://www.httrack.com/)
- [Wayback Machine](https://archive.org/web/)

# OSINT TOOLS

- [Meta OSINT](https://metaosint.github.io/)
- [Shrelock](https://github.com/sherlock-project/sherlock)
- [Maltego](https://www.maltego.com/)
- [OSINT Framework](https://osintframework.com/)
- [Creepy](https://www.geocreepy.com/)
- [Twint](https://forum.seccodeid.com/d/twint-twitter-intelligence-tool)
- [Telegram OSINT](https://forum.seccodeid.com/d/telegram-nearby-map)
- [Recon-Ng](https://github.com/lanmaster53/recon-ng)
- [Metagoofil](https://www.kali.org/tools/metagoofil/)
- [tinfoleak](https://github.com/vaguileradiaz/tinfoleak)
- [maigret](https://github.com/soxoj/maigret)
- [mosint](https://github.com/alpkeskin/mosint)
- [osint_stuff_tool_collection](https://github.com/cipher387/osint_stuff_tool_collection)
- [instaloctrack](https://github.com/bernsteining/instaloctrack)
- [SpyScrap](https://github.com/RuthGnz/SpyScrap)
- [osintteye](https://github.com/rlyonheart/osinteye)
- [metagofil](https://github.com/kurobeats/metagoofil)
- [recon-ng](https://github.com/lanmaster53/recon-ng)
- [Harvester](https://github.com/laramies/theHarvester)
- [Geo creepy](http://www.geocreepy.com/)
- [trape](https://github.com/jofpin/trape)
- [ReconDog](https://github.com/s0md3v/ReconDog)
- [iKy](https://github.com/kennbroorg/iKy)
- [Ghunt](https://github.com/mxrch/GHunt)
- [Moriarty-Project](https://github.com/AzizKpln/Moriarty-Project)
- [Mr.Holmes](https://github.com/Lucksi/Mr.Holmes)
- [octosuite Advanced Github OSINT Framework](https://github.com/rly0nheart/octosuite.git)  
- [Toutatis](https://github.com/megadose/toutatis)  
- [A tool for OSINT based threat hunting](https://github.com/ninoseki/mihari)
- [K𝚊𝚛𝚖𝚊 𝚟𝟸 is a Passive Open Source Intelligence](https://github.com/Dheerajmadhukar/karma_v2)  
- [Secure ELF parsing/loading library for forensics reconstruction of malware, and robust reverse engineering tools](https://github.com/elfmaster/libelfmaster)  
- [OSINT tool that allows you to find a person's accounts and emails + breached email](https://github.com/Greyjedix/Profil3r)  
- [A tool to search Aviation-related intelligence from public sources](https://github.com/n0skill/AVOSINT)
- [PoC OSINT Discord user and guild information harvester](https://github.com/V3ntus/darvester)  
- [Automate downloading archived deleted Tweets](https://github.com/Mennaruuk/twayback)
- [Discover the location of nearby Telegram users](https://github.com/tejado/telegram-nearby-map)
- [OSINT Tool on Twitter and Instagram](https://github.com/xadhrit/terra)  
- [The World's simplest facial recognition api for python and the command line](https://github.com/ageitgey/face_recognition)
- [Automation and automation of digital forensic tools](https://github.com/google/turbinia)  
- [E4GL30S1NT](https://github.com/C0MPL3XDEV/E4GL30S1NT)
- [Commit stream finding Github repositories by extracting commit](https://github.com/x1sec/commit-stream)
- [SingleFile copy of an entire web page in a single HTML file](https://github.com/gildas-lormeau/SingleFile)
- [Photon Incredibly fast crawler designed for OSINT](https://github.com/s0md3v/Photon)
- [infoooze](https://github.com/devXprite/infoooze)
- [More](https://forum.seccodeid.com/?q=osint)

# OSINT Online Tool  

- [Echosec](https://www.echosec.net/)
- [Foller](https://foller.me/)
- [Tweet Deck](https://tweetdeck.twitter.com/)
- [Tweet Trips](https://www.tweetedtrips.com/)
- [Tweet Tonomy](http://www.twitonomy.com/)
- [Twinangulate](https://www.twiangulate.com/search/)
- [Geosocial](http://geosocialfootprint.com/)
- [Hash tracking](https://www.hashtracking.com/)
- [Bellingcat](https://www.bellingcat.com/)
- [Socmint tool](http://socmint.tools/)
- [Spyse](https://spyse.com/)
- [OSINT Combine](https://www.osintcombine.com/tools)
- [Cell Id Lookup](https://www.reskrim.com/cek.php)
- [Device Info](https://www.deviceinfo.me/)
- [Cell Finder](https://cellidfinder.com/)
- [GRABIFY IP](https://grabify.link/)
- [Cek Rekening](https://cekrekening.id/home)
- [Thatsthem](https://thatsthem.com/)
- [IntelligenceX](https://intelx.io/tools)

# Telegram Tool

Search channel, username anymore

- [Telegago](https://cse.google.com/cse?cx=006368593537057042503:efxu7xprihg#gsc.tab=0)
- [TelegramDB](http://www.telegramdb.org/)
- [Telegram Search Engine](https://xtea.io/)
- [Telegram Database: channels, groups and users](https://t.me/s/privatelinks)
- [Telegram channels and groups catalog](https://tgstat.com/)
- [Telegago](https://cse.google.com/)
- [Social Finder](https://socialfinder.app/list/Telegram)
- [Lyzem Search](https://lyzem.com/)
- [Discover The Best Telegram Channels](https://telegramchannels.me/)
- [Tele Channel Overiview](https://telemetr.io/)
- [telegram-phone-number-checker](https://github.com/bellingcat/telegram-phone-number-checker)
- [Telepathy](https://github.com/proseltd/Telepathy)

# Document and Slides Search

- [Authorstream](http://www.authorstream.com)
- [Find-pdf-doc](http://www.findpdfdoc.com)
- [Free Full PDF](http://www.freefullpdf.com)
- [PDF Search Engine](http://www.pdfsearchengine.info)
- [RECAP](http://archive.recapthelaw.org)
- [SlideShare](http://www.slideshare.net)
- [Scribd](http://www.scribd.com)
- [soPDF.com](http://www.sopdf.com)
- [FileChef](https://www.filechef.com/)
- [File Search Engine](https://www.filesearch.link/)
- [FilePursuit](https://filepursuit.com/)
- [NAPALM FTP Indexer](https://www.searchftps.net/)
- [Cryptome](https://cryptome.org/)
- [Finda PDF](https://www.findapdf.com/)
- [Find PDF Doc](http://www.findpdfdoc.com/)

# Real-Time Search, Social Media Search, and General Social Media Tools

- [Buffer](https://buffer.com)
- [Hashtatit](http://www.hashatit.com)
- [Rival IQ](https://www.rivaliq.com)
- [SocialBakers](http://www.socialbakers.com)
- [SociaBlade](http://socialblade.com)
- [Social Searcher](http://www.social-searcher.com)
- [Mail.Ru Social Network Search](https://go.mail.ru/search_social)
- [WATools](https://watools.io/)
- [Profil3r](https://github.com/Rog3rSm1th/Profil3r)
- [Oblivion](https://github.com/loseys/Oblivion)
- [Social Analyzer](https://github.com/qeeqbox/social-analyzer)

# Image Search

- [7Photos](http://7photos.net)
- [Baidu Images](http://image.baidu.com)
- [Bing Images](http://www.bing.com/images)
- [Clarify](http://clarify.io)
- [Flickr](https://secure.flickr.com)
- [GoodSearch Image Search](http://www.goodsearch.com/search-image)
- [Google Image](https://images.google.com)
- [Image Identification Project](https://www.imageidentify.com)
- [MyPicsMap](http://www.mypicsmap.com)
- [PhotoBucket](http://photobucket.com)
- [Picsearch](http://www.picsearch.com)
- [PicTriev](http://www.pictriev.com)
- [StolenCameraFinder](http://www.stolencamerafinder.co.uk)
- [TinEye](https://tineye.com) - Reverse image search engine.
- [Worldcam](http://www.worldc.am)
- [Yahoo Image Search](https://images.search.yahoo.com)
- [Yandex Images](https://www.yandex.com/images)
- [Betaface](https://www.betaface.com/demo.html)
- [Search4faces](https://search4faces.com/)
- [Pimeyes](https://pimeyes.com/en)
- [Reminiai](https://remini.ai/)
- [Search4face](https://search4faces.com/en/)
- [Vkfacewatch](https://vk.watch/)
- [Facecheck](https://facecheck.id/)
- [Findmyclone](https://www.findmyclone.com/)
- [Face++](https://www.faceplusplus.com/)
- [AWS-Recon](https://aws.amazon.com/rekognition/)
- [Azure vidio indexer](https://vi.microsoft.com/en-us)

# Image Analysis

- [ExifTool](https://exiftool.org/)
- [Exif Search](http://www.exif-search.com)
- [FotoForensics](http://www.fotoforensics.com)
- [Gbimg.org](http://gbimg.org)
- [Ghiro](http://www.getghiro.org)
- [ImpulseAdventure](http://www.impulseadventure.com/photo/jpeg-snoop.html)
- [Jeffreys Image Metadata Viewer](http://exif.regex.info/)
- [JPEGsnoop](https://sourceforge.net/projects/jpegsnoop)
- [Metapicz](http://metapicz.com/)
- [Forensically](https://29a.ch/photo-forensics/)
- [DiffChecker](https://www.diffchecker.com/image-diff/)
- [ImgOps](https://imgops.com/)
- [Pimeyes](https://pimeyes.com/en)
- [Reminiai](https://remini.ai/)
- [Search4face](https://search4faces.com/en/)
- [Vkfacewatch](https://vk.watch/)
- [Facecheck](https://facecheck.id/)
- [Findmyclone](https://www.findmyclone.com/)
- [Face++](https://www.faceplusplus.com/)
- [AWS-Recon](https://aws.amazon.com/rekognition/)
- [Image Analyzer](https://www.maltego.com/transform-hub/image-analyzer/)
- [Pelock](https://www.pelock.com/products/steganography-online-codec)

# Stock Images

- [AlltheFreeStock](http://allthefreestock.com)
- [Death to Stock](http://deathtothestockphoto.com)
- [Freeimages](http://www.freeimages.com)
- [Freestocks.org](http://freestocks.org)
- [Gratisography](http://www.gratisography.com)
- [IM Free](http://www.imcreator.com/free)
- [ISO Republic](http://isorepublic.com)
- [iStockphoto](http://www.istockphoto.com)
- [Kaboompics](http://kaboompics.com)
- [LibreStock](https://librestock.com)
- [Life of Pix](http://www.lifeofpix.com)
- [NegativeSpace](http://negativespace.co)
- [New Old Stock](http://nos.twnsnd.co)
- [Pixabay](https://pixabay.com)
- [Pexels](https://www.pexels.com)
- [Stocksnap](https://stocksnap.io)
- [Shutterstock](http://www.shutterstock.com)
- [tookapic](https://stock.tookapic.com)
- [Unsplash](https://unsplash.com)
- [Pimeyes](https://pimeyes.com/en)

# Video Search and Other Video Tools

- [Aol Videos](http://on.aol.com)
- [Bing Videos](http://www.bing.com/?scope=video)
- [Blinkx](http://www.blinkx.com)
- [Clarify](http://clarify.io)
- [Clip Blast](http://www.clipblast.com)
- [DailyMotion](http://www.dailymotion.com)
- [Deturl](http://deturl.com)
- [DownloadHealper](http://www.downloadhelper.net)
- [Earthcam](http://www.earthcam.com)
- [Insecam](http://insecam.org/)
- [Frame by Frame](https://chrome.google.com/webstore/detail/frame-by-frame/cclnaabdfgnehogonpeddbgejclcjneh/)
Browser plugin that allows you to watch YouTube videos frame by frame.
- [Geosearch](http://www.geosearchtool.com)
- [Internet Archive: Open Source Videos](https://archive.org/details/opensource_movies)
- [LiveLeak](http://www.liveleak.com)
- [Metacafe](http://www.metacafe.com)
- [Metatube](http://www.metatube.com)
- [Montage](https://montage.storyful.com)
- [Veoh](http://www.veoh.com)
- [Vimeo](https://vimeo.com)
- [Voxalead](http://voxalead.labs.exalead.com)
- [Yahoo Video Search](http://video.search.yahoo.com)
- [YouTube](https://www.youtube.com)
- [YouTube Data Viewer](https://www.amnestyusa.org/citizenevidence)
- [ccSUBS](http://ccsubs.com/) Download Closed Captions & Subtitles from YouTube
- [YouTube Metadata](https://mattw.io/youtube-metadata/)
- [YouTube Geofind](https://mattw.io/youtube-geofind/)
- [Video Stabilization Methods](https://github.com/yaochih/awesome-video-stabilization)
- [Azure vidio indexer](https://vi.microsoft.com/en-us)

# Geospatial Research and Mapping Tools

- [Atlasify](http://www.atlasify.com)
- [Batchgeo](http://batchgeo.com)
- [Bing Maps](http://www.bing.com/maps)
- [CartoDB](https://cartodb.com)
- [Colorbrewer](http://colorbrewer2.org)
- [CrowdMap](https://crowdmap.com)
- [Dominoc925](https://dominoc925-pages.appspot.com/mapplets/cs_mgrs.html)
- [DualMaps](https://www.mapchannels.com/dualmaps7/map.htm)
- [GeoGig](http://geogig.org)
- [GeoNames](http://www.geonames.org)
- [Esri](http://www.esri.com)
- [Flash Earth](http://www.flashearth.com)
- [Google Earth](http://www.google.com/earth)
- [Google Earth Pro](https://www.google.com/intl/en/earth/versions/#earth-pro)
- [Google Maps](https://www.google.com/maps)
- [Google Maps Streetview Player](http://brianfolts.com/driver)
- [Google My Maps](https://www.google.com/maps/about/mymaps)
- [GPSVisualizer](http://www.gpsvisualizer.com)
- [GrassGIS](http://grass.osgeo.org)
- [Here](http://here.com)
- [Hyperlapse](https://github.com/TeehanLax/Hyperlapse.js)
- [Inspire Geoportal](http://inspire-geoportal.ec.europa.eu)
- [InstantAtlas](http://www.instantatlas.com)
- [Instant Google Street View](http://www.instantstreetview.com)
- [Kartograph](http://kartograph.org)
- [Leaflet](http://leafletjs.com)
- [MapAList](http://mapalist.com)
- [MapBox](https://www.mapbox.com)
- [Mapbuildr](https://mapbuildr.com)
- [Mapchart.net](https://mapchart.net)
- [Maperitive](http://maperitive.net)
- [MapHub](https://maphub.net)
- [MapJam](http://mapjam.com)
- [Mapline](https://mapline.com)
- [Map Maker](https://maps.co)
- [Mapquest](https://www.mapquest.com)
- [Modest Maps](http://modestmaps.com)
- [NGA GEOINT](https://github.com/ngageoint)
- [OpenLayers](http://openlayers.org)
- [Polymaps](http://polymaps.org)
- [Perry Castaneda Library](https://www.lib.utexas.edu/maps)
- [Open Street Map](http://www.openstreetmap.org)
- [QGIS](http://qgis.org)
- [QuickMaps](https://chrome.google.com/webstore/detail/quick-maps/bgbojmobaekecckmomemopckmeipecij)
- [Scribble Maps](http://scribblemaps.com)
- [Terrapattern](http://www.terrapattern.com)
- [Tableau](http://www.tableausoftware.com)
- [Timescape](https://www.timescape.io)
- [View in Google Earth](http://www.mgmaps.com/kml/#view)
- [Wikimapia](http://wikimapia.org)
- [World Aeronautical Database](http://worldaerodata.com)
- [WorldMap Harvard](http://worldmap.harvard.edu)
- [ViaMichelin](http://www.viamichelin.com)
- [Yahoo Maps](https://maps.yahoo.com)
- [Zeemaps](https://www.zeemaps.com)
- [Sentinel Hub](https://www.sentinel-hub.com/explore/sentinelplayground/)
- [Maxar](https://discover.digitalglobe.com/)
- [USGS (EarthExplorer)](https://earthexplorer.usgs.gov/)
- [Zoom Earth](https://zoom.earth/)
- [Remote Pixel](https://remotepixel.ca/projects/index.html)
- [SunCalc](https://www.suncalc.org/)
- [ArcGIS](https://livingatlas.arcgis.com/en/browse/)
- [Pic2Map](https://www.pic2map.com/)
- [Mapillary](https://www.mapillary.com/app/)
- [KartaView](https://kartaview.org/map/)
- [Satellites Pro](https://satellites.pro/)
- [Liveuamap](https://liveuamap.com/)
- [Descartes Labs](https://maps.descarteslabs.com/)
- [Baidu Maps](https://map.baidu.com/)
- [MapChecking](https://www.mapchecking.com/)
- [Windy](https://www.windy.com/)
- [SOAR](https://soar.earth/)
- [digiKam](https://www.digikam.org/)
- [geoq](https://github.com/ngageoint/geoq)
- [gvision](https://github.com/GONZOsint/gvision)

# Fact Checking

- [About Urban Legends](http://urbanlegends.about.com)
- [Captin Fact](https://captainfact.io/)
- [Check](https://meedan.com/check)
- [Citizen Desk](https://www.sourcefabric.org/en/citizendesk)
- [Emergent](http://www.emergent.info)
- [Fact Check](http://www.factcheck.org)
- [Full Fact](https://fullfact.org)
- [MediaBugs](http://mediabugs.org)
- [Snopes](http://www.snopes.com)
The definitive Internet reference source for urban legends, folklore, myths, rumors, and misinformation.
- [Verification Handbook](http://verificationhandbook.com)
- [Verification Junkie](http://verificationjunkie.com)
- [Verily](https://veri.ly)

# Server Information Gathering

- [Testssl](https://testssl.sh/)
- [Nesus](https://www.tenable.com/products/nessus)

# CTF Analysis

- [Cybercheff](https://gchq.github.io/CyberChef/)
- [Bettercap](https://github.com/bettercap/bettercap)
Framework to perform MITM (Man in the Middle) attacks.
- [Yersinia](https://github.com/tomac/yersinia)
A framework for layer 2 attacks
- [FeatherDuster](https://github.com/nccgroup/featherduster)
An automated, modular cryptanalysis tool
- [Hash Extender](https://github.com/iagox86/hash_extender)
A utility tool for performing hash length extension attacks
- [Hashcat](https://hashcat.net/hashcat/)
Password cracking
- [DLLInjector ](https://github.com/OpenSecurityResearch/dllinjector)
Inject dlls in processes
- [Metasploit](https://www.metasploit.com/)
Penetration testing software and exploit
- [Pwntools](https://github.com/Gallopsled/pwntools)
CTF framework and exploit development library
- [ROPgadget](https://github.com/JonathanSalwan/ROPgadget)
Framework for ROP exploitation
- [Exiftool](https://exiftool.org/)
Read, write and edit file metadata
- [Malzilla](https://malzilla.sourceforge.net/downloads.html)
Malware hunting tool
- [Zmap](https://zmap.io/)
An open-source network scanner.
- [Nmap](https://nmap.org/)
Net mapping and port scanner
- [Wireshark](https://www.wireshark.org/)
Analyze the network dumps
- [Apktool](https://ibotpeaches.github.io/Apktool/)
Android Decompiler
- [Ninja Binary](https://binary.ninja/)
Binary analysis framework
- [Binwalk](https://github.com/ReFirmLabs/binwalk)
Analyze, reverse engineer, and extract firmware images
- [GDB](https://www.sourceware.org/gdb/)
The GNU project debugger
- [GEF](https://github.com/hugsy/gef)
Advanced debugging capabilities for exploit devs & reverse engineers on Linux
- [IDA](https://www.hex-rays.com/ida-pro/)
Most used Reversing software
- [PEDA](https://github.com/longld/peda)
Python Exploit Development Assistance for GDB
- [Radare2](https://github.com/radareorg/radare2)
UNIX-like reverse engineering framework and command-line toolset
- [Windbg](http://www.windbg.org/)
Windows debugger distributed by Microsoft
- [Boomerang](https://github.com/BoomerangDecompiler/boomerang)
Decompile x86 binaries to C
- [Detox](http://relentless-coding.org/projects/jsdetox/install)
A Javascript malware analysis tool
- [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur)
Restoration of defocused and blurred photos/images
- [ImageMagick](http://www.imagemagick.org/script/index.php)
Tool for manipulating images
- [Exiv2](https://exiv2.org/manpage.html)
Image metadata manipulation tool
- [Stegbreak](https://linux.die.net/man/1/stegbreak)
Launches brute-force dictionary attacks on JPG image
- [Steghide](https://steghide.sourceforge.net/)
Hide data in various kind of images
- [Stegsolve](https://github.com/zardus/ctf-tools/blob/master/stegsolve/install)
Apply various steganography techniques to images
- [SearchSploit](https://www.exploit-db.com/searchsploit)
Command line search tool for Exploit-DB
- [Exploitalert](https://www.exploitalert.com/browse-exploit.html)

# Zero Day

- [0day](https://0day.today/)
- [Zerodium](https://zerodium.com/)
- [0day fans](https://0dayfans.com/)

# Cryptocurrency Investigation

- [Blockchain](https://www.blockchain.com/)
- [Flashpoint](https://flashpoint.io/resources/research/flashpoint-and-chainalysis-investigate-hydra-where-cryptocurrency-cybercrime-goes-dark/)
- [Intel471](https://intel471.com/)
- [Tatum](https://tatum.io/)
- [Ciphertrace](https://ciphertrace.com/)
- [Bitcoin Abuse](https://www.bitcoinabuse.com/)
- [Blockchain-Info](https://www.maltego.com/transform-hub/blockchain-info/)
- [GraphSense](https://github.com/INTERPOL-Innovation-Centre/GraphSense-Maltego-transform)

# Cell Investigation

- [Opencellid](https://opencellid.org/)
- [CellTower Locator - Cell2gps](http://www.cell2gps.com/)
- [Cell-id Query](https://www.cell-id.info/?lang=en)
- [Location API](unwiredlabs)
- [Cell Mapping](https://www.cellmapper.net/)
- [Global Internet Infrastructure Map](https://www.infrapedia.com/)
- [Spy Dialer](https://spydialer.com/)
- [Phone Validator](https://www.phonevalidator.com/)
- [Free Operator Search](https://freecarrierlookup.com/)
- [HLR Lookup](https://www.hlrlookup.com/)
- [Ceebydith HLR Lookup](https://ceebydith.com/cek-hlr-lokasi-hp.html)
- [Free HLR](https://www.free-hlr.com/)
- [HLR Lookup API](https://www.hlr-lookups.com/)
- [Maltego Phone Search](https://www.maltego.com/transform-hub/phonesearch/)
- [Emobiletracker](https://www.emobiletracker.com/)
- [Phone Validator](https://www.phonevalidator.com/index.aspx)
- [Reverse Phone](https://www.reversephonecheck.com/)
- [Reverse Phone Lookup](https://www.reversephonelookup.com/)
- [OpenCNAM](https://docs.maltego.com/support/solutions/articles/15000045282-maltego-opencnam-transforms)
- [Search Country Operator (IMSI)](https://www.heicard.com/en/operator.html)
- [Analysis of IMSI numbers](https://www.numberingplans.com/?page=analysis&sub=imsinr)
- [World MCC & MNC Code](https://en.wikipedia.org/wiki/Mobile_country_code)
- [World MCC & MNC Code 2](https://www.mcc-mnc.com/)
- [World Mobile Network Code](https://en.wikipedia.org/wiki/Mobile_network_codes_in_ITU_region_5xx_(Oceania))
- [World Network Coverage](https://www.nperf.com/en/map/ID/-/-/signal/?ll=-2.5678942164342513&lg=118.01999999999998&zoom=5)
- [Profone GSM Tracker](https://cellphonetrackers.org/gsm/gsm-tracker.php)

# IMEI Investigation

- [SNDeepinfo](https://sndeep.info/)
- [Imei Numbers](http://imei-number.com/)
- [Nobbi](http://www.nobbi.com/)
- [IMEI Info](https://www.imei.info/)
- [International Numberingplans](https://www.numberingplans.com/)
- [IPhone IMEI](https://iunlocker.com/en/check_imei.php)

# Chat Apps Investigation

WhatsApp

- [Analyze your WhatsApp Chat](https://whatsanalyze-80665.web.app/)
- [Chat Visualizer](https://chatvisualizer.com/)
- [WhatsApp Group Links](https://whatsgrouplink.com/)
- [Download WhatsApp Profile Picture](https://watools.io/download-profile-picture)

Telegram

- [TelegramDB](http://www.telegramdb.org/)
- [Telegram Search Engine](https://xtea.io/)
- [Telegram Database: channels, groups and users](https://t.me/s/privatelinks)
- [Telegram channels and groups catalog](https://tgstat.com/)
- [Telegago](https://cse.google.com/)
- [Social Finder](https://socialfinder.app/list/Telegram)
- [Lyzem Search](https://lyzem.com/)
- [Discover The Best Telegram Channels](https://telegramchannels.me/)
- [Tele Channel Overiview](https://telemetr.io/)

# Build Sockpuppet Accounts

Build your sockpuppet account and proctect your privacy

- [Thispersondoesnotexist](https://www.thispersondoesnotexist.com/)
- [Protonmail](https://protonmail.com/)
- [Nordvpn](https://nordvpn.com/)
- [NOX](https://www.bignox.com/)
- [Browser Extension](https://nordvpn.com/blog/use-these-browser-extensions-for-your-privacy/)
- [Burner Phone Number](https://www.mintmobile.com/)
- [Phone Burner](https://www.phoneburner.com/)
- [Hushed](https://hushed.com/)
- [Temp Phone Number](https://temporary-phone-number.com/)
- [Temp Mail 1](https://mail.tm/en/)
- [Temp Mail 2](https://temp-mail.org/en/)
- [Temp Mail 3](https://tempmailo.com/)
- [Cryptocurrency Payment Monero](https://www.getmonero.org/)
- [Cryptocurrency Payment Bitcoin](https://bitcoin.org/en/)
- [Openpgp](https://www.openpgp.org/)
- [Operating System](https://tails.boum.org/)
- [Zmail](https://zmail.sourceforge.net/)
- [Open DNS](https://www.opendns.com/home-internet-security/)
- [I2P](https://geti2p.net/en/)
- [TOR](https://www.torproject.org/download/)

Social Network and blogging

- Wordpress
- Blogger
- Medium  
- Facebook
- Instagram

# Enhance Image Quality

- [Letsenhance](https://letsenhance.io/)
- [Cutout](https://www.cutout.pro/photo-enhancer-sharpener-upscaler)
- [Upscale](https://upscalepics.com/)
- [Canva](https://www.canva.com/features/image-enhancer/)
- [Adobe](https://www.adobe.com/express/feature/image/enhance)
- [Picwish](https://picwish.com/unblur-image-portrait)
- [Fotor](https://www.fotor.com/features/unblur-image/)
- [SIUN](https://github.com/minyuanye/SIUN)
- [DPED](https://github.com/aiff22/DPED)
- [neural-enhance](https://dockship.io/model/neural-enhance/5de4333901afe15d4ec10393)
- [neural-enhance](https://github.com/alexjc/neural-enhance)
- [Reminiai](https://remini.ai/)
- [Depix](https://github.com/beurtschipper/Depix)
- [Realesrgan](https://replicate.com/xinntao/realesrgan)  

# Locations Data Mapping

- [Google maps](https://www.google.co.id/maps)
- [Social geo lens](https://www.osintcombine.com/social-geo-lens)
- [Open street map](https://www.openstreetmap.org/)
- [Google Maps Geocoding](https://www.maltego.com/transform-hub/google-maps-geocoding-transforms/)
- [Googleearthengine](https://earthengine.google.com/#intro)

# Discord Server Search  

- [Discord servers](https://discordservers.com/)
- [Discover servers](https://disboard.org/)
- [Discord history tracker](https://www.dht.chylex.com/)  

# Darkweb Intelligence

- [Dark Tracer](https://darktracer.com/)
- [Darkweb bookmarks](https://www.osintcombine.com/dw-osint-bookmarks)
- [Maltego digital shadows transform](https://www.maltego.com/transform-hub/digital-shadows/)
- [Maltego cybersixgill transform](https://www.maltego.com/transform-hub/cybersixgill/)
- [Doge Darknet Osint Graph Explorer](https://github.com/pielco11/DOGE)
- [Maltego social links professional transform](https://www.maltego.com/transform-hub/social-links-pro/)
- [TorBot](https://github.com/DedSecInside/TorBot)
- [Darkfeed](https://darkfeed.io/)

# Digital Forensics

- [MISP](https://www.misp-project.org/)
- [Maltego](https://www.maltego.com/)
- [Filesec](https://filesec.io/)
- [Lolbas](https://lolbas-project.github.io/)
- [Logstash kibana](https://www.elastic.co/logstash/)
- [Kibana](https://www.elastic.co/kibana/)
- [Extundelete Ext3 or ext4 partition recovery](https://extundelete.sourceforge.net/)
- [TestDisk](https://www.cgsecurity.org/wiki/TestDisk_Download)
- [VirusTotal](https://www.virustotal.com/gui/home/upload)
- [Avilla Forensics](https://forum.seccodeid.com/d/avillaforensics-mobile-digital-forensics)
- [Autopsy](https://www.autopsy.com/)
- [Recuva](https://www.ccleaner.com/recuva)
- [Magnetforensics](https://www.magnetforensics.com/free-tools/)
- [Opentxt](https://www.opentext.com/products/security-cloud)
- [Ntfstool Forensics](https://forum.seccodeid.com/d/ntfstool-forensics-tool-for-ntfs-parser-mft-bitlocker-deleted-files)
- [Sleuthkit](https://www.sleuthkit.org/sleuthkit/)
- [SIFT SANS](https://www.sans.org/tools/sift-workstation/)
- [SIFT CLI](https://github.com/teamdfir/sift-cli/releases/tag/v1.8.5)
- [HYAS Insight](https://www.maltego.com/transform-hub/hyas-insight/)

# Write Your Investigation

- [Yoga](https://github.com/WebBreacher/yoga)
- [Malteo CaseFile](https://docs.maltego.com/support/solutions/articles/15000018948-what-is-maltego-casefile-)

# Securing Your Privacy

- [Eraser](https://eraser.heidi.ie/)
- [Thunderbird](https://www.thunderbird.net/en-US/)
- [Ublock origin](https://github.com/gorhill/uBlock)
- [Zmail](https://zmail.sourceforge.net/)
- [Open DNS](https://www.opendns.com/home-internet-security/)
- [I2P](https://geti2p.net/en/)
- [Gnupg](https://gnupg.org/)
- [HTTPS Everywhere](https://www.eff.org/https-everywhere/)
- [Pelock](https://www.pelock.com/products/steganography-online-codec)
- [Tails OS](https://tails.boum.org/)
- [WOT](https://www.mywot.com/)
- [Temp Mail 1](https://mail.tm/en/)
- [Temp Mail 2](https://temp-mail.org/en/)
- [Temp Mail 3](https://tempmailo.com/)
- [Phone Burner](https://www.phoneburner.com/)
- [Hushed](https://hushed.com/)

Payment

- [Bitcoin](https://bitcoin.org/id/)
- [Monero](https://www.getmonero.org/)

# Fraud Checker

- [Cek Rekening](https://cekrekening.id/home) - Indonesian By Kominfo
- [Kredibel](https://www.kredibel.com/) - Indonesian
- [Verihub](https://verihubs.com/) - Indonesian
- [Scamadviser](https://www.maltego.com/transform-hub/scamadviser/)
- [Ipqualityscore](https://docs.maltego.com/support/solutions/articles/15000041408-maltego-ipqualityscore-transforms#overview-0-0)
- [OpenCNAM](https://docs.maltego.com/support/solutions/articles/15000045282-maltego-opencnam-transforms)
- [Fullcontact](https://www.fullcontact.com/)
