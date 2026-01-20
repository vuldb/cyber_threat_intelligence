# UAC-0215 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0215](https://vuldb.com/?actor.uac-0215). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0215](https://vuldb.com/?actor.uac-0215)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0215:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0215.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.201.112](https://vuldb.com/?ip.2.58.201.112) | 112.201.58.2.us.kuroit.com | - | High
2 | [13.49.21.253](https://vuldb.com/?ip.13.49.21.253) | ec2-13-49-21-253.eu-north-1.compute.amazonaws.com | - | Medium
3 | [23.160.56.100](https://vuldb.com/?ip.23.160.56.100) | - | - | High
4 | [23.160.56.122](https://vuldb.com/?ip.23.160.56.122) | - | - | High
5 | [37.153.155.143](https://vuldb.com/?ip.37.153.155.143) | - | - | High
6 | [38.180.110.238](https://vuldb.com/?ip.38.180.110.238) | - | - | High
7 | [38.180.146.210](https://vuldb.com/?ip.38.180.146.210) | - | - | High
8 | [38.180.146.230](https://vuldb.com/?ip.38.180.146.230) | - | - | High
9 | [45.11.230.105](https://vuldb.com/?ip.45.11.230.105) | 105.230.11.45.us.kuroit.com | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0215_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0215. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add-subadmin.php` | High
3 | File | `/add_new_invoice.php` | High
4 | File | `/add_user.php` | High
5 | File | `/admin/?page=zone` | High
6 | File | `/admin/aboutus.php` | High
7 | File | `/admin/action/delete-vaccine.php` | High
8 | File | `/admin/actions/check-attendance.php` | High
9 | File | `/admin/add-table.php` | High
10 | File | `/admin/admin_running.php` | High
11 | File | `/Admin/akun_edit.php` | High
12 | File | `/admin/apply.php` | High
13 | File | `/admin/category/view_category.php` | High
14 | File | `/admin/changeimage.php` | High
15 | File | `/Admin/changepassword.php` | High
16 | File | `/admin/class.php` | High
17 | File | `/admin/config_time_sync.php` | High
18 | File | `/admin/content/editor` | High
19 | File | `/admin/create-package.php` | High
20 | File | `/admin/delete_s6.php` | High
21 | File | `/admin/delete_user.php` | High
22 | File | `/admin/doAdminAction.php?act=addCate` | High
23 | File | `/admin/edit-brand.php` | High
24 | File | `/admin/edit-post.php` | High
25 | File | `/admin/edit_product.php` | High
26 | File | `/admin/edit_room.php` | High
27 | File | `/admin/includes/edit_post.php` | High
28 | File | `/admin/index.php?page=user-profile` | High
29 | File | `/admin/index2.html` | High
30 | File | `/Admin/login.php` | High
31 | File | `/admin/login.php` | High
32 | File | `/admin/mechanics/manage_mechanic.php` | High
33 | File | `/admin/modules/room/index.php` | High
34 | File | `/admin/profile.php` | High
35 | File | `/Admin/Proses_Edit_Akun.php` | High
36 | File | `/admin/register.php` | High
37 | File | `/admin/robot.php` | High
38 | File | `/admin/search-appointment.php` | High
39 | File | `/admin/search-invoices.php` | High
40 | File | `/admin/tags/save` | High
41 | File | `/admin/twitter.php` | High
42 | File | `/admin/user-bookings.php` | High
43 | File | `/admin/user/index.php?view=edit` | High
44 | File | `/admin/yesterday-reg-users.php` | High
45 | File | `/adminapi/system/file/openfile` | High
46 | File | `/administrator/addcategory.php` | High
47 | File | `/alphaware/summary.php` | High
48 | File | `/api/File/downloadFile` | High
49 | File | `/api/settings` | High
50 | File | `/api/sys/login` | High
51 | File | `/api/wizard/getCapability` | High
52 | File | `/app/api/v1/openvpn.py` | High
53 | File | `/app/controller/Api.php` | High
54 | File | `/app/index/controller/Common.php` | High
55 | File | `/app/sys1.php` | High
56 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
57 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
58 | File | `/applications/nexus/modules/front/store/store.php` | High
59 | File | `/auth.asp` | Medium
60 | File | `/backend/doc/his_doc_update-account.php` | High
61 | File | `/bitrix/admin/ldap_server_edit.php` | High
62 | File | `/biurl_grou` | Medium
63 | File | `/boafrm/formDMZ` | High
64 | File | `/borrow.php` | Medium
65 | File | `/browse.php` | Medium
66 | File | `/cgi-bin/apkg_mgr.cgi` | High
67 | File | `/cgi-bin/cstecgi.cgi` | High
68 | File | `/cgi-bin/nas_sharing.cgi` | High
69 | File | `/cgi-bin/photocenter_mgr.cgi` | High
70 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
71 | File | `/cgi-bin/wlogin.cgi` | High
72 | File | `/classes/Master.php` | High
73 | File | `/classes/Master.php?f=delete_record` | High
74 | File | `/classes/Master.php?f=save_category` | High
75 | ... | ... | ...

There are 658 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/6281076

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
