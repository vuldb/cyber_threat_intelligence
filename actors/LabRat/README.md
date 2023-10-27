# LabRat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LabRat](https://vuldb.com/?actor.labrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.labrat](https://vuldb.com/?actor.labrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LabRat:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LabRat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.234.16.54](https://vuldb.com/?ip.1.234.16.54) | - | - | High
2 | [23.94.204.157](https://vuldb.com/?ip.23.94.204.157) | 23-94-204-157-host.colocrossing.com | - | High
3 | [107.173.154.7](https://vuldb.com/?ip.107.173.154.7) | 107-173-154-7-host.colocrossing.com | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LabRat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LabRat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/academy/home/courses` | High
2 | File | `/admin/adclass.php` | High
3 | File | `/admin/admin-profile.php` | High
4 | File | `/admin/sales/view_details.php` | High
5 | File | `/admin/students/view_details.php` | High
6 | File | `/ajax-files/followBoard.php` | High
7 | File | `/ajax.php?action=read_msg` | High
8 | File | `/api/cron/settings/setJob/` | High
9 | File | `/api/v1/snapshots` | High
10 | File | `/api/v1/terminal/sessions/?limit=1` | High
11 | File | `/audit/log/log_management.php` | High
12 | File | `/auth/callback` | High
13 | File | `/authenticationendpoint/login.do` | High
14 | File | `/cgi-bin/mainfunction.cgi` | High
15 | File | `/cgi-bin/wlogin.cgi` | High
16 | File | `/cgi.cgi` | Medium
17 | File | `/classes/Users.php` | High
18 | File | `/collection/all` | High
19 | File | `/Content/Template/root/reverse-shell.aspx` | High
20 | File | `/ctcprotocol/Protocol` | High
21 | File | `/dottie.js` | Medium
22 | File | `/DXR.axd` | Medium
23 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
24 | File | `/env` | Low
25 | File | `/files/` | Low
26 | File | `/forms/doLogin` | High
27 | File | `/forum/away.php` | High
28 | File | `/goform/setportList` | High
29 | File | `/h/autoSaveDraft` | High
30 | File | `/index.php` | Medium
31 | File | `/index.php?p=admin/actions/users/send-password-reset-email` | High
32 | File | `/index.php?page=member` | High
33 | File | `/jurusanmatkul/data` | High
34 | File | `/librarian/bookdetails.php` | High
35 | File | `/log/decodmail.php` | High
36 | File | `/log/webmailattach.php` | High
37 | File | `/login.php?do=login` | High
38 | File | `/php-opos/index.php` | High
39 | File | `/public/login.htm` | High
40 | File | `/QueryView.php` | High
41 | File | `/recreate.php` | High
42 | ... | ... | ...

There are 362 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://sysdig.com/blog/labrat-cryptojacking-proxyjacking-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
