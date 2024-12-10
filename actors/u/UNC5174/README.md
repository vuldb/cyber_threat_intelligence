# UNC5174 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UNC5174](https://vuldb.com/?actor.unc5174). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.unc5174](https://vuldb.com/?actor.unc5174)

## Campaigns

The following _campaigns_ are known and can be associated with UNC5174:

* CVE-2023-46747

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UNC5174:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UNC5174.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [61.239.68.73](https://vuldb.com/?ip.61.239.68.73) | 061239068073.ctinets.com | CVE-2023-46747 | High
2 | [118.140.151.242](https://vuldb.com/?ip.118.140.151.242) | - | CVE-2023-46747 | High
3 | [172.104.124.74](https://vuldb.com/?ip.172.104.124.74) | li1734-74.members.linode.com | CVE-2023-46747 | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UNC5174_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UNC5174. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
2 | File | `/forum/away.php` | High
3 | File | `/portal/user-register.php` | High
4 | File | `adclick.php` | Medium
5 | File | `add.php/del.php` | High
6 | File | `addentry.php` | Medium
7 | File | `admin/conf_users_edit.php` | High
8 | File | `admin/page-login.php` | High
9 | File | `awstats.pl` | Medium
10 | File | `base_maintenance.php` | High
11 | File | `classified_right.php` | High
12 | File | `cloud.php` | Medium
13 | ... | ... | ...

There are 98 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cloud.google.com/blog/topics/threat-intelligence/initial-access-brokers-exploit-f5-screenconnect?hl=en
* https://www.mandiant.com/resources/blog/initial-access-brokers-exploit-f5-screenconnect

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
