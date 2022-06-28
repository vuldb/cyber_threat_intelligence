# Wilted Tulip - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Wilted Tulip_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wilted Tulip:

* [ES](https://vuldb.com/?country.es)
* [PT](https://vuldb.com/?country.pt)
* [SV](https://vuldb.com/?country.sv)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Wilted Tulip or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [CopyKittens](https://vuldb.com/?actor.copykittens) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wilted Tulip.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.34.180.252](https://vuldb.com/?ip.5.34.180.252) | vds-uuallex-113169.hosted-by-itldc.com | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
2 | [5.34.181.13](https://vuldb.com/?ip.5.34.181.13) | backups231.com | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
3 | [31.192.105.16](https://vuldb.com/?ip.31.192.105.16) | down-it-niscat.cosmeticdentistwellesley.com | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
4 | [31.192.105.17](https://vuldb.com/?ip.31.192.105.17) | - | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
5 | [31.192.105.28](https://vuldb.com/?ip.31.192.105.28) | - | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
6 | [38.130.75.20](https://vuldb.com/?ip.38.130.75.20) | h20-us75.fcsrv.net | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
7 | [51.254.76.54](https://vuldb.com/?ip.51.254.76.54) | - | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
8 | [62.109.2.52](https://vuldb.com/?ip.62.109.2.52) | ns.leangroup.ru | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
9 | [66.55.152.164](https://vuldb.com/?ip.66.55.152.164) | 66-55-152-164.choopa.net | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
10 | [68.232.180.122](https://vuldb.com/?ip.68.232.180.122) | 68-232-180-122.choopa.net | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
11 | [80.179.42.37](https://vuldb.com/?ip.80.179.42.37) | 80.179.42.37.forward.012.net.il | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
12 | [93.190.138.137](https://vuldb.com/?ip.93.190.138.137) | 93-190-138-137.hosted-by-worldstream.net | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
13 | [104.200.128.48](https://vuldb.com/?ip.104.200.128.48) | - | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
14 | [104.200.128.58](https://vuldb.com/?ip.104.200.128.58) | - | [CopyKittens](https://vuldb.com/?actor.copykittens) | High
15 | ... | ... | ... | ...

There are 57 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Wilted Tulip. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-250, CWE-264, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Wilted Tulip. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?module=fileman&section=get&page=grid` | High
2 | File | `/admin.php/singer/admin/singer/hy` | High
3 | File | `/admin.php/vod/admin/topic/del` | High
4 | File | `/admin/deluser.php` | High
5 | File | `/admin/edit.php` | High
6 | File | `/admin/googleads.php` | High
7 | File | `/admin/new-content` | High
8 | File | `/admin/operations/tax.php` | High
9 | File | `/admin/payment.php` | High
10 | File | `/admin/scheprofile.cgi` | High
11 | File | `/admin/weixin.php` | High
12 | File | `/apps/acs-commons/content/page-compare.html` | High
13 | File | `/base/SysEveMenuAuthPointMapper.xml` | High
14 | File | `/bcms/admin/courts/manage_court.php` | High
15 | File | `/bcms/classes/Master.php?f=save_court_rental` | High
16 | File | `/car-rental-management-system/admin/manage_booking.php` | High
17 | File | `/cgi-bin/kerbynet` | High
18 | File | `/classes/Users.php?f=save` | High
19 | File | `/cms/classes/Master.php?f=delete_client` | High
20 | File | `/config` | Low
21 | File | `/defaultui/player/modern.html` | High
22 | File | `/ffos/admin/categories/manage_category.php` | High
23 | File | `/ffos/admin/menus/view_menu.php` | High
24 | File | `/gaia-job-admin/user/add` | High
25 | File | `/goform/aspForm` | High
26 | File | `/goform/login_process` | High
27 | File | `/goform/setNetworkLan` | High
28 | File | `/goform/SetSysTimeCfg` | High
29 | File | `/html/Solar_Ftp.php` | High
30 | File | `/lists/admin/` | High
31 | File | `/mngset/authset` | High
32 | File | `/mtms/admin/?page=transaction/send` | High
33 | File | `/orrs/admin/trains/manage_train.php` | High
34 | File | `/otps/classes/Master.php?f=delete_team` | High
35 | ... | ... | ...

There are 298 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.clearskysec.com/wp-content/uploads/2017/07/Operation_Wilted_Tulip.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
