# Panda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Panda](https://vuldb.com/?actor.panda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.panda](https://vuldb.com/?actor.panda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Panda:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [IR](https://vuldb.com/?country.ir)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Panda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.123.17.223](https://vuldb.com/?ip.3.123.17.223) | ec2-3-123-17-223.eu-central-1.compute.amazonaws.com | - | Medium
2 | [5.56.133.246](https://vuldb.com/?ip.5.56.133.246) | 5-56-133-246.static.karizanta.com | - | High
3 | [46.173.217.80](https://vuldb.com/?ip.46.173.217.80) | - | - | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Panda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 3 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Panda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/addusers` | High
2 | File | `/api/blade-log/api/list` | High
3 | File | `/cgi-bin/editBookmark` | High
4 | File | `/cgi-bin/system_mgr.cgi` | High
5 | File | `/client/api/json/v2/nfareports/compareReport` | High
6 | File | `/etc/services/DEVICE.TIME.php` | High
7 | File | `/horde/imp/search.php` | High
8 | File | `/index.php` | Medium
9 | File | `/netflow/jspui/selectDevice.jsp` | High
10 | File | `/public/login.htm` | High
11 | File | `/public/login.htm?errormsg=&loginurl=%22%3E%3Csvg%20onload=prompt%28/XSS/%29%3E` | High
12 | File | `/reports/rwservlet` | High
13 | File | `/SASWebReportStudio/logonAndRender.do` | High
14 | ... | ... | ...

There are 106 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/09/panda-evolution.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
