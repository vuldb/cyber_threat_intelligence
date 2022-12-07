# Raccoon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Raccoon](https://vuldb.com/?actor.raccoon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.raccoon](https://vuldb.com/?actor.raccoon)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Raccoon:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Raccoon.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.232.242.170](https://vuldb.com/?ip.3.232.242.170) | ec2-3-232-242-170.compute-1.amazonaws.com | - | Medium
2 | [5.181.156.252](https://vuldb.com/?ip.5.181.156.252) | no-rdns.mivocloud.com | - | High
3 | [8.248.161.254](https://vuldb.com/?ip.8.248.161.254) | - | - | High
4 | [8.249.225.254](https://vuldb.com/?ip.8.249.225.254) | - | - | High
5 | [8.249.241.254](https://vuldb.com/?ip.8.249.241.254) | - | - | High
6 | [8.249.245.254](https://vuldb.com/?ip.8.249.245.254) | - | - | High
7 | [8.253.132.120](https://vuldb.com/?ip.8.253.132.120) | - | - | High
8 | [8.253.156.120](https://vuldb.com/?ip.8.253.156.120) | - | - | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Raccoon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Raccoon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/searchview.php` | High
2 | File | `/ajax-files/followBoard.php` | High
3 | File | `/ajax-files/postComment.php` | High
4 | File | `/api/RecordingList/DownloadRecord?file=` | High
5 | File | `/categorypage.php` | High
6 | File | `/cgi-bin/kerbynet` | High
7 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
8 | File | `/domain/add` | Medium
9 | File | `/etc/sudoers` | Medium
10 | File | `/home.php` | Medium
11 | File | `/index.php/weblinks-categories` | High
12 | File | `/plain` | Low
13 | File | `/rapi/read_url` | High
14 | File | `/searchpin.php` | High
15 | File | `/show_group_members.php` | High
16 | File | `/soap/server_sa` | High
17 | File | `/TemplateManager/indexExternalLocation.jsp` | High
18 | File | `/usr/local/etc/config/addons/mh/loopupd.sh` | High
19 | File | `/web/entry/en/address/adrsSetUserWizard.cgi` | High
20 | File | `/web/google_analytics.php` | High
21 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
22 | File | `addentry.php` | Medium
23 | File | `admin/scripts/FileUploader/php.php` | High
24 | File | `AdminByRequest.exe` | High
25 | File | `admincp.php?app=prop&do=add` | High
26 | File | `advsearch.php` | High
27 | File | `append/override_content_security_policy_directives` | High
28 | File | `archive_endian.h` | High
29 | File | `assets/add/dns.php` | High
30 | ... | ... | ...

There are 253 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.group-ib.com/fakesecurity_raccoon
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://blog.talosintelligence.com/2021/12/threat-roundup-1203-1210.html
* https://blogs.blackberry.com/en/2021/08/threat-spotlight-lockbit-2-0-ransomware-takes-on-top-consulting-firm

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
