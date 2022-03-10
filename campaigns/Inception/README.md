# Inception - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Inception_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Inception:

* [ES](https://vuldb.com/?country.es)
* [SV](https://vuldb.com/?country.sv)
* [DE](https://vuldb.com/?country.de)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Inception or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Inception](https://vuldb.com/?actor.inception) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Inception.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [51.255.139.194](https://vuldb.com/?ip.51.255.139.194) | ip194.ip-51-255-139.eu | [Inception](https://vuldb.com/?actor.inception) | High
2 | [82.221.100.55](https://vuldb.com/?ip.82.221.100.55) | web.a1yola.com | [Inception](https://vuldb.com/?actor.inception) | High
3 | [82.221.100.60](https://vuldb.com/?ip.82.221.100.60) | - | [Inception](https://vuldb.com/?actor.inception) | High
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used within Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/page_edit/3` | High
2 | File | `/api/notify.php` | High
3 | File | `/domain/service/.ewell-known/caldav` | High
4 | File | `/formAdvFirewall` | High
5 | File | `/mobile/SelectUsers.jsp` | High
6 | File | `/ProteinArraySignificanceTest.json` | High
7 | File | `/usr/local/bin/mjs` | High
8 | File | `/web` | Low
9 | File | `admin/bad.php` | High
10 | File | `admin/dl_sendmail.php` | High
11 | File | `admin/pages/useredit.php` | High
12 | File | `AdminBaseController.class.php` | High
13 | File | `AlertReceiver.java` | High
14 | File | `alfresco/s/admin/admin-nodebrowser` | High
15 | File | `AndroidFuture.java` | High
16 | File | `AndroidManifest.xml` | High
17 | File | `api/info.php` | Medium
18 | File | `attach.c` | Medium
19 | File | `box_code_apple.c` | High
20 | File | `bug_actiongroup.php` | High
21 | File | `bug_report_page.php` | High
22 | File | `cavsdec.c` | Medium
23 | ... | ... | ...

There are 192 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/interception
* https://securelist.com/recent-cloud-atlas-activity/92016/
* https://unit42.paloaltonetworks.com/unit42-inception-attackers-target-europe-year-old-office-vulnerability/
* https://www.threatminer.org/report.php?q=bcs_wp_InceptionReport_EN_v12914.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
