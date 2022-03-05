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
1 | [23.235.221.158](https://vuldb.com/?ip.23.235.221.158) | vps53141.inmotionhosting.com | [Nanocore](https://vuldb.com/?actor.nanocore) | High
2 | [45.146.165.91](https://vuldb.com/?ip.45.146.165.91) | - | [Lorec53](https://vuldb.com/?actor.lorec53) | High
3 | [69.174.99.181](https://vuldb.com/?ip.69.174.99.181) | unassigned.quadranet.com | [Agent Tesla](https://vuldb.com/?actor.agent_tesla) | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used within Phishing. This data is unique as it uses our predictive model for actor profiling.

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
8 | File | `/goform/telnet` | High
9 | File | `/HNAP1` | Low
10 | File | `/iissamples/sdk/asp/interaction/Form_JScript.asp` | High
11 | File | `/iwgallery/admin/pictures_edit.asp` | High
12 | File | `/modules/profile/index.php` | High
13 | File | `/public/plugins/` | High
14 | File | `/replication` | Medium
15 | File | `/rom-0` | Low
16 | File | `/TeamMate/Upload/DomainObjectDocumentUpload.ashx` | High
17 | File | `/tmp/phpglibccheck` | High
18 | File | `/uncpath/` | Medium
19 | File | `/uploads/dede` | High
20 | File | `/var/tmp/sess_*` | High
21 | File | `/WEB-INF/web.xml` | High
22 | File | `AccessPoint.aspx` | High
23 | File | `action.php` | Medium
24 | File | `actionphp/download.File.php` | High
25 | File | `activateuser.aspx` | High
26 | File | `add_comment.php` | High
27 | File | `AdHocQuery_Processor.aspx` | High
28 | File | `admin.asp` | Medium
29 | File | `admin/admin.asp` | High
30 | File | `admin/admin.php` | High
31 | File | `admin/content.php` | High
32 | File | `admin/gallery.php` | High
33 | File | `admin/images.aspx` | High
34 | File | `admin/index.php` | High
35 | File | `admin/index.php?id=users/action=edit/user_id=1` | High
36 | File | `admin/login.asp` | High
37 | File | `admin/manage-departments.php` | High
38 | File | `admin/sellerupd.php` | High
39 | File | `admin/sitesettings.php` | High
40 | File | `advsearch.asp` | High
41 | File | `AEAgent.cpp` | Medium
42 | File | `affich.php` | Medium
43 | File | `agent/Core/Controller/SendRequest.cpp` | High
44 | File | `ajax.php` | Medium
45 | File | `ajax_calls.php` | High
46 | File | `ajax_cmd.php` | Medium
47 | File | `album_portal.php` | High
48 | File | `apache-auth.conf` | High
49 | File | `appfeed.c` | Medium
50 | File | `ara.asp` | Low
51 | File | `askapache-firefox-adsense.php` | High
52 | File | `aspx` | Low
53 | File | `auction_details.php` | High
54 | File | `auth.inc.php` | Medium
55 | File | `backend/utilities/terminal.js` | High
56 | File | `blocking.asp` | Medium
57 | ... | ... | ...

There are 494 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://community.riskiq.com/article/e3a7ceea/indicators
* https://github.com/hvs-consulting/ioc_signatures/blob/main/M365_MFA_Phishing/HvS_M365_MFA_Phishing_2022-01_IOCs.csv
* https://nsfocusglobal.com/apt-retrospection-lorec53-an-active-russian-hack-group-launched-phishing-attacks-against-georgian-government/
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
