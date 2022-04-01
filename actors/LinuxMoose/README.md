# LinuxMoose - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LinuxMoose](https://vuldb.com/?actor.linuxmoose). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.linuxmoose](https://vuldb.com/?actor.linuxmoose)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LinuxMoose:

* [NL](https://vuldb.com/?country.nl)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LinuxMoose.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.124.41.11](https://vuldb.com/?ip.27.124.41.11) | - | - | High
2 | [27.124.41.31](https://vuldb.com/?ip.27.124.41.31) | - | - | High
3 | [27.124.41.33](https://vuldb.com/?ip.27.124.41.33) | - | - | High
4 | [27.124.41.52](https://vuldb.com/?ip.27.124.41.52) | - | - | High
5 | [42.119.173.138](https://vuldb.com/?ip.42.119.173.138) | - | - | High
6 | [62.210.6.34](https://vuldb.com/?ip.62.210.6.34) | 62-210-6-34.rev.poneytelecom.eu | - | High
7 | [77.247.177.31](https://vuldb.com/?ip.77.247.177.31) | - | - | High
8 | [77.247.177.36](https://vuldb.com/?ip.77.247.177.36) | - | - | High
9 | [77.247.177.87](https://vuldb.com/?ip.77.247.177.87) | - | - | High
10 | [77.247.178.177](https://vuldb.com/?ip.77.247.178.177) | - | - | High
11 | [79.176.26.142](https://vuldb.com/?ip.79.176.26.142) | bzq-79-176-26-142.red.bezeqint.net | - | High
12 | [82.146.63.15](https://vuldb.com/?ip.82.146.63.15) | ebay2.com | - | High
13 | [85.159.237.0](https://vuldb.com/?ip.85.159.237.0) | - | - | High
14 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LinuxMoose_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LinuxMoose. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/?module=users&section=cpanel&page=list` | High
4 | File | `/context/%2e/WEB-INF/web.xml` | High
5 | File | `/file?action=download&file` | High
6 | File | `/include/chart_generator.php` | High
7 | File | `/monitoring` | Medium
8 | File | `/new` | Low
9 | File | `/plugins/servlet/audit/resource` | High
10 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
11 | File | `/proc/<pid>/status` | High
12 | File | `/public/plugins/` | High
13 | File | `/replication` | Medium
14 | File | `/rest/api/1.0/render` | High
15 | File | `/RestAPI` | Medium
16 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
17 | File | `/secure/QueryComponent!Default.jspa` | High
18 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
19 | File | `/tmp` | Low
20 | File | `/trx_addons/v2/get/sc_layout` | High
21 | File | `/uncpath/` | Medium
22 | File | `/var/log/nginx` | High
23 | File | `/wp-json/wc/v3/webhooks` | High
24 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
25 | File | `AccountManagerService.java` | High
26 | File | `actions/CompanyDetailsSave.php` | High
27 | File | `ActiveServices.java` | High
28 | File | `ActivityManagerService.java` | High
29 | File | `admin.php` | Medium
30 | ... | ... | ...

There are 253 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/moose
* https://ioc.hatenablog.com/entry/2015/05/28/000000
* https://www.threatminer.org/report.php?q=Dissecting-LinuxMoose.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
