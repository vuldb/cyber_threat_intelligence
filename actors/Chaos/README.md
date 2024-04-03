# Chaos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chaos](https://vuldb.com/?actor.chaos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chaos](https://vuldb.com/?actor.chaos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chaos:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chaos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.120.164.69](https://vuldb.com/?ip.3.120.164.69) | chaos.fk0.name | - | High
2 | [5.180.44.53](https://vuldb.com/?ip.5.180.44.53) | 53.44-180-5.rdns.scalabledns.com | - | High
3 | [20.90.110.121](https://vuldb.com/?ip.20.90.110.121) | - | - | High
4 | [20.187.95.103](https://vuldb.com/?ip.20.187.95.103) | - | - | High
5 | [23.224.132.58](https://vuldb.com/?ip.23.224.132.58) | - | - | High
6 | [23.225.194.65](https://vuldb.com/?ip.23.225.194.65) | - | - | High
7 | [23.226.76.122](https://vuldb.com/?ip.23.226.76.122) | we.love.servers.at.ioflood.net | - | High
8 | [43.142.157.239](https://vuldb.com/?ip.43.142.157.239) | - | - | High
9 | [43.155.37.192](https://vuldb.com/?ip.43.155.37.192) | - | - | High
10 | [45.14.185.146](https://vuldb.com/?ip.45.14.185.146) | 146.185.14.45.servereasy.it | - | High
11 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chaos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chaos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add_post_sql.php` | High
2 | File | `/admin/article.php` | High
3 | File | `/admin/book_row.php` | High
4 | File | `/admin/contact-us.php` | High
5 | File | `/admin/general.cgi` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/reminders/manage_reminder.php` | High
8 | File | `/admin/services/view_service.php` | High
9 | File | `/admin/tag/delete` | High
10 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/api/jmeter/download/files` | High
13 | File | `/api/v1/terminal/sessions/?limit=1` | High
14 | File | `/api/wechat/app_auth` | High
15 | File | `/application/index/controller/Screen.php` | High
16 | File | `/apply.cgi` | Medium
17 | File | `/CCMAdmin/serverlist.asp` | High
18 | File | `/cgi-bin/luci/api/auth` | High
19 | File | `/cgi-bin/system_mgr.cgi` | High
20 | File | `/cgi-bin/wlogin.cgi` | High
21 | File | `/cgi/get_param.cgi` | High
22 | File | `/Controls/Generic/EBMK/Handlers/EStatements/DownloadEStatement.ashx` | High
23 | File | `/csms/admin/inquiries/view_details.php` | High
24 | File | `/cstecgi.cgi` | Medium
25 | File | `/devinfo` | Medium
26 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
27 | File | `/forum/away.php` | High
28 | File | `/goform/openSchedWifi` | High
29 | File | `/goform/SetStaticRouteCfg` | High
30 | File | `/group1/uploa` | High
31 | File | `/importexport.php` | High
32 | File | `/include/chart_generator.php` | High
33 | File | `/index.php` | Medium
34 | File | `/index.php?page=member` | High
35 | File | `/install.php` | Medium
36 | File | `/librarian/bookdetails.php` | High
37 | File | `/link/` | Low
38 | File | `/manage/IPSetup.php` | High
39 | File | `/matkul/data` | Medium
40 | File | `/message/form/` | High
41 | File | `/messageboard/view.php` | High
42 | File | `/net/tls/tls_sw.c` | High
43 | File | `/offersmail.php` | High
44 | File | `/out.php` | Medium
45 | File | `/owa/auth/logon.aspx` | High
46 | File | `/process/assignp.php` | High
47 | File | `/production/admin_view_info.php` | High
48 | ... | ... | ...

There are 418 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cloudsecurityalliance.org/blog/2023/06/15/chaos-malware-quietly-evolves-persistence-and-evasion-techniques/
* https://community.blueliv.com/#!/s/63353bd382df413eb5359c9b
* https://search.censys.io/hosts/3.120.164.69
* https://search.censys.io/hosts/45.14.185.146
* https://search.censys.io/hosts/45.76.80.199
* https://search.censys.io/hosts/47.103.98.239
* https://search.censys.io/hosts/47.113.145.151
* https://search.censys.io/hosts/50.193.250.21
* https://search.censys.io/hosts/52.0.83.31
* https://search.censys.io/hosts/64.227.71.105
* https://search.censys.io/hosts/79.137.51.184
* https://search.censys.io/hosts/93.90.59.79
* https://search.censys.io/hosts/94.21.157.169
* https://search.censys.io/hosts/100.25.226.74
* https://search.censys.io/hosts/103.56.19.194
* https://search.censys.io/hosts/116.203.230.194
* https://search.censys.io/hosts/117.20.108.15
* https://search.censys.io/hosts/130.61.253.246
* https://search.censys.io/hosts/161.97.117.117

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
