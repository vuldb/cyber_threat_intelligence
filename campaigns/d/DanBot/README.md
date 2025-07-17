# DanBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _DanBot_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with DanBot:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 18 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with DanBot or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lyceum](https://vuldb.com/?actor.lyceum) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of DanBot.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [62.113.196.37](https://vuldb.com/?ip.62.113.196.37) | aeroplan-redirect.online | [Lyceum](https://vuldb.com/?actor.lyceum) | High
2 | [62.113.207.181](https://vuldb.com/?ip.62.113.207.181) | - | [Lyceum](https://vuldb.com/?actor.lyceum) | High
3 | [75.87.185.45](https://vuldb.com/?ip.75.87.185.45) | cpe-75-87-185-45.kc.res.rr.com | [Lyceum](https://vuldb.com/?actor.lyceum) | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within DanBot. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during DanBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/act/ActDao.xml` | High
3 | File | `/add-students.php` | High
4 | File | `/admin.php?p=/Area/index#tab=t2` | High
5 | File | `/admin/` | Low
6 | File | `/admin/admin-update-employee.php` | High
7 | File | `/admin/booktime.php` | High
8 | File | `/admin/change-image.php` | High
9 | File | `/admin/index.php/web/ajax_all_lists` | High
10 | File | `/admin/login.php` | High
11 | File | `/admin/member_save.php` | High
12 | File | `/admin/return_add.php` | High
13 | File | `/admin/search-vehicle.php` | High
14 | File | `/admin/twitter.php` | High
15 | File | `/admin/view-enquiry.php` | High
16 | File | `/admin/voters_row.php` | High
17 | File | `/ajax.php?action=read_msg` | High
18 | File | `/api/authentication/login` | High
19 | File | `/api/clusters/local/topics/{topic}/messages` | High
20 | File | `/api/gen/clients/{language}` | High
21 | File | `/API/info` | Medium
22 | File | `/app/options.py` | High
23 | File | `/apply/index.php` | High
24 | File | `/bin/httpd` | Medium
25 | File | `/cgi-bin/cstecgi.cgi` | High
26 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
27 | File | `/cgi-bin/tosei_kikai.php` | High
28 | File | `/cgi-bin/wapopen` | High
29 | File | `/ci_spms/admin/category` | High
30 | File | `/ci_spms/admin/search/searching/` | High
31 | File | `/classes/Master.php?f=delete_appointment` | High
32 | File | `/classes/Master.php?f=delete_record` | High
33 | File | `/classes/Master.php?f=delete_train` | High
34 | File | `/cov/triggerEnvCov` | High
35 | File | `/ctcprotocol/Protocol` | High
36 | File | `/dashboard/admin/del_plan.php` | High
37 | File | `/dashboard/approve-reject.php` | High
38 | File | `/dashboard/menu-list.php` | High
39 | File | `/debug/pprof` | Medium
40 | File | `/dede/file_manage_control.php` | High
41 | File | `/detailed.php` | High
42 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
43 | File | `/dist/index.js` | High
44 | File | `/doctor/search.php` | High
45 | File | `/DXR.axd` | Medium
46 | File | `/ebics-server/ebics.aspx` | High
47 | File | `/ecommerce/popup_Item.php` | High
48 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
49 | File | `/empty_rooms.php` | High
50 | File | `/EXCU_SHELL` | Medium
51 | File | `/ffos/classes/Master.php?f=save_category` | High
52 | File | `/forum/away.php` | High
53 | File | `/general/address/private/address/query/delete.php` | High
54 | File | `/goform/ate` | Medium
55 | ... | ... | ...

There are 483 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.secureworks.com/blog/lyceum-takes-center-stage-in-middle-east-campaign

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
