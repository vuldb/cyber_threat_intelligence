# MuddyWater - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MuddyWater](https://vuldb.com/?actor.muddywater). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.muddywater](https://vuldb.com/?actor.muddywater)

## Campaigns

The following _campaigns_ are known and can be associated with MuddyWater:

* BlackWater
* Ligolo
* Log4j
* ...

There are 2 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MuddyWater:

* [JP](https://vuldb.com/?country.jp)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MuddyWater.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.5.1.1](https://vuldb.com/?ip.1.5.1.1) | - | - | High
2 | [5.9.0.155](https://vuldb.com/?ip.5.9.0.155) | static.155.0.9.5.clients.your-server.de | - | High
3 | [5.199.133.149](https://vuldb.com/?ip.5.199.133.149) | ve958.venus.servdiscount-customer.com | - | High
4 | [7.236.212.22](https://vuldb.com/?ip.7.236.212.22) | - | - | High
5 | [31.171.154.67](https://vuldb.com/?ip.31.171.154.67) | - | Seedworm | High
6 | [38.132.99.167](https://vuldb.com/?ip.38.132.99.167) | - | BlackWater | High
7 | [45.142.212.61](https://vuldb.com/?ip.45.142.212.61) | vm218389.pq.hosting | - | High
8 | [45.142.213.17](https://vuldb.com/?ip.45.142.213.17) | vm218393.pq.hosting | - | High
9 | [45.153.231.104](https://vuldb.com/?ip.45.153.231.104) | vm218397.pq.hosting | - | High
10 | [46.99.148.96](https://vuldb.com/?ip.46.99.148.96) | - | Seedworm | High
11 | [46.166.129.159](https://vuldb.com/?ip.46.166.129.159) | gcn.warrirge.com | - | High
12 | [51.77.97.65](https://vuldb.com/?ip.51.77.97.65) | ip65.ip-51-77-97.eu | - | High
13 | [66.219.22.235](https://vuldb.com/?ip.66.219.22.235) | core96.hostingmadeeasy.com | - | High
14 | [78.129.139.131](https://vuldb.com/?ip.78.129.139.131) | - | - | High
15 | [78.129.139.134](https://vuldb.com/?ip.78.129.139.134) | der134.creditloanlenders.com | - | High
16 | [78.129.139.147](https://vuldb.com/?ip.78.129.139.147) | - | - | High
17 | [78.129.139.148](https://vuldb.com/?ip.78.129.139.148) | - | Seedworm | High
18 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MuddyWater_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MuddyWater. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `//` | Low
3 | File | `/admin/api/admin/articles/` | High
4 | File | `/admin/api/theme-edit/` | High
5 | File | `/api/audits` | Medium
6 | File | `/api/browserextension/UpdatePassword/` | High
7 | File | `/back/index.php/user/User/?1` | High
8 | File | `/calendar/viewcalendar.php` | High
9 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
10 | File | `/clients/listclients.php` | High
11 | File | `/cms/category/list` | High
12 | File | `/contacts/listcontacts.php` | High
13 | File | `/data/app` | Medium
14 | File | `/Default/Bd` | Medium
15 | File | `/DocSystem/Repos/getReposAllUsers.do` | High
16 | File | `/etc/sudoers` | Medium
17 | File | `/face-recognition-php/facepay-master/camera.php` | High
18 | File | `/forums/editforum.php` | High
19 | File | `/general/search.php?searchtype=simple` | High
20 | File | `/goform/fast_setting_wifi_set` | High
21 | File | `/goform/setDiagnoseInfo` | High
22 | File | `/goform/setMacFilterCfg` | High
23 | File | `/goform/setSnmpInfo` | High
24 | File | `/goform/setSysPwd` | High
25 | File | `/goform/setUplinkInfo` | High
26 | File | `/goform/SysToolRestoreSet` | High
27 | File | `/hrm/controller/employee.php` | High
28 | File | `/hrm/employeeadd.php` | High
29 | File | `/index.php?module=configuration/application` | High
30 | File | `/index.php?module=entities/fields&entities_id=24` | High
31 | File | `/linkedcontent/listfiles.php` | High
32 | File | `/m3_exec.h` | Medium
33 | File | `/meetings/listmeetings.php` | High
34 | File | `/opac/Actions.php?a=login` | High
35 | File | `/out.php` | Medium
36 | File | `/output/outdbg.c` | High
37 | File | `/output/outieee.c` | High
38 | File | `/password/reset` | High
39 | File | `/picturesPreview` | High
40 | File | `/projects/listprojects.php` | High
41 | File | `/services/Card/findUser` | High
42 | File | `/user/loader.php?api=1` | High
43 | File | `1.x/src/rogatkin/web/WarRoller.java` | High
44 | File | `AbstractScheduleJob.java` | High
45 | File | `admin/panels/uploader/admin.uploader.php` | High
46 | File | `admin/partials/ajax/add_field_to_form.php` | High
47 | File | `agent/listener/templates/tail.html` | High
48 | File | `ajax_represent.php` | High
49 | ... | ... | ...

There are 422 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/05/recent-muddywater-associated-blackwater.html
* https://blog.talosintelligence.com/2022/01/iranian-apt-muddywater-targets-turkey.html
* https://blog.talosintelligence.com/2022/03/iranian-supergroup-muddywater.html
* https://github.com/blackorbird/APT_REPORT/blob/master/muddywater/wp_new_muddywater_findings_uncovered.pdf
* https://reaqta.com/2017/11/muddywater-apt-targeting-middle-east/
* https://securelist.com/muddywater/88059/
* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/seedworm-espionage-group
* https://twitter.com/ShadowChasing1/status/1481621068255137794
* https://unit42.paloaltonetworks.com/unit42-muddying-the-water-targeted-attacks-in-the-middle-east/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-055a
* https://www.clearskysec.com/wp-content/uploads/2019/06/Clearsky-Iranian-APT-group-%E2%80%98MuddyWater%E2%80%99-Adds-Exploits-to-Their-Arsenal.pdf
* https://www.mandiant.com/resources/telegram-malware-iranian-espionage
* https://www.microsoft.com/security/blog/2022/08/25/mercury-leveraging-log4j-2-vulnerabilities-in-unpatched-systems-to-target-israeli-organizations/
* https://www.threatminer.org/_reports/2019/TheMuddyWatersofAPTAttacks-CheckPointResearch.pdf#viewer.action=download

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
