# SolarMarker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [SolarMarker](https://vuldb.com/?actor.solarmarker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.solarmarker](https://vuldb.com/?actor.solarmarker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SolarMarker:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 30 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SolarMarker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.15.118](https://vuldb.com/?ip.2.58.15.118) | - | - | High
2 | [5.181.156.17](https://vuldb.com/?ip.5.181.156.17) | no-rdns.mivocloud.com | - | High
3 | [5.181.159.42](https://vuldb.com/?ip.5.181.159.42) | 5-181-159-42.mivocloud.com | - | High
4 | [37.120.233.92](https://vuldb.com/?ip.37.120.233.92) | no-rdns.m247.com | - | High
5 | [37.120.237.251](https://vuldb.com/?ip.37.120.237.251) | - | - | High
6 | [45.42.201.248](https://vuldb.com/?ip.45.42.201.248) | - | - | High
7 | [46.30.188.221](https://vuldb.com/?ip.46.30.188.221) | 46.30.188.221.static.quadranet.com | - | High
8 | [50.19.154.168](https://vuldb.com/?ip.50.19.154.168) | ec2-50-19-154-168.compute-1.amazonaws.com | - | Medium
9 | [52.7.205.182](https://vuldb.com/?ip.52.7.205.182) | ec2-52-7-205-182.compute-1.amazonaws.com | - | Medium
10 | [52.23.58.125](https://vuldb.com/?ip.52.23.58.125) | ec2-52-23-58-125.compute-1.amazonaws.com | - | Medium
11 | [52.87.104.17](https://vuldb.com/?ip.52.87.104.17) | ec2-52-87-104-17.compute-1.amazonaws.com | - | Medium
12 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _SolarMarker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by SolarMarker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/index.PHP` | High
2 | File | `/admin/index2.html` | High
3 | File | `/alphaware/details.php` | High
4 | File | `/api/baskets/{name}` | High
5 | File | `/api/RecordingList/DownloadRecord?file=` | High
6 | File | `/api2/html/` | Medium
7 | File | `/apiadmin/notice/add` | High
8 | File | `/apply.cgi` | Medium
9 | File | `/calendar/minimizer/index.php` | High
10 | File | `/cgi-bin-sdb/` | High
11 | File | `/cgi-bin/cstecgi.cgi` | High
12 | File | `/cgi-bin/p1_ftpserver.php` | High
13 | File | `/classes/master.php?f=delete_order` | High
14 | File | `/cloud_config/router_post/register` | High
15 | File | `/debug/pprof` | Medium
16 | File | `/ecommerce/support_ticket` | High
17 | File | `/Forms/tools_test_1` | High
18 | File | `/forum/away.php` | High
19 | File | `/forum/PostPrivateMessage` | High
20 | File | `/h/autoSaveDraft` | High
21 | File | `/h/calendar` | Medium
22 | File | `/holiday.php` | Medium
23 | File | `/home/cavesConsole` | High
24 | File | `/include/chart_generator.php` | High
25 | File | `/index.php` | Medium
26 | File | `/lam/tmp/` | Medium
27 | File | `/librarian/bookdetails.php` | High
28 | File | `/login/index.php` | High
29 | File | `/manager?action=getlogcat` | High
30 | File | `/mgmt/tm/util/bash` | High
31 | File | `/model/update_grade.php` | High
32 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
33 | File | `/oauth/idp/.well-known/openid-configuration` | High
34 | File | `/out.php` | Medium
35 | File | `/p1/p2/:name` | Medium
36 | File | `/param.file.tgz` | High
37 | File | `/patient/appointment.php` | High
38 | File | `/php-opos/index.php` | High
39 | File | `/php/exportrecord.php` | High
40 | File | `/php/ping.php` | High
41 | File | `/plesk-site-preview/` | High
42 | File | `/proc/<PID>/mem` | High
43 | File | `/product.php` | Medium
44 | File | `/product_list.php` | High
45 | File | `/protocol/iscgwtunnel/uploadiscgwrouteconf.php` | High
46 | File | `/ptms/?page=user` | High
47 | File | `/request.php` | Medium
48 | File | `/scripts/unlock_tasks.php` | High
49 | File | `/Service/ImageStationDataService.asmx` | High
50 | ... | ... | ...

There are 439 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/184/solarmarker-malware-iocs/
* https://github.com/esThreatIntelligence/iocs/blob/main/SolarMarker/iocs_4-8-2024.txt
* https://ioc.exchange/@squiblydoo@infosec.exchange/110854242511709508
* https://ioc.exchange/@squiblydoo@infosec.exchange/110952627273483306
* https://threatfox.abuse.ch
* https://tria.ge/210824-j7r4atcshe/behavioral2
* https://tria.ge/240509-r6z91sfc2z
* https://twitter.com/SquiblydooBlog/status/1498447061628379140
* https://twitter.com/SquiblydooBlog/status/1660782805687865344
* https://twitter.com/SquiblydooBlog/status/1671556028226207746
* https://www.esentire.com/blog/solarmarker-impersonates-job-employment-website-indeed-with-a-team-building-themed-lure

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
