# Sednit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Sednit_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sednit:

* [US](https://vuldb.com/country/us)
* [CH](https://vuldb.com/country/ch)
* [RU](https://vuldb.com/country/ru)
* ...

There are 20 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Sednit or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT28](https://vuldb.com/actor/apt28) | High
2 | [Sednit](https://vuldb.com/actor/sednit) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sednit.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [1.23.82.72](https://vuldb.com/ip/1.23.82.72) | - | [Sednit](https://vuldb.com/actor/sednit) | High
2 | [2.2.82.64](https://vuldb.com/ip/2.2.82.64) | - | [Sednit](https://vuldb.com/actor/sednit) | High
3 | [2.12.51.56](https://vuldb.com/ip/2.12.51.56) | arennes-655-1-148-56.w2-12.abo.wanadoo.fr | [Sednit](https://vuldb.com/actor/sednit) | High
4 | [3.95.29.25](https://vuldb.com/ip/3.95.29.25) | ec2-3-95-29-25.compute-1.amazonaws.com | [Sednit](https://vuldb.com/actor/sednit) | Medium
5 | [5.135.183.154](https://vuldb.com/ip/5.135.183.154) | ns3290077.ip-5-135-183.eu | [Sednit](https://vuldb.com/actor/sednit) | High
6 | [19.2.45.3](https://vuldb.com/ip/19.2.45.3) | - | [Sednit](https://vuldb.com/actor/sednit) | High
7 | [21.15.46.55](https://vuldb.com/ip/21.15.46.55) | - | [Sednit](https://vuldb.com/actor/sednit) | High
8 | [31.7.62.103](https://vuldb.com/ip/31.7.62.103) | - | [Sednit](https://vuldb.com/actor/sednit) | High
9 | [31.220.43.99](https://vuldb.com/ip/31.220.43.99) | nl-2.sa-irc.com | [Sednit](https://vuldb.com/actor/sednit) | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Sednit. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-273, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Sednit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/?explorer/index/zip` | High
3 | File | `/about_us` | Medium
4 | File | `/add-subadmin.php` | High
5 | File | `/add_new_invoice.php` | High
6 | File | `/add_user.php` | High
7 | File | `/admin.php` | Medium
8 | File | `/admin/?page=zone` | High
9 | File | `/admin/aboutus.php` | High
10 | File | `/admin/action/delete-vaccine.php` | High
11 | File | `/admin/actions/check-attendance.php` | High
12 | File | `/admin/add-table.php` | High
13 | File | `/admin/admin_running.php` | High
14 | File | `/Admin/akun_edit.php` | High
15 | File | `/admin/apply.php` | High
16 | File | `/admin/changeimage.php` | High
17 | File | `/Admin/changepassword.php` | High
18 | File | `/admin/completed-requests.php` | High
19 | File | `/admin/content/editor` | High
20 | File | `/admin/create-package.php` | High
21 | File | `/admin/delete_s6.php` | High
22 | File | `/admin/delete_user.php` | High
23 | File | `/admin/doAdminAction.php?act=addCate` | High
24 | File | `/admin/edit-art-product-detail.php?editid=2` | High
25 | File | `/admin/edit-brand.php` | High
26 | File | `/admin/edit-card-detail.php` | High
27 | File | `/admin/edit-post.php` | High
28 | File | `/admin/edit-user.php` | High
29 | File | `/admin/edit_fuel.php` | High
30 | File | `/admin/edit_room.php` | High
31 | File | `/admin/home.php?con=add` | High
32 | File | `/admin/includes/edit_post.php` | High
33 | File | `/admin/index.php?page=user-profile` | High
34 | File | `/admin/index2.html` | High
35 | File | `/Admin/login.php` | High
36 | File | `/admin/login.php` | High
37 | File | `/admin/mechanics/manage_mechanic.php` | High
38 | File | `/admin/modules/room/index.php` | High
39 | File | `/admin/profile.php` | High
40 | File | `/Admin/Proses_Edit_Akun.php` | High
41 | File | `/admin/robot.php` | High
42 | File | `/admin/search-invoices.php` | High
43 | File | `/admin/search-vehicle.php` | High
44 | File | `/admin/tags/save` | High
45 | File | `/admin/twitter.php` | High
46 | File | `/admin/user-bookings.php` | High
47 | File | `/admin/user/index.php?view=edit` | High
48 | File | `/admin/view-card-detail.php` | High
49 | File | `/admin/yesterday-reg-users.php` | High
50 | File | `/adminapi/system/file/openfile` | High
51 | File | `/administrator/addcategory.php` | High
52 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
53 | File | `/ajax.php?action=save_payroll` | High
54 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
55 | File | `/alphaware/summary.php` | High
56 | File | `/api/File/downloadFile` | High
57 | File | `/api/settings` | High
58 | File | `/api/sys/login` | High
59 | File | `/api/wizard/getCapability` | High
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
72 | File | `/BalloonSave.ashx` | High
73 | File | `/bin/httpd` | Medium
74 | File | `/bitrix/admin/ldap_server_edit.php` | High
75 | File | `/biurl_grou` | Medium
76 | File | `/boaform/formSysCmd` | High
77 | File | `/boafrm/formDMZ` | High
78 | File | `/boafrm/formTmultiAP` | High
79 | File | `/boafrm/formWanConfigSetup` | High
80 | File | `/borrow.php` | Medium
81 | File | `/browse.php` | Medium
82 | File | `/cgi-bin/apkg_mgr.cgi` | High
83 | ... | ... | ...

There are 732 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/eset-sednit-part-2.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/eset-sednit-part3.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/APT28/history-report-pdf/sednit-update-analysis-zebrocy_.pdf
* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q3
* https://www.cyber45.com
* https://www.welivesecurity.com/wp-content/uploads/2016/10/eset-sednit-part-2.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
