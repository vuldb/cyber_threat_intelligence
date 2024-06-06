# Panda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Panda](https://vuldb.com/?actor.panda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.panda](https://vuldb.com/?actor.panda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Panda:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [IR](https://vuldb.com/?country.ir)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Panda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.123.17.223](https://vuldb.com/?ip.3.123.17.223) | ec2-3-123-17-223.eu-central-1.compute.amazonaws.com | - | Medium
2 | [5.56.133.246](https://vuldb.com/?ip.5.56.133.246) | 5-56-133-246.static.karizanta.com | - | High
3 | [13.62.0.0](https://vuldb.com/?ip.13.62.0.0) | - | - | High
4 | [45.77.45.228](https://vuldb.com/?ip.45.77.45.228) | 45.77.45.228.vultrusercontent.com | - | High
5 | [46.173.217.80](https://vuldb.com/?ip.46.173.217.80) | - | - | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Panda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/edit-admin.php` | High
2 | File | `/admin/view_sendlist.php` | High
3 | File | `/adminapi/system/crud` | High
4 | File | `/api/` | Low
5 | File | `/api/addusers` | High
6 | File | `/api/blade-log/api/list` | High
7 | File | `/application/index/controller/Datament.php` | High
8 | File | `/application/index/controller/File.php` | High
9 | File | `/application/index/controller/Screen.php` | High
10 | File | `/application/index/controller/Service.php` | High
11 | File | `/att_add.php` | Medium
12 | File | `/cancel.php` | Medium
13 | File | `/cgi-bin/cstecgi.cgi` | High
14 | File | `/cgi-bin/editBookmark` | High
15 | File | `/cgi-bin/go` | Medium
16 | File | `/cgi-bin/system_mgr.cgi` | High
17 | File | `/cgi-bin/webviewer_login_page` | High
18 | File | `/client/api/json/v2/nfareports/compareReport` | High
19 | File | `/dede/file_manage_control.php` | High
20 | File | `/edit.php` | Medium
21 | File | `/etc/services/DEVICE.TIME.php` | High
22 | File | `/ext/collect/find_text.do` | High
23 | File | `/forum/away.php` | High
24 | File | `/general/email/outbox/delete.php` | High
25 | File | `/horde/imp/search.php` | High
26 | File | `/index.php` | Medium
27 | File | `/log/webmailattach.php` | High
28 | File | `/myprofile.php` | High
29 | File | `/netflow/jspui/selectDevice.jsp` | High
30 | File | `/new_item` | Medium
31 | File | `/public/login.htm` | High
32 | File | `/public/login.htm?errormsg=&loginurl=%22%3E%3Csvg%20onload=prompt%28/XSS/%29%3E` | High
33 | File | `/reports/rwservlet` | High
34 | File | `/SASWebReportStudio/logonAndRender.do` | High
35 | File | `/search.htm?searchtext=%22%3E%3Csvg%20onload=prompt%28/XSS/%29%3E` | High
36 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
37 | ... | ... | ...

There are 321 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/panda-evolution.html
* https://jp.security.ntt/tech_blog/102glv5
* https://www.welivesecurity.com/2023/04/26/evasive-panda-apt-group-malware-updates-popular-chinese-software/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
