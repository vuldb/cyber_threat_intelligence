# UNC4841 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UNC4841](https://vuldb.com/?actor.unc4841). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.unc4841](https://vuldb.com/?actor.unc4841)

## Campaigns

The following _campaigns_ are known and can be associated with UNC4841:

* CVE-2023-2868

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UNC4841:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [KR](https://vuldb.com/?country.kr)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UNC4841.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.224.42.29](https://vuldb.com/?ip.23.224.42.29) | - | CVE-2023-2868 | High
2 | [23.224.78.130](https://vuldb.com/?ip.23.224.78.130) | - | CVE-2023-2868 | High
3 | [23.224.78.131](https://vuldb.com/?ip.23.224.78.131) | - | CVE-2023-2868 | High
4 | [23.224.78.132](https://vuldb.com/?ip.23.224.78.132) | - | CVE-2023-2868 | High
5 | [23.224.78.133](https://vuldb.com/?ip.23.224.78.133) | - | CVE-2023-2868 | High
6 | [23.224.78.134](https://vuldb.com/?ip.23.224.78.134) | - | CVE-2023-2868 | High
7 | [37.9.35.217](https://vuldb.com/?ip.37.9.35.217) | cdwk201570.example.com | CVE-2023-2868 | High
8 | [38.54.1.82](https://vuldb.com/?ip.38.54.1.82) | - | CVE-2023-2868 | High
9 | [38.54.113.205](https://vuldb.com/?ip.38.54.113.205) | - | CVE-2023-2868 | High
10 | [38.60.254.165](https://vuldb.com/?ip.38.60.254.165) | - | CVE-2023-2868 | High
11 | [45.63.76.67](https://vuldb.com/?ip.45.63.76.67) | 45.63.76.67.vultrusercontent.com | CVE-2023-2868 | High
12 | ... | ... | ... | ...

There are 43 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UNC4841_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UNC4841. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/link/link_mod.php` | High
2 | File | `/api/` | Low
3 | File | `/api/RecordingList/DownloadRecord?file=` | High
4 | File | `/api/sys/login` | High
5 | File | `/app/options.py` | High
6 | File | `/cgi-bin/wlogin.cgi` | High
7 | File | `/cgi/sshcheck.cgi` | High
8 | File | `/classes/Users.php?f=save` | High
9 | File | `/common/download?filename=1.jsp&delete=false` | High
10 | File | `/crmeb/crmeb/services/UploadService.php` | High
11 | File | `/debug/pprof` | Medium
12 | File | `/etc/postfix/sender_login` | High
13 | File | `/example/editor` | High
14 | File | `/filemanager/php/connector.php` | High
15 | File | `/filemanager/upload.php` | High
16 | File | `/forgetpassword.php` | High
17 | File | `/forum/away.php` | High
18 | File | `/home/www/cgi-bin/login.cgi` | High
19 | File | `/Items/*/RemoteImages/Download` | High
20 | File | `/items/view_item.php` | High
21 | File | `/librarian/bookdetails.php` | High
22 | File | `/mail/index.html` | High
23 | File | `/medical/inventories.php` | High
24 | File | `/modules/profile/index.php` | High
25 | File | `/out.php` | Medium
26 | File | `/php-jms/updateTxtview.php` | High
27 | File | `/proxy` | Low
28 | File | `/question.php` | High
29 | File | `/resources//../` | High
30 | File | `/RestAPI` | Medium
31 | File | `/start_apply.htm` | High
32 | File | `/student/bookdetails.php` | High
33 | File | `/templates/header.inc.php` | High
34 | File | `/user/getuserprofile` | High
35 | File | `/user/loader.php?api=1` | High
36 | ... | ... | ...

There are 307 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.mandiant.com/resources/blog/barracuda-esg-exploited-globally

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
