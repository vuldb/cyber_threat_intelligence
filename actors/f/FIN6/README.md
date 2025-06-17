# FIN6 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FIN6](https://vuldb.com/?actor.fin6). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fin6](https://vuldb.com/?actor.fin6)

## Campaigns

The following _campaigns_ are known and can be associated with FIN6:

* MAZE
* Point of Sale Thin Clients

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FIN6:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FIN6.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.72.0.200](https://vuldb.com/?ip.2.72.0.200) | 2-72-0-200.kcell.kz | Point of Sale Thin Clients | High
2 | [5.39.219.15](https://vuldb.com/?ip.5.39.219.15) | - | Point of Sale Thin Clients | High
3 | [5.199.167.188](https://vuldb.com/?ip.5.199.167.188) | - | MAZE | High
4 | [31.220.45.151](https://vuldb.com/?ip.31.220.45.151) | - | - | High
5 | [34.245.88.113](https://vuldb.com/?ip.34.245.88.113) | ec2-34-245-88-113.eu-west-1.compute.amazonaws.com | Point of Sale Thin Clients | Medium
6 | [35.182.31.181](https://vuldb.com/?ip.35.182.31.181) | ec2-35-182-31-181.ca-central-1.compute.amazonaws.com | Point of Sale Thin Clients | Medium
7 | [37.1.213.9](https://vuldb.com/?ip.37.1.213.9) | - | MAZE | High
8 | [37.1.221.212](https://vuldb.com/?ip.37.1.221.212) | adspect.net | - | High
9 | [37.139.21.20](https://vuldb.com/?ip.37.139.21.20) | - | Point of Sale Thin Clients | High
10 | [37.252.7.142](https://vuldb.com/?ip.37.252.7.142) | - | MAZE | High
11 | [45.247.22.27](https://vuldb.com/?ip.45.247.22.27) | - | Point of Sale Thin Clients | High
12 | [46.4.113.237](https://vuldb.com/?ip.46.4.113.237) | static.237.113.4.46.clients.your-server.de | - | High
13 | [46.166.173.109](https://vuldb.com/?ip.46.166.173.109) | - | - | High
14 | [47.75.151.154](https://vuldb.com/?ip.47.75.151.154) | - | Point of Sale Thin Clients | High
15 | [54.39.233.188](https://vuldb.com/?ip.54.39.233.188) | mail.ov120.slpmt.net | MAZE | High
16 | ... | ... | ... | ...

There are 61 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _FIN6_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FIN6. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//` | Low
2 | File | `/accountancy/admin/accountmodel.php` | High
3 | File | `/admin/bookList?page=1&limit=10` | High
4 | File | `/admin/conferences/get-all-status/` | High
5 | File | `/admin/create_product.php` | High
6 | File | `/admin/edit-admin.php` | High
7 | File | `/admin/emp-profile-avatar.php` | High
8 | File | `/admin/index.php?n=system&c=filept&a=doGetFileList` | High
9 | File | `/admin/index2.html` | High
10 | File | `/admin/maintenance/view_designation.php` | High
11 | File | `/admin/setup` | Medium
12 | File | `/admin/user/manage_user.php` | High
13 | File | `/advance_push/public/login` | High
14 | File | `/ajax-files/postComment.php` | High
15 | File | `/anony/mjpg.cgi` | High
16 | File | `/application/common.php#action_log` | High
17 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
18 | File | `/catalog` | Medium
19 | File | `/cgi-bin/cstecgi.cgi` | High
20 | File | `/cgi-bin/ExportSettings.sh` | High
21 | File | `/cgi-bin/login_action.cgi` | High
22 | File | `/cgi-bin/webproc` | High
23 | File | `/checkLogin.cgi` | High
24 | File | `/classes/profile.class.php` | High
25 | File | `/common/run_report.php` | High
26 | File | `/data/inc/images.php` | High
27 | File | `/data/syslog.filter.json` | High
28 | File | `/data/wps.setup.json` | High
29 | File | `/docs/captcha_(number).jpeg` | High
30 | File | `/etc/config/rpcd` | High
31 | File | `/etc/hosts` | Medium
32 | File | `/export` | Low
33 | File | `/forum/` | Low
34 | File | `/forum/away.php` | High
35 | File | `/goform/net\_Web\_get_value` | High
36 | File | `/index.php` | Medium
37 | File | `/index.php/weblinks-categories` | High
38 | File | `/j_security_check` | High
39 | File | `/login.html` | Medium
40 | File | `/menu.html` | Medium
41 | File | `/mics/j_spring_security_check` | High
42 | File | `/mnt/sdcard/$PRO_NAME/upgrade.sh` | High
43 | File | `/mnt/skyeye/mode_switch.sh` | High
44 | File | `/mybb_1806/Upload/admin/index.php` | High
45 | File | `/oauth/token` | Medium
46 | File | `/plain` | Low
47 | File | `/pms/admin/visits/view_visit.php` | High
48 | File | `/public/login.htm` | High
49 | File | `/romfile.cfg` | Medium
50 | File | `/scp/directory.php` | High
51 | File | `/search.php` | Medium
52 | File | `/setSystemAdmin` | High
53 | File | `/smsa/add_class_submit.php` | High
54 | File | `/spip.php` | Medium
55 | File | `/system/WCore/WHelper.php` | High
56 | File | `/uncpath/` | Medium
57 | File | `/upload` | Low
58 | File | `/uploads/tags.php` | High
59 | File | `/var/www/xms/application/config/config.php` | High
60 | ... | ... | ...

There are 523 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* http://blog.morphisec.com/new-global-attack-on-point-of-sale-systems
* https://securityintelligence.com/posts/more_eggs-anyone-threat-actor-itg08-strikes-again/
* https://usa.visa.com/dam/VCOM/global/support-legal/documents/fin6-cybercrime-group-expands-threat-To-ecommerce-merchants.pdf
* https://www.fireeye.com/blog/threat-research/2019/04/pick-six-intercepting-a-fin6-intrusion.html
* https://www.fireeye.com/blog/threat-research/2020/05/tactics-techniques-procedures-associated-with-maze-ransomware-incidents.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
