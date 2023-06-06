# Inception - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Inception_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Inception:

* [AR](https://vuldb.com/?country.ar)
* [FR](https://vuldb.com/?country.fr)
* [PT](https://vuldb.com/?country.pt)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Inception or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Inception](https://vuldb.com/?actor.inception) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Inception.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [51.255.139.194](https://vuldb.com/?ip.51.255.139.194) | ip194.ip-51-255-139.eu | [Inception](https://vuldb.com/?actor.inception) | High
2 | [82.221.100.55](https://vuldb.com/?ip.82.221.100.55) | web.a1yola.com | [Inception](https://vuldb.com/?actor.inception) | High
3 | [82.221.100.60](https://vuldb.com/?ip.82.221.100.60) | - | [Inception](https://vuldb.com/?actor.inception) | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/import_xml_file/` | High
2 | File | `/action/wirelessConnect` | High
3 | File | `/admin/?page=user/manage_user` | High
4 | File | `/admin/myaccount` | High
5 | File | `/admin/orders/update_status.php` | High
6 | File | `/admin/pages/sections_save.php` | High
7 | File | `/admin/positions_row.php` | High
8 | File | `/admin/settings/fields` | High
9 | File | `/admin/userprofile.php` | High
10 | File | `/ajax.php?action=save_company` | High
11 | File | `/api/v1/chat.getThreadsList` | High
12 | File | `/api/v2/cli/commands` | High
13 | File | `/api/v2/open/rowsInfo` | High
14 | File | `/api/v3/flows/instances/default-user-settings-flow/execute/` | High
15 | File | `/asms/admin/?page=user/manage_user` | High
16 | File | `/blog/comment` | High
17 | File | `/classes/Login.php` | High
18 | File | `/dosen/data` | Medium
19 | File | `/E-mobile/App/System/File/downfile.php` | High
20 | File | `/env` | Low
21 | File | `/etc/master.passwd` | High
22 | File | `/etc/os-release` | High
23 | File | `/file_manager/admin/save_user.php` | High
24 | File | `/front/search.php` | High
25 | File | `/garage/php_action/createBrand.php` | High
26 | File | `/goform/addressNat` | High
27 | File | `/goform/AdvSetWrlsafeset` | High
28 | File | `/goform/editFileName` | High
29 | File | `/goform/form2WizardStep54` | High
30 | File | `/goform/setSysAdm` | High
31 | File | `/goform/webExcptypemanFilter` | High
32 | File | `/goform/WifiBasicSet` | High
33 | File | `/goform/WifiMacFilterGet` | High
34 | File | `/hss/admin/categories/view_category.php` | High
35 | File | `/isomedia/meta.c` | High
36 | File | `/jurusanmatkul/data` | High
37 | File | `/mods/_core/courses/users/create_course.php` | High
38 | File | `/module/report_event/index.php` | High
39 | File | `/Redcock-Farm/farm/category.php` | High
40 | ... | ... | ...

There are 347 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/interception
* https://research.checkpoint.com/2022/cloud-atlas-targets-entities-in-russia-and-belarus-amid-the-ongoing-war-in-ukraine/
* https://securelist.com/recent-cloud-atlas-activity/92016/
* https://unit42.paloaltonetworks.com/unit42-inception-attackers-target-europe-year-old-office-vulnerability/
* https://www.threatminer.org/report.php?q=bcs_wp_InceptionReport_EN_v12914.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
