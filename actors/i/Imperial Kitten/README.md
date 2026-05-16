# Imperial Kitten - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Imperial Kitten](https://vuldb.com/?actor.imperial_kitten). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.imperial_kitten](https://vuldb.com/?actor.imperial_kitten)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Imperial Kitten:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Imperial Kitten.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [37.120.233.84](https://vuldb.com/?ip.37.120.233.84) | no-rdns.m247.com | - | High
2 | [45.8.146.37](https://vuldb.com/?ip.45.8.146.37) | vm1396047.stark-industries.solutions | - | High
3 | [45.32.181.118](https://vuldb.com/?ip.45.32.181.118) | 45.32.181.118.vultrusercontent.com | - | Medium
4 | [45.81.226.38](https://vuldb.com/?ip.45.81.226.38) | vm4336982.25ssd.had.wf | - | High
5 | [45.93.82.109](https://vuldb.com/?ip.45.93.82.109) | - | - | High
6 | [45.93.93.198](https://vuldb.com/?ip.45.93.93.198) | - | - | High
7 | [45.155.37.105](https://vuldb.com/?ip.45.155.37.105) | - | - | High
8 | [45.155.37.140](https://vuldb.com/?ip.45.155.37.140) | - | - | High
9 | [51.81.165.110](https://vuldb.com/?ip.51.81.165.110) | ip110.ip-51-81-165.us | - | High
10 | [64.176.164.117](https://vuldb.com/?ip.64.176.164.117) | 64.176.164.117.vultrusercontent.com | - | Medium
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Imperial Kitten_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Imperial Kitten. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=tracks` | High
2 | File | `/academy/tutor/filter` | High
3 | File | `/add_user.php` | High
4 | File | `/admin.php` | Medium
5 | File | `/admin/` | Low
6 | File | `/admin/?page=system_info/contact_info` | High
7 | File | `/admin/sales-reports-detail.php` | High
8 | File | `/admin/search-appointment.php` | High
9 | File | `/amssplus/modules/book/main/bookdetail_school_person.php` | High
10 | File | `/app/options.py` | High
11 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
12 | File | `/auth_files/photo/` | High
13 | File | `/BalloonSave.ashx` | High
14 | File | `/boafrm/formRoute` | High
15 | File | `/card_scan.php` | High
16 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
17 | File | `/cgi-bin/mesh.cgi?page=upgrade` | High
18 | File | `/cgi-bin/touchlist_sync.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/checklogin.php` | High
21 | File | `/classes/master.php?f=delete_order` | High
22 | File | `/classes/SystemSettings.php?f=update_settings` | High
23 | File | `/cms/users/complaint-details.php` | High
24 | File | `/controller/api/Room.php` | High
25 | File | `/cwc/login` | Medium
26 | File | `/dashboard.php` | High
27 | File | `/dayrui/Fcms/Init.php` | High
28 | File | `/debuginfo.htm` | High
29 | File | `/dev-api/common/upload` | High
30 | File | `/dialog/select_media.php` | High
31 | File | `/endpoint/update.php` | High
32 | File | `/etc/passwd` | Medium
33 | File | `/etc/quagga` | Medium
34 | File | `/forms/doLogin` | High
35 | File | `/goform/formPPPoESetup` | High
36 | File | `/goform/SetVirtualServerCfg` | High
37 | File | `/goform/VerAPIMant` | High
38 | File | `/goform/WifiExtraSet` | High
39 | File | `/goform/wirelessAdvancedHidden` | High
40 | File | `/h/autoSaveDraft` | High
41 | File | `/h/calendar` | Medium
42 | File | `/HNAP1/` | Low
43 | File | `/includes/article_detail.php` | High
44 | File | `/includes/header_menu.php` | High
45 | ... | ... | ...

There are 386 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://aws.amazon.com/blogs/security/new-amazon-threat-intelligence-findings-nation-state-actors-bridging-cyber-and-kinetic-warfare/
* https://www.crowdstrike.com/blog/imperial-kitten-deploys-novel-malware-families/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
