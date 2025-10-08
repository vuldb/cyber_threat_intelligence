# LaplasClipper - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LaplasClipper](https://vuldb.com/?actor.laplasclipper). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.laplasclipper](https://vuldb.com/?actor.laplasclipper)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LaplasClipper:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LaplasClipper.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.62.241](https://vuldb.com/?ip.5.61.62.241) | - | - | High
2 | [45.83.122.33](https://vuldb.com/?ip.45.83.122.33) | mitchellgrimshaw121.sitesblog.com | - | High
3 | [45.84.121.44](https://vuldb.com/?ip.45.84.121.44) | - | - | High
4 | [45.159.188.125](https://vuldb.com/?ip.45.159.188.125) | coinreborn24.com | - | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LaplasClipper_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-44 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LaplasClipper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/?page=reserve` | High
4 | File | `/adfs/ls` | Medium
5 | File | `/admin.php?p=/Area/index#tab=t2` | High
6 | File | `/admin/add_ikev2.php` | High
7 | File | `/admin/admin_action.php` | High
8 | File | `/admin/category_save.php` | High
9 | File | `/admin/index.php` | High
10 | File | `/admin/index2.html` | High
11 | File | `/admin/list_ipAddressPolicy.php` | High
12 | File | `/admin/login.php` | High
13 | File | `/admin/manage_model.php` | High
14 | File | `/admin/manage_user.php` | High
15 | File | `/admin/new-content` | High
16 | File | `/admin/search-vehicle.php` | High
17 | File | `/admin/subject.php` | High
18 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
19 | File | `/admin/twitter.php` | High
20 | File | `/admin/voters_add.php` | High
21 | File | `/admin/voters_delete.php` | High
22 | File | `/api/v1/settings` | High
23 | File | `/api/v1/toolbox/device/update/swap` | High
24 | File | `/app/zentao/module/repo/model.php` | High
25 | File | `/authentication/logout.php` | High
26 | File | `/bin/httpd` | Medium
27 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
28 | File | `/catalog/all-products` | High
29 | File | `/cgi-bin/cstecgi.cgi` | High
30 | File | `/cgi-bin/ExportSettings.sh` | High
31 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
32 | File | `/com/esafenet/servlet/policy/HookService.java` | High
33 | File | `/controllers/updatesettings.php` | High
34 | File | `/dashboard/admin/submit_plan_new.php` | High
35 | File | `/doctor/appointment-bwdates-reports-details.php` | High
36 | File | `/edit-subject.php` | High
37 | File | `/endpoint/add-user.php` | High
38 | File | `/etc/controller-agent/agent.conf` | High
39 | File | `/etc/postfix/sender_login` | High
40 | File | `/etc/shadow.sample` | High
41 | ... | ... | ...

There are 350 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/6c910d55-f846-46f8-bfa5-b6af3986466c
* https://app.any.run/tasks/47c2c5a4-d752-4ba2-a2d4-15665bd5aac3
* https://bazaar.abuse.ch/sample/bd7b6f6ef2d0adfb9b2e058fc46ad29ff1edffc648f9d7408745916bb8a2f310/
* https://cyble.com/blog/new-laplas-clipper-distributed-by-smokeloader/
* https://de.darktrace.com/blog/laplas-clipper-defending-against-crypto-currency-thieves-with-detect-respond
* https://github.com/Cisco-Talos/IOCs/blob/main/2023/02/new-mortalkombat-ransomware-and-laplas-clipper-malware-threats.txt
* https://threatfox.abuse.ch
* https://twitter.com/1ZRR4H/status/1623067548781539339
* https://twitter.com/crep1x/status/1636352242969108484
* https://twitter.com/James_inthe_box/status/1626288456795291650

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
