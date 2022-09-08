# TA551 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TA551](https://vuldb.com/?actor.ta551). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ta551](https://vuldb.com/?actor.ta551)

## Campaigns

The following _campaigns_ are known and can be associated with TA551:

* Cobalt Strike
* DarkVNC
* Hancitor
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TA551:

* [IT](https://vuldb.com/?country.it)
* [ES](https://vuldb.com/?country.es)
* [AR](https://vuldb.com/?country.ar)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TA551.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.209.76.110](https://vuldb.com/?ip.8.209.76.110) | - | Hancitor | High
2 | [23.82.141.241](https://vuldb.com/?ip.23.82.141.241) | - | Cobalt Strike | High
3 | [23.106.223.174](https://vuldb.com/?ip.23.106.223.174) | - | - | High
4 | [43.128.225.230](https://vuldb.com/?ip.43.128.225.230) | - | Hancitor | High
5 | [43.128.229.136](https://vuldb.com/?ip.43.128.229.136) | - | Hancitor | High
6 | [43.128.232.152](https://vuldb.com/?ip.43.128.232.152) | - | Hancitor | High
7 | [43.129.239.78](https://vuldb.com/?ip.43.129.239.78) | - | Hancitor | High
8 | [43.133.160.144](https://vuldb.com/?ip.43.133.160.144) | - | Hancitor | High
9 | [45.8.146.139](https://vuldb.com/?ip.45.8.146.139) | vm580483.stark-industries.solutions | IcedID | High
10 | [45.89.67.166](https://vuldb.com/?ip.45.89.67.166) | srbtv.ru | - | High
11 | [45.95.11.151](https://vuldb.com/?ip.45.95.11.151) | vm220095.pq.hosting | - | High
12 | [45.95.11.153](https://vuldb.com/?ip.45.95.11.153) | vm284420.pq.hosting | - | High
13 | [45.95.11.154](https://vuldb.com/?ip.45.95.11.154) | 4ser-1640356836.4server.su | - | High
14 | [45.95.11.155](https://vuldb.com/?ip.45.95.11.155) | slfk.lz | - | High
15 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA551_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA551. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/?page=reports/stockin` | High
2 | File | `/admin/?page=reports/stockout` | High
3 | File | `/admin/addemployee.php` | High
4 | File | `/admin/login.php` | High
5 | File | `/admin/modify1.php` | High
6 | File | `/admin/search.php` | High
7 | File | `/api/v1/user` | Medium
8 | File | `/appConfig/userDB.json` | High
9 | File | `/bin/boa` | Medium
10 | File | `/blog/edit` | Medium
11 | File | `/categories/view_category.php` | High
12 | File | `/cgi-bin/ExportAllSettings.sh` | High
13 | File | `/classes/Master.php?f=delete_category` | High
14 | File | `/classes/Master.php?f=delete_img` | High
15 | File | `/classes/Master.php?f=delete_stockin` | High
16 | File | `/classes/Master.php?f=delete_stockout` | High
17 | File | `/classes/Master.php?f=delete_waste` | High
18 | File | `/client.php` | Medium
19 | File | `/coreframe/app/attachment/admin/index.php` | High
20 | File | `/dede/co_do.php` | High
21 | File | `/dishes.php` | Medium
22 | File | `/edituser.php` | High
23 | File | `/etc/ciel.cfg` | High
24 | File | `/etc/init0.d/S80telnetd.sh` | High
25 | File | `/etc/passwd` | Medium
26 | File | `/etc/shadow.sample` | High
27 | File | `/goform/form2userconfig.cgi` | High
28 | File | `/goform/SetLEDCfg` | High
29 | ... | ... | ...

There are 241 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/diary/28092
* https://isc.sans.edu/diary/IcedID+%28Bokbot%29+with+Dark+VNC+and+Cobalt+Strike/28884
* https://isc.sans.edu/diary/Monster+Libra+%28TA551Shathak%29+--%3E+IcedID+%28Bokbot%29+--%3E+Cobalt+Strike+%26+DarkVNC/28974
* https://isc.sans.edu/diary/Monster+Libra+%28TA551Shathak%29+pushes+IcedID+%28Bokbot%29+with+Dark+VNC+and+Cobalt+Strike/28934
* https://isc.sans.edu/diary/rss/27738
* https://isc.sans.edu/forums/diary/More+TA551+Shathak+Word+docs+push+IcedID+Bokbot/26674/
* https://isc.sans.edu/forums/diary/TA551+Shathak+Word+docs+push+IcedID+Bokbot/26438/
* https://www.malware-traffic-analysis.net/2021/09/14/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
