# HijackLoader - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [HijackLoader](https://vuldb.com/?actor.hijackloader). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hijackloader](https://vuldb.com/?actor.hijackloader)

## Campaigns

The following _campaigns_ are known and can be associated with HijackLoader:

* ClickFix

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with HijackLoader:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of HijackLoader.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.141.233.196](https://vuldb.com/?ip.45.141.233.196) | - | - | High
2 | [62.60.234.80](https://vuldb.com/?ip.62.60.234.80) | susko.aho.cuata | - | High
3 | [77.83.207.69](https://vuldb.com/?ip.77.83.207.69) | - | - | High
4 | [78.40.209.164](https://vuldb.com/?ip.78.40.209.164) | 6288squidsbased.example.com | - | High
5 | [91.212.166.51](https://vuldb.com/?ip.91.212.166.51) | - | ClickFix | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _HijackLoader_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by HijackLoader. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/?explorer/index/zip` | High
3 | File | `/add-subadmin.php` | High
4 | File | `/add_new_invoice.php` | High
5 | File | `/add_user.php` | High
6 | File | `/admin/?page=system_info/contact_info` | High
7 | File | `/admin/?page=zone` | High
8 | File | `/admin/about-us.php` | High
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
26 | File | `/admin/edit-post.php` | High
27 | File | `/admin/edit-user.php` | High
28 | File | `/admin/edit_room.php` | High
29 | File | `/admin/includes/edit_post.php` | High
30 | File | `/admin/index.php?page=user-profile` | High
31 | File | `/admin/index2.html` | High
32 | File | `/Admin/login.php` | High
33 | File | `/admin/login.php` | High
34 | File | `/admin/manage-ambulance.php` | High
35 | File | `/admin/mechanics/manage_mechanic.php` | High
36 | File | `/admin/modules/room/index.php` | High
37 | File | `/admin/profile.php` | High
38 | File | `/Admin/Proses_Edit_Akun.php` | High
39 | File | `/admin/robot.php` | High
40 | File | `/admin/search-invoices.php` | High
41 | File | `/admin/tags/save` | High
42 | File | `/admin/twitter.php` | High
43 | File | `/admin/user-bookings.php` | High
44 | File | `/admin/user/index.php?view=edit` | High
45 | File | `/admin/yesterday-reg-users.php` | High
46 | File | `/adminapi/system/file/openfile` | High
47 | File | `/administrator/addcategory.php` | High
48 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
49 | File | `/admin_members.php?ac=editsave` | High
50 | File | `/ajax.php?action=save_payroll` | High
51 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
52 | File | `/alphaware/summary.php` | High
53 | File | `/api/File/downloadFile` | High
54 | File | `/api/settings` | High
55 | File | `/api/sys/login` | High
56 | File | `/api/wizard/getCapability` | High
57 | File | `/app/api/controller/collect.php` | High
58 | File | `/app/api/v1/openvpn.py` | High
59 | File | `/app/controller/Api.php` | High
60 | File | `/app/index/controller/Common.php` | High
61 | File | `/app/register.php?action=reg` | High
62 | File | `/app/sys1.php` | High
63 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
64 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
65 | File | `/applications/nexus/modules/front/store/store.php` | High
66 | File | `/assetsGroupReport/assetsService.j%73p` | High
67 | File | `/auth.asp` | Medium
68 | File | `/backend/doc/his_doc_update-account.php` | High
69 | File | `/bin/httpd` | Medium
70 | File | `/bitrix/admin/ldap_server_edit.php` | High
71 | File | `/biurl_grou` | Medium
72 | File | `/boaform/formSysCmd` | High
73 | File | `/boafrm/formDMZ` | High
74 | File | `/boafrm/formTmultiAP` | High
75 | File | `/borrow.php` | Medium
76 | File | `/browse.php` | Medium
77 | ... | ... | ...

There are 681 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/315bc97f-69e0-4346-9f68-973f46961f9c
* https://app.any.run/tasks/237209eb-af1a-47e5-a2d4-76012f2f33f0
* https://bazaar.abuse.ch/sample/16a0e939d42dbe39946c3a48bc07ec9b6ef565c0828f66be053d1320e5f7c4f7/
* https://bazaar.abuse.ch/sample/eec9b4769ab34844f5f6caa304bad459780fe72e337eb8d686f01fcfd3833ac0/
* https://threatfox.abuse.ch
* https://tria.ge/260112-ncybsadx4c
* https://urlhaus.abuse.ch/url/3555651/
* https://urlhaus.abuse.ch/url/3573826/
* https://urlhaus.abuse.ch/url/3581742/
* https://urlhaus.abuse.ch/url/3590817/
* https://urlhaus.abuse.ch/url/3601321/
* https://urlhaus.abuse.ch/url/3611729/
* https://urlhaus.abuse.ch/url/3632295/
* https://urlhaus.abuse.ch/url/3690055/
* https://urlhaus.abuse.ch/url/3691747/
* https://urlhaus.abuse.ch/url/3692031/
* https://urlhaus.abuse.ch/url/3697164/
* https://urlhaus.abuse.ch/url/3762002/
* https://www.seqrite.com/blog/deconstructing-a-cyber-deception-an-analysis-of-the-clickfix-hijackloader-phishing-campaign/
* https://www.virustotal.com/gui/file/6260f900197592b6d88f500c58e3bb03cc98606ac5f4f5c33b2953c2b3aa2309
* https://www.virustotal.com/gui/file/57748e42e68e56c1f8813ed1c6a372191dfacc6488b4500f973a3aad93add2ed

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
