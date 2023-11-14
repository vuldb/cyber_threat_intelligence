# OpBlueRaven - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _OpBlueRaven_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with OpBlueRaven:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with OpBlueRaven or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [FIN7](https://vuldb.com/?actor.fin7) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of OpBlueRaven.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.177.23](https://vuldb.com/?ip.5.252.177.23) | 5-252-177-23.mivocloud.com | [FIN7](https://vuldb.com/?actor.fin7) | High
2 | [5.252.177.37](https://vuldb.com/?ip.5.252.177.37) | no-rdns.mivocloud.com | [FIN7](https://vuldb.com/?actor.fin7) | High
3 | [23.83.133.119](https://vuldb.com/?ip.23.83.133.119) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
4 | [37.1.211.239](https://vuldb.com/?ip.37.1.211.239) | ourdrops.org | [FIN7](https://vuldb.com/?actor.fin7) | High
5 | [37.1.215.4](https://vuldb.com/?ip.37.1.215.4) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
6 | [37.1.215.72](https://vuldb.com/?ip.37.1.215.72) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
7 | [37.252.4.131](https://vuldb.com/?ip.37.252.4.131) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
8 | [45.77.60.230](https://vuldb.com/?ip.45.77.60.230) | 45.77.60.230.vultr.com | [FIN7](https://vuldb.com/?actor.fin7) | Medium
9 | [45.77.204.130](https://vuldb.com/?ip.45.77.204.130) | 45.77.204.130.vultr.com | [FIN7](https://vuldb.com/?actor.fin7) | Medium
10 | [45.87.152.64](https://vuldb.com/?ip.45.87.152.64) | free.pq.hosting | [FIN7](https://vuldb.com/?actor.fin7) | High
11 | [45.133.216.25](https://vuldb.com/?ip.45.133.216.25) | lisulisimp.example.com | [FIN7](https://vuldb.com/?actor.fin7) | High
12 | ... | ... | ... | ...

There are 44 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/account/delivery` | High
4 | File | `/admin.php/accessory/filesdel.html` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/?page=user/manage` | High
7 | File | `/admin/about-us.php` | High
8 | File | `/admin/add-new.php` | High
9 | File | `/admin/admin-profile.php` | High
10 | File | `/admin/api/theme-edit/` | High
11 | File | `/admin/article/article-edit-run.php` | High
12 | File | `/admin/attendance_row.php` | High
13 | File | `/admin/cashadvance_row.php` | High
14 | File | `/admin/controller/JobLogController.java` | High
15 | File | `/admin/deduction_row.php` | High
16 | File | `/admin/doctors.php` | High
17 | File | `/admin/edit-accepted-appointment.php` | High
18 | File | `/admin/employee_row.php` | High
19 | File | `/admin/invoice.php` | High
20 | File | `/admin/login.php` | High
21 | File | `/admin/maintenance/brand.php` | High
22 | File | `/admin/maintenance/view_designation.php` | High
23 | File | `/admin/read.php?mudi=getSignal` | High
24 | File | `/admin/sys_sql_query.php` | High
25 | File | `/ajax.php?action=read_msg` | High
26 | File | `/alphaware/summary.php` | High
27 | File | `/api/` | Low
28 | File | `/api/admin/store/product/list` | High
29 | File | `/api/baskets/{name}` | High
30 | File | `/api/stl/actions/search` | High
31 | File | `/api/sys/login` | High
32 | File | `/api/sys/set_passwd` | High
33 | File | `/api/v2/cli/commands` | High
34 | File | `/api/wechat/app_auth` | High
35 | File | `/apply.cgi` | Medium
36 | File | `/App_Resource/UEditor/server/upload.aspx` | High
37 | File | `/author/list?limit=10&offset=0&order=desc` | High
38 | File | `/bin/ate` | Medium
39 | File | `/blog` | Low
40 | File | `/boat/login.php` | High
41 | File | `/booking/show_bookings/` | High
42 | File | `/browse` | Low
43 | File | `/bsms_ci/index.php/book` | High
44 | File | `/cgi-bin` | Medium
45 | File | `/cgi-bin/wlogin.cgi` | High
46 | File | `/chaincity/user/ticket/create` | High
47 | File | `/changePassword` | High
48 | File | `/classes/Master.php?f=delete_category` | High
49 | File | `/classes/Master.php?f=delete_sub_category` | High
50 | File | `/classes/Users.php?f=save` | High
51 | File | `/collection/all` | High
52 | File | `/common/info.cgi` | High
53 | File | `/company/store` | High
54 | File | `/Content/Template/root/reverse-shell.aspx` | High
55 | File | `/dashboard/add-blog.php` | High
56 | File | `/debug/pprof` | Medium
57 | File | `/ecshop/admin/template.php` | High
58 | File | `/env` | Low
59 | File | `/etc/pki/pesign` | High
60 | File | `/forum/away.php` | High
61 | File | `/front/roomtype-details.php` | High
62 | ... | ... | ...

There are 546 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/OpBlueRaven

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
