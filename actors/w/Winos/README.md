# Winos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Winos](https://vuldb.com/?actor.winos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.winos](https://vuldb.com/?actor.winos)

## Campaigns

The following _campaigns_ are known and can be associated with Winos:

* Catena
* Taiwanese Organizations

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Winos:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Winos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.122.59.71](https://vuldb.com/?ip.27.122.59.71) | - | - | High
2 | [43.226.125.44](https://vuldb.com/?ip.43.226.125.44) | - | - | High
3 | [47.83.184.193](https://vuldb.com/?ip.47.83.184.193) | - | - | High
4 | [47.86.28.28](https://vuldb.com/?ip.47.86.28.28) | - | - | High
5 | [47.238.125.85](https://vuldb.com/?ip.47.238.125.85) | - | - | High
6 | [103.46.185.44](https://vuldb.com/?ip.103.46.185.44) | undefined.hostname.localhost | Catena | High
7 | [103.46.185.73](https://vuldb.com/?ip.103.46.185.73) | undefined.hostname.localhost | - | High
8 | ... | ... | ... | ...

There are 28 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Winos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Winos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/add-courier.php` | High
2 | File | `/add_user.php` | High
3 | File | `/admin-profile.php` | High
4 | File | `/admin.php` | Medium
5 | File | `/admin.php?p=/Area/index#tab=t2` | High
6 | File | `/admin/?page=system_info` | High
7 | File | `/admin/aboutus.php` | High
8 | File | `/admin/admin/save` | High
9 | File | `/admin/admin_feature.php` | High
10 | File | `/admin/admin_running.php` | High
11 | File | `/admin/announcement/index.php?view=add` | High
12 | File | `/Admin/assets/backend/seller/add_seller.php` | High
13 | File | `/admin/bwdates-reports-details.php` | High
14 | File | `/Admin/changepassword.php` | High
15 | File | `/admin/checklogin.php` | High
16 | File | `/admin/deleteitem.php` | High
17 | File | `/admin/delete_student.php` | High
18 | File | `/admin/delete_user.php` | High
19 | File | `/admin/edit-services.php` | High
20 | File | `/admin/editsite.php` | High
21 | File | `/admin/employee/index.php?view=edit` | High
22 | File | `/admin/forget-password.php` | High
23 | File | `/admin/index.php` | High
24 | File | `/admin/index2.html` | High
25 | File | `/admin/manage-users.php` | High
26 | File | `/admin/manage_theater.php` | High
27 | File | `/admin/new-content` | High
28 | File | `/admin/posts.php?source=add_post` | High
29 | File | `/admin/products/index.php?view=add` | High
30 | File | `/admin/products/index.php?view=edit` | High
31 | File | `/admin/receipt.php` | High
32 | File | `/admin/search1.php` | High
33 | File | `/admin/uesrs.php&&action=delete&userid=4` | High
34 | File | `/admin/update_room.php` | High
35 | File | `/adminPage/conf/check` | High
36 | File | `/admin_delete.php` | High
37 | File | `/ahrw/jsp/gsfr_feditorHTML.jsp` | High
38 | File | `/ajax.php?action=delete_payment` | High
39 | File | `/ajax.php?action=login` | High
40 | File | `/ajax.php?action=save_course` | High
41 | File | `/api/admin/update_account/` | High
42 | File | `/api/store_integral/order/detail/:uni` | High
43 | File | `/api/users/updateAvatar` | High
44 | File | `/api/v1/courses/` | High
45 | File | `/api/v1/devices/register` | High
46 | File | `/app-api/v1/members/openid/` | High
47 | File | `/app-api/v1/orders/` | High
48 | File | `/app/uploading/upload-mp3.php` | High
49 | File | `/application/index/controller/Unity.php` | High
50 | File | `/authentication/` | High
51 | File | `/auth_files/photo/` | High
52 | File | `/bin/httpd` | Medium
53 | File | `/boafrm/formDebugDiagnosticRun` | High
54 | File | `/boafrm/formIpQoS` | High
55 | File | `/boafrm/formLtefotaUpgradeQuectel` | High
56 | File | `/boafrm/formVpnConfigSetup` | High
57 | File | `/booking/show_bookings/` | High
58 | File | `/cgi-bin/api.values.post` | High
59 | File | `/cgi-bin/cstecgi.cgi` | High
60 | File | `/cgi-bin/DownloadFlash` | High
61 | File | `/cgi-bin/DownloadLog` | High
62 | File | `/cgi-bin/nas_sharing.cgi` | High
63 | File | `/cgi/timepro.cgi` | High
64 | File | `/checkin.php` | Medium
65 | File | `/check_user.php` | High
66 | File | `/crm/contact/transfer` | High
67 | File | `/dashboard/approve-reject.php` | High
68 | ... | ... | ...

There are 593 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/rapid7/Rapid7-Labs/blob/main/IOCs/nsis-abuse-srdi-winos4/iocs.txt
* https://www.fortinet.com/blog/threat-research/threat-group-targets-companies-in-taiwan
* https://www.malwarebytes.com/blog/threat-intel/2026/01/how-real-software-downloads-can-hide-remote-backdoors
* https://www.rapid7.com/blog/post/2025/05/22/nsis-abuse-and-srdi-shellcode-anatomy-of-the-winos-4-0-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
