# PlugX - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _PlugX_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PlugX:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with PlugX or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TA459](https://vuldb.com/?actor.ta459) | High
2 | [PlugX](https://vuldb.com/?actor.plugx) | High
3 | [Mustang Panda](https://vuldb.com/?actor.mustang_panda) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PlugX.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [13.213.157.52](https://vuldb.com/?ip.13.213.157.52) | ec2-13-213-157-52.ap-southeast-1.compute.amazonaws.com | [PlugX](https://vuldb.com/?actor.plugx) | Medium
2 | [18.138.107.235](https://vuldb.com/?ip.18.138.107.235) | ec2-18-138-107-235.ap-southeast-1.compute.amazonaws.com | [PlugX](https://vuldb.com/?actor.plugx) | Medium
3 | [34.92.30.54](https://vuldb.com/?ip.34.92.30.54) | 54.30.92.34.bc.googleusercontent.com | [PlugX](https://vuldb.com/?actor.plugx) | Medium
4 | [34.96.224.146](https://vuldb.com/?ip.34.96.224.146) | 146.224.96.34.bc.googleusercontent.com | [PlugX](https://vuldb.com/?actor.plugx) | Medium
5 | [35.220.176.90](https://vuldb.com/?ip.35.220.176.90) | 90.176.220.35.bc.googleusercontent.com | [PlugX](https://vuldb.com/?actor.plugx) | Medium
6 | [35.220.214.142](https://vuldb.com/?ip.35.220.214.142) | 142.214.220.35.bc.googleusercontent.com | [PlugX](https://vuldb.com/?actor.plugx) | Medium
7 | [43.252.175.119](https://vuldb.com/?ip.43.252.175.119) | - | [TA459](https://vuldb.com/?actor.ta459) | High
8 | [45.32.125.79](https://vuldb.com/?ip.45.32.125.79) | manages.space | [PlugX](https://vuldb.com/?actor.plugx) | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within PlugX. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during PlugX. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$JENKINS_HOME/jenkins.security.RekeySecretAdminMonitor/backups` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin/` | Low
4 | File | `/admin/?/plugin/comment/settings` | High
5 | File | `/admin/ajax/file-browser/upload/` | High
6 | File | `/admin/index.php` | High
7 | File | `/api/filemanager` | High
8 | File | `/api/request/?OPERATION_NAME` | High
9 | File | `/api/trackedEntityInstances` | High
10 | File | `/apparel--accessories` | High
11 | File | `/apply_noauth.cgi` | High
12 | File | `/context/%2e/WEB-INF/web.xml` | High
13 | File | `/domains/index.fts` | High
14 | File | `/download` | Medium
15 | File | `/DroboAccess/delete_user` | High
16 | File | `/foundry/modules/news/newscolumns.php` | High
17 | File | `/ghost/preview` | High
18 | File | `/GponForm/device_Form?script/` | High
19 | File | `/LDMS/frm_splitfrm.aspx` | High
20 | File | `/media/api` | Medium
21 | File | `/member/test/points` | High
22 | File | `/modules/profile/index.php` | High
23 | File | `/Mum.Geo.Services/DataAccessService.svc` | High
24 | File | `/NAGErrors` | Medium
25 | File | `/port_3480` | Medium
26 | File | `/q` | Low
27 | File | `/secure/QueryComponent!Default.jspa` | High
28 | File | `/service-list` | High
29 | File | `/smstest.html` | High
30 | File | `/start-stop` | Medium
31 | File | `/tmp` | Low
32 | File | `/tmp/kamailio_fifo` | High
33 | File | `/tmp/scfgdndf` | High
34 | File | `/uncpath/` | Medium
35 | File | `/view/friend_profile.php` | High
36 | File | `/WEB-INF/web.xml` | High
37 | File | `/wp-json/oembed/1.0/embed?url` | High
38 | File | `AccessManagerCoreService.exe` | High
39 | File | `actions/authenticate.php` | High
40 | File | `actions/doreport.php` | High
41 | File | `addlyricsform.php` | High
42 | File | `addmerchpicform.php` | High
43 | ... | ... | ...

There are 372 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://twitter.com/0xrb/status/1469184108030955529
* https://twitter.com/0xrb/status/1470678183301181441
* https://twitter.com/0xrb/status/1478253942123347968
* https://twitter.com/0xrb/status/1482976719300890629
* https://twitter.com/0xrb/status/1484467191445475328
* https://twitter.com/xorhex/status/1406496693735067650
* https://twitter.com/xorhex/status/1422815329684758537
* https://www.threatminer.org/report.php?q=InPursuitofOpticalFibersandTroopIntel_TargetedAttackDistributesPlugXinRussia_Proofpoint.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
