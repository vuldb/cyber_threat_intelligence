# MAZE - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _MAZE_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MAZE:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with MAZE or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [FIN6](https://vuldb.com/?actor.fin6) | High
2 | [Maze](https://vuldb.com/?actor.maze) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MAZE.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.199.167.188](https://vuldb.com/?ip.5.199.167.188) | - | [Maze](https://vuldb.com/?actor.maze) | High
2 | [37.1.213.9](https://vuldb.com/?ip.37.1.213.9) | - | [Maze](https://vuldb.com/?actor.maze) | High
3 | [37.252.7.142](https://vuldb.com/?ip.37.252.7.142) | - | [Maze](https://vuldb.com/?actor.maze) | High
4 | [54.39.233.188](https://vuldb.com/?ip.54.39.233.188) | mail.ov120.slpmt.net | [FIN6](https://vuldb.com/?actor.fin6) | High
5 | [91.208.184.174](https://vuldb.com/?ip.91.208.184.174) | sell.mybeststore.club | [FIN6](https://vuldb.com/?actor.fin6) | High
6 | [91.218.114.4](https://vuldb.com/?ip.91.218.114.4) | - | [Maze](https://vuldb.com/?actor.maze) | High
7 | [91.218.114.11](https://vuldb.com/?ip.91.218.114.11) | - | [Maze](https://vuldb.com/?actor.maze) | High
8 | [91.218.114.25](https://vuldb.com/?ip.91.218.114.25) | mail.autozetconsignment.com | [Maze](https://vuldb.com/?actor.maze) | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within MAZE. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 11 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during MAZE. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//` | Low
2 | File | `/admin/bookList?page=1&limit=10` | High
3 | File | `/admin/create_product.php` | High
4 | File | `/admin/edit-admin.php` | High
5 | File | `/admin/emp-profile-avatar.php` | High
6 | File | `/admin/index2.html` | High
7 | File | `/ajax-files/postComment.php` | High
8 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
9 | File | `/cgi-bin/cstecgi.cgi` | High
10 | File | `/cgi-bin/login_action.cgi` | High
11 | File | `/cgi-bin/webproc` | High
12 | File | `/Digital-Infrastructure-9.6.7/y9-digitalbase-webapp/y9-module-filemanager/risenet-y9boot-webapp-filemanager/src/main/java/net/risesoft/y9public/controller/Y9FileController.java` | High
13 | File | `/export` | Low
14 | File | `/forum/away.php` | High
15 | File | `/index.php` | Medium
16 | File | `/index.php/weblinks-categories` | High
17 | File | `/menu.html` | Medium
18 | File | `/mics/j_spring_security_check` | High
19 | File | `/mybb_1806/Upload/admin/index.php` | High
20 | File | `/scp/directory.php` | High
21 | File | `/search.php` | Medium
22 | File | `/smsa/add_class_submit.php` | High
23 | ... | ... | ...

There are 196 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.talosintelligence.com/2019/12/IR-Lessons-Maze.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0304-0311.html
* https://ddanchev.blogspot.com/2024/06/exposing-sonatrach-data-leak-and-data.html
* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-Maze.csv
* https://www.fireeye.com/blog/threat-research/2020/05/tactics-techniques-procedures-associated-with-maze-ransomware-incidents.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
