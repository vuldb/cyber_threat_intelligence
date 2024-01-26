# Panda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Panda](https://vuldb.com/?actor.panda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.panda](https://vuldb.com/?actor.panda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Panda:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [IR](https://vuldb.com/?country.ir)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Panda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.123.17.223](https://vuldb.com/?ip.3.123.17.223) | ec2-3-123-17-223.eu-central-1.compute.amazonaws.com | - | Medium
2 | [5.56.133.246](https://vuldb.com/?ip.5.56.133.246) | 5-56-133-246.static.karizanta.com | - | High
3 | [13.62.0.0](https://vuldb.com/?ip.13.62.0.0) | - | - | High
4 | [46.173.217.80](https://vuldb.com/?ip.46.173.217.80) | - | - | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Panda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/` | Low
2 | File | `/api/addusers` | High
3 | File | `/api/blade-log/api/list` | High
4 | File | `/cgi-bin/editBookmark` | High
5 | File | `/cgi-bin/system_mgr.cgi` | High
6 | File | `/cgi-bin/webviewer_login_page` | High
7 | File | `/client/api/json/v2/nfareports/compareReport` | High
8 | File | `/dede/file_manage_control.php` | High
9 | File | `/etc/services/DEVICE.TIME.php` | High
10 | File | `/horde/imp/search.php` | High
11 | File | `/index.php` | Medium
12 | File | `/netflow/jspui/selectDevice.jsp` | High
13 | File | `/public/login.htm` | High
14 | File | `/public/login.htm?errormsg=&loginurl=%22%3E%3Csvg%20onload=prompt%28/XSS/%29%3E` | High
15 | File | `/reports/rwservlet` | High
16 | File | `/SASWebReportStudio/logonAndRender.do` | High
17 | File | `/search.htm?searchtext=%22%3E%3Csvg%20onload=prompt%28/XSS/%29%3E` | High
18 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
19 | File | `/secure/admin/ViewInstrumentation.jspa` | High
20 | File | `/tab_tariffe.php` | High
21 | File | `/tmp` | Low
22 | File | `/tmp/app/.env` | High
23 | ... | ... | ...

There are 194 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/panda-evolution.html
* https://www.welivesecurity.com/2023/04/26/evasive-panda-apt-group-malware-updates-popular-chinese-software/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
