# APT32 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT32](https://vuldb.com/?actor.apt32). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt32](https://vuldb.com/?actor.apt32)

## Campaigns

The following _campaigns_ are known and can be associated with APT32:

* Cobalt Kitty
* OceanLotus

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT32:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT32.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.230.35.192](https://vuldb.com/?ip.5.230.35.192) | - | - | High
2 | [23.227.196.126](https://vuldb.com/?ip.23.227.196.126) | 23-227-196-126.static.hvvc.us | Cobalt Kitty | High
3 | [23.227.196.210](https://vuldb.com/?ip.23.227.196.210) | 23-227-196-210.static.hvvc.us | - | High
4 | [23.227.199.121](https://vuldb.com/?ip.23.227.199.121) | 23-227-199-121.static.hvvc.us | Cobalt Kitty | High
5 | [27.102.70.211](https://vuldb.com/?ip.27.102.70.211) | - | Cobalt Kitty | High
6 | [37.59.198.130](https://vuldb.com/?ip.37.59.198.130) | - | OceanLotus | High
7 | [37.59.198.131](https://vuldb.com/?ip.37.59.198.131) | - | OceanLotus | High
8 | [45.32.100.179](https://vuldb.com/?ip.45.32.100.179) | 45.32.100.179.vultr.com | OceanLotus | Medium
9 | [45.32.105.45](https://vuldb.com/?ip.45.32.105.45) | - | OceanLotus | High
10 | [45.32.114.49](https://vuldb.com/?ip.45.32.114.49) | 45.32.114.49.vultr.com | OceanLotus | Medium
11 | [45.76.147.201](https://vuldb.com/?ip.45.76.147.201) | 45.76.147.201.vultr.com | OceanLotus | Medium
12 | [45.76.179.28](https://vuldb.com/?ip.45.76.179.28) | 45.76.179.28.vultr.com | OceanLotus | Medium
13 | [45.76.179.151](https://vuldb.com/?ip.45.76.179.151) | 45.76.179.151.vultr.com | OceanLotus | Medium
14 | [45.77.39.101](https://vuldb.com/?ip.45.77.39.101) | 45.77.39.101.vultr.com | OceanLotus | Medium
15 | ... | ... | ... | ...

There are 54 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT32_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT32. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/` | Low
2 | File | `/admin/article.php` | High
3 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
4 | File | `/api/` | Low
5 | File | `/cgi-bin/cgiServer.exx` | High
6 | File | `/cgi-bin/login_action.cgi` | High
7 | File | `/cgi-bin/nobody/Search.cgi` | High
8 | File | `/cgi-bin/system_mgr.cgi` | High
9 | File | `/cgi-bin/webviewer_login_page` | High
10 | File | `/dev/sg0` | Medium
11 | File | `/event/runquery.do` | High
12 | File | `/export` | Low
13 | File | `/filemanager/php/connector.php` | High
14 | File | `/forum/away.php` | High
15 | File | `/goform/setmac` | High
16 | File | `/log_download.cgi` | High
17 | File | `/manager?action=getlogcat` | High
18 | File | `/mgmt/tm/util/bash` | High
19 | File | `/nova/bin/detnet` | High
20 | File | `/pages/systemcall.php?command={COMMAND}` | High
21 | File | `/password.html` | High
22 | File | `/php_action/fetchSelectedCategories.php` | High
23 | File | `/public/login.htm` | High
24 | File | `/services/prefs.php` | High
25 | File | `/system/ws/v11/ss/email` | High
26 | File | `/uncpath/` | Medium
27 | File | `/upload` | Low
28 | File | `/user/update_booking.php` | High
29 | File | `add_edit_user.asp` | High
30 | File | `add_vhost.php` | High
31 | File | `admin/gv_mail.php` | High
32 | File | `admin/images.aspx` | High
33 | File | `admin/index.php` | High
34 | File | `administrator.php` | High
35 | File | `administrator/components/com_media/helpers/media.php` | High
36 | ... | ... | ...

There are 309 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cdn2.hubspot.net/hubfs/3354902/Cybereason%20Labs%20Analysis%20Operation%20Cobalt%20Kitty.pdf
* https://www.fireeye.com/blog/threat-research/2017/05/cyber-espionage-apt32.html
* https://www.huntress.com/blog/advanced-persistent-threat-targeting-vietnamese-human-rights-defenders
* https://www.volexity.com/blog/2017/11/06/oceanlotus-blossoms-mass-digital-surveillance-and-exploitation-of-asean-nations-the-media-human-rights-and-civil-society/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
