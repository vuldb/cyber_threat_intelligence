# DarkVNC - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _DarkVNC_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DarkVNC:

* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* [IT](https://vuldb.com/?country.it)
* ...

There are 2 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with DarkVNC or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TA551](https://vuldb.com/?actor.ta551) | High
2 | [DarkVNC](https://vuldb.com/?actor.darkvnc) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DarkVNC.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [2.152.208.135](https://vuldb.com/?ip.2.152.208.135) | 2.152.208.135.dyn.user.ono.com | [DarkVNC](https://vuldb.com/?actor.darkvnc) | High
2 | [20.211.121.138](https://vuldb.com/?ip.20.211.121.138) | - | [DarkVNC](https://vuldb.com/?actor.darkvnc) | High
3 | [65.20.106.109](https://vuldb.com/?ip.65.20.106.109) | 65.20.106.109.vultrusercontent.com | [DarkVNC](https://vuldb.com/?actor.darkvnc) | Medium
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within DarkVNC. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during DarkVNC. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/index.php` | High
2 | File | `/cimom` | Low
3 | File | `/config/` | Medium
4 | File | `/dev/fd` | Low
5 | File | `/doc/index.php` | High
6 | File | `/index.php` | Medium
7 | File | `/members/index.php` | High
8 | File | `/my_photo_gallery/image.php` | High
9 | File | `/net` | Low
10 | File | `/proc` | Low
11 | File | `/reps/classes/Users.php?f=delete_agent` | High
12 | File | `/s/` | Low
13 | File | `/services/details.asp` | High
14 | File | `/uncpath/` | Medium
15 | File | `389/tcp` | Low
16 | File | `12122006-djtest.doc` | High
17 | File | `abf_js.php` | Medium
18 | File | `abitwhizzy.php` | High
19 | File | `about.mgm.php` | High
20 | File | `acc.php` | Low
21 | File | `acc_verify.php` | High
22 | File | `activate.php` | Medium
23 | File | `activenews_search.asp` | High
24 | File | `add.php` | Low
25 | File | `addadmin.asp` | Medium
26 | File | `addguest.cgi` | Medium
27 | File | `addpost1.asp` | Medium
28 | File | `addpost1.php` | Medium
29 | File | `addressbook.update.php` | High
30 | File | `addshowsform.php` | High
31 | File | `addweblog.php` | High
32 | File | `add_go.php` | Medium
33 | File | `add_post.php3` | High
34 | File | `admin.a6mambocredits.php` | High
35 | File | `admin.loudmouth.php` | High
36 | File | `admin.lurm_constructor.php` | High
37 | File | `admin.php` | Medium
38 | File | `admin.pl` | Medium
39 | File | `admin/haber_ekle.asp` | High
40 | File | `admin/index.php` | High
41 | File | `admin/main.asp` | High
42 | File | `admin/modules_data.php` | High
43 | File | `admin/specials.php` | High
44 | File | `admin_default.asp` | High
45 | File | `admin_events.php` | High
46 | File | `agencyprofile.asp` | High
47 | File | `agenda.php3` | Medium
48 | File | `agent_links.pl` | High
49 | File | `agent_subaffiliates.pl` | High
50 | File | `akocomment.php` | High
51 | File | `anjel.index.php` | High
52 | File | `api.php` | Low
53 | File | `articleview.php` | High
54 | File | `ascan_6.asp` | Medium
55 | File | `ashnews.php` | Medium
56 | File | `attributes_preview.php` | High
57 | File | `auth.cookie.inc.php` | High
58 | File | `authfiles/login.asp` | High
59 | File | `authldap.php` | Medium
60 | File | `authuser.php` | Medium
61 | File | `bad_link.php` | Medium
62 | File | `BaseLoader.php` | High
63 | File | `bengine.exe` | Medium
64 | File | `bigshow.php` | Medium
65 | File | `bin/ftp` | Low
66 | File | `blog.php` | Medium
67 | File | `board.php` | Medium
68 | File | `bottom.php` | Medium
69 | File | `calendar.php` | Medium
70 | File | `calendar_new.asp` | High
71 | File | `cat.asp` | Low
72 | File | `catalog.php` | Medium
73 | File | `catalogue.asp` | High
74 | File | `cgi.c` | Low
75 | File | `change_pass.php` | High
76 | File | `chan_skinny.c` | High
77 | File | `check.php` | Medium
78 | File | `checkprofile.asp` | High
79 | File | `claro_init_global.inc.php` | High
80 | File | `class` | Low
81 | File | `class.definition.php` | High
82 | File | `class.forumposts.php` | High
83 | File | `class.inputfilter.php` | High
84 | File | `class.novaAdmin.mysql.php` | High
85 | File | `class_template.php` | High
86 | File | `client.php` | Medium
87 | File | `clients.php` | Medium
88 | File | `clspack.exe` | Medium
89 | File | `cmpro_header.inc.php` | High
90 | File | `comadd.php` | Medium
91 | File | `comment.php` | Medium
92 | File | `common.php` | Medium
93 | File | `components_modify_content.php` | High
94 | File | `components_new_content.php` | High
95 | File | `compteur.php` | Medium
96 | File | `conf.pollxt.php` | High
97 | ... | ... | ...

There are 860 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/esThreatIntelligence/iocs/blob/main/DarkVNC/darkvnc_iocs-1-9-2024.txt
* https://isc.sans.edu/diary/28884
* https://isc.sans.edu/diary/28934
* https://isc.sans.edu/diary/IcedID+%28Bokbot%29+with+Dark+VNC+and+Cobalt+Strike/28884
* https://threatfox.abuse.ch
* https://twitter.com/fr0s7_/status/1712788618824106443
* https://twitter.com/unit42_intel/status/1541888192802181120
* https://twitter.com/Unit42_Intel/status/1587463493300719616
* https://www.virustotal.com/gui/file/78bf839b8dbb956925e0d3a3f72ad939143310fd8db627f6df8f509070e81a03/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
