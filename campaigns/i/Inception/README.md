# Inception - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Inception_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Inception:

* [FR](https://vuldb.com/?country.fr)
* [PT](https://vuldb.com/?country.pt)
* [DE](https://vuldb.com/?country.de)
* ...

There are 8 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/wirelessConnect` | High
2 | File | `/admin.php?p=/Area/index#tab=t2` | High
3 | File | `/admin/` | Low
4 | File | `/admin/?page=bike` | High
5 | File | `/admin/?page=user/manage_user` | High
6 | File | `/admin/action/new-feed.php` | High
7 | File | `/admin/app/service_crud.php` | High
8 | File | `/admin/cms_content.php` | High
9 | File | `/admin/course.php` | High
10 | File | `/admin/edit-services.php` | High
11 | File | `/admin/edit_product.php` | High
12 | File | `/admin/index.php` | High
13 | File | `/admin/index.php?act=reset_admin_psw` | High
14 | File | `/admin/ind_backstage.php` | High
15 | File | `/admin/options-theme.php` | High
16 | File | `/admin/orders/update_status.php` | High
17 | File | `/admin/pages/sections_save.php` | High
18 | File | `/admin/php/crud.php` | High
19 | File | `/admin/positions_row.php` | High
20 | File | `/admin/userprofile.php` | High
21 | File | `/admin_route/inc_service_credits.php` | High
22 | File | `/adplanet/PlanetCommentList` | High
23 | File | `/ajax.php?action=save_company` | High
24 | File | `/ample/app/action/edit_product.php` | High
25 | File | `/api/es/admin/v3/security/user/1` | High
26 | File | `/api/v2/cli/commands` | High
27 | File | `/api/v2/open/rowsInfo` | High
28 | File | `/api/v3/flows/instances/default-user-settings-flow/execute/` | High
29 | File | `/api/wechat/app_auth` | High
30 | File | `/application/index/controller/File.php` | High
31 | File | `/asms/admin/?page=user/manage_user` | High
32 | File | `/att_add.php` | Medium
33 | File | `/blog/comment` | High
34 | File | `/cgi-bin/cstecgi.cgi` | High
35 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
36 | File | `/classes/Login.php` | High
37 | File | `/config,admin.jsp` | High
38 | File | `/Content/Plugins/uploader/FileChoose.html?fileUrl=/Upload/File/Pics/&parent` | High
39 | File | `/course/filterRecords/` | High
40 | File | `/dosen/data` | Medium
41 | File | `/E-mobile/App/System/File/downfile.php` | High
42 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
43 | File | `/Employer/EditProfile.php` | High
44 | File | `/env` | Low
45 | File | `/etc/master.passwd` | High
46 | File | `/etc/os-release` | High
47 | File | `/ext/collect/find_text.do` | High
48 | File | `/file_manager/admin/save_user.php` | High
49 | File | `/front/search.php` | High
50 | File | `/garage/php_action/createBrand.php` | High
51 | File | `/goform/addressNat` | High
52 | File | `/goform/AdvSetWrlsafeset` | High
53 | File | `/goform/editFileName` | High
54 | File | `/goform/form2WizardStep54` | High
55 | ... | ... | ...

There are 484 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
