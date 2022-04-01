# Dofoil - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dofoil](https://vuldb.com/?actor.dofoil). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dofoil](https://vuldb.com/?actor.dofoil)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dofoil:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dofoil.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.149.253.100](https://vuldb.com/?ip.5.149.253.100) | enappiv.com | - | High
2 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
3 | [23.3.13.137](https://vuldb.com/?ip.23.3.13.137) | a23-3-13-137.deploy.static.akamaitechnologies.com | - | High
4 | [23.6.24.15](https://vuldb.com/?ip.23.6.24.15) | a23-6-24-15.deploy.static.akamaitechnologies.com | - | High
5 | [23.6.65.194](https://vuldb.com/?ip.23.6.65.194) | a23-6-65-194.deploy.static.akamaitechnologies.com | - | High
6 | [23.209.185.159](https://vuldb.com/?ip.23.209.185.159) | a23-209-185-159.deploy.static.akamaitechnologies.com | - | High
7 | [27.100.36.191](https://vuldb.com/?ip.27.100.36.191) | - | - | High
8 | [37.230.112.146](https://vuldb.com/?ip.37.230.112.146) | audiotop.ru | - | High
9 | [45.63.25.55](https://vuldb.com/?ip.45.63.25.55) | 45.63.25.55.vultr.com | - | Medium
10 | [50.3.75.246](https://vuldb.com/?ip.50.3.75.246) | web.netkolik.org | - | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dofoil_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dofoil. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?module=users&section=cpanel&page=list` | High
2 | File | `/admin/powerline` | High
3 | File | `/admin/syslog` | High
4 | File | `/api/upload` | Medium
5 | File | `/cgi-bin` | Medium
6 | File | `/context/%2e/WEB-INF/web.xml` | High
7 | File | `/export` | Low
8 | File | `/monitoring` | Medium
9 | File | `/new` | Low
10 | File | `/proc/<pid>/status` | High
11 | File | `/public/plugins/` | High
12 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
13 | File | `/secure/QueryComponent!Default.jspa` | High
14 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
15 | File | `/tmp` | Low
16 | File | `/uncpath/` | Medium
17 | File | `/wp-admin` | Medium
18 | File | `/wp-json/wc/v3/webhooks` | High
19 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
20 | File | `AccountManagerService.java` | High
21 | File | `actions/CompanyDetailsSave.php` | High
22 | File | `ActiveServices.java` | High
23 | File | `ActivityManagerService.java` | High
24 | File | `admin.php` | Medium
25 | File | `admin/?n=user&c=admin_user&a=doGetUserInfo` | High
26 | File | `admin/add-glossary.php` | High
27 | File | `admin/conf_users_edit.php` | High
28 | File | `admin/edit-comments.php` | High
29 | File | `admin/src/containers/InputModalStepperProvider/index.js` | High
30 | ... | ... | ...

There are 254 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/04/threat-roundup-0326-0402.html
* https://blogs.blackberry.com/en/2018/07/threat-spotlight-resurgent-smoke-loader-malware-dissected

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
