# Akira - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Akira_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Akira:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Akira or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [AdaptixC2](https://vuldb.com/?actor.adaptixc2) | High
2 | [Akira](https://vuldb.com/?actor.akira) | High
3 | [Bumblebee](https://vuldb.com/?actor.bumblebee) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Akira.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.94.54.125](https://vuldb.com/?ip.23.94.54.125) | storage.mak.com.br | [Akira](https://vuldb.com/?actor.akira) | High
2 | [23.227.162.18](https://vuldb.com/?ip.23.227.162.18) | 23-227-162-18.static.hvvc.us | [Akira](https://vuldb.com/?actor.akira) | High
3 | [31.222.247.64](https://vuldb.com/?ip.31.222.247.64) | - | [Akira](https://vuldb.com/?actor.akira) | High
4 | [38.114.123.167](https://vuldb.com/?ip.38.114.123.167) | 167-123-114-38.clients.gthost.com | [Akira](https://vuldb.com/?actor.akira) | High
5 | [38.114.123.229](https://vuldb.com/?ip.38.114.123.229) | 229-123-114-38.clients.gthost.com | [Akira](https://vuldb.com/?actor.akira) | High
6 | [42.252.99.59](https://vuldb.com/?ip.42.252.99.59) | - | [Akira](https://vuldb.com/?actor.akira) | High
7 | [45.11.59.16](https://vuldb.com/?ip.45.11.59.16) | dedicated.sollutium.com | [Akira](https://vuldb.com/?actor.akira) | High
8 | [45.55.76.210](https://vuldb.com/?ip.45.55.76.210) | - | [Akira](https://vuldb.com/?actor.akira) | High
9 | [45.56.163.58](https://vuldb.com/?ip.45.56.163.58) | 45.56.163.58.static.quadranet.com | [Akira](https://vuldb.com/?actor.akira) | High
10 | [45.66.249.93](https://vuldb.com/?ip.45.66.249.93) | - | [Akira](https://vuldb.com/?actor.akira) | High
11 | [45.86.208.0](https://vuldb.com/?ip.45.86.208.0) | - | [Akira](https://vuldb.com/?actor.akira) | High
12 | [45.86.208.146](https://vuldb.com/?ip.45.86.208.146) | - | [Akira](https://vuldb.com/?actor.akira) | High
13 | [45.86.208.240](https://vuldb.com/?ip.45.86.208.240) | - | [Akira](https://vuldb.com/?actor.akira) | High
14 | [45.227.254.26](https://vuldb.com/?ip.45.227.254.26) | - | [Akira](https://vuldb.com/?actor.akira) | High
15 | [45.242.96.0](https://vuldb.com/?ip.45.242.96.0) | - | [Akira](https://vuldb.com/?actor.akira) | High
16 | [57.128.101.78](https://vuldb.com/?ip.57.128.101.78) | relay-46094b16.net.anydesk.com | [Akira](https://vuldb.com/?actor.akira) | High
17 | ... | ... | ... | ...

There are 64 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Akira. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Akira. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/?module=users&section=cpanel&page=list` | High
3 | File | `/AcceptZip.ashx` | High
4 | File | `/add_employee.php` | High
5 | File | `/admin/aboutus.php` | High
6 | File | `/admin/add-ambulance.php` | High
7 | File | `/admin/ajax.php?action=confirm_order` | High
8 | File | `/admin/client_user` | High
9 | File | `/admin/config_time_sync.php` | High
10 | File | `/admin/create_product.php` | High
11 | File | `/admin/deleteuser.php` | High
12 | File | `/admin/edit-admin.php` | High
13 | File | `/admin/edit-ambulance.php` | High
14 | File | `/admin/edit.php` | High
15 | File | `/admin/edit_supplier.php` | High
16 | File | `/admin/emp-profile-avatar.php` | High
17 | File | `/admin/index.php?n=system&c=filept&a=doGetFileList` | High
18 | File | `/admin/inventory/manage_stock.php` | High
19 | File | `/admin/ipAddPost.php` | High
20 | File | `/admin/login.php` | High
21 | File | `/admin/orders/update_status.php` | High
22 | File | `/admin/positions_add.php` | High
23 | File | `/admin/process_category_edit.php` | High
24 | File | `/Admin/resultdetails.php` | High
25 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
26 | File | `/adminapi/system/crud` | High
27 | File | `/administrator/bidlist.php` | High
28 | File | `/ajax.php?action=delete_tenant` | High
29 | File | `/ajax.php?action=save_deductions` | High
30 | File | `/api/authentication/login` | High
31 | File | `/api/wizard/getDualbandSync` | High
32 | File | `/apiadmin/upload/attach` | High
33 | File | `/app/system/column/admin/index.class.php` | High
34 | File | `/application/pay/controller/Index.php` | High
35 | File | `/appy.cgi` | Medium
36 | File | `/artist-display.php` | High
37 | File | `/backend/admin/his_admin_register_patient.php` | High
38 | File | `/boafrm/formParentControl` | High
39 | File | `/boafrm/formReflashClientTbl` | High
40 | File | `/boafrm/formWlanMultipleAP` | High
41 | File | `/boat/login.php` | High
42 | File | `/cancelar-enturmacao-em-lote/` | High
43 | File | `/cas/logout` | Medium
44 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
45 | File | `/cgi-bin/hd_config.cgi` | High
46 | File | `/cgi-bin/nas_sharing.cgi` | High
47 | File | `/cgi-bin/p1_ftpserver.php` | High
48 | File | `/cgi-bin/tosei_kikai.php` | High
49 | File | `/cgi-bin/wlogin.cgi` | High
50 | File | `/classes/Master.php` | High
51 | File | `/classes/Master.php?f=delete_category` | High
52 | File | `/classes/profile.class.php` | High
53 | File | `/classes/SystemSettings.php?f=update_settings` | High
54 | File | `/com/ruoyi/common/utils/sql/SqlUtil.java` | High
55 | File | `/conf/app.conf` | High
56 | File | `/control/register_case.php` | High
57 | File | `/dataSet/testTransform;swagger-ui` | High
58 | File | `/diario-de-observacoes/` | High
59 | File | `/edit-computer-detail.php` | High
60 | File | `/edit/server` | Medium
61 | File | `/edit_student.php` | High
62 | File | `/expedit.php` | Medium
63 | File | `/export` | Low
64 | File | `/foms/routers/place-order.php` | High
65 | File | `/forum/away.php` | High
66 | File | `/front/admin/tenancyDetail.php` | High
67 | File | `/goform/formSetPassword` | High
68 | File | `/goform/RP_setBasicAuto` | High
69 | ... | ... | ...

There are 607 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://arcticwolf.com/resources/blog/arctic-wolf-labs-observes-increased-fog-and-akira-ransomware-activity-linked-to-sonicwall-ssl-vpn/
* https://arcticwolf.com/resources/blog/smash-and-grab-aggressive-akira-campaign-targets-sonicwall-vpns/
* https://de.darktrace.com/blog/akira-ransomware-how-darktrace-foiled-another-novel-ransomware-attack
* https://github.com/sophoslabs/IoCs/blob/master/2023-12%20Akira%20followup.csv
* https://thedfirreport.com/2025/08/05/from-bing-search-to-ransomware-bumblebee-and-adaptixc2-deliver-akira/
* https://www.esentire.com/security-advisories/undisclosed-sonicwall-zero-day-leading-to-akira-ransomware

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
