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

There are 15 more country items available. Please use our online service to access the data.

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
12 | [66.219.22.235](https://vuldb.com/?ip.66.219.22.235) | core96.hostingmadeeasy.com | - | High
13 | [78.129.139.134](https://vuldb.com/?ip.78.129.139.134) | der134.creditloanlenders.com | - | High
14 | [78.129.139.147](https://vuldb.com/?ip.78.129.139.147) | - | - | High
15 | ... | ... | ... | ...

There are 56 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MuddyWater_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MuddyWater. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\CheckPoint\ZoneAlarm\Data\Updates` | High
2 | File | `/admin/add_exercises.php` | High
3 | File | `/admin/add_trainers.php` | High
4 | File | `/admin/edit.php` | High
5 | File | `/admin/settings/fields` | High
6 | File | `/admin/students/view_student.php` | High
7 | File | `/api/v1/chat.getThreadsList` | High
8 | File | `/api/v1/user` | Medium
9 | File | `/bd_genie_create_account.cgi` | High
10 | File | `/bin/boa` | Medium
11 | File | `/buspassms/download-pass.php` | High
12 | File | `/carbon/mediation_secure_vault/properties/ajaxprocessor.jsp` | High
13 | File | `/carbon/ndatasource/validateconnection/ajaxprocessor.jsp` | High
14 | File | `/cgi-bin/DownloadFlash` | High
15 | File | `/claire_blake` | High
16 | File | `/cnr` | Low
17 | File | `/dashboard/add-portfolio.php` | High
18 | File | `/dashboard/add-service.php` | High
19 | File | `/dashboard/settings` | High
20 | File | `/dashboard/updatelogo.php` | High
21 | File | `/DesignTools/CssEditor.aspx` | High
22 | File | `/ebics-server/ebics.aspx` | High
23 | File | `/etc/networkd-dispatcher` | High
24 | File | `/etc/shadow.sample` | High
25 | File | `/etc/version` | Medium
26 | File | `/fw.login.php` | High
27 | File | `/gasmark/assets/myimages/oneWord.php` | High
28 | File | `/git-prereceive-callback` | High
29 | File | `/goform/addRouting` | High
30 | File | `/goform/Diagnosis` | High
31 | File | `/goform/expandDlnaFile` | High
32 | File | `/goform/fast_setting_wifi_set` | High
33 | File | `/goform/form2userconfig.cgi` | High
34 | File | `/goform/NatStaticSetting` | High
35 | File | `/goform/NTPSyncWithHost` | High
36 | File | `/goform/openSchedWifi/` | High
37 | ... | ... | ...

There are 321 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/05/recent-muddywater-associated-blackwater.html
* https://blog.talosintelligence.com/2022/01/iranian-apt-muddywater-targets-turkey.html
* https://blog.talosintelligence.com/2022/03/iranian-supergroup-muddywater.html
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

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
