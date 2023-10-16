# Chaos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chaos](https://vuldb.com/?actor.chaos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chaos](https://vuldb.com/?actor.chaos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chaos:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chaos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.180.44.53](https://vuldb.com/?ip.5.180.44.53) | 53.44-180-5.rdns.scalabledns.com | - | High
2 | [20.90.110.121](https://vuldb.com/?ip.20.90.110.121) | - | - | High
3 | [20.187.95.103](https://vuldb.com/?ip.20.187.95.103) | - | - | High
4 | [23.224.132.58](https://vuldb.com/?ip.23.224.132.58) | - | - | High
5 | [23.225.194.65](https://vuldb.com/?ip.23.225.194.65) | - | - | High
6 | [23.226.76.122](https://vuldb.com/?ip.23.226.76.122) | we.love.servers.at.ioflood.net | - | High
7 | [43.142.157.239](https://vuldb.com/?ip.43.142.157.239) | - | - | High
8 | ... | ... | ... | ...

There are 28 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chaos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chaos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add_post_sql.php` | High
2 | File | `/admin/article.php` | High
3 | File | `/admin/getallarticleinfo` | High
4 | File | `/admin/reminders/manage_reminder.php` | High
5 | File | `/admin/services/view_service.php` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/v1/terminal/sessions/?limit=1` | High
8 | File | `/auparse/auparse.c` | High
9 | File | `/baseOpLog.do` | High
10 | File | `/CCMAdmin/serverlist.asp` | High
11 | File | `/cgi-bin/luci/api/auth` | High
12 | File | `/cgi-bin/luci/api/wireless` | High
13 | File | `/cgi-bin/wlogin.cgi` | High
14 | File | `/cgi/get_param.cgi` | High
15 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
16 | File | `/csms/admin/inquiries/view_details.php` | High
17 | File | `/cstecgi.cgi` | Medium
18 | File | `/dashboard/contact` | High
19 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
20 | File | `/env` | Low
21 | File | `/forum/away.php` | High
22 | File | `/goform/setDiagnoseInfo` | High
23 | File | `/goform/WifiBasicSet` | High
24 | File | `/hrm/employeeview.php` | High
25 | File | `/htdocs/cgibin` | High
26 | File | `/importexport.php` | High
27 | File | `/include/chart_generator.php` | High
28 | File | `/index.php` | Medium
29 | File | `/index.php?page=member` | High
30 | File | `/librarian/bookdetails.php` | High
31 | File | `/link/` | Low
32 | File | `/matkul/data` | Medium
33 | File | `/message/form/` | High
34 | File | `/messageboard/view.php` | High
35 | File | `/out.php` | Medium
36 | File | `/src/Illuminate/Laravel.php` | High
37 | File | `/SVFE2/pages/feegroups/country_group.jsf` | High
38 | File | `/system/dict/list` | High
39 | File | `/system/user/resetPwd` | High
40 | File | `/SystemManage/Organize/GetTreeGridJson?_search=false&nd=1681813520783&rows=10000&page=1&sidx=&sord=asc` | High
41 | File | `/SystemManage/Role/GetGridJson?keyword=&page=1&rows=20` | High
42 | File | `/textpattern/index.php` | High
43 | ... | ... | ...

There are 373 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cloudsecurityalliance.org/blog/2023/06/15/chaos-malware-quietly-evolves-persistence-and-evasion-techniques/
* https://community.blueliv.com/#!/s/63353bd382df413eb5359c9b

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
