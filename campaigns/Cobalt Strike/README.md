# Cobalt Strike - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cobalt Strike_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cobalt Strike:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cobalt Strike or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Cobalt Strike](https://vuldb.com/?actor.cobalt_strike) | High
2 | [Conti](https://vuldb.com/?actor.conti) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cobalt Strike.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.108.57.108](https://vuldb.com/?ip.23.108.57.108) | - | [Cobalt Strike](https://vuldb.com/?actor.cobalt_strike) | High
2 | [62.128.111.176](https://vuldb.com/?ip.62.128.111.176) | - | [Cobalt Strike](https://vuldb.com/?actor.cobalt_strike) | High
3 | [82.118.21.1](https://vuldb.com/?ip.82.118.21.1) | 77626-46583.hyperdomen.com | [Conti](https://vuldb.com/?actor.conti) | High
4 | ... | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cobalt Strike. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1211 | CWE-254, CWE-358 | 7PK Security Features | High
4 | ... | ... | ... | ...

There are 1 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cobalt Strike. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/admin/success_story.php` | High
3 | File | `/bin/bw` | Low
4 | File | `/etc/tomcat8/Catalina/attack` | High
5 | File | `/movie-portal-script/movie.php` | High
6 | File | `/notice-edit.php` | High
7 | File | `/servlet/webacc` | High
8 | File | `/tmp` | Low
9 | File | `/uncpath/` | Medium
10 | File | `/wp-content/plugins/updraftplus/admin.php` | High
11 | File | `abook_database.php` | High
12 | File | `add_comment.php` | High
13 | File | `admin/images.php` | High
14 | File | `admin/index.php/template/upload` | High
15 | File | `admin/preview.php` | High
16 | File | `agent/Core/Controller/SendRequest.cpp` | High
17 | File | `AjaxResponse.jsp` | High
18 | File | `apl_42.c` | Medium
19 | File | `app/code/core/Mage/Rss/Helper/Order.php` | High
20 | File | `archive_read_support_format_rar5.c` | High
21 | File | `blanko.preview.php` | High
22 | File | `blueprints/sections/edit/1` | High
23 | File | `boardData103.php/boardDataJP.php/boardDataNA.php/boardDataWW.php` | High
24 | File | `breadcrumbs_create.php` | High
25 | File | `burl.c` | Low
26 | File | `cachemgr.cgi` | Medium
27 | File | `CFM File Handler` | High
28 | File | `cgi-bin/awstats.pl` | High
29 | File | `cgi-bin/webproc` | High
30 | File | `Change-password.php` | High
31 | File | `class.t3lib_formmail.php` | High
32 | File | `content/common/cursors/webcursor.cc` | High
33 | File | `content/content.systempreferences.php` | High
34 | ... | ... | ...

There are 288 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://research.checkpoint.com/2019/cobalt-group-returns-to-kazakhstan/
* https://therecord.media/disgruntled-ransomware-affiliate-leaks-the-conti-gangs-technical-manuals/
* https://twitter.com/malware_traffic/status/1400876426497253379
* https://twitter.com/malware_traffic/status/1415740795622248452
* https://twitter.com/Unit42_Intel/status/1392174941181812737
* https://us-cert.cisa.gov/ncas/alerts/aa21-148a
* https://www.welivesecurity.com/2021/03/10/exchange-servers-under-siege-10-apt-groups/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
