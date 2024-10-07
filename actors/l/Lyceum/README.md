# Lyceum - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lyceum](https://vuldb.com/?actor.lyceum). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lyceum](https://vuldb.com/?actor.lyceum)

## Campaigns

The following _campaigns_ are known and can be associated with Lyceum:

* DanBot

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lyceum:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lyceum.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [62.113.196.37](https://vuldb.com/?ip.62.113.196.37) | aeroplan-redirect.online | DanBot | High
2 | [62.113.207.181](https://vuldb.com/?ip.62.113.207.181) | - | DanBot | High
3 | [75.87.185.45](https://vuldb.com/?ip.75.87.185.45) | cpe-75-87-185-45.kc.res.rr.com | DanBot | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lyceum_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lyceum. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/` | Low
5 | File | `/admin/admin-update-employee.php` | High
6 | File | `/admin/login.php` | High
7 | File | `/admin/return_add.php` | High
8 | File | `/ajax.php?action=read_msg` | High
9 | File | `/api/clusters/local/topics/{topic}/messages` | High
10 | File | `/api/gen/clients/{language}` | High
11 | File | `/API/info` | Medium
12 | File | `/app/options.py` | High
13 | File | `/apply/index.php` | High
14 | File | `/bin/httpd` | Medium
15 | File | `/cgi-bin/cstecgi.cgi` | High
16 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
17 | File | `/cgi-bin/tosei_kikai.php` | High
18 | File | `/cgi-bin/wapopen` | High
19 | File | `/ci_spms/admin/category` | High
20 | File | `/ci_spms/admin/search/searching/` | High
21 | File | `/classes/Master.php?f=delete_appointment` | High
22 | File | `/classes/Master.php?f=delete_record` | High
23 | File | `/classes/Master.php?f=delete_train` | High
24 | File | `/Content/Template/root/reverse-shell.aspx` | High
25 | File | `/course/api/upload/pic` | High
26 | File | `/ctcprotocol/Protocol` | High
27 | File | `/dashboard/menu-list.php` | High
28 | File | `/debug/pprof` | Medium
29 | File | `/detailed.php` | High
30 | File | `/dist/index.js` | High
31 | File | `/DXR.axd` | Medium
32 | File | `/ebics-server/ebics.aspx` | High
33 | File | `/ecommerce/popup_Item.php` | High
34 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
35 | File | `/EXCU_SHELL` | Medium
36 | File | `/ffos/classes/Master.php?f=save_category` | High
37 | File | `/forum/away.php` | High
38 | File | `/goform/execCommand` | High
39 | File | `/goform/modifyDhcpRule` | High
40 | File | `/goform/ModifyPppAuthWhiteMac` | High
41 | File | `/goform/net\_Web\_get_value` | High
42 | File | `/goform/setStaOffline` | High
43 | File | `/goform/WizardHandle` | High
44 | ... | ... | ...

There are 377 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://research.checkpoint.com/2022/state-sponsored-attack-groups-capitalise-on-russia-ukraine-war-for-cyber-espionage/
* https://www.secureworks.com/blog/lyceum-takes-center-stage-in-middle-east-campaign

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
