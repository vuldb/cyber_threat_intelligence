# SonicWall VPN - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _SonicWall VPN_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with SonicWall VPN:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* ...

There are 12 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with SonicWall VPN or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Akira](https://vuldb.com/?actor.akira) | High
2 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of SonicWall VPN.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [42.252.99.59](https://vuldb.com/?ip.42.252.99.59) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [45.86.208.0](https://vuldb.com/?ip.45.86.208.0) | - | [Akira](https://vuldb.com/?actor.akira) | High
3 | [45.86.208.240](https://vuldb.com/?ip.45.86.208.240) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within SonicWall VPN. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during SonicWall VPN. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?module=users&section=cpanel&page=list` | High
2 | File | `/AcceptZip.ashx` | High
3 | File | `/admin/add-ambulance.php` | High
4 | File | `/admin/create_product.php` | High
5 | File | `/admin/emp-profile-avatar.php` | High
6 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
7 | File | `/ajax.php?action=delete_tenant` | High
8 | File | `/api/authentication/login` | High
9 | File | `/apiadmin/upload/attach` | High
10 | File | `/artist-display.php` | High
11 | File | `/backend/admin/his_admin_register_patient.php` | High
12 | File | `/billing/test_accesscodelogin.php` | High
13 | File | `/boafrm/formParentControl` | High
14 | File | `/cgi-bin/nas_sharing.cgi` | High
15 | File | `/cgi-bin/p1_ftpserver.php` | High
16 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
17 | File | `/cgi-bin/tosei_kikai.php` | High
18 | File | `/classes/Master.php` | High
19 | File | `/classes/profile.class.php` | High
20 | File | `/classes/SystemSettings.php?f=update_settings` | High
21 | File | `/conf/app.conf` | High
22 | File | `/control/register_case.php` | High
23 | File | `/edit/server` | Medium
24 | File | `/foms/routers/place-order.php` | High
25 | File | `/forum/away.php` | High
26 | File | `/freelist_main.php` | High
27 | File | `/goform/formSetPassword` | High
28 | File | `/h/autoSaveDraft` | High
29 | File | `/hoteldruid/clienti.php` | High
30 | File | `/include/menu_v.inc.php` | High
31 | File | `/include/Model/Upload.php` | High
32 | File | `/include/stat/stat.php` | High
33 | ... | ... | ...

There are 284 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.esentire.com/security-advisories/undisclosed-sonicwall-zero-day-leading-to-akira-ransomware
* https://www.huntress.com/blog/exploitation-of-sonicwall-vpn

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
