# Cisco ASA SSL VPN - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cisco ASA SSL VPN_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cisco ASA SSL VPN:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [TR](https://vuldb.com/?country.tr)
* ...

There are 25 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cisco ASA SSL VPN or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cisco ASA SSL VPN.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.61.43.231](https://vuldb.com/?ip.5.61.43.231) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [5.183.253.129](https://vuldb.com/?ip.5.183.253.129) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [31.184.236.63](https://vuldb.com/?ip.31.184.236.63) | zemal.kiprises.net | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [31.184.236.71](https://vuldb.com/?ip.31.184.236.71) | miseria.independentbookstores.net | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | [31.184.236.79](https://vuldb.com/?ip.31.184.236.79) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
6 | [45.66.209.122](https://vuldb.com/?ip.45.66.209.122) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
7 | [45.80.107.220](https://vuldb.com/?ip.45.80.107.220) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
8 | [45.227.252.237](https://vuldb.com/?ip.45.227.252.237) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
9 | [45.227.255.51](https://vuldb.com/?ip.45.227.255.51) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
10 | [46.161.27.123](https://vuldb.com/?ip.46.161.27.123) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
11 | [62.233.50.11](https://vuldb.com/?ip.62.233.50.11) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
12 | [62.233.50.13](https://vuldb.com/?ip.62.233.50.13) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
13 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cisco ASA SSL VPN. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-270, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cisco ASA SSL VPN. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#ProductSerie/view/` | High
2 | File | `/.pomerium` | Medium
3 | File | `/Account/login.php` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=bike` | High
6 | File | `/admin/?page=musics/manage_music` | High
7 | File | `/admin/ajax.php?action=delete_user` | High
8 | File | `/admin/apply.php` | High
9 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/complex_header_2.php` | High
10 | File | `/admin/book-details.php` | High
11 | File | `/admin/bwdates-report-details.php` | High
12 | File | `/admin/change-image.php` | High
13 | File | `/Admin/changepassword.php` | High
14 | File | `/admin/cmsVote/save` | High
15 | File | `/admin/cms_content.php` | High
16 | File | `/admin/emp-profile-avatar.php` | High
17 | File | `/admin/forms/option_lists/edit.php` | High
18 | File | `/admin/general-setting` | High
19 | File | `/admin/inquiries/view_inquiry.php` | High
20 | File | `/admin/operations/expense_category.php` | High
21 | File | `/admin/order.php` | High
22 | File | `/admin/orders/view_order.php` | High
23 | File | `/admin/product/manage_product.php` | High
24 | File | `/admin/projects/{projectname}/skills/{skillname}/video` | High
25 | File | `/admin/service` | High
26 | File | `/admin/sou.php` | High
27 | File | `/admin/users.php` | High
28 | File | `/adminapi/system/crud` | High
29 | File | `/adminapi/system/file/openfile` | High
30 | File | `/api/v1/custom_component` | High
31 | File | `/api/wechat/app_auth` | High
32 | File | `/backend/admin/his_admin_add_vendor.php` | High
33 | File | `/backend/admin/his_admin_register_patient.php` | High
34 | File | `/cancel.php` | Medium
35 | File | `/car-rental-management-system/admin/index.php?page=manage_car` | High
36 | File | `/category.php` | High
37 | File | `/cgi-bin/cstecgi.cgi` | High
38 | File | `/cgi-bin/discovery.cgi` | High
39 | File | `/cgi-bin/nas_sharing.cgi` | High
40 | File | `/cgi-bin/widget_api.cgi` | High
41 | File | `/classes/Master.php` | High
42 | File | `/classes/Master.php?f=delete_category` | High
43 | File | `/classes/Master.php?f=save_medicine` | High
44 | File | `/classes/SystemSettings.php?f=update_settings` | High
45 | File | `/classes/Users.php?f=delete` | High
46 | File | `/control/register_case.php` | High
47 | File | `/dataSet/resolveSql` | High
48 | File | `/download` | Medium
49 | File | `/downloadFile.php` | High
50 | File | `/dtale/chart-data/1` | High
51 | File | `/DXR.axd` | Medium
52 | File | `/editar-cliente.php` | High
53 | File | `/editar-produto.php` | High
54 | File | `/endpoint/add-folder.php` | High
55 | File | `/endpoint/add-task.php` | High
56 | File | `/etc/shadow` | Medium
57 | File | `/file/updateprofile.php` | High
58 | File | `/filemanager/upload` | High
59 | File | `/file_manager/login.php` | High
60 | ... | ... | ...

There are 523 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.rapid7.com/blog/post/2023/08/29/under-siege-rapid7-observed-exploitation-of-cisco-asa-ssl-vpns/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
