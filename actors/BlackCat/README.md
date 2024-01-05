# BlackCat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlackCat](https://vuldb.com/?actor.blackcat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.blackcat](https://vuldb.com/?actor.blackcat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackCat:

* [US](https://vuldb.com/?country.us)
* [SV](https://vuldb.com/?country.sv)
* [DE](https://vuldb.com/?country.de)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackCat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [20.46.245.56](https://vuldb.com/?ip.20.46.245.56) | - | - | High
2 | [23.106.223.97](https://vuldb.com/?ip.23.106.223.97) | - | - | High
3 | [37.120.238.58](https://vuldb.com/?ip.37.120.238.58) | - | - | High
4 | [45.134.20.66](https://vuldb.com/?ip.45.134.20.66) | - | - | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlackCat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-29 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackCat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `.tin` | Low
3 | File | `/acms/admin/cargo_types/manage_cargo_type.php` | High
4 | File | `/admin/ajax.php?action=confirm_order` | High
5 | File | `/admin/ajax.php?action=delete_user` | High
6 | File | `/admin/ajax.php?action=delete_window` | High
7 | File | `/admin/ajax/avatar.php` | High
8 | File | `/admin/article/article-add.php` | High
9 | File | `/admin/edit_members.php` | High
10 | File | `/admin/edit_subject.php` | High
11 | File | `/admin/fst_upload.inc.php` | High
12 | File | `/admin/index.php` | High
13 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
14 | File | `/admin/list_onlineuser.php` | High
15 | File | `/admin/login.php` | High
16 | File | `/admin/options` | High
17 | File | `/admin/report/index.php` | High
18 | File | `/admin/services/manage_service.php` | High
19 | File | `/admin/settings/` | High
20 | File | `/admin/show.php` | High
21 | File | `/admin/students/update_status.php` | High
22 | File | `/admin/subject.php` | High
23 | File | `/admin/user/manage_user.php` | High
24 | File | `/admin/users/index.php` | High
25 | File | `/ample/app/ajax/member_data.php` | High
26 | File | `/article/DelectArticleById/` | High
27 | File | `/asms/classes/Master.php?f=delete_service` | High
28 | File | `/auth/auth.php?user=1` | High
29 | File | `/b2b-supermarket/shopping-cart` | High
30 | File | `/blog` | Low
31 | File | `/bsms_ci/index.php/user/edit_user/` | High
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
34 | File | `/classes/Master.php?f=delete_category` | High
35 | File | `/classes/Master.php?f=delete_inquiry` | High
36 | File | `/classes/Master.php?f=save_reminder` | High
37 | File | `/classes/Users.php?f=delete_client` | High
38 | File | `/clients/listclients.php` | High
39 | File | `/clients/profile` | High
40 | File | `/cms/category/list` | High
41 | File | `/collection/all` | High
42 | File | `/company/store` | High
43 | File | `/contacts/listcontacts.php` | High
44 | File | `/Default/Bd` | Medium
45 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
46 | File | `/ext/phar/phar_object.c` | High
47 | File | `/file-manager/upload.php` | High
48 | File | `/forum/away.php` | High
49 | File | `/fos/admin/index.php?page=menu` | High
50 | File | `/friends` | Medium
51 | File | `/goform/AddSysLogRule` | High
52 | File | `/goform/SafeEmailFilter` | High
53 | File | `/goform/SetIpMacBind` | High
54 | File | `/goform/setSnmpInfo` | High
55 | File | `/goform/setUplinkInfo` | High
56 | File | `/goform/SysToolReboot` | High
57 | File | `/goform/WifiBasicSet` | High
58 | File | `/graphql` | Medium
59 | File | `/home/get_tasks_list` | High
60 | File | `/hrm/employeeview.php` | High
61 | ... | ... | ...

There are 536 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/03/from-blackmatter-to-blackcat-analyzing.html
* https://threatfox.abuse.ch
* https://www.ic3.gov/Media/News/2022/220420.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
