# Gaming Companies - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Gaming Companies_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gaming Companies:

* [MS](https://vuldb.com/?country.ms)
* [HK](https://vuldb.com/?country.hk)
* [KR](https://vuldb.com/?country.kr)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Gaming Companies or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [PassCV](https://vuldb.com/?actor.passcv) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Gaming Companies.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [14.29.50.66](https://vuldb.com/?ip.14.29.50.66) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
2 | [23.252.164.156](https://vuldb.com/?ip.23.252.164.156) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
3 | [23.252.164.238](https://vuldb.com/?ip.23.252.164.238) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
4 | [27.255.64.94](https://vuldb.com/?ip.27.255.64.94) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
5 | [42.121.131.17](https://vuldb.com/?ip.42.121.131.17) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
6 | [45.114.9.206](https://vuldb.com/?ip.45.114.9.206) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
7 | [45.125.13.227](https://vuldb.com/?ip.45.125.13.227) | spk.cloudie.hk | [PassCV](https://vuldb.com/?actor.passcv) | High
8 | [45.125.13.247](https://vuldb.com/?ip.45.125.13.247) | spk.cloudie.hk | [PassCV](https://vuldb.com/?actor.passcv) | High
9 | [58.64.203.13](https://vuldb.com/?ip.58.64.203.13) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
10 | [61.36.11.112](https://vuldb.com/?ip.61.36.11.112) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
11 | [69.56.214.232](https://vuldb.com/?ip.69.56.214.232) | e8.d6.3845.static.theplanet.com | [PassCV](https://vuldb.com/?actor.passcv) | High
12 | [98.126.91.205](https://vuldb.com/?ip.98.126.91.205) | suvmagic.com | [PassCV](https://vuldb.com/?actor.passcv) | High
13 | [98.126.107.249](https://vuldb.com/?ip.98.126.107.249) | 98.126.107.249.static.krypt.com | [PassCV](https://vuldb.com/?actor.passcv) | High
14 | [98.126.193.223](https://vuldb.com/?ip.98.126.193.223) | 98.126.193.223.customer.vpls.net | [PassCV](https://vuldb.com/?actor.passcv) | High
15 | [101.55.33.106](https://vuldb.com/?ip.101.55.33.106) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
16 | [101.55.64.183](https://vuldb.com/?ip.101.55.64.183) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
17 | [101.55.64.209](https://vuldb.com/?ip.101.55.64.209) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
18 | [101.55.64.246](https://vuldb.com/?ip.101.55.64.246) | - | [PassCV](https://vuldb.com/?actor.passcv) | High
19 | ... | ... | ... | ...

There are 74 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Gaming Companies. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Gaming Companies. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/adfs/ls` | Medium
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/index2.html` | High
5 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
6 | File | `/api/upload.php` | High
7 | File | `/baseOpLog.do` | High
8 | File | `/bitrix/admin/ldap_server_edit.php` | High
9 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
10 | File | `/cgi-bin/api-get_line_status` | High
11 | File | `/cgi-bin/wapopen` | High
12 | File | `/config/getuser` | High
13 | File | `/controller/OnlinePreviewController.java` | High
14 | File | `/export` | Low
15 | File | `/getcfg.php` | Medium
16 | File | `/includes/rrdtool.inc.php` | High
17 | File | `/mifs/c/i/reg/reg.html` | High
18 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
19 | File | `/pages/systemcall.php?command={COMMAND}` | High
20 | File | `/server-info` | Medium
21 | ... | ... | ...

There are 172 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.blackberry.com/en/2016/10/digitally-signed-malware-targeting-gaming-companies

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
