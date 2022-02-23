# APT10 - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT10](https://vuldb.com/?actor.apt10). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt10](https://vuldb.com/?actor.apt10)

## Campaigns

The following _campaigns_ are known and can be associated with APT10:

* A41APT
* Cloud Hopper

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT10:

* US
* RU
* DE
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT10.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 23.89.193.34 | - | Cloud Hopper | High
2 | 23.110.64.147 | - | Cloud Hopper | High
3 | 23.252.105.137 | 23.252.105.137.16clouds.com | Cloud Hopper | High
4 | 27.102.66.67 | - | - | High
5 | 27.102.115.249 | - | - | High
6 | 27.102.127.75 | - | - | High
7 | 27.102.127.80 | - | - | High
8 | 27.102.128.157 | - | - | High
9 | 31.184.197.215 | 31-184-197-215.static.x5x-noc.ru | Cloud Hopper | High
10 | 31.184.197.227 | 31-184-197-227.static.x5x-noc.ru | Cloud Hopper | High
11 | 31.184.198.23 | - | Cloud Hopper | High
12 | 31.184.198.38 | - | Cloud Hopper | High
13 | 37.187.7.74 | ns3372567.ip-37-187-7.eu | Cloud Hopper | High
14 | 37.235.52.18 | 18.52.235.37.in-addr.arpa | Cloud Hopper | High
15 | 38.72.112.45 | - | Cloud Hopper | High
16 | 38.72.114.16 | - | Cloud Hopper | High
17 | 38.72.115.9 | - | Cloud Hopper | High
18 | 45.62.112.161 | 45.62.112.161.16clouds.com | Cloud Hopper | High
19 | 45.138.157.83 | google.com.tm | A41APT | High
20 | 46.108.39.134 | - | Cloud Hopper | High
21 | 50.2.160.104 | - | Cloud Hopper | High
22 | 52.74.71.131 | ec2-52-74-71-131.ap-southeast-1.compute.amazonaws.com | Cloud Hopper | Medium
23 | 52.74.213.16 | ec2-52-74-213-16.ap-southeast-1.compute.amazonaws.com | Cloud Hopper | Medium
24 | ... | ... | ... | ...

There are 91 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by APT10. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT10. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htpasswd` | Medium
2 | File | `/../conf/config.properties` | High
3 | File | `/drivers/infiniband/core/cm.c` | High
4 | File | `/forum/away.php` | High
5 | File | `/horde/util/go.php` | High
6 | File | `/images/` | Medium
7 | File | `/inc/parser/xhtml.php` | High
8 | File | `/login` | Low
9 | File | `/mgmt/shared/authz/users/` | High
10 | File | `/modules/profile/index.php` | High
11 | File | `/out.php` | Medium
12 | File | `/public/plugins/` | High
13 | File | `/secure/admin/ViewInstrumentation.jspa` | High
14 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
15 | File | `/system/proxy` | High
16 | File | `/tmp/phpglibccheck` | High
17 | File | `/uncpath/` | Medium
18 | File | `adclick.php` | Medium
19 | File | `add.php` | Low
20 | File | `addentry.php` | Medium
21 | File | `addressbookprovider.php` | High
22 | File | `admin/htaccess/bpsunlock.php` | High
23 | File | `admin/pageUploadCSV.php` | High
24 | File | `ajax_udf.php` | Medium
25 | File | `application.js.php` | High
26 | File | `apply.cgi` | Medium
27 | File | `arm/lithium-codegen-arm.cc` | High
28 | File | `authenticate.c` | High
29 | File | `Authenticate.class.php` | High
30 | File | `base_maintenance.php` | High
31 | File | `booking_details.php` | High
32 | ... | ... | ...

There are 277 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/janhenrikdotcom/iocs/blob/master/APT10/Operation%20Cloud%20Hopper%20-%20Indicators%20of%20Compromise%20v3.csv
* https://github.com/PwCUK-CTO/OperationCloudHopper/blob/master/cloud-hopper-indicators-of-compromise-v3.csv
* https://github.com/riduangan/APT10/blob/master/IOC
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
