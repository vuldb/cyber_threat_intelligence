# Bl00dy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Bl00dy](https://vuldb.com/?actor.bl00dy). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bl00dy](https://vuldb.com/?actor.bl00dy)

## Campaigns

The following _campaigns_ are known and can be associated with Bl00dy:

* CVE-2023-27350
* CVE-2024-1708 / CVE-2024-1709

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bl00dy:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Bl00dy.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.18.233](https://vuldb.com/?ip.5.8.18.233) | - | CVE-2023-27350 | High
2 | [5.8.18.240](https://vuldb.com/?ip.5.8.18.240) | - | CVE-2023-27350 | High
3 | [5.188.206.14](https://vuldb.com/?ip.5.188.206.14) | - | CVE-2023-27350 | High
4 | [23.26.137.225](https://vuldb.com/?ip.23.26.137.225) | - | CVE-2024-1708 / CVE-2024-1709 | High
5 | ... | ... | ... | ...

There are 17 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Bl00dy_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bl00dy. This data is unique as it uses our predictive model for actor profiling.

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
10 | File | `/admin/index2.html` | High
11 | File | `/admin/login.php` | High
12 | File | `/admin/member_save.php` | High
13 | File | `/admin/search-vehicle.php` | High
14 | File | `/admin/voters_row.php` | High
15 | File | `/ajax.php?action=read_msg` | High
16 | File | `/api/authentication/login` | High
17 | File | `/api/baskets/{name}` | High
18 | File | `/api/clusters/local/topics/{topic}/messages` | High
19 | File | `/api/gen/clients/{language}` | High
20 | File | `/API/info` | Medium
21 | File | `/application/index/controller/Databasesource.php` | High
22 | File | `/bin/httpd` | Medium
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/cgi-bin/nas_sharing.cgi` | High
25 | File | `/cgi-bin/supervisor/adcommand.cgi` | High
26 | File | `/cgi-bin/tosei_kikai.php` | High
27 | File | `/cgi-bin/wapopen` | High
28 | File | `/classes/Master.php?f=delete_appointment` | High
29 | File | `/cov/triggerEnvCov` | High
30 | File | `/ctcprotocol/Protocol` | High
31 | File | `/dashboard/admin/del_plan.php` | High
32 | File | `/dashboard/approve-reject.php` | High
33 | File | `/dashboard/menu-list.php` | High
34 | File | `/debug/pprof` | Medium
35 | File | `/dede/file_manage_control.php` | High
36 | File | `/detailed.php` | High
37 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
38 | File | `/dist/index.js` | High
39 | File | `/doctor/search.php` | High
40 | File | `/DXR.axd` | Medium
41 | File | `/ebics-server/ebics.aspx` | High
42 | File | `/empty_rooms.php` | High
43 | File | `/EXCU_SHELL` | Medium
44 | File | `/ffos/classes/Master.php?f=save_category` | High
45 | File | `/forum/away.php` | High
46 | File | `/general/address/private/address/query/delete.php` | High
47 | File | `/goform/ate` | Medium
48 | File | `/goform/form2systime.cgi` | High
49 | File | `/goform/formSetLog` | High
50 | File | `/goform/formWlanSetup_Wizard` | High
51 | ... | ... | ...

There are 447 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-131a
* https://www.trendmicro.com/en_us/research/24/b/threat-actor-groups-including-black-basta-are-exploiting-recent-.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
