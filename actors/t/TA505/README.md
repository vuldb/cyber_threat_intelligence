# TA505 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TA505](https://vuldb.com/?actor.ta505). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ta505](https://vuldb.com/?actor.ta505)

## Campaigns

The following _campaigns_ are known and can be associated with TA505:

* Ammyy
* SDBbot
* servhelper
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TA505:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TA505.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.149.252.171](https://vuldb.com/?ip.5.149.252.171) | absolutecorporation.info | SDBbot | High
2 | [5.149.254.25](https://vuldb.com/?ip.5.149.254.25) | bmc.srv60.swdc.ams1.nl.fortunix.net | - | High
3 | [27.102.118.143](https://vuldb.com/?ip.27.102.118.143) | - | - | High
4 | [37.59.52.229](https://vuldb.com/?ip.37.59.52.229) | bemta-05.srv.sopeople.net | SDBbot | High
5 | [37.252.8.63](https://vuldb.com/?ip.37.252.8.63) | - | - | High
6 | [45.8.126.7](https://vuldb.com/?ip.45.8.126.7) | mail01.bivoic.com | SDBbot | High
7 | [45.63.101.210](https://vuldb.com/?ip.45.63.101.210) | 45.63.101.210.vultr.com | servhelper | Medium
8 | [45.76.206.149](https://vuldb.com/?ip.45.76.206.149) | 45.76.206.149.vultr.com | - | Medium
9 | [45.76.223.177](https://vuldb.com/?ip.45.76.223.177) | 45.76.223.177.vultr.com | - | Medium
10 | [45.77.16.211](https://vuldb.com/?ip.45.77.16.211) | 45.77.16.211.vultr.com | - | Medium
11 | [45.129.137.237](https://vuldb.com/?ip.45.129.137.237) | - | - | High
12 | [45.142.213.139](https://vuldb.com/?ip.45.142.213.139) | jorrygo1.example.com | - | High
13 | [45.142.214.119](https://vuldb.com/?ip.45.142.214.119) | vm293088.pq.hosting | - | High
14 | [46.161.27.241](https://vuldb.com/?ip.46.161.27.241) | - | Servhelper/Flawedgrace | High
15 | [66.42.45.55](https://vuldb.com/?ip.66.42.45.55) | 66.42.45.55.vultr.com | - | Medium
16 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA505_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA505. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/actuator/heapdump` | High
3 | File | `/admin/action/update-deworm.php` | High
4 | File | `/admin/add-services.php` | High
5 | File | `/admin/add_postlogin.php` | High
6 | File | `/admin/add_visitor.php` | High
7 | File | `/admin/admin.php` | High
8 | File | `/admin/adminHome.php` | High
9 | File | `/admin/admin_user.php` | High
10 | File | `/admin/ajax.php?action=save_area` | High
11 | File | `/admin/applicants/controller.php` | High
12 | File | `/admin/booking-search.php` | High
13 | File | `/admin/category/view_category.php` | High
14 | File | `/admin/company/index.php` | High
15 | File | `/admin/course.php` | High
16 | File | `/admin/del_service.php` | High
17 | File | `/admin/departments/manage_department.php` | High
18 | File | `/admin/div_data/delete?divId=9` | High
19 | File | `/admin/employee/controller.php` | High
20 | File | `/admin/index.php?page=categories` | High
21 | File | `/admin/login.php` | High
22 | File | `/admin/mod_room/controller.php?action=add` | High
23 | File | `/admin/reportupload.aspx` | High
24 | File | `/admin/search.php` | High
25 | File | `/admin/singlelogin.php` | High
26 | File | `/admin/sys_sql_query.php` | High
27 | File | `/adminPage/main/upload` | High
28 | File | `/admin_class.php` | High
29 | File | `/admin_ping.htm` | High
30 | File | `/ample/app/action/edit_product.php` | High
31 | File | `/api/` | Low
32 | File | `/api/clusters/local/topics/{topic}/messages` | High
33 | File | `/api/discoveries/` | High
34 | File | `/api/plugin/uninstall` | High
35 | File | `/api/RecordingList/DownloadRecord?file=` | High
36 | File | `/api/sys/login` | High
37 | File | `/api/test/download` | High
38 | File | `/app/sys1.php` | High
39 | File | `/application/index/controller/File.php` | High
40 | File | `/apply.cgi` | Medium
41 | File | `/apply/index.php` | High
42 | File | `/assets/php/upload.php` | High
43 | File | `/audimex/cgi-bin/wal.fcgi` | High
44 | File | `/auth_pic.cgi` | High
45 | File | `/blog` | Low
46 | File | `/boaform/device_reset.cgi` | High
47 | File | `/boafrm/formMapDelDevice` | High
48 | File | `/cgi-bin-sdb/` | High
49 | File | `/cgi-bin-sdb/ExportSettings.sh` | High
50 | File | `/cgi-bin/adm.cgi` | High
51 | File | `/cgi-bin/cstecgi.cgi` | High
52 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
53 | File | `/cgi-bin/nas_sharing.cgi` | High
54 | File | `/cgi-bin/wlogin.cgi` | High
55 | File | `/checkout` | Medium
56 | File | `/classes/Master.php?f=save_inquiry` | High
57 | File | `/classes/SystemSettings.php?f=update_settings` | High
58 | File | `/classes/Users.php?f=save` | High
59 | File | `/cms/classes/Users.php?f=delete_client` | High
60 | File | `/collection/all` | High
61 | File | `/controller/company/Index.php#sendCompanyLogo` | High
62 | File | `/crmeb/crmeb/services/UploadService.php` | High
63 | File | `/dashboard/createblog` | High
64 | File | `/debug/pprof` | Medium
65 | File | `/Default/Bd` | Medium
66 | File | `/dipam/athlete-profile.php` | High
67 | File | `/dosen/data` | Medium
68 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
69 | File | `/Employee/apply_leave.php` | High
70 | File | `/Employee/edit-profile.php` | High
71 | File | `/employee_gatepass/admin/?page=employee/manage_employee` | High
72 | File | `/etc/pki/pesign` | High
73 | File | `/etc/postfix/sender_login` | High
74 | File | `/etc/puppetlabs/puppetserver/conf.d/ca.conf` | High
75 | File | `/file-manager/rename.php` | High
76 | ... | ... | ...

There are 666 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.fox-it.com/2021/12/02/tracking-a-p2p-network-related-to-ta505/
* https://cyble.com/blog/rms-tools-sneaky-comeback-phishing-campaign-mirroring-banned-applications/
* https://documents.trendmicro.com/assets/TA505_tactics_HTML_RATs_techniques_latest_campaigns_appendix.pdf
* https://securityintelligence.com/posts/ta505-continues-to-infect-networks-with-sdbbot-rat/
* https://www.cybereason.com/blog/threat-actor-ta505-targets-financial-enterprises-using-lolbins-and-a-new-backdoor-malware
* https://www.deepinstinct.com/2019/04/02/new-servhelper-variant-employs-excel-4-0-macro-to-drop-signed-payload/
* https://www.proofpoint.com/us/threat-insight/post/leaked-ammyy-admin-source-code-turned-malware
* https://www.proofpoint.com/us/threat-insight/post/servhelper-and-flawedgrace-new-malware-introduced-ta505
* https://www.proofpoint.com/us/threat-insight/post/ta505-distributes-new-sdbbot-remote-access-trojan-get2-downloader
* https://www.ptsecurity.com/ww-en/analytics/pt-esc-threat-intelligence/operation-ta505-part2/
* https://www.ptsecurity.com/ww-en/analytics/pt-esc-threat-intelligence/operation-ta505-part3/
* https://www.zerofox.com/blog/ta505-halloween-malware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
