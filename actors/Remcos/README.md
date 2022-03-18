# Remcos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Remcos](https://vuldb.com/?actor.remcos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.remcos](https://vuldb.com/?actor.remcos)

## Campaigns

The following _campaigns_ are known and can be associated with Remcos:

* Ukraine

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Remcos:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Remcos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.37.41](https://vuldb.com/?ip.5.61.37.41) | - | - | High
2 | [5.181.234.139](https://vuldb.com/?ip.5.181.234.139) | - | - | High
3 | [5.181.234.145](https://vuldb.com/?ip.5.181.234.145) | - | - | High
4 | [8.253.139.120](https://vuldb.com/?ip.8.253.139.120) | - | - | High
5 | [13.107.42.12](https://vuldb.com/?ip.13.107.42.12) | 1drv.ms | - | High
6 | [13.107.43.13](https://vuldb.com/?ip.13.107.43.13) | - | - | High
7 | [13.225.230.20](https://vuldb.com/?ip.13.225.230.20) | server-13-225-230-20.jfk51.r.cloudfront.net | - | High
8 | [13.250.255.10](https://vuldb.com/?ip.13.250.255.10) | ec2-13-250-255-10.ap-southeast-1.compute.amazonaws.com | - | Medium
9 | [15.197.142.173](https://vuldb.com/?ip.15.197.142.173) | a4ec4c6ea1c92e2e6.awsglobalaccelerator.com | - | High
10 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
11 | [20.42.73.27](https://vuldb.com/?ip.20.42.73.27) | - | - | High
12 | [20.190.151.7](https://vuldb.com/?ip.20.190.151.7) | - | - | High
13 | [20.190.151.8](https://vuldb.com/?ip.20.190.151.8) | - | - | High
14 | [20.190.151.68](https://vuldb.com/?ip.20.190.151.68) | - | - | High
15 | [20.190.151.70](https://vuldb.com/?ip.20.190.151.70) | - | - | High
16 | [20.190.151.131](https://vuldb.com/?ip.20.190.151.131) | - | - | High
17 | [20.190.151.132](https://vuldb.com/?ip.20.190.151.132) | - | - | High
18 | [20.190.151.133](https://vuldb.com/?ip.20.190.151.133) | - | - | High
19 | [20.190.152.21](https://vuldb.com/?ip.20.190.152.21) | - | - | High
20 | [20.190.154.139](https://vuldb.com/?ip.20.190.154.139) | - | - | High
21 | [23.3.13.88](https://vuldb.com/?ip.23.3.13.88) | a23-3-13-88.deploy.static.akamaitechnologies.com | - | High
22 | [23.21.27.29](https://vuldb.com/?ip.23.21.27.29) | ec2-23-21-27-29.compute-1.amazonaws.com | - | Medium
23 | [23.21.205.229](https://vuldb.com/?ip.23.21.205.229) | ec2-23-21-205-229.compute-1.amazonaws.com | - | Medium
24 | [23.38.131.139](https://vuldb.com/?ip.23.38.131.139) | a23-38-131-139.deploy.static.akamaitechnologies.com | - | High
25 | [23.78.173.83](https://vuldb.com/?ip.23.78.173.83) | a23-78-173-83.deploy.static.akamaitechnologies.com | - | High
26 | [23.199.63.11](https://vuldb.com/?ip.23.199.63.11) | a23-199-63-11.deploy.static.akamaitechnologies.com | - | High
27 | [23.199.63.83](https://vuldb.com/?ip.23.199.63.83) | a23-199-63-83.deploy.static.akamaitechnologies.com | - | High
28 | [23.227.38.74](https://vuldb.com/?ip.23.227.38.74) | - | - | High
29 | [34.96.116.138](https://vuldb.com/?ip.34.96.116.138) | 138.116.96.34.bc.googleusercontent.com | - | Medium
30 | [34.102.136.180](https://vuldb.com/?ip.34.102.136.180) | 180.136.102.34.bc.googleusercontent.com | - | Medium
31 | ... | ... | ... | ...

There are 119 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Remcos_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Remcos. This data is unique as it uses our predictive model for actor profiling.

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
13 | File | `/SASWebReportStudio/logonAndRender.do` | High
14 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
15 | File | `/secure/admin/ViewInstrumentation.jspa` | High
16 | File | `/system/proxy` | High
17 | File | `/tmp/phpglibccheck` | High
18 | File | `adclick.php` | Medium
19 | File | `add.php` | Low
20 | File | `addentry.php` | Medium
21 | File | `addressbookprovider.php` | High
22 | File | `admin/pageUploadCSV.php` | High
23 | File | `ajax_udf.php` | Medium
24 | File | `AppCompatCache.exe` | High
25 | File | `application.js.php` | High
26 | File | `apply.cgi` | Medium
27 | File | `arm/lithium-codegen-arm.cc` | High
28 | File | `authenticate.c` | High
29 | File | `Authenticate.class.php` | High
30 | File | `base_maintenance.php` | High
31 | ... | ... | ...

There are 259 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/02/threat-roundup-0219-0226.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0226-0305.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0730-0806.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0806-0813.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0813-0820.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0827-0903.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0910-0917.html
* https://blog.talosintelligence.com/2021/09/threat-roundup-0917-0924.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-0924-1001.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1008-1015.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1015-1022.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1022-1029.html
* https://blog.talosintelligence.com/2021/11/threat-roundup-1112-1119.html
* https://blog.talosintelligence.com/2022/01/threat-roundup-1231-0107.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0211-0218.html
* https://blog.talosintelligence.com/2022/03/ukraine-invasion-scams-malware.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
