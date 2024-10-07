# TG-3390 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TG-3390](https://vuldb.com/?actor.tg-3390). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tg-3390](https://vuldb.com/?actor.tg-3390)

## Campaigns

The following _campaigns_ are known and can be associated with TG-3390:

* Bronze Union
* Emissary Panda
* Gh0st RAT

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TG-3390:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TG-3390.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [43.242.35.13](https://vuldb.com/?ip.43.242.35.13) | - | Gh0st RAT | High
2 | [43.242.35.16](https://vuldb.com/?ip.43.242.35.16) | - | Gh0st RAT | High
3 | [45.114.9.174](https://vuldb.com/?ip.45.114.9.174) | - | Bronze Union | High
4 | [49.143.192.221](https://vuldb.com/?ip.49.143.192.221) | - | - | High
5 | [49.143.205.30](https://vuldb.com/?ip.49.143.205.30) | - | - | High
6 | [66.63.178.142](https://vuldb.com/?ip.66.63.178.142) | unassigned.quadranet.com | - | High
7 | [67.215.232.179](https://vuldb.com/?ip.67.215.232.179) | ed-cricalf.latention.com | - | High
8 | [67.215.232.181](https://vuldb.com/?ip.67.215.232.181) | ninths.latention.com | - | High
9 | ... | ... | ... | ...

There are 32 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TG-3390_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TG-3390. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/pages/` | High
3 | File | `/admins` | Low
4 | File | `/ajax/getBasicInfo.php` | High
5 | File | `/api/admin/system/store/order/list` | High
6 | File | `/cgi-bin/cstecgi.cgi` | High
7 | File | `/cgi-bin/live_api.cgi` | High
8 | File | `/cgi-bin/wapopen` | High
9 | File | `/cgi-bin/wlogin.cgi` | High
10 | File | `/clientdetails/admin/regester.php` | High
11 | File | `/csms/?page=contact_us` | High
12 | File | `/etc/ajenti/config.yml` | High
13 | File | `/etc/shadow` | Medium
14 | File | `/farm/product.php` | High
15 | File | `/forum/away.php` | High
16 | File | `/getcfg.php` | Medium
17 | File | `/goform/telnet` | High
18 | File | `/infusions/shoutbox_panel/shoutbox_admin.php` | High
19 | File | `/modules/profile/index.php` | High
20 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
21 | File | `/oscommerce/admin/currencies.php` | High
22 | File | `/proc/pid/syscall` | High
23 | File | `/ptippage.cgi` | High
24 | File | `/rom-0` | Low
25 | File | `/session/list/allActiveSession` | High
26 | File | `/syslog_rules` | High
27 | File | `/tmp/out` | Medium
28 | File | `/uncpath/` | Medium
29 | File | `/upload` | Low
30 | File | `/users/{id}` | Medium
31 | File | `/usr/bin/pkexec` | High
32 | File | `/var/tmp/sess_*` | High
33 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
34 | File | `/video` | Low
35 | File | `/videotalk` | Medium
36 | File | `action-visitor.php` | High
37 | File | `actionphp/download.File.php` | High
38 | ... | ... | ...

There are 328 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/emissary-panda-attacks-middle-east-government-sharepoint-servers/
* https://www.nccgroup.com/uk/about-us/newsroom-and-events/blogs/2018/may/emissary-panda-a-potential-new-malicious-tool/
* https://www.secureworks.com/research/a-peek-into-bronze-unions-toolbox
* https://www.secureworks.com/research/bronze-union
* https://www.secureworks.com/research/threat-group-3390-targets-organizations-for-cyberespionage

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
