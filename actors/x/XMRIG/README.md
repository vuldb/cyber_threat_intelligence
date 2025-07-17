# xmrig - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xmrig](https://vuldb.com/?actor.xmrig). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xmrig](https://vuldb.com/?actor.xmrig)

## Campaigns

The following _campaigns_ are known and can be associated with xmrig:

* CVE-2021-44228
* CVE-2025-31324
* SeleniumGreed

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xmrig:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [SH](https://vuldb.com/?country.sh)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xmrig.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.95.123.5](https://vuldb.com/?ip.23.95.123.5) | 23-95-123-5-host.colocrossing.com | CVE-2025-31324 | High
2 | [27.36.82.56](https://vuldb.com/?ip.27.36.82.56) | - | - | High
3 | [43.163.195.252](https://vuldb.com/?ip.43.163.195.252) | - | - | High
4 | [45.95.147.236](https://vuldb.com/?ip.45.95.147.236) | protect.privacy | - | High
5 | [45.138.16.193](https://vuldb.com/?ip.45.138.16.193) | - | - | High
6 | [47.109.69.229](https://vuldb.com/?ip.47.109.69.229) | - | - | High
7 | [51.195.211.231](https://vuldb.com/?ip.51.195.211.231) | ip231.ip-51-195-211.eu | - | High
8 | [59.36.188.253](https://vuldb.com/?ip.59.36.188.253) | - | - | High
9 | [77.105.147.158](https://vuldb.com/?ip.77.105.147.158) | square-jar.aeza.network | - | High
10 | ... | ... | ... | ...

There are 37 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xmrig_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-35, CWE-36, CWE-44 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xmrig. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/adfs/ls` | Medium
4 | File | `/admin-api/upload_image` | High
5 | File | `/admin.php?p=/Area/index#tab=t2` | High
6 | File | `/admin.php?page=album` | High
7 | File | `/Admin/add-admin.php` | High
8 | File | `/admin/add_ikev2.php` | High
9 | File | `/admin/admin_action.php` | High
10 | File | `/admin/admin_members.php?ac=search` | High
11 | File | `/admin/ajax.php?action=login` | High
12 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/js_data.php` | High
13 | File | `/admin/blood/update/B+.php` | High
14 | File | `/admin/category/view_category.php` | High
15 | File | `/admin/category_save.php` | High
16 | File | `/admin/cmsTemplate/replace` | High
17 | File | `/admin/content/editor` | High
18 | File | `/admin/customermanagementframework/customers/list` | High
19 | File | `/admin/deleteBooking.php` | High
20 | File | `/admin/emp-profile-avatar.php` | High
21 | File | `/admin/foreigner-search.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/index2.html` | High
24 | File | `/admin/list_ipAddressPolicy.php` | High
25 | File | `/admin/manage_model.php` | High
26 | File | `/admin/manage_user.php` | High
27 | File | `/admin/moneyRecord_deal.php?mudi=delRecord` | High
28 | File | `/admin/password-recovery.php` | High
29 | File | `/admin/print.php` | High
30 | File | `/admin/products/index.php` | High
31 | File | `/admin/registration.php` | High
32 | File | `/admin/search-report-details.php` | High
33 | File | `/admin/search-vehicle.php` | High
34 | File | `/admin/subject.php` | High
35 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
36 | File | `/admin/template` | High
37 | File | `/admin/twitter.php` | High
38 | File | `/admin/update_room.php` | High
39 | File | `/animalsupdate.php` | High
40 | File | `/api/admin/user?id` | High
41 | File | `/api/upload` | Medium
42 | File | `/api/v1/settings` | High
43 | File | `/api/v1/toolbox/device/update/swap` | High
44 | File | `/api/v2/maps` | Medium
45 | File | `/app/zentao/module/repo/model.php` | High
46 | File | `/backend/admin/his_admin_register_patient.php` | High
47 | File | `/bin/httpd` | Medium
48 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
49 | File | `/cgi-bin/cstecgi.cgi` | High
50 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
51 | File | `/cgi-bin/ExportSettings.sh` | High
52 | File | `/cgi-bin/photocenter_mgr.cgi` | High
53 | File | `/class/edit/edit` | High
54 | File | `/classes/Master.php` | High
55 | File | `/classes/Master.php?f=log_employee` | High
56 | File | `/classes/SystemSettings.php?f=update_settings` | High
57 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
58 | File | `/com/esafenet/servlet/policy/HookService.java` | High
59 | File | `/control/WANIPConnection` | High
60 | File | `/course.php` | Medium
61 | File | `/cov/triggerUnitCover` | High
62 | ... | ... | ...

There are 542 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/5fec2efb82df413ea934b2d1
* https://cybersecuritynews.com/sysrv-botnet-google-xmrig-spreader/
* https://en.fofa.info/result?qbase64=Ym9keT0iWE1SaWciICYmIHRpdGxlPT0iSW5kZXggb2YgLyI%3D&page=2&page_size=10
* https://search.censys.io/hosts/45.138.16.193
* https://search.censys.io/hosts/89.221.225.7
* https://search.censys.io/hosts/104.233.210.195
* https://search.censys.io/hosts/172.84.76.231
* https://search.censys.io/hosts/179.61.147.132
* https://search.censys.io/hosts/196.251.70.216
* https://search.censys.io/hosts/196.251.86.71
* https://search.censys.io/hosts/213.192.33.143
* https://threatfox.abuse.ch
* https://tria.ge/230707-zfx1zacf4s/behavioral1
* https://tria.ge/231117-r45rqabb9y
* https://urlhaus.abuse.ch/url/3186497/
* https://urlhaus.abuse.ch/url/3522756/
* https://urlhaus.abuse.ch/url/3547058/
* https://urlhaus.abuse.ch/url/3551023/
* https://urlhaus.abuse.ch/url/3555257/
* https://urlhaus.abuse.ch/url/3555767/
* https://urlhaus.abuse.ch/url/3569048/
* https://www.cadosecurity.com/containerised-clicks-malicious-use-of-9hits-on-vulnerable-docker-hosts/
* https://www.cyber45.com
* https://www.darktrace.com/blog/tracking-cve-2025-31324-darktraces-detection-of-sap-netweaver-exploitation-before-and-after-disclosure
* https://www.shodan.io/host/195.201.139.229
* https://www.uptycs.com/blog/log4j-campaign-xmrig-malware
* https://www.virustotal.com/gui/file/7f98872e415358424986167baac5c0bf3e729207b6a3562187ee89892f5a7fbc/relations
* https://www.wiz.io/blog/seleniumgreed-cryptomining-exploit-attack-flow-remediation-steps
* https://www.wiz.io/blog/wiz-research-identifies-exploitation-in-the-wild-of-aviatrix-cve-2024-50603
* https://x.com/orlof_v/status/1906650981674127671

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
