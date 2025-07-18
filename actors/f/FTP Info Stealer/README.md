# FTP Info Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FTP Info Stealer](https://vuldb.com/?actor.ftp_info_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ftp_info_stealer](https://vuldb.com/?actor.ftp_info_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FTP Info Stealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FTP Info Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [37.221.67.219](https://vuldb.com/?ip.37.221.67.219) | raiden2023 | - | High
2 | [45.67.34.152](https://vuldb.com/?ip.45.67.34.152) | vm1401885.stark-industries.solutions | - | High
3 | [45.67.34.234](https://vuldb.com/?ip.45.67.34.234) | vm1407334.stark-industries.solutions | - | High
4 | [45.67.34.238](https://vuldb.com/?ip.45.67.34.238) | vps.hostry.com | - | High
5 | [45.84.0.152](https://vuldb.com/?ip.45.84.0.152) | vm1338883.stark-industries.solutions | - | High
6 | [45.133.216.145](https://vuldb.com/?ip.45.133.216.145) | vm1309698.stark-industries.solutions | - | High
7 | [45.133.216.170](https://vuldb.com/?ip.45.133.216.170) | mail.stiegl-at.com | - | High
8 | [45.133.216.249](https://vuldb.com/?ip.45.133.216.249) | vm699942.stark-industries.solutions | - | High
9 | ... | ... | ... | ...

There are 33 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _FTP Info Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FTP Info Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add_user.php` | High
2 | File | `/adfs/ls` | Medium
3 | File | `/admin.php/news/admin/topic/save` | High
4 | File | `/admin/attendance_action.php` | High
5 | File | `/admin/comn/service/update.json` | High
6 | File | `/admin/login.php` | High
7 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
8 | File | `/agc/vicidial.php` | High
9 | File | `/api/baskets/{name}` | High
10 | File | `/api/RecordingList/DownloadRecord?file=` | High
11 | File | `/app/options.py` | High
12 | File | `/apply.cgi` | Medium
13 | File | `/auth_files/photo/` | High
14 | File | `/card_scan.php` | High
15 | File | `/cgi-bin/cstecgi.cgi` | High
16 | File | `/cgi-bin/luci/api/switch` | High
17 | File | `/cgi-bin/touchlist_sync.cgi` | High
18 | File | `/cgi-bin/wlogin.cgi` | High
19 | File | `/classes/Master.php?f=delete_inquiry` | High
20 | File | `/contact.php` | Medium
21 | File | `/controller/company/Index.php#sendCompanyLogo` | High
22 | File | `/core/config-revisions` | High
23 | File | `/cwc/login` | Medium
24 | File | `/debuginfo.htm` | High
25 | File | `/Electron/download` | High
26 | File | `/etc/passwd` | Medium
27 | File | `/etc/quagga` | Medium
28 | File | `/forms/doLogin` | High
29 | File | `/forum/away.php` | High
30 | File | `/goform/VerAPIMant` | High
31 | File | `/goform/WifiExtraSet` | High
32 | File | `/guest_auth/cfg/upLoadCfg.php` | High
33 | File | `/h/autoSaveDraft` | High
34 | File | `/h/calendar` | Medium
35 | File | `/h/rest` | Low
36 | File | `/index.php` | Medium
37 | File | `/items/search` | High
38 | File | `/load.php` | Medium
39 | File | `/lua/set-passwd.lua` | High
40 | File | `/mims/login.php` | High
41 | File | `/newProject.php` | High
42 | File | `/nova/bin/detnet` | High
43 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
44 | File | `/out.php` | Medium
45 | ... | ... | ...

There are 385 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/threatlabz/iocs/blob/main/infostealer/pirated_software_iocs.txt
* https://www.malware-traffic-analysis.net/2019/02/07/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
