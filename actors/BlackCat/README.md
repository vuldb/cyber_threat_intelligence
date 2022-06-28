# BlackCat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlackCat](https://vuldb.com/?actor.blackcat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.blackcat](https://vuldb.com/?actor.blackcat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackCat:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackCat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.46.245.56](https://vuldb.com/?ip.20.46.245.56) | - | - | High
2 | [23.106.223.97](https://vuldb.com/?ip.23.106.223.97) | - | - | High
3 | [37.120.238.58](https://vuldb.com/?ip.37.120.238.58) | - | - | High
4 | ... | ... | ... | ...

There are 12 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlackCat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-250, CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 11 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackCat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/admin/plog/index.html` | High
2 | File | `/admin.php/admin/ulog/index.html` | High
3 | File | `/admin.php/Label/js_del` | High
4 | File | `/admin.php/Label/page_del` | High
5 | File | `/admin.php/user/zu_del` | High
6 | File | `/admin.php?id=siteoptions&social=display&value=0&sid=2` | High
7 | File | `/admin.php?id=siteoptions&social=edit&sid=2` | High
8 | File | `/admin/edit.php` | High
9 | File | `/admin/inbox.php&action=read` | High
10 | File | `/admin/new-content` | High
11 | File | `/admin/posts.php` | High
12 | File | `/admin/posts.php&action=delete` | High
13 | File | `/admin/run_ajax.php` | High
14 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
15 | File | `/admin/uesrs.php&&action=delete&userid=4` | High
16 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
17 | File | `/api/programs/orgUnits?programs` | High
18 | File | `/bcms/admin/?page=reports/daily_court_rental_report` | High
19 | File | `/bcms/admin/?page=service_transactions/manage_service_transaction` | High
20 | File | `/bcms/classes/Master.php?f=delete_court_rental` | High
21 | File | `/blog/blog.php` | High
22 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
23 | File | `/cgi-bin/kerbynet` | High
24 | File | `/cgi/get_param.cgi` | High
25 | File | `/checklogin.jsp` | High
26 | File | `/cms/classes/Master.php?f=delete_service` | High
27 | File | `/ctpms/admin/?page=individuals/view_individual` | High
28 | File | `/ctpms/classes/Master.php?f=delete_img` | High
29 | File | `/dashboard/snapshot/*?orgId=0` | High
30 | File | `/etc/ajenti/config.yml` | High
31 | File | `/fuel/sitevariables/delete/4` | High
32 | File | `/goform/AdvSetLanIp` | High
33 | File | `/goform/aspForm` | High
34 | File | `/goform/SetNetControlList` | High
35 | File | `/goform/setNetworkLan` | High
36 | File | `/goform/websURLFilterAddDel` | High
37 | ... | ... | ...

There are 322 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/03/from-blackmatter-to-blackcat-analyzing.html
* https://www.ic3.gov/Media/News/2022/220420.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
