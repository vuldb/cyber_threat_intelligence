# Azorult - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Azorult_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Azorult:

* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 15 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Azorult or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Ramnit](https://vuldb.com/?actor.ramnit) | High
2 | [Amadey Bot](https://vuldb.com/?actor.amadey_bot) | High
3 | [Azorult](https://vuldb.com/?actor.azorult) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Azorult.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [2.59.42.63](https://vuldb.com/?ip.2.59.42.63) | vds-cw08597.timeweb.ru | [Amadey Bot](https://vuldb.com/?actor.amadey_bot) | High
2 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | [Azorult](https://vuldb.com/?actor.azorult) | High
3 | [23.81.246.150](https://vuldb.com/?ip.23.81.246.150) | - | [AZORult and NanoCore](https://vuldb.com/?actor.azorult_and_nanocore) | High
4 | [23.106.124.148](https://vuldb.com/?ip.23.106.124.148) | - | [Azorult](https://vuldb.com/?actor.azorult) | High
5 | [23.221.227.176](https://vuldb.com/?ip.23.221.227.176) | a23-221-227-176.deploy.static.akamaitechnologies.com | [Azorult](https://vuldb.com/?actor.azorult) | High
6 | [23.247.102.10](https://vuldb.com/?ip.23.247.102.10) | word-finish.golddoubly.com | [AZORult and NanoCore](https://vuldb.com/?actor.azorult_and_nanocore) | High
7 | [34.117.59.81](https://vuldb.com/?ip.34.117.59.81) | 81.59.117.34.bc.googleusercontent.com | [Azorult](https://vuldb.com/?actor.azorult) | Medium
8 | [37.140.192.153](https://vuldb.com/?ip.37.140.192.153) | scp59.hosting.reg.ru | [Azorult](https://vuldb.com/?actor.azorult) | High
9 | [37.140.192.166](https://vuldb.com/?ip.37.140.192.166) | scp46.hosting.reg.ru | [Azorult](https://vuldb.com/?actor.azorult) | High
10 | [45.76.18.39](https://vuldb.com/?ip.45.76.18.39) | 45.76.18.39.vultrusercontent.com | [Azorult](https://vuldb.com/?actor.azorult) | High
11 | [45.139.236.14](https://vuldb.com/?ip.45.139.236.14) | - | [Azorult](https://vuldb.com/?actor.azorult) | High
12 | [45.140.147.214](https://vuldb.com/?ip.45.140.147.214) | vm1329418.stark-industries.solutions | [Azorult](https://vuldb.com/?actor.azorult) | High
13 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Azorult. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Azorult. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/ajax.php` | High
3 | File | `/admin/ajax.php?action=save_window` | High
4 | File | `/admin/article.php` | High
5 | File | `/admin/countrymanagement.php` | High
6 | File | `/admin/deluser.php` | High
7 | File | `/admin/transactions/track_shipment.php` | High
8 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
9 | File | `/admin/user/manage_user.php` | High
10 | File | `/administration/settings_registration.php` | High
11 | File | `/administration/theme.php` | High
12 | File | `/ajax-files/postComment.php` | High
13 | File | `/alert_check/action=delete_alert_checker/alert_test_id` | High
14 | File | `/auparse/auparse.c` | High
15 | File | `/aux` | Low
16 | File | `/BindAccount/SuccessTips.js` | High
17 | File | `/categorypage.php` | High
18 | File | `/cgi-bin/system_mgr.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/Master.php` | High
21 | File | `/collection/all` | High
22 | File | `/config/list` | Medium
23 | File | `/data/syslog.filter.json` | High
24 | File | `/data/wps.setup.json` | High
25 | File | `/forum/away.php` | High
26 | File | `/goform/QuickIndex` | High
27 | File | `/goform/SetInternetLanInfo` | High
28 | File | `/goform/setMacFilterCfg` | High
29 | File | `/goform/SetNetControlList` | High
30 | File | `/goform/WifiBasicSet` | High
31 | File | `/home.php` | Medium
32 | File | `/home/httpd/cgi-bin/cgi.cgi` | High
33 | File | `/index.php` | Medium
34 | File | `/iwgallery/pictures/details.asp` | High
35 | File | `/list_temp_photo_pin_upload.php` | High
36 | File | `/login.php` | Medium
37 | File | `/manage/network-basic.php` | High
38 | File | `/medical/inventories.php` | High
39 | File | `/news-portal-script/information.php` | High
40 | File | `/nova/bin/console` | High
41 | File | `/pages.php` | Medium
42 | File | `/pages/save_user.php` | High
43 | File | `/patient/doctors.php` | High
44 | File | `/PluXml/core/admin/parametres_edittpl.php` | High
45 | File | `/print.php` | Medium
46 | File | `/public/login.htm` | High
47 | File | `/reviewer/system/system/admins/manage/users/user-update.php` | High
48 | File | `/rom-0` | Low
49 | File | `/searchpin.php` | High
50 | File | `/services/Card/findUser` | High
51 | File | `/showfile.php` | High
52 | File | `/show_group_members.php` | High
53 | File | `/timeline2.php` | High
54 | File | `/uncpath/` | Medium
55 | File | `/uno/central.php` | High
56 | File | `/user/profile` | High
57 | File | `/user/ticket/create` | High
58 | File | `/usr/local/psa/admin/sbin/wrapper` | High
59 | ... | ... | ...

There are 519 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://1275.ru/ioc/308/gs-031-azorult-stealer-iocs/
* https://bazaar.abuse.ch/sample/1609eb4e44b1fa7f776e21ba522d7a83aa473df55e75fd7c49485685f09a6653/
* https://bazaar.abuse.ch/sample/7897cbf57b2a25446cedc1995c9950478a2c371c99ef87a0c82c7544742925f8/
* https://bazaar.abuse.ch/sample/c157531bb4d14cd35fc3ffe2a62fdd292f8e16566c663dcfbf083d75c4a94773/
* https://blog.cyble.com/2021/10/26/a-deep-dive-analysis-of-azorult-stealer/
* https://blog.talosintelligence.com/2020/01/threat-roundup-0117-0124.html
* https://blog.talosintelligence.com/threat-roundup-0630-0707-2/
* https://blogs.blackberry.com/en/2020/01/threat-spotlight-amadey-bot
* https://cert.gov.ua/article/2806
* https://isc.sans.edu/forums/diary/More+malspam+pushing+passwordprotected+Word+docs+for+AZORult+and+Hermes+Ransomware/23992/
* https://research.checkpoint.com/2018/new-ramnit-campaign-spreads-azorult-malware/
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=198.98.54.161
* https://tria.ge/220314-ymactadghk
* https://tria.ge/220602-c7n6tagcgn
* https://www.zscaler.com/blogs/research/multistage-freedom-loader-used-spread-azorult-and-nanocore-rat

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
