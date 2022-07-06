# UAC-0056 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0056](https://vuldb.com/?actor.uac-0056). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0056](https://vuldb.com/?actor.uac-0056)

## Campaigns

The following _campaigns_ are known and can be associated with UAC-0056:

* GraphSteel/GrimPlant
* Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0056:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0056.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.42.185.63](https://vuldb.com/?ip.31.42.185.63) | dedicated.vsys.host | Ukraine | High
2 | [45.84.0.116](https://vuldb.com/?ip.45.84.0.116) | n5336.md | - | High
3 | [45.146.164.37](https://vuldb.com/?ip.45.146.164.37) | - | Ukraine | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0056_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0056. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/?page=system_info/contact_info` | High
3 | File | `/admin/login.php` | High
4 | File | `/admin/produts/controller.php` | High
5 | File | `/admin/user/team` | High
6 | File | `/adminlogin.asp` | High
7 | File | `/ad_js.php` | Medium
8 | File | `/api/RecordingList/DownloadRecord?file=` | High
9 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
10 | File | `/cgi-bin/system_mgr.cgi` | High
11 | File | `/common/logViewer/logViewer.jsf` | High
12 | File | `/crmeb/app/admin/controller/store/CopyTaobao.php` | High
13 | File | `/etc/sudoers` | Medium
14 | File | `/forum/away.php` | High
15 | File | `/goform/aspForm` | High
16 | File | `/hocms/classes/Master.php?f=delete_collection` | High
17 | File | `/includes/rrdtool.inc.php` | High
18 | File | `/index.php` | Medium
19 | File | `/mc-admin/post.php?state=delete&delete` | High
20 | File | `/mifs/c/i/reg/reg.html` | High
21 | File | `/ms/cms/content/list.do` | High
22 | File | `/oauth/token/request` | High
23 | File | `/orms/` | Low
24 | File | `/plesk-site-preview/` | High
25 | File | `/school/model/get_admin_profile.php` | High
26 | File | `/student-grading-system/rms.php?page=grade` | High
27 | File | `/system-info/health` | High
28 | File | `/timeline2.php` | High
29 | File | `/uncpath/` | Medium
30 | File | `/usr/local/nagiosxi/html/includes/configwizards/windowswmi/windowswmi.inc.php` | High
31 | File | `/www/ping_response.cgi` | High
32 | File | `ABuffer.cpp` | Medium
33 | File | `account.asp` | Medium
34 | File | `addentry.php` | Medium
35 | File | `addmember.php` | High
36 | File | `addtocart.asp` | High
37 | File | `addtomylist.asp` | High
38 | File | `admin.php` | Medium
39 | File | `admin.x-shop.php` | High
40 | File | `admin/auth.php` | High
41 | File | `admin/changedata.php` | High
42 | File | `admin/config/confmgr.php` | High
43 | File | `admin/dashboard.php` | High
44 | ... | ... | ...

There are 379 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/18419
* https://cert.gov.ua/article/37704
* https://cert.gov.ua/article/38374
* https://unit42.paloaltonetworks.com/ukraine-targeted-outsteel-saintbot/
* https://www.sentinelone.com/blog/threat-actor-uac-0056-targeting-ukraine-with-fake-translation-software/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
