# Fortinet - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Fortinet_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortinet:

* [US](https://vuldb.com/?country.us)
* [TR](https://vuldb.com/?country.tr)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 18 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Fortinet or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fortinet.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [20.207.197.237](https://vuldb.com/?ip.20.207.197.237) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [23.120.100.230](https://vuldb.com/?ip.23.120.100.230) | 23-120-100-230.lightspeed.tukrga.sbcglobal.net | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [31.206.51.194](https://vuldb.com/?ip.31.206.51.194) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fortinet. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-41, CWE-44, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortinet. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/upload/serverDownload` | High
2 | File | `/admin/auth/men` | High
3 | File | `/admin/index2.html` | High
4 | File | `/admin/login.php` | High
5 | File | `/admin/menu_save.php` | High
6 | File | `/admin/scripts/pi-hole/phpqueryads.php` | High
7 | File | `/admin/user.php` | High
8 | File | `/admin/yesterday-reg-users.php` | High
9 | File | `/api/v1/challenges//solves` | High
10 | File | `/api/v1/vhosts/vid-` | High
11 | File | `/apply.cgi` | Medium
12 | File | `/boafrm/formMapDelDevice` | High
13 | File | `/cgi-bin/cstecgi.cgi` | High
14 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
15 | File | `/cgi-bin/JSONAPI` | High
16 | File | `/cgi-bin/portal` | High
17 | File | `/cgi-bin/wlogin.cgi` | High
18 | File | `/classes/Users.php?f=save` | High
19 | File | `/debug/pprof` | Medium
20 | File | `/DXR.axd` | Medium
21 | File | `/etc/shadow` | Medium
22 | File | `/expense-monthwise-reports-detailed.php` | High
23 | File | `/fastcms.html#/template/menu` | High
24 | File | `/fort/portal_login` | High
25 | File | `/gbo.aspx` | Medium
26 | ... | ... | ...

There are 222 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://arcticwolf.com/resources/blog/arctic-wolf-observes-malicious-configuration-changes-fortinet-fortigate-devices-via-sso-accounts/
* https://doublepulsar.com/burning-zero-days-fortijump-fortimanager-vulnerability-used-by-nation-state-in-espionage-via-msps-c79abec59773
* https://www.bleepingcomputer.com/news/security/spike-in-fortinet-vpn-brute-force-attacks-raises-zero-day-concerns/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
