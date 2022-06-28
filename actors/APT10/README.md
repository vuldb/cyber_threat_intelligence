# APT10 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT10](https://vuldb.com/?actor.apt10). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt10](https://vuldb.com/?actor.apt10)

## Campaigns

The following _campaigns_ are known and can be associated with APT10:

* A41APT
* Cache Panda
* Cloud Hopper

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT10:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT10.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.89.193.34](https://vuldb.com/?ip.23.89.193.34) | - | Cloud Hopper | High
2 | [23.110.64.147](https://vuldb.com/?ip.23.110.64.147) | - | Cloud Hopper | High
3 | [23.224.75.91](https://vuldb.com/?ip.23.224.75.91) | - | Cache Panda | High
4 | [23.224.75.93](https://vuldb.com/?ip.23.224.75.93) | - | Cache Panda | High
5 | [23.252.105.137](https://vuldb.com/?ip.23.252.105.137) | 23.252.105.137.16clouds.com | Cloud Hopper | High
6 | [27.102.66.67](https://vuldb.com/?ip.27.102.66.67) | - | - | High
7 | [27.102.115.249](https://vuldb.com/?ip.27.102.115.249) | - | - | High
8 | [27.102.127.75](https://vuldb.com/?ip.27.102.127.75) | - | - | High
9 | [27.102.127.80](https://vuldb.com/?ip.27.102.127.80) | - | - | High
10 | [27.102.128.157](https://vuldb.com/?ip.27.102.128.157) | - | - | High
11 | [31.184.197.215](https://vuldb.com/?ip.31.184.197.215) | 31-184-197-215.static.x5x-noc.ru | Cloud Hopper | High
12 | [31.184.197.227](https://vuldb.com/?ip.31.184.197.227) | 31-184-197-227.static.x5x-noc.ru | Cloud Hopper | High
13 | [31.184.198.23](https://vuldb.com/?ip.31.184.198.23) | - | Cloud Hopper | High
14 | [31.184.198.38](https://vuldb.com/?ip.31.184.198.38) | - | Cloud Hopper | High
15 | [37.187.7.74](https://vuldb.com/?ip.37.187.7.74) | ns3372567.ip-37-187-7.eu | Cloud Hopper | High
16 | [37.235.52.18](https://vuldb.com/?ip.37.235.52.18) | 18.52.235.37.in-addr.arpa | Cloud Hopper | High
17 | [38.72.112.45](https://vuldb.com/?ip.38.72.112.45) | - | Cloud Hopper | High
18 | [38.72.114.16](https://vuldb.com/?ip.38.72.114.16) | - | Cloud Hopper | High
19 | [38.72.115.9](https://vuldb.com/?ip.38.72.115.9) | - | Cloud Hopper | High
20 | [43.245.196.120](https://vuldb.com/?ip.43.245.196.120) | - | Cache Panda | High
21 | [43.245.196.121](https://vuldb.com/?ip.43.245.196.121) | - | Cache Panda | High
22 | [43.245.196.122](https://vuldb.com/?ip.43.245.196.122) | - | Cache Panda | High
23 | [43.245.196.123](https://vuldb.com/?ip.43.245.196.123) | - | Cache Panda | High
24 | [43.245.196.124](https://vuldb.com/?ip.43.245.196.124) | - | Cache Panda | High
25 | ... | ... | ... | ...

There are 98 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT10_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 3 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT10. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/../conf/config.properties` | High
2 | File | `/drivers/infiniband/core/cm.c` | High
3 | File | `/files.md5` | Medium
4 | File | `/forum/away.php` | High
5 | File | `/horde/util/go.php` | High
6 | File | `/images/` | Medium
7 | File | `/inc/parser/xhtml.php` | High
8 | File | `/login` | Low
9 | File | `/modules/profile/index.php` | High
10 | File | `/one_church/userregister.php` | High
11 | File | `/out.php` | Medium
12 | File | `/owa/auth/logon.aspx` | High
13 | File | `/public/plugins/` | High
14 | File | `/SAP_Information_System/controllers/add_admin.php` | High
15 | File | `/SASWebReportStudio/logonAndRender.do` | High
16 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
17 | File | `/secure/admin/ViewInstrumentation.jspa` | High
18 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
19 | File | `/system/proxy` | High
20 | File | `/tmp/phpglibccheck` | High
21 | File | `/uncpath/` | Medium
22 | File | `/v2/quantum/save-data-upload-big-file` | High
23 | File | `4.edu.php` | Medium
24 | File | `adclick.php` | Medium
25 | File | `add.php` | Low
26 | File | `addentry.php` | Medium
27 | File | `addressbookprovider.php` | High
28 | File | `admin.jcomments.php` | High
29 | File | `admin/pageUploadCSV.php` | High
30 | File | `ajax_udf.php` | Medium
31 | File | `AppCompatCache.exe` | High
32 | File | `application.js.php` | High
33 | ... | ... | ...

There are 277 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/janhenrikdotcom/iocs/blob/master/APT10/Operation%20Cloud%20Hopper%20-%20Indicators%20of%20Compromise%20v3.csv
* https://github.com/PwCUK-CTO/OperationCloudHopper/blob/master/cloud-hopper-indicators-of-compromise-v3.csv
* https://github.com/riduangan/APT10/blob/master/IOC
* https://medium.com/cycraft/supply-chain-attack-targeting-taiwan-financial-sector-bae2f0962934
* https://securelist.com/apt10-sophisticated-multi-layered-loader-ecipekac-discovered-in-a41apt-campaign/101519/
* https://www.fireeye.com/blog/threat-research/2018/09/apt10-targeting-japanese-corporations-using-updated-ttps.html
* https://www.threatminer.org/report.php?q=Accenture-Hogfish-Threat-Analysis.pdf&y=2018
* https://www.threatminer.org/report.php?q=cloud-hopper-indicators-of-compromise-v3-PwC.pdf&y=2017

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
