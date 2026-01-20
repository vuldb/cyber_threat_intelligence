# ACR Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ACR Stealer](https://vuldb.com/?actor.acr_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.acr_stealer](https://vuldb.com/?actor.acr_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ACR Stealer:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ACR Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.179.202](https://vuldb.com/?ip.2.56.179.202) | vm4398840.example.com | - | High
2 | [5.78.68.46](https://vuldb.com/?ip.5.78.68.46) | static.46.68.78.5.clients.your-server.de | - | High
3 | [5.78.86.200](https://vuldb.com/?ip.5.78.86.200) | static.200.86.78.5.clients.your-server.de | - | High
4 | [5.161.82.163](https://vuldb.com/?ip.5.161.82.163) | static.163.82.161.5.clients.your-server.de | - | High
5 | [5.161.99.194](https://vuldb.com/?ip.5.161.99.194) | static.194.99.161.5.clients.your-server.de | - | High
6 | [5.161.111.91](https://vuldb.com/?ip.5.161.111.91) | static.91.111.161.5.clients.your-server.de | - | High
7 | [5.223.48.66](https://vuldb.com/?ip.5.223.48.66) | static.66.48.223.5.clients.your-server.de | - | High
8 | [5.223.62.246](https://vuldb.com/?ip.5.223.62.246) | static.246.62.223.5.clients.your-server.de | - | High
9 | [5.223.63.41](https://vuldb.com/?ip.5.223.63.41) | static.41.63.223.5.clients.your-server.de | - | High
10 | [5.223.75.1](https://vuldb.com/?ip.5.223.75.1) | static.1.75.223.5.clients.your-server.de | - | High
11 | [5.223.78.197](https://vuldb.com/?ip.5.223.78.197) | static.197.78.223.5.clients.your-server.de | - | High
12 | [37.27.9.21](https://vuldb.com/?ip.37.27.9.21) | static.21.9.27.37.clients.your-server.de | - | High
13 | [37.27.40.177](https://vuldb.com/?ip.37.27.40.177) | static.177.40.27.37.clients.your-server.de | - | High
14 | [45.95.232.57](https://vuldb.com/?ip.45.95.232.57) | 115745.ip-ptr.tech | - | High
15 | [45.144.29.250](https://vuldb.com/?ip.45.144.29.250) | vm4344963.example.com | - | High
16 | ... | ... | ... | ...

There are 58 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ACR Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ACR Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=recruit/resume/edit&op=status` | High
2 | File | `/admin/convert/export_z3950_new.php` | High
3 | File | `/admin/dashboard/profile` | High
4 | File | `/admin/edit-doc.php` | High
5 | File | `/admin/edit.php` | High
6 | File | `/admin/index3.php` | High
7 | File | `/admin/maintenance/view_designation.php` | High
8 | File | `/admin/manage_user.php` | High
9 | File | `/admin/return_add.php` | High
10 | File | `/admin/search-appointment.php` | High
11 | File | `/admin/sys_sql_query.php` | High
12 | File | `/admin/update-rooms.php` | High
13 | File | `/admin/user/uploadImg` | High
14 | File | `/admin/wlmultipleap.asp` | High
15 | File | `/admin_system/api.php` | High
16 | File | `/adms/classes/Users.php` | High
17 | File | `/api/admin/user/list` | High
18 | File | `/api/database` | High
19 | File | `/api/eventinstance` | High
20 | File | `/api/sys_msg/list/1/10` | High
21 | File | `/api/v1/chat.getThreadsList` | High
22 | File | `/api/v2/cli/commands` | High
23 | File | `/cgi-bin/cstecgi.cgi` | High
24 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
25 | File | `/cgi-bin/ExportLogs.sh` | High
26 | File | `/cgi-bin/koha/opac-MARCdetail.pl` | High
27 | File | `/cgi-bin/luci;stok=/locale` | High
28 | File | `/cgi-bin/mainfunction.cgi` | High
29 | File | `/cgi-bin/nas_sharing.cgi` | High
30 | File | `/cgi-bin/wapopen` | High
31 | File | `/cgi-bin/webproc` | High
32 | File | `/change-language/de_DE` | High
33 | File | `/classes/Master.php?f=save_inquiry` | High
34 | File | `/currentsetting.htm` | High
35 | File | `/databases/database/list` | High
36 | File | `/debug/pprof` | Medium
37 | File | `/devinfo` | Medium
38 | File | `/download.php?file=author.png` | High
39 | File | `/eduauth/student/search.php` | High
40 | File | `/env` | Low
41 | File | `/etc/fwupd/redfish.conf` | High
42 | File | `/etc/passwd` | Medium
43 | File | `/etc/shadow` | Medium
44 | File | `/export` | Low
45 | File | `/filex/read-raw` | High
46 | File | `/forum/away.php` | High
47 | File | `/goform/formSchedule` | High
48 | File | `/goform/formSetRoute` | High
49 | File | `/goform/formSetWanDhcpplus` | High
50 | File | `/goform/formWlanGuestSetup` | High
51 | File | `/hedwig.cgi` | Medium
52 | File | `/if.cgi` | Low
53 | File | `/ihomers/app` | Medium
54 | File | `/includes/common.inc.php` | High
55 | ... | ... | ...

There are 484 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/89128/
* https://bazaar.abuse.ch/browse/signature/ACRStealer/
* https://bazaar.abuse.ch/browse/tag/ACRStealer/
* https://bazaar.abuse.ch/sample/8753968482ef91fe499489d0d3e3add91fe90f49b98f347793e654da937edaeb/
* https://blog.sekoia.io/webdav-as-a-service-uncovering-the-infrastructure-behind-emmenhtal-loader-distribution/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
