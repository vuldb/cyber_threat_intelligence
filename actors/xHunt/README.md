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
* [DE](https://vuldb.com/?country.de)
* ...

There are 30 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36, CWE-37 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-87 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.../gogo/` | Medium
2 | File | `//proc/kcore` | Medium
3 | File | `/?ajax-request=jnews` | High
4 | File | `/?r=recruit/resume/edit&op=status` | High
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/?page=user/manage` | High
7 | File | `/admin/?page=user/manage_user&id=3` | High
8 | File | `/admin/about-us.php` | High
9 | File | `/admin/del_category.php` | High
10 | File | `/admin/del_service.php` | High
11 | File | `/admin/edit-accepted-appointment.php` | High
12 | File | `/admin/edit-services.php` | High
13 | File | `/admin/edit.php` | High
14 | File | `/admin/edit_category.php` | High
15 | File | `/admin/edit_subject.php` | High
16 | File | `/admin/forgot-password.php` | High
17 | File | `/admin/index.PHP` | High
18 | File | `/admin/index.php` | High
19 | File | `/admin/maintenance/view_designation.php` | High
20 | File | `/admin/manage_academic.php` | High
21 | File | `/admin/products/manage_product.php` | High
22 | File | `/admin/reg.php` | High
23 | File | `/admin/search-appointment.php` | High
24 | File | `/admin/students/manage.php` | High
25 | File | `/admin/sys_sql_query.php` | High
26 | File | `/adms/admin/?page=vehicles/view_transaction` | High
27 | File | `/alerts/alertConfigField.php` | High
28 | File | `/api/baskets/{name}` | High
29 | File | `/api/sys/login` | High
30 | File | `/api/user/upsert/<uuid>` | High
31 | File | `/appliance/users?action=edit` | High
32 | File | `/backup.pl` | Medium
33 | File | `/belegungsplan/monatsuebersicht.inc.php` | High
34 | File | `/blog` | Low
35 | File | `/booking/show_bookings/` | High
36 | File | `/bsms_ci/index.php` | High
37 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
38 | File | `/cgi-bin/luci;stok=/locale` | High
39 | File | `/classes/Master.php?f=save_sub_category` | High
40 | File | `/classes/Users.php?f=save` | High
41 | File | `/collection/all` | High
42 | File | `/dashboard/settings` | High
43 | File | `/dipam/athlete-profile.php` | High
44 | File | `/E-mobile/App/System/File/downfile.php` | High
45 | File | `/edoc/doctor/patient.php` | High
46 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
47 | File | `/etc/gsissh/sshd_config` | High
48 | File | `/etc/ldap.conf` | High
49 | File | `/etc/passwd` | Medium
50 | File | `/etc/shadow` | Medium
51 | File | `/face-recognition-php/facepay-master/camera.php` | High
52 | File | `/foms/place-order.php` | High
53 | File | `/forum/away.php` | High
54 | File | `/function/login.php` | High
55 | File | `/fusion/portal/action/Link` | High
56 | File | `/gadgets/definitions/uptime.CapacityWhatIfGadget/getmetrics.php` | High
57 | File | `/gadgets/definitions/uptime.CapacityWhatifGadget/getxenmetrics.php` | High
58 | File | `/goform/wizard_end` | High
59 | File | `/hrm/employeeview.php` | High
60 | File | `/index.php` | Medium
61 | File | `/index.php?app=main&func=passport&action=login` | High
62 | File | `/kelasdosen/data` | High
63 | ... | ... | ...

There are 554 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
