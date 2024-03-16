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
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 29 more country items available. Please use our online service to access the data.

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
15 | ... | ... | ... | ...

There are 57 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA505_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-37 | Path Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA505. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/admin/action/update-deworm.php` | High
3 | File | `/admin/add-services.php` | High
4 | File | `/admin/ajax.php?action=save_area` | High
5 | File | `/admin/del_service.php` | High
6 | File | `/admin/departments/manage_department.php` | High
7 | File | `/admin/reportupload.aspx` | High
8 | File | `/admin/sys_sql_query.php` | High
9 | File | `/admin_ping.htm` | High
10 | File | `/ample/app/action/edit_product.php` | High
11 | File | `/api/` | Low
12 | File | `/api/clusters/local/topics/{topic}/messages` | High
13 | File | `/api/plugin/uninstall` | High
14 | File | `/api/RecordingList/DownloadRecord?file=` | High
15 | File | `/api/sys/login` | High
16 | File | `/app/sys1.php` | High
17 | File | `/application/index/controller/File.php` | High
18 | File | `/apply.cgi` | Medium
19 | File | `/apply/index.php` | High
20 | File | `/assets/php/upload.php` | High
21 | File | `/audimex/cgi-bin/wal.fcgi` | High
22 | File | `/auth_pic.cgi` | High
23 | File | `/blog` | Low
24 | File | `/boaform/device_reset.cgi` | High
25 | File | `/cgi-bin-sdb/` | High
26 | File | `/cgi-bin-sdb/ExportSettings.sh` | High
27 | File | `/cgi-bin/adm.cgi` | High
28 | File | `/cgi-bin/cstecgi.cgi` | High
29 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
30 | File | `/cgi-bin/wlogin.cgi` | High
31 | File | `/classes/Master.php?f=save_inquiry` | High
32 | File | `/classes/Users.php?f=save` | High
33 | File | `/collection/all` | High
34 | File | `/common/ticket_associated_tickets.php` | High
35 | File | `/crmeb/crmeb/services/UploadService.php` | High
36 | File | `/dashboard/createblog` | High
37 | File | `/debug/pprof` | Medium
38 | File | `/dipam/athlete-profile.php` | High
39 | File | `/dosen/data` | Medium
40 | File | `/Duty/AjaxHandle/Write/UploadFile.ashx` | High
41 | File | `/etc/pki/pesign` | High
42 | File | `/etc/postfix/sender_login` | High
43 | File | `/etc/puppetlabs/puppetserver/conf.d/ca.conf` | High
44 | File | `/file-manager/rename.php` | High
45 | File | `/filex/proxy-download` | High
46 | File | `/home/filter_listings` | High
47 | File | `/hrm/employeeadd.php` | High
48 | File | `/im/user/` | Medium
49 | File | `/include/chart_generator.php` | High
50 | File | `/include/file.php` | High
51 | File | `/index.php` | Medium
52 | File | `/index.php?pluginApp/to/yzOffice/getFile` | High
53 | File | `/jeecg-boot/jmreport/upload` | High
54 | File | `/jeecg-boot/sys/common/upload` | High
55 | File | `/listplace/user/ticket/create` | High
56 | File | `/LoginRegistration.php` | High
57 | File | `/mgmt/tm/util/bash` | High
58 | File | `/modules/profile/index.php` | High
59 | File | `/out.php` | Medium
60 | File | `/pages/long_s_short.php` | High
61 | ... | ... | ...

There are 529 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.fox-it.com/2021/12/02/tracking-a-p2p-network-related-to-ta505/
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
