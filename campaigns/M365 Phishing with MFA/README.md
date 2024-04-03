# M365 Phishing with MFA - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _M365 Phishing with MFA_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with M365 Phishing with MFA:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 21 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with M365 Phishing with MFA or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of M365 Phishing with MFA.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [85.203.46.65](https://vuldb.com/?ip.85.203.46.65) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [85.203.46.213](https://vuldb.com/?ip.85.203.46.213) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [185.192.71.57](https://vuldb.com/?ip.185.192.71.57) | - | [Unknown](https://vuldb.com/?actor.unknown) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within M365 Phishing with MFA. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during M365 Phishing with MFA. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/ClickAndBanexDemo/admin/admin.asp` | High
3 | File | `/configs/application.ini` | High
4 | File | `/HNAP1` | Low
5 | File | `/iissamples/sdk/asp/interaction/Form_JScript.asp` | High
6 | File | `/index.php` | Medium
7 | File | `/iwgallery/admin/pictures_edit.asp` | High
8 | File | `/jmreport/loadTableData` | High
9 | File | `/lists/index.php` | High
10 | File | `/mail/index.html` | High
11 | File | `/okm:root` | Medium
12 | File | `/public/plugins/` | High
13 | File | `/replication` | Medium
14 | File | `/TeamMate/Upload/DomainObjectDocumentUpload.ashx` | High
15 | File | `/uncpath/` | Medium
16 | File | `/uploads/dede` | High
17 | File | `/WEB-INF/web.xml` | High
18 | File | `/wp-json/oembed/1.0/embed?url` | High
19 | File | `AccessPoint.aspx` | High
20 | File | `activateuser.aspx` | High
21 | File | `AdHocQuery_Processor.aspx` | High
22 | File | `admin.asp` | Medium
23 | File | `admin/admin.asp` | High
24 | File | `admin/images.aspx` | High
25 | File | `admin/index.php` | High
26 | File | `admin/login.asp` | High
27 | File | `advsearch.asp` | High
28 | File | `AEAgent.cpp` | Medium
29 | File | `ajax.php` | Medium
30 | File | `ajax_calls.php` | High
31 | File | `ajax_cmd.php` | Medium
32 | File | `allmanageup.pl` | High
33 | File | `appfeed.c` | Medium
34 | File | `appointment.php` | High
35 | File | `ara.asp` | Low
36 | ... | ... | ...

There are 312 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/hvs-consulting/ioc_signatures/blob/main/M365_MFA_Phishing/HvS_M365_MFA_Phishing_2022-01_IOCs.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
