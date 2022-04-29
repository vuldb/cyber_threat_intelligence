# Prophet Spider - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Prophet Spider](https://vuldb.com/?actor.prophet_spider). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.prophet_spider](https://vuldb.com/?actor.prophet_spider)

## Campaigns

The following _campaigns_ are known and can be associated with Prophet Spider:

* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Prophet Spider:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [IL](https://vuldb.com/?country.il)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Prophet Spider.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.157.38.50](https://vuldb.com/?ip.5.157.38.50) | - | Log4Shell | High
2 | [23.129.64.218](https://vuldb.com/?ip.23.129.64.218) | - | Log4Shell | High
3 | [23.236.146.162](https://vuldb.com/?ip.23.236.146.162) | - | Log4Shell | High
4 | [45.61.146.242](https://vuldb.com/?ip.45.61.146.242) | - | Log4Shell | High
5 | [45.146.165.168](https://vuldb.com/?ip.45.146.165.168) | - | Log4Shell | High
6 | [45.154.255.147](https://vuldb.com/?ip.45.154.255.147) | cust-147.keff.org | Log4Shell | High
7 | [51.79.175.139](https://vuldb.com/?ip.51.79.175.139) | vps-dc8b0481.vps.ovh.ca | Log4Shell | High
8 | [51.222.121.180](https://vuldb.com/?ip.51.222.121.180) | ip180.ip-51-222-121.net | Log4Shell | High
9 | [62.102.148.68](https://vuldb.com/?ip.62.102.148.68) | - | Log4Shell | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Prophet Spider_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php?id=siteoptions&social=display&value=0&sid=2` | High
2 | File | `/admin.php?id=siteoptions&social=edit&sid=2` | High
3 | File | `/admin.php?r=admin/AdminBackup/del` | High
4 | File | `/admin/edit.php` | High
5 | File | `/admin/inbox.php&action=delete` | High
6 | File | `/admin/inbox.php&action=read` | High
7 | File | `/admin/index.php?mode=content&page=media&action=edit` | High
8 | File | `/admin/pagerole.php&action=edit` | High
9 | File | `/admin/posts.php` | High
10 | File | `/admin/posts.php&action=delete` | High
11 | File | `/admin/posts.php&action=edit` | High
12 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
13 | File | `/admin/siteoptions.php&social=remove&sid=2` | High
14 | File | `/admin/uesrs.php&&action=delete&userid=4` | High
15 | File | `/admin/uesrs.php&action=display&value=Hide` | High
16 | File | `/admin/uesrs.php&action=display&value=Show` | High
17 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
18 | File | `/admin/uesrs.php&action=type&userrole=User` | High
19 | File | `/administrator/alerts/alertLightbox.php` | High
20 | File | `/agenttrayicon` | High
21 | File | `/api/students/me/messages/` | High
22 | File | `/apps/acs-commons/content/page-compare.html` | High
23 | File | `/blog/blog.php` | High
24 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
25 | File | `/cdsms/classes/Master.php?f=delete_package` | High
26 | File | `/cmd?cmd=connect` | High
27 | File | `/hocms/classes/Master.php?f=delete_collection` | High
28 | File | `/hocms/classes/Master.php?f=delete_member` | High
29 | File | `/hocms/classes/Master.php?f=delete_phase` | High
30 | File | `/index.php?m=admin&c=custom&a=plugindelhandle` | High
31 | File | `/login` | Low
32 | File | `/manager/files` | High
33 | File | `/module/api.php?mobile/wapNasIPS` | High
34 | File | `/module/api.php?mobile/webNasIPS` | High
35 | ... | ... | ...

There are 304 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
