# BlueHero - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlueHero](https://vuldb.com/?actor.bluehero). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bluehero](https://vuldb.com/?actor.bluehero)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlueHero:

* [IN](https://vuldb.com/?country.in)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlueHero.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.5.10.1](https://vuldb.com/?ip.2.5.10.1) | - | - | High
2 | [10.3.6.0](https://vuldb.com/?ip.10.3.6.0) | - | - | High
3 | [12.1.3.0](https://vuldb.com/?ip.12.1.3.0) | - | - | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlueHero_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlueHero. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/.vnc/sesman_${username}_passwd` | High
3 | File | `/?page=reports` | High
4 | File | `/academic-calendar` | High
5 | File | `/add-company.php` | High
6 | File | `/add-customer.php` | High
7 | File | `/add-notes.php` | High
8 | File | `/add-pig.php` | Medium
9 | File | `/admin/` | Low
10 | File | `/admin/?page=inventory/view_inventory&id=2` | High
11 | File | `/admin/add-category.php` | High
12 | File | `/admin/add_ikev2.php` | High
13 | File | `/admin/admin-profile.php` | High
14 | File | `/admin/ajax.php?action=login` | High
15 | File | `/admin/ajax.php?action=save_settings` | High
16 | File | `/admin/communitymanagement.php` | High
17 | File | `/admin/contactus.php` | High
18 | File | `/admin/delete_account.php` | High
19 | File | `/admin/edit-artist-detail.php?editid=1` | High
20 | File | `/admin/edit-category.php` | High
21 | File | `/admin/edit-subadmin.php` | High
22 | File | `/admin/edit-subcategory.php` | High
23 | File | `/admin/emp-profile-avatar.php` | High
24 | File | `/admin/goods/update` | High
25 | File | `/admin/index.php?page=categories` | High
26 | File | `/admin/index2.html` | High
27 | File | `/admin/login.php` | High
28 | File | `/Admin/login.php` | High
29 | File | `/admin/manage-pages.php` | High
30 | File | `/admin/manage_user.php` | High
31 | File | `/admin/menu_update.php` | High
32 | File | `/admin/modal_add_product.php` | High
33 | File | `/admin/project/update/2` | High
34 | File | `/admin/students/manage.php` | High
35 | File | `/admin/success_story.php` | High
36 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
37 | File | `/api/files/recipepictures/` | High
38 | File | `/api/upload` | Medium
39 | File | `/api/v1/settings` | High
40 | File | `/api/v2/categories` | High
41 | File | `/api/v2/cli/commands` | High
42 | File | `/api/wizard/getBasicInfo` | High
43 | File | `/api/wizard/getCapability` | High
44 | File | `/app/fax/fax_view.php` | High
45 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
46 | File | `/app/xml_cdr/xml_cdr_details.php` | High
47 | File | `/auth_files/photo/` | High
48 | File | `/billaction.php` | High
49 | File | `/binutils/debug.c` | High
50 | File | `/boafrm/formMultiAP` | High
51 | File | `/boafrm/formStats` | High
52 | File | `/boafrm/formWlanRedirect` | High
53 | File | `/bwdates-reports-details.php` | High
54 | File | `/cgi-bin/Config.cgi?action=set` | High
55 | File | `/cgi-bin/cstecgi.cgi` | High
56 | File | `/cgi-bin/nas_sharing.cgi` | High
57 | File | `/changeUsername.php` | High
58 | File | `/chat/group/send` | High
59 | File | `/class/edit/edit` | High
60 | File | `/classes/Master.php` | High
61 | ... | ... | ...

There are 532 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://s.tencent.com/research/report/675
* https://www.zscaler.com/blogs/research/recent-bulehero-botnet-payload

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
