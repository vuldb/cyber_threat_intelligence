# Inception - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Inception_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Inception:

* [SV](https://vuldb.com/?country.sv)
* [ES](https://vuldb.com/?country.es)
* [DE](https://vuldb.com/?country.de)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Inception or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Inception](https://vuldb.com/?actor.inception) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Inception.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [51.255.139.194](https://vuldb.com/?ip.51.255.139.194) | ip194.ip-51-255-139.eu | [Inception](https://vuldb.com/?actor.inception) | High
2 | [82.221.100.55](https://vuldb.com/?ip.82.221.100.55) | web.a1yola.com | [Inception](https://vuldb.com/?actor.inception) | High
3 | [82.221.100.60](https://vuldb.com/?ip.82.221.100.60) | - | [Inception](https://vuldb.com/?actor.inception) | High
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-250, CWE-264, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Inception. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.jboss-cli-history` | High
2 | File | `/admin.php?id=posts&action=display&value=1&postid=` | High
3 | File | `/admin/inbox.php&action=read` | High
4 | File | `/admin/news/news_mod.php` | High
5 | File | `/admin/page_edit/3` | High
6 | File | `/administrator/alerts/alertLightbox.php` | High
7 | File | `/apps/acs-commons/content/page-compare.html` | High
8 | File | `/blog/blog.php` | High
9 | File | `/cgi-bin/luci/api/diagnose` | High
10 | File | `/cgi-bin/main.cgi` | High
11 | File | `/cgi-bin/uploadWeiXinPic` | High
12 | File | `/cms/classes/Master.php?f=delete_designation` | High
13 | File | `/controller/Adv.php` | High
14 | File | `/dvcset/sysset/set.cgi` | High
15 | File | `/example/editor` | High
16 | File | `/goform/setsambacfg` | High
17 | File | `/goform/websURLFilter` | High
18 | File | `/guest_auth/cfg/upLoadCfg.php` | High
19 | File | `/include/make.php` | High
20 | File | `/jquery_file_upload/server/php/index.php` | High
21 | File | `/mobile/SelectUsers.jsp` | High
22 | File | `/php/ajax.php` | High
23 | File | `/ptms/classes/Users.php` | High
24 | File | `/public/admin/index.php?add_product` | High
25 | File | `/resolv/nss_dns/dns-host.c` | High
26 | File | `/role/saveOrUpdateRole.do` | High
27 | File | `/scbs/admin/?page=facilities/manage_facility` | High
28 | ... | ... | ...

There are 236 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/interception
* https://securelist.com/recent-cloud-atlas-activity/92016/
* https://unit42.paloaltonetworks.com/unit42-inception-attackers-target-europe-year-old-office-vulnerability/
* https://www.threatminer.org/report.php?q=bcs_wp_InceptionReport_EN_v12914.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
