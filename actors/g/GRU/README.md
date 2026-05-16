# GRU - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GRU](https://vuldb.com/?actor.gru). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gru](https://vuldb.com/?actor.gru)

## Campaigns

The following _campaigns_ are known and can be associated with GRU:

* Critical Infrastructure
* Western Logistics Entities and Technology Companies

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GRU:

* [US](https://vuldb.com/?country.us)
* [PL](https://vuldb.com/?country.pl)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GRU.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.42.4.138](https://vuldb.com/?ip.31.42.4.138) | 31.42.4.138.alfanet24.pl | Western Logistics Entities and Technology Companies | High
2 | [31.135.199.145](https://vuldb.com/?ip.31.135.199.145) | client-145.home.subnet-199.nat.dynamic.home-net.pl | Western Logistics Entities and Technology Companies | High
3 | [46.112.70.252](https://vuldb.com/?ip.46.112.70.252) | user-46-112-70-252.play-internet.pl | Western Logistics Entities and Technology Companies | High
4 | [46.248.185.236](https://vuldb.com/?ip.46.248.185.236) | 46-248-185-236.rev.iq.pl | Western Logistics Entities and Technology Companies | High
5 | [64.176.67.117](https://vuldb.com/?ip.64.176.67.117) | 64.176.67.117.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
6 | [64.176.69.196](https://vuldb.com/?ip.64.176.69.196) | 64.176.69.196.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
7 | [64.176.70.18](https://vuldb.com/?ip.64.176.70.18) | 64.176.70.18.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
8 | [64.176.70.238](https://vuldb.com/?ip.64.176.70.238) | 64.176.70.238.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
9 | [64.176.71.201](https://vuldb.com/?ip.64.176.71.201) | 64.176.71.201.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
10 | [70.34.242.220](https://vuldb.com/?ip.70.34.242.220) | 70.34.242.220.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
11 | [70.34.243.226](https://vuldb.com/?ip.70.34.243.226) | 70.34.243.226.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
12 | [70.34.244.100](https://vuldb.com/?ip.70.34.244.100) | 70.34.244.100.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
13 | [70.34.245.215](https://vuldb.com/?ip.70.34.245.215) | 70.34.245.215.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
14 | [70.34.252.168](https://vuldb.com/?ip.70.34.252.168) | 70.34.252.168.vultrusercontent.com | Western Logistics Entities and Technology Companies | Medium
15 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GRU_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GRU. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/actuator` | Medium
3 | File | `/add-subadmin.php` | High
4 | File | `/addmem.php` | Medium
5 | File | `/addProduct.php` | High
6 | File | `/admin/?page=system_info` | High
7 | File | `/admin/?page=zone` | High
8 | File | `/admin/aboutus.php` | High
9 | File | `/admin/actions/check-attendance.php` | High
10 | File | `/admin/activity.php` | High
11 | File | `/admin/add-table.php` | High
12 | File | `/admin/admin_running.php` | High
13 | File | `/admin/changeimage.php` | High
14 | File | `/Admin/changepassword.php` | High
15 | File | `/admin/completed-requests.php` | High
16 | File | `/admin/delete_activity.php` | High
17 | File | `/admin/delete_s6.php` | High
18 | File | `/admin/delete_student.php` | High
19 | File | `/admin/delete_user.php` | High
20 | File | `/admin/edit-art-product-detail.php?editid=2` | High
21 | File | `/admin/edit-user.php` | High
22 | File | `/admin/editsite.php` | High
23 | File | `/admin/edit_room.php` | High
24 | File | `/admin/expenses.php` | High
25 | File | `/admin/fetch_product_details.php` | High
26 | File | `/admin/includes/edit_post.php` | High
27 | File | `/admin/index.php` | High
28 | File | `/admin/index.php?page=user-profile` | High
29 | File | `/Admin/login.php` | High
30 | File | `/admin/login.php` | High
31 | File | `/admin/login_query.php` | High
32 | File | `/admin/mechanics/manage_mechanic.php` | High
33 | File | `/admin/modules/lesson/index.php` | High
34 | File | `/admin/modules/room/index.php` | High
35 | File | `/admin/quesadd.php` | High
36 | File | `/admin/system/structure/getdirectorydata/web/baseinfo/companyManage` | High
37 | File | `/admin/tags/save` | High
38 | File | `/admin/user-bookings.php` | High
39 | File | `/admin/user/index.php?view=edit` | High
40 | File | `/admin/view-member-report.php` | High
41 | File | `/admin/yesterday-reg-users.php` | High
42 | File | `/adminapi/system/file/openfile` | High
43 | File | `/administrator/addcategory.php` | High
44 | File | `/Administrator/PHP/AdminAddUser.php` | High
45 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
46 | File | `/ajax.php?action=save_payroll` | High
47 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
48 | File | `/alphaware/summary.php` | High
49 | File | `/api/File/downloadFile` | High
50 | File | `/api/jobs` | Medium
51 | File | `/api/settings` | High
52 | File | `/api/sys/login` | High
53 | File | `/api/v1/settings` | High
54 | File | `/api/wizard/getCapability` | High
55 | File | `/app/api/controller/collect.php` | High
56 | File | `/app/api/v1/openvpn.py` | High
57 | File | `/app/checkout/delete.php` | High
58 | File | `/app/controller/Api.php` | High
59 | File | `/app/register.php?action=reg` | High
60 | File | `/app/sys1.php` | High
61 | File | `/assetsGroupReport/assetsService.j%73p` | High
62 | File | `/auth.asp` | Medium
63 | File | `/BBfile/Blood/o+.php` | High
64 | File | `/bin/goahead` | Medium
65 | File | `/bin/httpd` | Medium
66 | File | `/binutils/debug.c` | High
67 | File | `/biurl_grou` | Medium
68 | File | `/blog/bContent/save` | High
69 | File | `/boaform/formSysCmd` | High
70 | File | `/boafrm/formDMZ` | High
71 | File | `/boafrm/formIpQoS` | High
72 | File | `/boafrm/formTmultiAP` | High
73 | File | `/borrow.php` | Medium
74 | File | `/browse.php` | Medium
75 | File | `/cart/update/attr` | High
76 | File | `/cgi-bin/adm.cgi` | High
77 | File | `/cgi-bin/cstecgi.cgi` | High
78 | File | `/cgi-bin/ExportIbmsConfig.sh` | High
79 | File | `/cgi-bin/firewall.cgi` | High
80 | File | `/cgi-bin/imode_alldata.php` | High
81 | File | `/cgi-bin/login.cgi` | High
82 | File | `/cgi-bin/nas_sharing.cgi` | High
83 | ... | ... | ...

There are 728 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://media.defense.gov/2021/Jul/01/2002753896/-1/-1/1/CSA_GRU_GLOBAL_BRUTE_FORCE_CAMPAIGN_UOO158036-21.PDF
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-141a
* https://www.picussecurity.com/resource/blog/cisa-alert-aa24-249a-russian-military-cyber-actors-target-us-and-global-critical-infrastructure

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
