# APT29 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT29](https://vuldb.com/?actor.apt29). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt29](https://vuldb.com/?actor.apt29)

## Campaigns

The following _campaigns_ are known and can be associated with APT29:

* COVID-19
* PowerDuke
* StellarParticle
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT29:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 25 more country items available. Please use our online service to access the data.

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
7 | [31.170.107.186](https://vuldb.com/?ip.31.170.107.186) | ohra.supplrald.com | - | High
8 | [45.120.156.69](https://vuldb.com/?ip.45.120.156.69) | - | - | High
9 | [45.123.190.167](https://vuldb.com/?ip.45.123.190.167) | - | COVID-19 | High
10 | [45.123.190.168](https://vuldb.com/?ip.45.123.190.168) | - | - | High
11 | [45.129.229.48](https://vuldb.com/?ip.45.129.229.48) | - | COVID-19 | High
12 | [45.152.84.57](https://vuldb.com/?ip.45.152.84.57) | - | - | High
13 | [46.19.143.69](https://vuldb.com/?ip.46.19.143.69) | - | - | High
14 | [46.246.120.178](https://vuldb.com/?ip.46.246.120.178) | - | - | High
15 | [50.7.192.146](https://vuldb.com/?ip.50.7.192.146) | - | - | High
16 | [64.18.143.66](https://vuldb.com/?ip.64.18.143.66) | - | - | High
17 | [65.15.88.243](https://vuldb.com/?ip.65.15.88.243) | adsl-065-015-088-243.sip.asm.bellsouth.net | PowerDuke | High
18 | [66.29.115.55](https://vuldb.com/?ip.66.29.115.55) | 647807.ds.nac.net | - | High
19 | [66.70.247.215](https://vuldb.com/?ip.66.70.247.215) | ip215.ip-66-70-247.net | - | High
20 | [69.59.28.57](https://vuldb.com/?ip.69.59.28.57) | - | - | High
21 | [79.141.168.109](https://vuldb.com/?ip.79.141.168.109) | - | - | High
22 | ... | ... | ... | ...

There are 83 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT29_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT29. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?module=users&section=cpanel&page=list` | High
2 | File | `/admin/login.php` | High
3 | File | `/admin/powerline` | High
4 | File | `/admin/produts/controller.php` | High
5 | File | `/admin/syslog` | High
6 | File | `/admin/user/team` | High
7 | File | `/api/upload` | Medium
8 | File | `/cgi-bin` | Medium
9 | File | `/cgi-bin/kerbynet` | High
10 | File | `/cgi-bin/system_mgr.cgi` | High
11 | File | `/common/logViewer/logViewer.jsf` | High
12 | File | `/context/%2e/WEB-INF/web.xml` | High
13 | File | `/crmeb/app/admin/controller/store/CopyTaobao.php` | High
14 | File | `/dcim/sites/add/` | High
15 | File | `/fudforum/adm/hlplist.php` | High
16 | File | `/login` | Low
17 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
18 | File | `/monitoring` | Medium
19 | File | `/ms/cms/content/list.do` | High
20 | File | `/new` | Low
21 | File | `/orms/` | Low
22 | File | `/proc/<pid>/status` | High
23 | File | `/public/plugins/` | High
24 | File | `/rom` | Low
25 | File | `/scripts/killpvhost` | High
26 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
27 | File | `/secure/QueryComponent!Default.jspa` | High
28 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
29 | File | `/tmp` | Low
30 | File | `/tmp/redis.ds` | High
31 | File | `/uncpath/` | Medium
32 | File | `/wp-admin` | Medium
33 | File | `/wp-json/wc/v3/webhooks` | High
34 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
35 | File | `ABuffer.cpp` | Medium
36 | File | `AccountManagerService.java` | High
37 | File | `actions/CompanyDetailsSave.php` | High
38 | ... | ... | ...

There are 330 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog-assets.f-secure.com/wp-content/uploads/2020/03/18122307/F-Secure_Dukes_Whitepaper.pdf
* https://github.com/blackorbird/APT_REPORT/blob/master/International%20Strategic/Russia/Advisory-APT29-targets-COVID-19-vaccine-development.pdf
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
