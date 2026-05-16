# Rogue RDP - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Rogue RDP_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Rogue RDP:

* [US](https://vuldb.com/country/us)
* [CH](https://vuldb.com/country/ch)
* [RU](https://vuldb.com/country/ru)
* ...

There are 17 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Rogue RDP or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [UAC-215](https://vuldb.com/actor/uac-215) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Rogue RDP.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [2.58.201.112](https://vuldb.com/ip/2.58.201.112) | 112.201.58.2.us.kuroit.com | [UAC-215](https://vuldb.com/actor/uac-215) | High
2 | [13.49.21.253](https://vuldb.com/ip/13.49.21.253) | ec2-13-49-21-253.eu-north-1.compute.amazonaws.com | [UAC-215](https://vuldb.com/actor/uac-215) | Medium
3 | [23.160.56.100](https://vuldb.com/ip/23.160.56.100) | - | [UAC-215](https://vuldb.com/actor/uac-215) | High
4 | [23.160.56.122](https://vuldb.com/ip/23.160.56.122) | - | [UAC-215](https://vuldb.com/actor/uac-215) | High
5 | [37.153.155.143](https://vuldb.com/ip/37.153.155.143) | - | [UAC-215](https://vuldb.com/actor/uac-215) | High
6 | [38.180.110.238](https://vuldb.com/ip/38.180.110.238) | - | [UAC-215](https://vuldb.com/actor/uac-215) | High
7 | [38.180.146.210](https://vuldb.com/ip/38.180.146.210) | - | [UAC-215](https://vuldb.com/actor/uac-215) | High
8 | [38.180.146.230](https://vuldb.com/ip/38.180.146.230) | - | [UAC-215](https://vuldb.com/actor/uac-215) | High
9 | [45.11.230.105](https://vuldb.com/ip/45.11.230.105) | 105.230.11.45.us.kuroit.com | [UAC-215](https://vuldb.com/actor/uac-215) | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Rogue RDP. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Rogue RDP. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/?explorer/index/zip` | High
3 | File | `/add-subadmin.php` | High
4 | File | `/add_new_invoice.php` | High
5 | File | `/add_user.php` | High
6 | File | `/admin/?page=zone` | High
7 | File | `/admin/aboutus.php` | High
8 | File | `/admin/action/delete-vaccine.php` | High
9 | File | `/admin/actions/check-attendance.php` | High
10 | File | `/admin/add-table.php` | High
11 | File | `/admin/admin_running.php` | High
12 | File | `/Admin/akun_edit.php` | High
13 | File | `/admin/apply.php` | High
14 | File | `/admin/category/view_category.php` | High
15 | File | `/admin/changeimage.php` | High
16 | File | `/Admin/changepassword.php` | High
17 | File | `/admin/class.php` | High
18 | File | `/admin/completed-requests.php` | High
19 | File | `/admin/config_time_sync.php` | High
20 | File | `/admin/content/editor` | High
21 | File | `/admin/create-package.php` | High
22 | File | `/admin/delete_s6.php` | High
23 | File | `/admin/delete_user.php` | High
24 | File | `/admin/doAdminAction.php?act=addCate` | High
25 | File | `/admin/edit-art-product-detail.php?editid=2` | High
26 | File | `/admin/edit-brand.php` | High
27 | File | `/admin/edit-post.php` | High
28 | File | `/admin/edit-user.php` | High
29 | File | `/admin/edit_product.php` | High
30 | File | `/admin/edit_room.php` | High
31 | File | `/admin/includes/edit_post.php` | High
32 | File | `/admin/index.php?page=user-profile` | High
33 | File | `/admin/index2.html` | High
34 | File | `/Admin/login.php` | High
35 | File | `/admin/login.php` | High
36 | File | `/admin/mechanics/manage_mechanic.php` | High
37 | File | `/admin/modules/room/index.php` | High
38 | File | `/admin/profile.php` | High
39 | File | `/Admin/Proses_Edit_Akun.php` | High
40 | File | `/admin/register.php` | High
41 | File | `/admin/robot.php` | High
42 | File | `/admin/search-appointment.php` | High
43 | File | `/admin/search-invoices.php` | High
44 | File | `/admin/tags/save` | High
45 | File | `/admin/twitter.php` | High
46 | File | `/admin/user-bookings.php` | High
47 | File | `/admin/user/index.php?view=edit` | High
48 | File | `/admin/yesterday-reg-users.php` | High
49 | File | `/adminapi/system/file/openfile` | High
50 | File | `/administrator/addcategory.php` | High
51 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
52 | File | `/ajax.php?action=save_payroll` | High
53 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
54 | File | `/alphaware/summary.php` | High
55 | File | `/api/File/downloadFile` | High
56 | File | `/api/settings` | High
57 | File | `/api/sys/login` | High
58 | File | `/api/wizard/getCapability` | High
59 | File | `/api/wizard/setLanguage` | High
60 | File | `/app/api/controller/collect.php` | High
61 | File | `/app/api/v1/openvpn.py` | High
62 | File | `/app/controller/Api.php` | High
63 | File | `/app/index/controller/Common.php` | High
64 | File | `/app/register.php?action=reg` | High
65 | File | `/app/sys1.php` | High
66 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
67 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
68 | File | `/applications/nexus/modules/front/store/store.php` | High
69 | File | `/assetsGroupReport/assetsService.j%73p` | High
70 | File | `/auth.asp` | Medium
71 | File | `/backend/doc/his_doc_update-account.php` | High
72 | File | `/bin/httpd` | Medium
73 | File | `/bitrix/admin/ldap_server_edit.php` | High
74 | File | `/biurl_grou` | Medium
75 | File | `/boaform/formSysCmd` | High
76 | File | `/boafrm/formDMZ` | High
77 | File | `/boafrm/formTmultiAP` | High
78 | File | `/borrow.php` | Medium
79 | File | `/browse.php` | Medium
80 | File | `/cgi-bin/apkg_mgr.cgi` | High
81 | ... | ... | ...

There are 714 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://cert.gov.ua/article/6281076

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
