# Phishing - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Phishing_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Phishing:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 23 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Phishing or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Nanocore](https://vuldb.com/?actor.nanocore) | High
3 | [NetWire](https://vuldb.com/?actor.netwire) | High
4 | ... | ...

There are 3 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Phishing.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.37.215.204](https://vuldb.com/?ip.3.37.215.204) | ec2-3-37-215-204.ap-northeast-2.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
2 | [16.162.223.161](https://vuldb.com/?ip.16.162.223.161) | ec2-16-162-223-161.ap-east-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
3 | [18.229.249.186](https://vuldb.com/?ip.18.229.249.186) | ec2-18-229-249-186.sa-east-1.compute.amazonaws.com | [Unknown](https://vuldb.com/?actor.unknown) | Medium
4 | [23.235.221.158](https://vuldb.com/?ip.23.235.221.158) | vps53141.inmotionhosting.com | [Nanocore](https://vuldb.com/?actor.nanocore) | High
5 | [45.76.84.233](https://vuldb.com/?ip.45.76.84.233) | 45.76.84.233.vultrusercontent.com | [Unknown](https://vuldb.com/?actor.unknown) | High
6 | ... | ... | ... | ...

There are 21 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Phishing. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Phishing. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/cgi-bin/wapopen` | High
3 | File | `/ClickAndBanexDemo/admin/admin.asp` | High
4 | File | `/concat?/%2557EB-INF/web.xml` | High
5 | File | `/configs/application.ini` | High
6 | File | `/context/%2e/WEB-INF/web.xml` | High
7 | File | `/etc/ajenti/config.yml` | High
8 | File | `/forum/away.php` | High
9 | File | `/goform/telnet` | High
10 | File | `/HNAP1` | Low
11 | File | `/iissamples/sdk/asp/interaction/Form_JScript.asp` | High
12 | File | `/iwgallery/admin/pictures_edit.asp` | High
13 | File | `/modules/profile/index.php` | High
14 | File | `/public/plugins/` | High
15 | File | `/replication` | Medium
16 | File | `/rom-0` | Low
17 | File | `/TeamMate/Upload/DomainObjectDocumentUpload.ashx` | High
18 | File | `/tmp/phpglibccheck` | High
19 | File | `/uncpath/` | Medium
20 | File | `/uploads/dede` | High
21 | File | `/var/tmp/sess_*` | High
22 | File | `/WEB-INF/web.xml` | High
23 | File | `AccessPoint.aspx` | High
24 | File | `actionphp/download.File.php` | High
25 | File | `activateuser.aspx` | High
26 | File | `adclick.php` | Medium
27 | File | `add_comment.php` | High
28 | File | `AdHocQuery_Processor.aspx` | High
29 | File | `admin` | Low
30 | File | `admin.asp` | Medium
31 | File | `admin/admin.asp` | High
32 | File | `admin/admin.php` | High
33 | File | `admin/content.php` | High
34 | File | `admin/gallery.php` | High
35 | File | `admin/images.aspx` | High
36 | File | `admin/index.php` | High
37 | File | `admin/index.php?id=users/action=edit/user_id=1` | High
38 | File | `admin/login.asp` | High
39 | File | `admin/manage-departments.php` | High
40 | File | `admin/sellerupd.php` | High
41 | File | `admin/sitesettings.php` | High
42 | File | `advsearch.asp` | High
43 | File | `AEAgent.cpp` | Medium
44 | File | `affich.php` | Medium
45 | File | `agent/Core/Controller/SendRequest.cpp` | High
46 | File | `ajax.php` | Medium
47 | File | `ajax_calls.php` | High
48 | File | `ajax_cmd.php` | Medium
49 | File | `album_portal.php` | High
50 | File | `appfeed.c` | Medium
51 | File | `ara.asp` | Low
52 | File | `aspx` | Low
53 | File | `auction_details.php` | High
54 | File | `auth.inc.php` | Medium
55 | File | `backend/utilities/terminal.js` | High
56 | File | `blocking.asp` | Medium
57 | File | `blueprints/sections/edit/1` | High
58 | ... | ... | ...

There are 503 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://community.riskiq.com/article/e3a7ceea/indicators
* https://ddanchev.blogspot.com/2008/02/inside-botnet-phishing-activities.html
* https://github.com/hvs-consulting/ioc_signatures/blob/main/M365_MFA_Phishing/HvS_M365_MFA_Phishing_2022-01_IOCs.csv
* https://nsfocusglobal.com/apt-retrospection-lorec53-an-active-russian-hack-group-launched-phishing-attacks-against-georgian-government/
* https://twitter.com/__0XYC__/status/1502593457201811459
* https://unit42.paloaltonetworks.com/nanocorerat-behind-an-increase-in-tax-themed-phishing-e-mails/
* https://us-cert.cisa.gov/ncas/alerts/aa20-225a
* https://www.fortinet.com/blog/threat-research/phishing-campaign-targeting-korean-to-deliver-agent-tesla-new-variant
* https://www.mandiant.com/resources/dissecting-netwire-phishing-campaigns-usage-process-hollowing

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
