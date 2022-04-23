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
* [RU](https://vuldb.com/?country.ru)
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

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Prophet Spider. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/goods/update` | High
2 | File | `/agenttrayicon` | High
3 | File | `/blog/blog.php` | High
4 | File | `/cmd?cmd=connect` | High
5 | File | `/etc/puppetlabs/puppetserver/conf.d/ca.conf` | High
6 | File | `/goform/login_process` | High
7 | File | `/include/make.php` | High
8 | File | `/login` | Low
9 | File | `/manager/files` | High
10 | File | `/nova/bin/detnet` | High
11 | File | `/nova/bin/igmp-proxy` | High
12 | File | `/ofcms/company-c-47` | High
13 | File | `/php/ajax.php` | High
14 | File | `/preauth` | Medium
15 | File | `/sql/sql_string.h` | High
16 | File | `/src/njs_vmcode.c` | High
17 | File | `/uncpath/` | Medium
18 | File | `/var/log/demisto/` | High
19 | File | `/webminlog/view.cgi` | High
20 | File | `/_error` | Low
21 | File | `a2billing/customer/iridium_threed.php` | High
22 | File | `actions/beats_uploader.php` | High
23 | File | `actions/vote_channel.php` | High
24 | File | `ActiveServices.java` | High
25 | File | `admin.php` | Medium
26 | File | `admin/moduleinterface.php` | High
27 | File | `admin/profile/save` | High
28 | File | `admin/tools/utf8conversion/index.php` | High
29 | File | `ad_manage.php` | High
30 | File | `asm/preproc.c` | High
31 | File | `Atom.CMS_admin_ajax_list-sort.php` | High
32 | ... | ... | ...

There are 269 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2022/01/log4u-shell4me

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
