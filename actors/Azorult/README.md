# Azorult - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Azorult](https://vuldb.com/?actor.azorult). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.azorult](https://vuldb.com/?actor.azorult)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Azorult:

* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Azorult.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
2 | [23.106.124.148](https://vuldb.com/?ip.23.106.124.148) | - | - | High
3 | [23.221.227.176](https://vuldb.com/?ip.23.221.227.176) | a23-221-227-176.deploy.static.akamaitechnologies.com | - | High
4 | [34.117.59.81](https://vuldb.com/?ip.34.117.59.81) | 81.59.117.34.bc.googleusercontent.com | - | Medium
5 | [37.140.192.153](https://vuldb.com/?ip.37.140.192.153) | scp59.hosting.reg.ru | - | High
6 | [37.140.192.166](https://vuldb.com/?ip.37.140.192.166) | scp46.hosting.reg.ru | - | High
7 | [45.76.18.39](https://vuldb.com/?ip.45.76.18.39) | 45.76.18.39.vultrusercontent.com | - | High
8 | [45.139.236.14](https://vuldb.com/?ip.45.139.236.14) | - | - | High
9 | [45.140.147.214](https://vuldb.com/?ip.45.140.147.214) | vm1329418.stark-industries.solutions | - | High
10 | [46.183.221.76](https://vuldb.com/?ip.46.183.221.76) | ip-221-76.dataclub.info | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Azorult_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Azorult. This data is unique as it uses our predictive model for actor profiling.

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
21 | File | `/config/list` | Medium
22 | File | `/data/syslog.filter.json` | High
23 | File | `/data/wps.setup.json` | High
24 | File | `/forum/away.php` | High
25 | File | `/goform/QuickIndex` | High
26 | File | `/goform/SetInternetLanInfo` | High
27 | File | `/goform/setMacFilterCfg` | High
28 | File | `/goform/SetNetControlList` | High
29 | File | `/goform/WifiBasicSet` | High
30 | File | `/home.php` | Medium
31 | File | `/home/httpd/cgi-bin/cgi.cgi` | High
32 | File | `/iwgallery/pictures/details.asp` | High
33 | File | `/list_temp_photo_pin_upload.php` | High
34 | File | `/login.php` | Medium
35 | File | `/manage/network-basic.php` | High
36 | File | `/medical/inventories.php` | High
37 | File | `/news-portal-script/information.php` | High
38 | File | `/nova/bin/console` | High
39 | File | `/pages.php` | Medium
40 | File | `/pages/save_user.php` | High
41 | File | `/patient/doctors.php` | High
42 | File | `/PluXml/core/admin/parametres_edittpl.php` | High
43 | File | `/print.php` | Medium
44 | File | `/public/login.htm` | High
45 | File | `/reviewer/system/system/admins/manage/users/user-update.php` | High
46 | File | `/rom-0` | Low
47 | File | `/searchpin.php` | High
48 | File | `/services/Card/findUser` | High
49 | File | `/showfile.php` | High
50 | File | `/show_group_members.php` | High
51 | File | `/timeline2.php` | High
52 | File | `/uncpath/` | Medium
53 | File | `/uno/central.php` | High
54 | File | `/user/profile` | High
55 | File | `/user/ticket/create` | High
56 | File | `/usr/local/psa/admin/sbin/wrapper` | High
57 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
58 | File | `/vloggers_merch/classes/Master.php?f=delete_order` | High
59 | ... | ... | ...

There are 513 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/308/gs-031-azorult-stealer-iocs/
* https://bazaar.abuse.ch/sample/7897cbf57b2a25446cedc1995c9950478a2c371c99ef87a0c82c7544742925f8/
* https://bazaar.abuse.ch/sample/c157531bb4d14cd35fc3ffe2a62fdd292f8e16566c663dcfbf083d75c4a94773/
* https://blog.cyble.com/2021/10/26/a-deep-dive-analysis-of-azorult-stealer/
* https://blog.talosintelligence.com/2020/01/threat-roundup-0117-0124.html
* https://blog.talosintelligence.com/threat-roundup-0630-0707-2/
* https://cert.gov.ua/article/2806
* https://isc.sans.edu/forums/diary/More+malspam+pushing+passwordprotected+Word+docs+for+AZORult+and+Hermes+Ransomware/23992/
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=198.98.54.161
* https://tria.ge/220314-ymactadghk
* https://tria.ge/220602-c7n6tagcgn

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
