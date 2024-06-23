# PowerTrick - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PowerTrick](https://vuldb.com/?actor.powertrick). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.powertrick](https://vuldb.com/?actor.powertrick)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PowerTrick:

* [DE](https://vuldb.com/?country.de)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PowerTrick.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.161.246](https://vuldb.com/?ip.5.9.161.246) | static.246.161.9.5.clients.your-server.de | - | High
2 | [192.99.38.41](https://vuldb.com/?ip.192.99.38.41) | ns501815.ip-192-99-38.net | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PowerTrick_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PowerTrick. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config.php?display=disa&view=form` | High
2 | File | `/apps/acs-commons/content/page-compare.html` | High
3 | File | `/cgi/get_param.cgi` | High
4 | File | `/edit-db.php` | Medium
5 | File | `/files/password` | High
6 | File | `/guest_auth/cfg/upLoadCfg.php` | High
7 | File | `/hocms/classes/Master.php?f=delete_member` | High
8 | File | `/lists/admin/` | High
9 | File | `/phppath/php` | Medium
10 | File | `/services/getFile.cmd` | High
11 | File | `/sns/classes/Master.php?f=delete_img` | High
12 | File | `/usr/bin/pkexec` | High
13 | File | `/v2/quantum/save-data-upload-big-file` | High
14 | File | `/var/log/messages` | High
15 | File | `/web/jquery/uploader/multi_uploadify.php` | High
16 | File | `/webconsole/Controller` | High
17 | File | `/wordpress/wp-admin/admin.php?page=weblib-circulation-desk&orderby=title&order=DESC` | High
18 | File | `abook_database.php` | High
19 | File | `acl/save_user.cgi` | High
20 | File | `adaptive-images-script.php` | High
21 | File | `admin/auth.php` | High
22 | File | `admin/cgi-bin/listdir.pl` | High
23 | File | `adminuseredit.php?usertoedit=XSS` | High
24 | File | `AvastSvc.exe` | Medium
25 | File | `backupsettings.conf` | High
26 | File | `base/ErrorHandler.php` | High
27 | ... | ... | ...

There are 224 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/SentineLabs/PowerTrick/tree/master/IOCs

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
