# Charming Kitten - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Charming Kitten](https://vuldb.com/?actor.charming_kitten). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.charming_kitten](https://vuldb.com/?actor.charming_kitten)

## Campaigns

The following _campaigns_ are known and can be associated with Charming Kitten:

* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Charming Kitten:

* NL
* CN
* US
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Charming Kitten.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 5.79.69.198 | - | - | High
2 | 5.79.69.206 | - | - | High
3 | 5.79.105.153 | - | - | High
4 | 5.79.105.156 | - | - | High
5 | 5.79.105.161 | - | - | High
6 | 5.79.105.165 | - | - | High
7 | 5.152.202.51 | h5-152-202-51.host.redstation.co.uk | - | High
8 | 5.152.202.52 | h5-152-202-52.host.redstation.co.uk | - | High
9 | 31.3.236.90 | h31-3-236-90.host.redstation.co.uk | - | High
10 | 31.3.236.91 | h31-3-236-91.host.redstation.co.uk | - | High
11 | 31.3.236.92 | h31-3-236-92.host.redstation.co.uk | - | High
12 | 37.220.8.13 | h37-220-8-13.host.redstation.co.uk | - | High
13 | 46.17.97.37 | - | - | High
14 | 46.17.97.40 | - | - | High
15 | 46.17.97.240 | - | - | High
16 | 46.17.97.243 | - | - | High
17 | 51.254.254.217 | me14.mecide.com | - | High
18 | 51.255.28.57 | - | - | High
19 | 54.36.217.8 | ip8.ip-54-36-217.eu | - | High
20 | 54.37.164.254 | - | - | High
21 | 54.38.49.6 | ip6.ip-54-38-49.eu | Log4Shell | High
22 | 69.30.221.126 | - | - | High
23 | ... | ... | ... | ...

There are 88 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Charming Kitten. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Charming Kitten. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/.env` | Low
3 | File | `/?module=users&section=cpanel&page=list` | High
4 | File | `/admin/powerline` | High
5 | File | `/admin/syslog` | High
6 | File | `/api/upload` | Medium
7 | File | `/cgi-bin` | Medium
8 | File | `/context/%2e/WEB-INF/web.xml` | High
9 | File | `/medical/inventories.php` | High
10 | File | `/monitoring` | Medium
11 | File | `/new` | Low
12 | File | `/plugins/servlet/audit/resource` | High
13 | File | `/plugins/servlet/project-config/PROJECT/roles` | High
14 | File | `/proc/<pid>/status` | High
15 | File | `/public/plugins/` | High
16 | File | `/replication` | Medium
17 | File | `/RestAPI` | Medium
18 | File | `/secure/QueryComponent!Default.jspa` | High
19 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
20 | File | `/tmp` | Low
21 | File | `/uncpath/` | Medium
22 | File | `/var/log/nginx` | High
23 | File | `/wp-json/wc/v3/webhooks` | High
24 | File | `AccountManagerService.java` | High
25 | File | `actions/CompanyDetailsSave.php` | High
26 | File | `ActiveServices.java` | High
27 | File | `admin.php` | Medium
28 | File | `admin/?n=user&c=admin_user&a=doGetUserInfo` | High
29 | File | `admin/add-glossary.php` | High
30 | ... | ... | ...

There are 258 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/tree/master/Charming%20Kitten
* https://research.checkpoint.com/2022/apt35-exploits-log4j-vulnerability-to-distribute-new-modular-powershell-toolkit/
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.08/Charming%20Kitten.pdf
* https://www.clearskysec.com/wp-content/uploads/2017/12/Charming_Kitten_2017.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
