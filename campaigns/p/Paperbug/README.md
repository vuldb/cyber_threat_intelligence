# Paperbug - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Paperbug_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Paperbug:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 12 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Paperbug or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Nomadic Octopus](https://vuldb.com/?actor.nomadic_octopus) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Paperbug.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [44.227.65.245](https://vuldb.com/?ip.44.227.65.245) | ec2-44-227-65-245.us-west-2.compute.amazonaws.com | [Nomadic Octopus](https://vuldb.com/?actor.nomadic_octopus) | Medium
2 | [44.227.76.166](https://vuldb.com/?ip.44.227.76.166) | ec2-44-227-76-166.us-west-2.compute.amazonaws.com | [Nomadic Octopus](https://vuldb.com/?actor.nomadic_octopus) | Medium
3 | [54.36.185.101](https://vuldb.com/?ip.54.36.185.101) | ip101.ip-54-36-185.eu | [Nomadic Octopus](https://vuldb.com/?actor.nomadic_octopus) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Paperbug. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Paperbug. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/acms/classes/Master.php?f=delete_cargo` | High
2 | File | `/admin.php/news/admin/topic/save` | High
3 | File | `/admin/comn/service/update.json` | High
4 | File | `/api/RecordingList/DownloadRecord?file=` | High
5 | File | `/apply.cgi` | Medium
6 | File | `/cgi-bin/cstecgi.cgi` | High
7 | File | `/ci_hms/massage_room/edit/1` | High
8 | File | `/dev/shm` | Medium
9 | File | `/dl/dl_print.php` | High
10 | File | `/forum/away.php` | High
11 | File | `/getcfg.php` | Medium
12 | File | `/Maintenance/configfile.cfg` | High
13 | File | `/mkshop/Men/profile.php` | High
14 | File | `/ofcms/company-c-47` | High
15 | File | `/php/ping.php` | High
16 | File | `/pms/update_user.php?user_id=1` | High
17 | File | `/proc/kcore/` | Medium
18 | File | `/rapi/read_url` | High
19 | File | `/scripts/unlock_tasks.php` | High
20 | File | `/SysInfo1.htm` | High
21 | File | `/sysinfo_json.cgi` | High
22 | File | `/system/dictData/loadDictItem` | High
23 | File | `/system/user/modules/mod_users/controller.php` | High
24 | File | `/uncpath/` | Medium
25 | File | `/usr/sbin/httpd` | High
26 | File | `/util/print.c` | High
27 | ... | ... | ...

There are 229 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/b1312c87c1b9de8b519e8416fa819cef04cea004/Paperbug

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
