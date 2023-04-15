# Microsoft Exchange - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Microsoft Exchange_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Microsoft Exchange:

* [US](https://vuldb.com/?country.us)
* [JP](https://vuldb.com/?country.jp)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 31 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Microsoft Exchange or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Tortilla](https://vuldb.com/?actor.tortilla) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Microsoft Exchange.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.180.61.17](https://vuldb.com/?ip.5.180.61.17) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [47.242.39.92](https://vuldb.com/?ip.47.242.39.92) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [54.221.65.242](https://vuldb.com/?ip.54.221.65.242) | ec2-54-221-65-242.compute-1.amazonaws.com | [Tortilla](https://vuldb.com/?actor.tortilla) | Medium
4 | [61.244.94.85](https://vuldb.com/?ip.61.244.94.85) | 061244094085.ctinets.com | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Microsoft Exchange. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-27 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Microsoft Exchange. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/academic/studenview_left.php` | High
2 | File | `/Admin/add-student.php` | High
3 | File | `/admin/new-content` | High
4 | File | `/advanced-tools/nova/bin/netwatch` | High
5 | File | `/alarm_pi/alarmService.php` | High
6 | File | `/api/crontab` | Medium
7 | File | `/api/RecordingList/DownloadRecord?file=` | High
8 | File | `/api/storage/upload/PostImage` | High
9 | File | `/application/common.php#action_log` | High
10 | File | `/asms/admin/products/manage_product.php` | High
11 | File | `/asms/products/view_product.php` | High
12 | File | `/cgi-bin/koha/members/paycollect.pl` | High
13 | File | `/common/download?filename=1.jsp&delete=false` | High
14 | File | `/common/info.cgi` | High
15 | File | `/config/getuser` | High
16 | File | `/config/list` | Medium
17 | File | `/dashboard/snapshot/*?orgId=0` | High
18 | File | `/exports/export.php` | High
19 | File | `/gena.cgi` | Medium
20 | File | `/home/cavesConsole` | High
21 | File | `/home/kickPlayer` | High
22 | File | `/home/masterConsole` | High
23 | File | `/home/sendBroadcast` | High
24 | File | `/html/portal/flash.jsp` | High
25 | File | `/include/chart_generator.php` | High
26 | File | `/lan.asp` | Medium
27 | File | `/librarian/bookdetails.php` | High
28 | File | `/loginVaLidation.php` | High
29 | File | `/manage/emailrichment/userlist.php?CUSTOMER_ID_INNER=1` | High
30 | File | `/metrics` | Medium
31 | File | `/MIME/INBOX-MM-1/` | High
32 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
33 | File | `/photo/webapi/photo.php` | High
34 | File | `/plesk-site-preview/` | High
35 | File | `/requests.php` | High
36 | File | `/resources//../` | High
37 | File | `/secure/QueryComponent!Default.jspa` | High
38 | ... | ... | ...

There are 325 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2021/11/babuk-exploits-exchange.html
* https://github.com/Cisco-Talos/IOCs/blob/main/2022/09/threat-advisory-exchange-server-vulns.txt
* https://isc.sans.edu/forums/diary/Scanning+for+Microsoft+Exchange+eDiscovery/27748/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
