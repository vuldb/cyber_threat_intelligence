# servhelper - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _servhelper_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with servhelper:

* [US](https://vuldb.com/?country.us)
* [AT](https://vuldb.com/?country.at)
* [RU](https://vuldb.com/?country.ru)

## Actors

These _actors_ are associated with servhelper or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TA505](https://vuldb.com/?actor.ta505) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of servhelper.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.63.101.210](https://vuldb.com/?ip.45.63.101.210) | 45.63.101.210.vultr.com | [TA505](https://vuldb.com/?actor.ta505) | Medium
2 | [46.161.27.241](https://vuldb.com/?ip.46.161.27.241) | - | [TA505](https://vuldb.com/?actor.ta505) | High
3 | [151.236.23.56](https://vuldb.com/?ip.151.236.23.56) | 56.23.236.151.in-addr.arpa | [TA505](https://vuldb.com/?actor.ta505) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within servhelper. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1059 | CWE-94 | Cross Site Scripting | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during servhelper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/addusers` | High
2 | File | `/dus/shopliste/index.php` | High
3 | File | `/etc/path` | Medium
4 | File | `/nagiosql/admin/checkcommands.php` | High
5 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
6 | File | `/public/login.htm` | High
7 | File | `/sendKey` | Medium
8 | File | `/tmp` | Low
9 | File | `/usr/5bin/su` | Medium
10 | File | `/usr/bin/mail` | High
11 | File | `/var/dt/` | Medium
12 | File | `00.jsp` | Low
13 | File | `adclick.php` | Medium
14 | File | `admin.asp` | Medium
15 | File | `admin.php` | Medium
16 | File | `admin/` | Low
17 | File | `admin/manage-comments.php` | High
18 | File | `administrator/mail/download.cfm` | High
19 | File | `AdminViewError/AdminAddadmin` | High
20 | File | `agentdisplay.php` | High
21 | File | `ashnews.php/ashheadlines.php` | High
22 | File | `auction.cgi` | Medium
23 | File | `autologin.jsp` | High
24 | File | `axspawn.c` | Medium
25 | File | `base_ag_main.php` | High
26 | File | `base_qry_main.php` | High
27 | File | `bigsam_guestbook.php` | High
28 | File | `bugzilla_email_append.pl` | High
29 | ... | ... | ...

There are 244 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.deepinstinct.com/2019/04/02/new-servhelper-variant-employs-excel-4-0-macro-to-drop-signed-payload/
* https://www.proofpoint.com/us/threat-insight/post/servhelper-and-flawedgrace-new-malware-introduced-ta505

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
