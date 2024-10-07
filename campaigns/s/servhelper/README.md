# servhelper - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _servhelper_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with servhelper:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with servhelper or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TA505](https://vuldb.com/?actor.ta505) | High
2 | [ServHelper](https://vuldb.com/?actor.servhelper) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of servhelper.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.181.156.79](https://vuldb.com/?ip.5.181.156.79) | 5-181-156-79.mivocloud.com | [ServHelper](https://vuldb.com/?actor.servhelper) | High
2 | [5.181.156.250](https://vuldb.com/?ip.5.181.156.250) | no-rdns.mivocloud.com | [ServHelper](https://vuldb.com/?actor.servhelper) | High
3 | [45.63.101.210](https://vuldb.com/?ip.45.63.101.210) | 45.63.101.210.vultr.com | [TA505](https://vuldb.com/?actor.ta505) | Medium
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within servhelper. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during servhelper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/admin/admin_login.php` | High
3 | File | `/api/addusers` | High
4 | File | `/api/RecordingList/DownloadRecord?file=` | High
5 | File | `/apply.cgi` | Medium
6 | File | `/cgi-bin/cstecgi.cgi` | High
7 | File | `/debug/pprof` | Medium
8 | File | `/dus/shopliste/index.php` | High
9 | File | `/etc/path` | Medium
10 | File | `/hrm/employeeadd.php` | High
11 | File | `/licenses` | Medium
12 | File | `/login` | Low
13 | File | `/nagiosql/admin/checkcommands.php` | High
14 | File | `/OA_HTML/cabo/jsps/a.jsp` | High
15 | File | `/php/ping.php` | High
16 | File | `/public/login.htm` | High
17 | File | `/rapi/read_url` | High
18 | File | `/scripts/unlock_tasks.php` | High
19 | File | `/sendKey` | Medium
20 | File | `/setSystemAdmin` | High
21 | File | `/signup_script.php` | High
22 | File | `/SysInfo1.htm` | High
23 | File | `/sysinfo_json.cgi` | High
24 | File | `/system/dictData/loadDictItem` | High
25 | File | `/system/user/modules/mod_users/controller.php` | High
26 | File | `/tmp` | Low
27 | File | `/type.php` | Medium
28 | File | `/uncpath/` | Medium
29 | File | `/usr/5bin/su` | Medium
30 | File | `/usr/bin/mail` | High
31 | File | `/var/dt/` | Medium
32 | File | `/view-property.php` | High
33 | File | `/view/vpn/autovpn/sub_commit.php` | High
34 | File | `/wp-admin/admin-post.php?es_skip=1&option_name` | High
35 | File | `/_vti_bin/_vti_log` | High
36 | File | `00.jsp` | Low
37 | File | `adclick.php` | Medium
38 | File | `admin.asp` | Medium
39 | File | `admin.php` | Medium
40 | File | `admin/` | Low
41 | File | `admin/Login.php` | High
42 | File | `admin/manage-comments.php` | High
43 | File | `Administration/Controllers/ImportController.cs` | High
44 | File | `administrator/mail/download.cfm` | High
45 | File | `AdminViewError/AdminAddadmin` | High
46 | ... | ... | ...

There are 395 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://bazaar.abuse.ch/sample/58514fa7288607858aae17799ded4bb96d5f9b78733ad1ca2cece597d5516d44/
* https://bazaar.abuse.ch/sample/bac78c78e97c8458437ffcbb31b4a54a141200a8cb656eac2dcab06691bc4a91/
* https://bazaar.abuse.ch/sample/be31a5c1391bbc1c62d8f2c9fbebb9147ba69371fd8e7fcf81fcb5a9ac6ddf73/
* https://bazaar.abuse.ch/sample/d53c9d7349bdbee8f73709c263cb08c2ca721365bb0670993b81fe2fd9200bac/
* https://bazaar.abuse.ch/sample/d6372afdd18503ab17f18ebec05254727c7a0377d425bc74e4ae12ffe6243c4c/
* https://bazaar.abuse.ch/sample/f60f32ec899bcb92fd50491a8c32f0548afbd4dc02462dfa373d484b4b161a86/
* https://threatfox.abuse.ch
* https://www.deepinstinct.com/2019/04/02/new-servhelper-variant-employs-excel-4-0-macro-to-drop-signed-payload/
* https://www.proofpoint.com/us/threat-insight/post/servhelper-and-flawedgrace-new-malware-introduced-ta505

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
