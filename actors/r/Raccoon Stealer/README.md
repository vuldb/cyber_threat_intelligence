# Raccoon Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Raccoon Stealer](https://vuldb.com/?actor.raccoon_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.raccoon_stealer](https://vuldb.com/?actor.raccoon_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Raccoon Stealer:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [SH](https://vuldb.com/?country.sh)
* ...

There are 19 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Raccoon Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.247](https://vuldb.com/?ip.2.58.56.247) | powered.by.rdp.sh | - | High
2 | [5.42.199.87](https://vuldb.com/?ip.5.42.199.87) | - | - | High
3 | [5.252.22.62](https://vuldb.com/?ip.5.252.22.62) | vm523526.stark-industries.solutions | - | High
4 | [5.252.22.66](https://vuldb.com/?ip.5.252.22.66) | s-germany.rocks | - | High
5 | [5.252.22.107](https://vuldb.com/?ip.5.252.22.107) | ns3.pacehost.de | - | High
6 | [23.88.55.150](https://vuldb.com/?ip.23.88.55.150) | static.150.55.88.23.clients.your-server.de | - | High
7 | [31.13.195.44](https://vuldb.com/?ip.31.13.195.44) | - | - | High
8 | [45.61.136.191](https://vuldb.com/?ip.45.61.136.191) | - | - | High
9 | [45.67.34.152](https://vuldb.com/?ip.45.67.34.152) | vm749292.stark-industries.solutions | - | High
10 | [45.67.34.234](https://vuldb.com/?ip.45.67.34.234) | server.ga2.so-net.ne.jp | - | High
11 | [45.67.35.251](https://vuldb.com/?ip.45.67.35.251) | vm684273.stark-industries.solutions | - | High
12 | [45.84.0.80](https://vuldb.com/?ip.45.84.0.80) | sfixbfc.cn | - | High
13 | [45.92.156.52](https://vuldb.com/?ip.45.92.156.52) | - | - | High
14 | [45.92.156.53](https://vuldb.com/?ip.45.92.156.53) | - | - | High
15 | [45.133.216.145](https://vuldb.com/?ip.45.133.216.145) | mail.axiknh.top | - | High
16 | [45.133.216.170](https://vuldb.com/?ip.45.133.216.170) | wireguard.vasilchenko.dev | - | High
17 | [45.133.216.249](https://vuldb.com/?ip.45.133.216.249) | vm699942.stark-industries.solutions | - | High
18 | [45.138.74.104](https://vuldb.com/?ip.45.138.74.104) | descriptive-servant.aeza.network | - | High
19 | [45.142.212.100](https://vuldb.com/?ip.45.142.212.100) | pikpik.top | - | High
20 | [45.142.215.50](https://vuldb.com/?ip.45.142.215.50) | vm700900.stark-industries.solutions | - | High
21 | [45.142.215.92](https://vuldb.com/?ip.45.142.215.92) | vm586875.stark-industries.solutions | - | High
22 | ... | ... | ... | ...

There are 86 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Raccoon Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Raccoon Stealer. This data is unique as it uses our predictive model for actor profiling.

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
14 | File | `/admin/changeimage.php` | High
15 | File | `/Admin/changepassword.php` | High
16 | File | `/admin/completed-requests.php` | High
17 | File | `/admin/content/editor` | High
18 | File | `/admin/create-package.php` | High
19 | File | `/admin/delete_s6.php` | High
20 | File | `/admin/delete_user.php` | High
21 | File | `/admin/doAdminAction.php?act=addCate` | High
22 | File | `/admin/edit-art-product-detail.php?editid=2` | High
23 | File | `/admin/edit-brand.php` | High
24 | File | `/admin/edit-post.php` | High
25 | File | `/admin/edit-user.php` | High
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
36 | File | `/admin/robot.php` | High
37 | File | `/admin/search-invoices.php` | High
38 | File | `/admin/tags/save` | High
39 | File | `/admin/twitter.php` | High
40 | File | `/admin/user-bookings.php` | High
41 | File | `/admin/user/index.php?view=edit` | High
42 | File | `/admin/yesterday-reg-users.php` | High
43 | File | `/adminapi/system/file/openfile` | High
44 | File | `/administrator/addcategory.php` | High
45 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
46 | File | `/ajax.php?action=save_payroll` | High
47 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
48 | File | `/alphaware/summary.php` | High
49 | File | `/api/File/downloadFile` | High
50 | File | `/api/settings` | High
51 | File | `/api/sys/login` | High
52 | File | `/api/wizard/getCapability` | High
53 | File | `/app/api/controller/collect.php` | High
54 | File | `/app/api/v1/openvpn.py` | High
55 | File | `/app/controller/Api.php` | High
56 | File | `/app/index/controller/Common.php` | High
57 | File | `/app/register.php?action=reg` | High
58 | File | `/app/sys1.php` | High
59 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
60 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
61 | File | `/applications/nexus/modules/front/store/store.php` | High
62 | File | `/assetsGroupReport/assetsService.j%73p` | High
63 | File | `/auth.asp` | Medium
64 | File | `/backend/doc/his_doc_update-account.php` | High
65 | File | `/bin/httpd` | Medium
66 | File | `/bitrix/admin/ldap_server_edit.php` | High
67 | File | `/biurl_grou` | Medium
68 | File | `/boaform/formSysCmd` | High
69 | File | `/boafrm/formDMZ` | High
70 | File | `/boafrm/formTmultiAP` | High
71 | File | `/borrow.php` | Medium
72 | File | `/browse.php` | Medium
73 | File | `/cgi-bin/apkg_mgr.cgi` | High
74 | File | `/cgi-bin/cstecgi.cgi` | High
75 | ... | ... | ...

There are 661 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/610bc7b082df417ed032f5f1
* https://de.darktrace.com/blog/the-last-of-its-kind-analysis-of-a-raccoon-stealer-v1-infection-part-1
* https://github.com/SEKOIA-IO/Community/blob/main/IOCs/raccoonstealer/raccoon_stealer_iocs_20220628.csv
* https://www.esentire.com/blog/d3f-ck-loader-the-new-maas-loader
* https://www.zerofox.com/blog/brief-raccoon-stealer-version-2-0/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
