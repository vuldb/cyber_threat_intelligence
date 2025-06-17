# PTI-249 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [PTI-249](https://vuldb.com/?actor.pti-249). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pti-249](https://vuldb.com/?actor.pti-249)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PTI-249:

* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PTI-249.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.161.16.233](https://vuldb.com/?ip.5.161.16.233) | static.233.16.161.5.clients.your-server.de | - | High
2 | [5.161.16.237](https://vuldb.com/?ip.5.161.16.237) | static.237.16.161.5.clients.your-server.de | - | High
3 | [5.161.16.251](https://vuldb.com/?ip.5.161.16.251) | static.251.16.161.5.clients.your-server.de | - | High
4 | [5.161.17.7](https://vuldb.com/?ip.5.161.17.7) | static.7.17.161.5.clients.your-server.de | - | High
5 | [5.161.17.9](https://vuldb.com/?ip.5.161.17.9) | static.9.17.161.5.clients.your-server.de | - | High
6 | [5.161.23.93](https://vuldb.com/?ip.5.161.23.93) | static.93.23.161.5.clients.your-server.de | - | High
7 | [5.161.23.201](https://vuldb.com/?ip.5.161.23.201) | static.201.23.161.5.clients.your-server.de | - | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PTI-249_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 25 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PTI-249. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.dbshell` | Medium
2 | File | `/advance_push/public/login` | High
3 | File | `/bin/boa` | Medium
4 | File | `/bsms_ci/index.php/user/edit_user/` | High
5 | File | `/cgi-bin/nobody/VerifyCode.cgi` | High
6 | File | `/common/download_agent_installer.php` | High
7 | File | `/ControlManager/cgi-bin/VA/isaNVWRequest.dll` | High
8 | File | `/DataHandler/Handler_CFG.ashx` | High
9 | File | `/DocSystem/Repos/getReposAllUsers.do` | High
10 | File | `/dus/fotos_grafiken/index.php` | High
11 | File | `/ext/phar/phar_object.c` | High
12 | File | `/file-manager/upload.php` | High
13 | File | `/forum/away.php` | High
14 | File | `/goform/GetNewDir` | High
15 | File | `/HNAP1` | Low
16 | File | `/index.php?menu=asterisk_cli` | High
17 | File | `/modules/eligibility/Student.php` | High
18 | File | `/modules/profile/index.php` | High
19 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
20 | File | `/out.php` | Medium
21 | File | `/owa/auth/logon.aspx` | High
22 | File | `/proc/self/environ` | High
23 | File | `/proc/timer_list` | High
24 | File | `/public/plugins/` | High
25 | File | `/spip.php` | Medium
26 | File | `/student-grading-system/rms.php?page=student_p&amp` | High
27 | File | `/student/bookdetails.php` | High
28 | File | `/templates/default/html/windows/right.php` | High
29 | File | `/uncpath/` | Medium
30 | File | `/usr/bin/gxserve-update.sh` | High
31 | File | `/usr/local/www/csrf/csrf-magic.php` | High
32 | File | `/var/db/sudo/lectured` | High
33 | File | `/var/log/postgresql` | High
34 | File | `/var/log/sanlock.log` | High
35 | File | `/vendor/htmlawed/htmlawed/htmLawedTest.php` | High
36 | File | `/web/` | Low
37 | File | `/webman/info.cgi` | High
38 | File | `/Websquare/likeClickComment/` | High
39 | File | `/wp-admin/options-general.php` | High
40 | File | `/_vti_pvt/access.cnf` | High
41 | File | `4.2.0.CP06` | Medium
42 | File | `102/tcp` | Low
43 | File | `acl.c` | Low
44 | File | `actionphp/download.File.php` | High
45 | File | `adclick.php` | Medium
46 | ... | ... | ...

There are 397 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/b1312c87c1b9de8b519e8416fa819cef04cea004/PTI-249

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
