# xHunt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xHunt](https://vuldb.com/?actor.xhunt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xhunt](https://vuldb.com/?actor.xhunt)

## Campaigns

The following _campaigns_ are known and can be associated with xHunt:

* BumbleBee

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xHunt:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [UA](https://vuldb.com/?country.ua)
* ...

There are 26 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xHunt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.92.127.18](https://vuldb.com/?ip.23.92.127.18) | - | BumbleBee | High
2 | [46.246.3.253](https://vuldb.com/?ip.46.246.3.253) | - | BumbleBee | High
3 | [46.246.3.254](https://vuldb.com/?ip.46.246.3.254) | - | BumbleBee | High
4 | [77.243.191.20](https://vuldb.com/?ip.77.243.191.20) | - | BumbleBee | High
5 | [82.102.21.219](https://vuldb.com/?ip.82.102.21.219) | - | BumbleBee | High
6 | [84.17.55.68](https://vuldb.com/?ip.84.17.55.68) | unn-84-17-55-68.cdn77.com | BumbleBee | High
7 | ... | ... | ... | ...

There are 24 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xHunt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.git/` | Low
2 | File | `/.env` | Low
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/add-students.php` | High
5 | File | `/admin` | Low
6 | File | `/admin-api/upload_image` | High
7 | File | `/admin.php/accessory/filesdel.html` | High
8 | File | `/admin/?page=user/list` | High
9 | File | `/admin/?page=user/manage_user&id=3` | High
10 | File | `/admin/about-us.php` | High
11 | File | `/admin/action/new-father.php` | High
12 | File | `/Admin/add-student.php` | High
13 | File | `/admin/admin-update-employee.php` | High
14 | File | `/admin/app/service_crud.php` | High
15 | File | `/admin/application-bwdates-reports-details.php` | High
16 | File | `/admin/del_category.php` | High
17 | File | `/admin/del_service.php` | High
18 | File | `/admin/edit-accepted-appointment.php` | High
19 | File | `/admin/edit-admin.php` | High
20 | File | `/admin/edit-services.php` | High
21 | File | `/admin/edit_category.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/ind_backstage.php` | High
24 | File | `/admin/list_crl_conf` | High
25 | File | `/Admin/login.php` | High
26 | File | `/admin/pages/list` | High
27 | File | `/admin/search.php` | High
28 | File | `/admin/system.html` | High
29 | File | `/admin/sys_sql_query.php` | High
30 | File | `/api/baskets/{name}` | High
31 | File | `/api/process.php` | High
32 | File | `/api/swaggerui/static` | High
33 | File | `/api/sys/login` | High
34 | File | `/api/v1/toolbox/device/update/swap` | High
35 | File | `/api/v2/maps` | Medium
36 | File | `/api/v4/teams//channels/deleted` | High
37 | File | `/app/admin/controller/Upload.php` | High
38 | File | `/app/ajax/search_sales_report.php` | High
39 | File | `/app/controller/Setup.php` | High
40 | File | `/app/middleware/TokenVerify.php` | High
41 | File | `/appliance/users?action=edit` | High
42 | File | `/application/index/controller/Screen.php` | High
43 | File | `/application/websocket/controller/Setting.php` | High
44 | File | `/apply/index.php` | High
45 | File | `/auth/auth.php?user=1` | High
46 | File | `/backend/register.php` | High
47 | File | `/bin/boa` | Medium
48 | File | `/blog` | Low
49 | File | `/boafrm/formMapDelDevice` | High
50 | File | `/cgi-bin/cstecgi.cgi` | High
51 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
52 | File | `/cgi-bin/luci;stok=/locale` | High
53 | File | `/cgi-bin/myMusic.cgi` | High
54 | File | `/cgi-bin/nas_sharing.cgi` | High
55 | File | `/cgi-bin/p1_ftpserver.php` | High
56 | File | `/cgi-bin/photocenter_mgr.cgi` | High
57 | File | `/cgi-bin/wlogin.cgi` | High
58 | File | `/classes/Master.php` | High
59 | File | `/classes/Master.php?f=save_category` | High
60 | File | `/classes/Master.php?f=save_medicine` | High
61 | File | `/classes/SystemSettings.php?f=update_settings` | High
62 | File | `/classes/Users.php?f=save` | High
63 | File | `/collection/all` | High
64 | File | `/common/show_image.php` | High
65 | File | `/conf/app.conf` | High
66 | File | `/control/register_case.php` | High
67 | File | `/dashboard/system/basics/name` | High
68 | File | `/description.php` | High
69 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
70 | ... | ... | ...

There are 611 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
