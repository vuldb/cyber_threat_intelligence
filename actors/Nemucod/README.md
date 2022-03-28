# Nemucod - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nemucod](https://vuldb.com/?actor.nemucod). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nemucod](https://vuldb.com/?actor.nemucod)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nemucod:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nemucod.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [185.130.104.156](https://vuldb.com/?ip.185.130.104.156) | . | - | High
2 | [185.130.104.178](https://vuldb.com/?ip.185.130.104.178) | mail.instadavance.com | - | High
3 | [185.159.82.11](https://vuldb.com/?ip.185.159.82.11) | customer.clientshostname.com | - | High
4 | ... | ... | ... | ...

There are 2 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nemucod_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nemucod. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?module=users&section=cpanel&page=list` | High
2 | File | `/admin/powerline` | High
3 | File | `/admin/syslog` | High
4 | File | `/api/upload` | Medium
5 | File | `/cgi-bin` | Medium
6 | File | `/cgi-bin/kerbynet` | High
7 | File | `/context/%2e/WEB-INF/web.xml` | High
8 | File | `/dcim/sites/add/` | High
9 | File | `/EXCU_SHELL` | Medium
10 | File | `/forum/away.php` | High
11 | File | `/fudforum/adm/hlplist.php` | High
12 | File | `/login` | Low
13 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
14 | File | `/monitoring` | Medium
15 | File | `/new` | Low
16 | File | `/proc/<pid>/status` | High
17 | File | `/public/login.htm` | High
18 | File | `/public/plugins/` | High
19 | File | `/rom` | Low
20 | File | `/scripts/killpvhost` | High
21 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
22 | File | `/secure/QueryComponent!Default.jspa` | High
23 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
24 | File | `/tmp` | Low
25 | File | `/tmp/redis.ds` | High
26 | File | `/uncpath/` | Medium
27 | File | `/ViewUserHover.jspa` | High
28 | File | `/wp-admin` | Medium
29 | File | `/wp-json/wc/v3/webhooks` | High
30 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
31 | File | `AccountManagerService.java` | High
32 | File | `actions/CompanyDetailsSave.php` | High
33 | File | `ActiveServices.java` | High
34 | File | `ActivityManagerService.java` | High
35 | File | `addlink.php` | Medium
36 | ... | ... | ...

There are 313 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/unit42-practice-makes-perfect-nemucod-evolves-delivery-obfuscation-techniques-harvest-credentials/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
