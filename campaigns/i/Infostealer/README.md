# Infostealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Infostealer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Infostealer:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 14 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Infostealer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Infostealer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.34.178.21](https://vuldb.com/?ip.5.34.178.21) | node240816.us | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
2 | [5.188.87.58](https://vuldb.com/?ip.5.188.87.58) | - | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
3 | [46.173.215.132](https://vuldb.com/?ip.46.173.215.132) | - | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | High
4 | [66.42.63.27](https://vuldb.com/?ip.66.42.63.27) | 66.42.63.27.vultrusercontent.com | [Vietnam Unknown](https://vuldb.com/?actor.vietnam_unknown) | Medium
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Infostealer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37, CWE-44, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Infostealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/addcustind.php` | High
2 | File | `/admin` | Low
3 | File | `/admin/add-category.php` | High
4 | File | `/admin/add-property.php` | High
5 | File | `/admin/admin_editor.php` | High
6 | File | `/admin/admin_widgets.php?action=remove/widget=Statistics` | High
7 | File | `/admin/ad_list.php?action=pass` | High
8 | File | `/admin/ajax.php?action=login` | High
9 | File | `/admin/booking-bwdates-reports-details.php` | High
10 | File | `/admin/create_product.php` | High
11 | File | `/admin/DatabaseQuery` | High
12 | File | `/admin/edit-admin.php` | High
13 | File | `/admin/extensions/upload.php` | High
14 | File | `/admin/forgot-password.php` | High
15 | File | `/admin/index.php` | High
16 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
17 | File | `/admin/index2.html` | High
18 | File | `/admin/options-theme.php` | High
19 | File | `/admin/request-received-bydonar.php` | High
20 | File | `/admin/salary_slip.php` | High
21 | File | `/admin/sales/index.php` | High
22 | File | `/adminPage/conf/reload` | High
23 | File | `/adms/admin/?page=vehicles/view_transaction` | High
24 | File | `/animalsadd.php` | High
25 | File | `/api/` | Low
26 | File | `/api/client/editemedia.php` | High
27 | File | `/api/Common/uploadFile` | High
28 | File | `/Api/FileUpload.ashx?method=DoUpload` | High
29 | File | `/api/runscript` | High
30 | File | `/api/snapshots/` | High
31 | File | `/api/v1/snapshots` | High
32 | File | `/api/v2/maps` | Medium
33 | File | `/api/wizard/setsyncpppoecfg` | High
34 | File | `/apply/index.php` | High
35 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
36 | File | `/candidate/index.php` | High
37 | File | `/cgi-bin/adm.cgi` | High
38 | File | `/cgi-bin/wlogin.cgi` | High
39 | File | `/classes/Master.php` | High
40 | File | `/classes/Master.php?f=log_employee` | High
41 | File | `/classes/SystemSettings.php?f=update_settings` | High
42 | File | `/classes/Users.php?f=delete` | High
43 | File | `/classes/Users.php?f=save` | High
44 | File | `/cms/category/list` | High
45 | File | `/cms/classes/Users.php?f=delete_client` | High
46 | File | `/confirmbooking.php` | High
47 | File | `/core/config-revisions` | High
48 | File | `/crmeb/crmeb/services/UploadService.php` | High
49 | File | `/Default/Bd` | Medium
50 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
51 | ... | ... | ...

There are 442 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://labs.withsecure.com/publications/darkgate-malware-campaign

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
