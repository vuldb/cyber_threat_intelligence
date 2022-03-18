# FIN6 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FIN6](https://vuldb.com/?actor.fin6). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fin6](https://vuldb.com/?actor.fin6)

## Campaigns

The following _campaigns_ are known and can be associated with FIN6:

* MAZE

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FIN6:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FIN6.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.199.167.188](https://vuldb.com/?ip.5.199.167.188) | - | MAZE | High
2 | [31.220.45.151](https://vuldb.com/?ip.31.220.45.151) | - | - | High
3 | [37.1.213.9](https://vuldb.com/?ip.37.1.213.9) | - | MAZE | High
4 | [37.1.221.212](https://vuldb.com/?ip.37.1.221.212) | adspect.net | - | High
5 | [37.252.7.142](https://vuldb.com/?ip.37.252.7.142) | - | MAZE | High
6 | [46.4.113.237](https://vuldb.com/?ip.46.4.113.237) | static.237.113.4.46.clients.your-server.de | - | High
7 | [46.166.173.109](https://vuldb.com/?ip.46.166.173.109) | - | - | High
8 | [54.39.233.188](https://vuldb.com/?ip.54.39.233.188) | mail.ov120.slpmt.net | MAZE | High
9 | [62.210.136.65](https://vuldb.com/?ip.62.210.136.65) | 62-210-136-65.rev.poneytelecom.eu | - | High
10 | [89.105.194.236](https://vuldb.com/?ip.89.105.194.236) | - | - | High
11 | [91.208.184.174](https://vuldb.com/?ip.91.208.184.174) | sell.mybeststore.club | MAZE | High
12 | [91.218.114.4](https://vuldb.com/?ip.91.218.114.4) | - | MAZE | High
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by FIN6. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FIN6. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/accountancy/admin/accountmodel.php` | High
2 | File | `/admin/setup` | Medium
3 | File | `/advance_push/public/login` | High
4 | File | `/ajax-files/postComment.php` | High
5 | File | `/anony/mjpg.cgi` | High
6 | File | `/bin/sh` | Low
7 | File | `/catalog` | Medium
8 | File | `/cgi-bin/ExportSettings.sh` | High
9 | File | `/cgi-bin/login_action.cgi` | High
10 | File | `/cgi-bin/webproc` | High
11 | File | `/checkLogin.cgi` | High
12 | File | `/classes/profile.class.php` | High
13 | File | `/common/run_report.php` | High
14 | File | `/data/inc/images.php` | High
15 | File | `/data/syslog.filter.json` | High
16 | File | `/data/wps.setup.json` | High
17 | File | `/docs/captcha_(number).jpeg` | High
18 | File | `/etc/config/rpcd` | High
19 | File | `/etc/hosts` | Medium
20 | File | `/forum/` | Low
21 | File | `/goform/net\_Web\_get_value` | High
22 | File | `/index.php` | Medium
23 | File | `/index.php/weblinks-categories` | High
24 | File | `/j_security_check` | High
25 | File | `/login.html` | Medium
26 | File | `/menu.html` | Medium
27 | File | `/mics/j_spring_security_check` | High
28 | File | `/mnt/sdcard/$PRO_NAME/upgrade.sh` | High
29 | File | `/mnt/skyeye/mode_switch.sh` | High
30 | File | `/mybb_1806/Upload/admin/index.php` | High
31 | File | `/oauth/token` | Medium
32 | File | `/plain` | Low
33 | File | `/romfile.cfg` | Medium
34 | File | `/scp/directory.php` | High
35 | File | `/setSystemAdmin` | High
36 | File | `/system/WCore/WHelper.php` | High
37 | File | `/tmp/connlicj.bin` | High
38 | File | `/uncpath/` | Medium
39 | File | `/upload` | Low
40 | File | `/userfs/bin/tcapi` | High
41 | File | `/var/www/xms/application/config/config.php` | High
42 | File | `/var/www/xms/application/controllers/gatherLogs.php` | High
43 | File | `/var/www/xms/application/controllers/verifyLogin.php` | High
44 | File | `/var/www/xms/cleanzip.sh` | High
45 | File | `/vendor/phpdocumentor/reflection-docblock/tests/phpDocumentor/Reflection/DocBlock/Tag/LinkTagTeet.php` | High
46 | File | `/websocket/exec` | High
47 | File | `/workspaceCleanup` | High
48 | File | `/wp-admin/admin-ajax.php?action=get_wdtable&table_id=1` | High
49 | File | `account/gallery.php` | High
50 | File | `add_edit_cat.asp` | High
51 | File | `admin.htm` | Medium
52 | File | `admin.php` | Medium
53 | ... | ... | ...

There are 462 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securityintelligence.com/posts/more_eggs-anyone-threat-actor-itg08-strikes-again/
* https://usa.visa.com/dam/VCOM/global/support-legal/documents/fin6-cybercrime-group-expands-threat-To-ecommerce-merchants.pdf
* https://www.fireeye.com/blog/threat-research/2019/04/pick-six-intercepting-a-fin6-intrusion.html
* https://www.fireeye.com/blog/threat-research/2020/05/tactics-techniques-procedures-associated-with-maze-ransomware-incidents.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
