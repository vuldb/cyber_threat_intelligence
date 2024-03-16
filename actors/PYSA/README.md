# PYSA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PYSA](https://vuldb.com/?actor.pysa). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pysa](https://vuldb.com/?actor.pysa)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PYSA:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [EG](https://vuldb.com/?country.eg)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PYSA.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.129.64.190](https://vuldb.com/?ip.23.129.64.190) | - | - | High
2 | [45.147.231.210](https://vuldb.com/?ip.45.147.231.210) | - | - | High
3 | [185.220.100.240](https://vuldb.com/?ip.185.220.100.240) | tor-exit-13.zbau.f3netze.de | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PYSA_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PYSA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Account/login.php` | High
2 | File | `/ad-list` | Medium
3 | File | `/admin` | Low
4 | File | `/admin/` | Low
5 | File | `/admin/?page=user/manage_user&id=3` | High
6 | File | `/admin/action/add_con.php` | High
7 | File | `/admin/app/profile_crud.php` | High
8 | File | `/admin/attendance_row.php` | High
9 | File | `/admin/book_row.php` | High
10 | File | `/admin/edit_teacher.php` | High
11 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
12 | File | `/admin/login.php` | High
13 | File | `/admin/maintenance/brand.php` | High
14 | File | `/admin/maintenance/manage_category.php` | High
15 | File | `/admin/maintenance/view_designation.php` | High
16 | File | `/admin/modal_add_product.php` | High
17 | File | `/admin/php/crud.php` | High
18 | File | `/admin/read.php?mudi=getSignal` | High
19 | File | `/admin/report/index.php` | High
20 | File | `/admin/reportupload.aspx` | High
21 | File | `/admin/return_add.php` | High
22 | File | `/admin/service.php` | High
23 | File | `/admin/service_requests/manage_inventory.php` | High
24 | File | `/admin/settings/` | High
25 | File | `/admin/students.php` | High
26 | File | `/admin/theme-edit.php` | High
27 | File | `/admin/update_s6.php` | High
28 | File | `/admin/user/manage_user.php` | High
29 | File | `/admin/users` | Medium
30 | File | `/adplanet/PlanetUser` | High
31 | File | `/ajax.php?action=read_msg` | High
32 | File | `/ajax.php?action=save_company` | High
33 | File | `/ample/app/action/edit_product.php` | High
34 | File | `/api/controllers/merchant/design/MaterialController.php` | High
35 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
36 | File | `/api/sys/login` | High
37 | File | `/app/api/controller/default/File.php` | High
38 | File | `/app/middleware/TokenVerify.php` | High
39 | File | `/application/index/controller/Screen.php` | High
40 | File | `/apps/login_auth.php` | High
41 | File | `/bin/sh` | Low
42 | File | `/blog` | Low
43 | File | `/ccm/system/dialogs/file/delete/1/submit` | High
44 | File | `/cgi-bin/cstecgi.cgi` | High
45 | File | `/cgi-bin/ping.cgi` | High
46 | File | `/cgi-bin/touchlist_sync.cgi` | High
47 | File | `/changeimage.php` | High
48 | File | `/claire_blake` | High
49 | File | `/classes/Master.php` | High
50 | File | `/classes/Master.php?f=delete_inquiry` | High
51 | File | `/classes/Users.php` | High
52 | File | `/core/config-revisions` | High
53 | File | `/dashboard/Cinvoice/manage_invoice` | High
54 | File | `/dashboard/message` | High
55 | File | `/debug/pprof` | Medium
56 | File | `/dipam/save-delegates.php` | High
57 | File | `/edit_user.php` | High
58 | File | `/Employer/EditProfile.php` | High
59 | File | `/endpoint/add-guest.php` | High
60 | File | `/endpoint/add-user.php` | High
61 | File | `/etc/hosts.deny` | High
62 | File | `/etc/init.d/update_notifications.sh` | High
63 | File | `/file-manager/rename.php` | High
64 | File | `/file-manager/upload.php` | High
65 | File | `/file_manager/admin/save_user.php` | High
66 | File | `/forum/away.php` | High
67 | File | `/front/admin/tenancyDetail.php` | High
68 | File | `/general/attendance/manage/ask_duty/delete.php` | High
69 | ... | ... | ...

There are 603 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/120/pysa-ransomware-iocs/
* https://thedfirreport.com/2020/11/23/pysa-mespinoza-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
