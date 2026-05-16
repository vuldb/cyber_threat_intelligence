# Catena - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Catena_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Catena:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Catena or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Winos](https://vuldb.com/?actor.winos) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Catena.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [103.46.185.44](https://vuldb.com/?ip.103.46.185.44) | undefined.hostname.localhost | [Winos](https://vuldb.com/?actor.winos) | High
2 | [134.122.204.11](https://vuldb.com/?ip.134.122.204.11) | - | [Winos](https://vuldb.com/?actor.winos) | High
3 | [156.251.17.243](https://vuldb.com/?ip.156.251.17.243) | - | [Winos](https://vuldb.com/?actor.winos) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Catena. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Catena. This data is unique as it uses our predictive model for actor profiling.

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
24 | File | `/admin/manage-users.php` | High
25 | File | `/admin/manage_theater.php` | High
26 | File | `/admin/new-content` | High
27 | File | `/admin/posts.php?source=add_post` | High
28 | File | `/admin/products/index.php?view=add` | High
29 | File | `/admin/products/index.php?view=edit` | High
30 | File | `/admin/receipt.php` | High
31 | File | `/admin/search1.php` | High
32 | File | `/admin/uesrs.php&&action=delete&userid=4` | High
33 | File | `/admin/update_room.php` | High
34 | File | `/adminPage/conf/check` | High
35 | File | `/admin_delete.php` | High
36 | File | `/ahrw/jsp/gsfr_feditorHTML.jsp` | High
37 | File | `/ajax.php?action=delete_payment` | High
38 | File | `/ajax.php?action=login` | High
39 | File | `/ajax.php?action=save_course` | High
40 | File | `/api/admin/update_account/` | High
41 | File | `/api/store_integral/order/detail/:uni` | High
42 | File | `/api/users/updateAvatar` | High
43 | File | `/api/v1/courses/` | High
44 | File | `/api/v1/devices/register` | High
45 | File | `/app-api/v1/members/openid/` | High
46 | File | `/app-api/v1/orders/` | High
47 | File | `/app/uploading/upload-mp3.php` | High
48 | File | `/application/index/controller/Unity.php` | High
49 | File | `/authentication/` | High
50 | File | `/auth_files/photo/` | High
51 | File | `/bin/httpd` | Medium
52 | File | `/boafrm/formDebugDiagnosticRun` | High
53 | File | `/boafrm/formIpQoS` | High
54 | File | `/boafrm/formLtefotaUpgradeQuectel` | High
55 | File | `/boafrm/formVpnConfigSetup` | High
56 | File | `/booking/show_bookings/` | High
57 | File | `/cgi-bin/api.values.post` | High
58 | File | `/cgi-bin/cstecgi.cgi` | High
59 | File | `/cgi-bin/DownloadFlash` | High
60 | File | `/cgi-bin/DownloadLog` | High
61 | File | `/cgi-bin/nas_sharing.cgi` | High
62 | File | `/cgi/timepro.cgi` | High
63 | File | `/checkin.php` | Medium
64 | File | `/check_user.php` | High
65 | File | `/crm/contact/transfer` | High
66 | File | `/dashboard/approve-reject.php` | High
67 | File | `/database?action=GetDatabaseAccess` | High
68 | ... | ... | ...

There are 598 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.rapid7.com/blog/post/2025/05/22/nsis-abuse-and-srdi-shellcode-anatomy-of-the-winos-4-0-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
