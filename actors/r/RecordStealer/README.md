# RecordStealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RecordStealer](https://vuldb.com/?actor.recordstealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.recordstealer](https://vuldb.com/?actor.recordstealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RecordStealer:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RecordStealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.67.34.152](https://vuldb.com/?ip.45.67.34.152) | mail.worthlesspussy.info | - | High
2 | [45.67.34.234](https://vuldb.com/?ip.45.67.34.234) | varitbucks.site | - | High
3 | [45.67.34.238](https://vuldb.com/?ip.45.67.34.238) | vm644735.stark-industries.solutions | - | High
4 | [45.84.0.152](https://vuldb.com/?ip.45.84.0.152) | vm603207.stark-industries.solutions | - | High
5 | [45.133.216.145](https://vuldb.com/?ip.45.133.216.145) | new18.vpsfast | - | High
6 | [45.133.216.170](https://vuldb.com/?ip.45.133.216.170) | wireguard.vasilchenko.dev | - | High
7 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RecordStealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RecordStealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add_user.php` | High
2 | File | `/adfs/ls` | Medium
3 | File | `/admin/attendance_action.php` | High
4 | File | `/admin/login.php` | High
5 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
6 | File | `/agc/vicidial.php` | High
7 | File | `/api/baskets/{name}` | High
8 | File | `/api/RecordingList/DownloadRecord?file=` | High
9 | File | `/apply.cgi` | Medium
10 | File | `/cgi-bin/cstecgi.cgi` | High
11 | File | `/cgi-bin/luci/api/switch` | High
12 | File | `/cgi-bin/sm_changepassword.cgi` | High
13 | File | `/classes/Master.php?f=delete_inquiry` | High
14 | File | `/contact.php` | Medium
15 | File | `/controller/company/Index.php#sendCompanyLogo` | High
16 | File | `/core/config-revisions` | High
17 | File | `/debuginfo.htm` | High
18 | File | `/Electron/download` | High
19 | File | `/export` | Low
20 | File | `/forum/away.php` | High
21 | File | `/goform/VerAPIMant` | High
22 | File | `/goform/WifiExtraSet` | High
23 | File | `/guest_auth/cfg/upLoadCfg.php` | High
24 | File | `/h/rest` | Low
25 | File | `/include/chart_generator.php` | High
26 | File | `/index.php` | Medium
27 | File | `/items/search` | High
28 | File | `/jsonrpc` | Medium
29 | File | `/load.php` | Medium
30 | File | `/lua/set-passwd.lua` | High
31 | File | `/mims/login.php` | High
32 | File | `/newProject.php` | High
33 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
34 | File | `/owa/auth/logon.aspx` | High
35 | File | `/pages/animals.php` | High
36 | File | `/php/ping.php` | High
37 | ... | ... | ...

There are 319 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/35981/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
