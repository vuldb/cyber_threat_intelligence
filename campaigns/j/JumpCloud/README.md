# JumpCloud - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _JumpCloud_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with JumpCloud:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with JumpCloud or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DPRK](https://vuldb.com/?actor.dprk) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of JumpCloud.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.29.115.171](https://vuldb.com/?ip.23.29.115.171) | 23-29-115-171.static.hvvc.us | [DPRK](https://vuldb.com/?actor.dprk) | High
2 | [23.95.182.5](https://vuldb.com/?ip.23.95.182.5) | 23-95-182-5-host.colocrossing.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.82.250.186](https://vuldb.com/?ip.45.82.250.186) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [51.254.24.19](https://vuldb.com/?ip.51.254.24.19) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abcd/opac/php/otros_sitios.php` | High
2 | File | `/Account/login.php` | High
3 | File | `/add-students.php` | High
4 | File | `/addcategory.php` | High
5 | File | `/addproduct.php` | High
6 | File | `/admin/?page=musics/manage_music` | High
7 | File | `/admin/ajax.php?action=login` | High
8 | File | `/admin/categories/manage_category.php` | High
9 | File | `/admin/config_time_sync.php` | High
10 | File | `/admin/edit-post.php` | High
11 | File | `/admin/edit_supplier.php` | High
12 | File | `/admin/emp-profile-avatar.php` | High
13 | File | `/admin/forgot-password.php` | High
14 | File | `/admin/index.php` | High
15 | File | `/admin/index.php?page=manage_product` | High
16 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
17 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
18 | File | `/admin/index.php?r=user%2Fcreate` | High
19 | File | `/admin/login.php` | High
20 | File | `/Admin/login.php` | High
21 | File | `/admin/modules/product/controller.php?action=add` | High
22 | File | `/admin/mod_room/controller.php?action=add` | High
23 | File | `/Admin/registration.php` | High
24 | File | `/admin/role` | Medium
25 | File | `/admin/system.html` | High
26 | File | `/adminPage/conf/saveCmd` | High
27 | File | `/admin_class.php` | High
28 | File | `/ajax.php?action=delete_deductions` | High
29 | File | `/ajax.php?action=login` | High
30 | File | `/ajax/checkin.php` | High
31 | File | `/ajax/get_patient_history.php` | High
32 | File | `/api/v2/maps` | Medium
33 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
34 | File | `/applications/nexus/modules/front/store/store.php` | High
35 | File | `/apply.cgi` | Medium
36 | File | `/assoc_table.php` | High
37 | File | `/authMonitCallcenter` | High
38 | File | `/boaform/getASPdata/formFirewall` | High
39 | File | `/cgi-bin/apkg_mgr.cgi` | High
40 | File | `/cgi-bin/cstecgi.cgi` | High
41 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
42 | File | `/cgi-bin/hd_config.cgi` | High
43 | File | `/cgi-bin/myMusic.cgi` | High
44 | File | `/cgi-bin/photocenter_mgr.cgi` | High
45 | File | `/classes/Master.php` | High
46 | File | `/classes/Master.php?f=delete_category` | High
47 | File | `/classes/Master.php?f=delete_record` | High
48 | File | `/classes/Master.php?f=log_employee` | High
49 | File | `/classes/SystemSettings.php?f=update_settings` | High
50 | File | `/classes/Users.php?f=save` | High
51 | File | `/command_port.ini` | High
52 | File | `/common/show_image.php` | High
53 | File | `/diag_s.php` | Medium
54 | File | `/dtale/chart-data/1` | High
55 | File | `/E-Insurance/` | High
56 | File | `/edit-computer-detail.php` | High
57 | File | `/employee_gatepass/admin/?page=employee/manage_employee` | High
58 | File | `/employee_gatepass/classes/Master.php?f=delete_department` | High
59 | File | `/endpoint/add-folder.php` | High
60 | File | `/endpoint/delete-account.php` | High
61 | File | `/etc/shadow.sample` | High
62 | File | `/export` | Low
63 | File | `/fftools/ffmpeg_enc.c` | High
64 | File | `/forget.php` | Medium
65 | File | `/formSysLog` | Medium
66 | File | `/goform/AddDnsForward` | High
67 | File | `/goform/addIpMacBind` | High
68 | File | `/goform/addressNat` | High
69 | File | `/goform/AdvSetMacMtuWan` | High
70 | File | `/goform/apPortalAccessCodeAuth` | High
71 | File | `/goform/apPortalAuth` | High
72 | File | `/goform/apPortalOneKeyAuth` | High
73 | File | `/goform/apPortalPhoneAuth` | High
74 | File | `/goform/DelDhcpRule` | High
75 | File | `/goform/delIpMacBind` | High
76 | File | `/goform/DelPortMapping` | High
77 | File | `/goform/DhcpListClient` | High
78 | File | `/goform/DhcpSetSe` | High
79 | File | `/goform/DhcpSetSer` | High
80 | File | `/goform/execCommand` | High
81 | File | `/goform/frmL7ProtForm` | High
82 | File | `/goform/fromqossetting` | High
83 | File | `/goform/fromRouteStatic` | High
84 | ... | ... | ...

There are 743 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://jumpcloud.com/support/july-2023-iocs

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
