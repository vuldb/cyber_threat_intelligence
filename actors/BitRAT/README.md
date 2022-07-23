# BitRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BitRAT](https://vuldb.com/?actor.bitrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bitrat](https://vuldb.com/?actor.bitrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BitRAT:

* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BitRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [135.181.6.215](https://vuldb.com/?ip.135.181.6.215) | static.215.6.181.135.clients.your-server.de | - | High
2 | [135.181.140.153](https://vuldb.com/?ip.135.181.140.153) | static.153.140.181.135.clients.your-server.de | - | High
3 | [135.181.140.182](https://vuldb.com/?ip.135.181.140.182) | static.182.140.181.135.clients.your-server.de | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BitRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1059 | CWE-94 | Cross Site Scripting | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BitRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/includes/db_adodb.php` | High
2 | File | `/includes/db_connect.php` | High
3 | File | `/includes/session.php` | High
4 | File | `/modules/admin/vw_usr_roles.php` | High
5 | File | `/modules/projects/gantt2.php` | High
6 | File | `/modules/projects/vw_files.php` | High
7 | File | `/modules/public/date_format.php` | High
8 | File | `/modules/tasks/gantt.php` | High
9 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
10 | File | `actions/del.php` | High
11 | File | `addsite.php` | Medium
12 | File | `Admin.PHP` | Medium
13 | File | `admin.php` | Medium
14 | File | `admin/define.inc.php` | High
15 | File | `admin/general.php` | High
16 | File | `admin/review.php` | High
17 | File | `admincp/auth/secure.php` | High
18 | File | `affich.php` | Medium
19 | File | `agenda.php3` | Medium
20 | File | `agenda2.php3` | Medium
21 | File | `akocomments.php` | High
22 | File | `album_portal.php` | High
23 | File | `al_initialize.php` | High
24 | File | `announcements.php` | High
25 | File | `apa_phpinclude.inc.php` | High
26 | File | `application.php` | High
27 | File | `ashnews.php/ashheadlines.php` | High
28 | File | `auction\auction_common.php` | High
29 | File | `auktion.cgi` | Medium
30 | File | `auth.inc.php` | Medium
31 | File | `auth.php` | Medium
32 | File | `authform.inc.php` | High
33 | File | `bad_link.php` | Medium
34 | File | `bb_usage_stats.php` | High
35 | ... | ... | ...

There are 299 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.morphisec.com/the-babadeda-crypter-targeting-crypto-nft-defi-communities

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
