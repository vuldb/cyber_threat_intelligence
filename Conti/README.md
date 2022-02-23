# Conti - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Conti](https://vuldb.com/?actor.conti). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.conti](https://vuldb.com/?actor.conti)

## Campaigns

The following _campaigns_ are known and can be associated with Conti:

* Cobalt Strike

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Conti:

* DE
* US
* TR
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Conti.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 23.82.140.137 | - | - | High
2 | 23.106.160.174 | - | - | High
3 | 82.118.21.1 | 77626-46583.hyperdomen.com | Cobalt Strike | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Conti. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1211 | CWE-254, CWE-358 | 7PK Security Features | High
4 | ... | ... | ... | ...

There are 2 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Conti. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/success_story.php` | High
2 | File | `/bin/bw` | Low
3 | File | `/etc/tomcat8/Catalina/attack` | High
4 | File | `/movie-portal-script/movie.php` | High
5 | File | `/servlet/webacc` | High
6 | File | `/uncpath/` | Medium
7 | File | `abook_database.php` | High
8 | File | `add_comment.php` | High
9 | File | `admin/images.php` | High
10 | File | `admin/index.php/template/upload` | High
11 | File | `admin/preview.php` | High
12 | File | `agent/Core/Controller/SendRequest.cpp` | High
13 | File | `AjaxResponse.jsp` | High
14 | File | `apl_42.c` | Medium
15 | File | `app/code/core/Mage/Rss/Helper/Order.php` | High
16 | File | `archive_read_support_format_rar5.c` | High
17 | File | `blanko.preview.php` | High
18 | File | `blueprints/sections/edit/1` | High
19 | File | `boardData103.php/boardDataJP.php/boardDataNA.php/boardDataWW.php` | High
20 | File | `cachemgr.cgi` | Medium
21 | File | `CFM File Handler` | High
22 | File | `cgi-bin/awstats.pl` | High
23 | File | `cgi-bin/webproc` | High
24 | File | `Change-password.php` | High
25 | File | `class.t3lib_formmail.php` | High
26 | File | `content/common/cursors/webcursor.cc` | High
27 | File | `content/content.systempreferences.php` | High
28 | File | `course/classes/management_renderer.php` | High
29 | File | `dapur/index.php` | High
30 | ... | ... | ...

There are 256 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-Conti.csv
* https://therecord.media/disgruntled-ransomware-affiliate-leaks-the-conti-gangs-technical-manuals/
* https://twitter.com/vxunderground/status/1414809517993435139

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
