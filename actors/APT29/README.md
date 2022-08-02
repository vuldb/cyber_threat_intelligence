# APT29 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT29](https://vuldb.com/?actor.apt29). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt29](https://vuldb.com/?actor.apt29)

## Campaigns

The following _campaigns_ are known and can be associated with APT29:

* Cobalt Strike
* COVID-19
* PowerDuke
* ...

There are 2 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT29:

* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT29.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.66.134](https://vuldb.com/?ip.5.45.66.134) | - | - | High
2 | [5.199.174.164](https://vuldb.com/?ip.5.199.174.164) | - | - | High
3 | [23.29.115.180](https://vuldb.com/?ip.23.29.115.180) | 23-29-115-180.static.hvvc.us | StellarParticle | High
4 | [23.82.128.144](https://vuldb.com/?ip.23.82.128.144) | - | StellarParticle | High
5 | [27.102.130.115](https://vuldb.com/?ip.27.102.130.115) | - | - | High
6 | [31.7.63.141](https://vuldb.com/?ip.31.7.63.141) | game.bignamegamereviewz.com | - | High
7 | [31.31.74.79](https://vuldb.com/?ip.31.31.74.79) | - | Cobalt Strike | High
8 | [31.170.107.186](https://vuldb.com/?ip.31.170.107.186) | ohra.supplrald.com | - | High
9 | [45.120.156.69](https://vuldb.com/?ip.45.120.156.69) | - | - | High
10 | [45.123.190.167](https://vuldb.com/?ip.45.123.190.167) | - | COVID-19 | High
11 | [45.123.190.168](https://vuldb.com/?ip.45.123.190.168) | - | - | High
12 | [45.129.229.48](https://vuldb.com/?ip.45.129.229.48) | - | COVID-19 | High
13 | [45.152.84.57](https://vuldb.com/?ip.45.152.84.57) | - | - | High
14 | [46.19.143.69](https://vuldb.com/?ip.46.19.143.69) | - | - | High
15 | [46.246.120.178](https://vuldb.com/?ip.46.246.120.178) | - | - | High
16 | [50.7.192.146](https://vuldb.com/?ip.50.7.192.146) | - | - | High
17 | [64.18.143.66](https://vuldb.com/?ip.64.18.143.66) | - | - | High
18 | [65.15.88.243](https://vuldb.com/?ip.65.15.88.243) | adsl-065-015-088-243.sip.asm.bellsouth.net | PowerDuke | High
19 | [66.29.115.55](https://vuldb.com/?ip.66.29.115.55) | 647807.ds.nac.net | - | High
20 | [66.70.247.215](https://vuldb.com/?ip.66.70.247.215) | ip215.ip-66-70-247.net | - | High
21 | [69.59.28.57](https://vuldb.com/?ip.69.59.28.57) | - | - | High
22 | ... | ... | ... | ...

There are 85 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT29_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT29. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/admin/?page=system_info/contact_info` | High
3 | File | `/admin/dl_sendmail.php` | High
4 | File | `/admin/login.php` | High
5 | File | `/Ap4RtpAtom.cpp` | High
6 | File | `/app/options.py` | High
7 | File | `/bcms/admin/?page=user/list` | High
8 | File | `/bsms/?page=manage_account` | High
9 | File | `/cgi-bin/login.cgi` | High
10 | File | `/ci_hms/massage_room/edit/1` | High
11 | File | `/context/%2e/WEB-INF/web.xml` | High
12 | File | `/dashboard/reports/logs/view` | High
13 | File | `/debug/pprof` | Medium
14 | File | `/etc/hosts` | Medium
15 | File | `/fuel/index.php/fuel/logs/items` | High
16 | File | `/fuel/sitevariables/delete/4` | High
17 | File | `/goform/aspForm` | High
18 | File | `/hocms/classes/Master.php?f=delete_collection` | High
19 | File | `/hprms/admin/doctors/manage_doctor.php` | High
20 | File | `/index/jobfairol/show/` | High
21 | File | `/librarian/bookdetails.php` | High
22 | File | `/mgmt/tm/util/bash` | High
23 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
24 | File | `/ms/cms/content/list.do` | High
25 | File | `/orms/` | Low
26 | File | `/plesk-site-preview/` | High
27 | File | `/proc/<PID>/mem` | High
28 | File | `/proc/<pid>/status` | High
29 | File | `/public/plugins/` | High
30 | File | `/school/model/get_admin_profile.php` | High
31 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
32 | File | `/secure/QueryComponent!Default.jspa` | High
33 | ... | ... | ...

There are 280 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog-assets.f-secure.com/wp-content/uploads/2020/03/18122307/F-Secure_Dukes_Whitepaper.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/International%20Strategic/Russia/Advisory-APT29-targets-COVID-19-vaccine-development.pdf
* https://unit42.paloaltonetworks.com/cloaked-ursa-online-storage-services-campaigns/
* https://us-cert.cisa.gov/ncas/alerts/aa21-148a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar20-198c
* https://www.crowdstrike.com/blog/observations-from-the-stellarparticle-campaign/
* https://www.microsoft.com/security/blog/2018/12/03/analysis-of-cyberattack-on-u-s-think-tanks-non-profits-public-sector-by-unidentified-attackers/
* https://www.ncsc.gov.uk/files/Advisory-APT29-targets-COVID-19-vaccine-development-V1-1.pdf
* https://www.volexity.com/blog/2016/11/09/powerduke-post-election-spear-phishing-campaigns-targeting-think-tanks-and-ngos/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
