# LLMHijacking - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _LLMHijacking_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LLMHijacking:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 28 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with LLMHijacking or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LLMHijacking.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.223.72.184](https://vuldb.com/?ip.3.223.72.184) | ec2-3-223-72-184.compute-1.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
2 | [31.171.154.59](https://vuldb.com/?ip.31.171.154.59) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [34.211.200.85](https://vuldb.com/?ip.34.211.200.85) | ec2-34-211-200-85.us-west-2.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
4 | [44.227.217.144](https://vuldb.com/?ip.44.227.217.144) | ec2-44-227-217-144.us-west-2.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
5 | [45.85.144.253](https://vuldb.com/?ip.45.85.144.253) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
6 | [45.87.213.230](https://vuldb.com/?ip.45.87.213.230) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
7 | [103.136.147.217](https://vuldb.com/?ip.103.136.147.217) | 103.136.147.217.static.po.net | [Unknown](https://vuldb.com/?actor.unknown) | High
8 | [103.136.147.219](https://vuldb.com/?ip.103.136.147.219) | 103.136.147.219.static.po.net | [Unknown](https://vuldb.com/?actor.unknown) | High
9 | [103.216.220.23](https://vuldb.com/?ip.103.216.220.23) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
10 | [103.216.220.43](https://vuldb.com/?ip.103.216.220.43) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
11 | ... | ... | ... | ...

There are 41 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within LLMHijacking. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-29, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-270, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LLMHijacking. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/.dbus-keyrings` | High
4 | File | `/?import` | Medium
5 | File | `/adaddmed.php` | High
6 | File | `/add-apartment.php` | High
7 | File | `/addproduct.php` | High
8 | File | `/add_reference_to_local_model` | High
9 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
10 | File | `/admin/aboutus.php` | High
11 | File | `/admin/add-services.php` | High
12 | File | `/admin/add_subject.php` | High
13 | File | `/admin/ajax.php?action=login` | High
14 | File | `/admin/ajax.php?action=save_settings` | High
15 | File | `/admin/cmsTemplate/savePlace` | High
16 | File | `/admin/config_ISCGroupNoCache.php` | High
17 | File | `/Admin/detail.php` | High
18 | File | `/admin/edit-guard-detail.php` | High
19 | File | `/admin/edit_subject.php` | High
20 | File | `/admin/emp-profile-avatar.php` | High
21 | File | `/admin/forms/option_lists/edit.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/index.php?page=manage_lot` | High
24 | File | `/admin/list_ipAddressPolicy.php` | High
25 | File | `/admin/manage-users.php` | High
26 | File | `/admin/network/diag_ping6` | High
27 | File | `/admin/pages/` | High
28 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
29 | File | `/admin/services/view_service.php` | High
30 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
31 | File | `/admin/userGroup_deal.php?mudi=add&nohrefStr=close` | High
32 | File | `/admin/user_save.php` | High
33 | File | `/ajax.php?action=delete_plan` | High
34 | File | `/api/admin/question/edit` | High
35 | File | `/api/admin/settings` | High
36 | File | `/api/admin/user` | High
37 | File | `/api/school/registerSchool` | High
38 | File | `/api/v1/admin/restart` | High
39 | File | `/api/v1/steps` | High
40 | File | `/application/index/controller/Screen.php` | High
41 | File | `/attendancelist.php` | High
42 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
43 | File | `/boafrm/formMapDel` | High
44 | File | `/cgi` | Low
45 | File | `/cgi-bin/cstecgi.cgi` | High
46 | File | `/classes/Master.php` | High
47 | File | `/classes/Master.php?f=delete_category` | High
48 | ... | ... | ...

There are 421 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://permiso.io/blog/exploiting-hosted-models

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
