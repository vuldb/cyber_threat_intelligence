# AMOS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [AMOS](https://vuldb.com/?actor.amos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.amos](https://vuldb.com/?actor.amos)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AMOS:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AMOS.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.64.45](https://vuldb.com/?ip.5.42.64.45) | - | - | High
2 | [5.42.64.83](https://vuldb.com/?ip.5.42.64.83) | - | - | High
3 | [5.42.65.55](https://vuldb.com/?ip.5.42.65.55) | - | - | High
4 | [5.42.65.102](https://vuldb.com/?ip.5.42.65.102) | - | - | High
5 | [5.42.65.106](https://vuldb.com/?ip.5.42.65.106) | - | - | High
6 | [5.42.65.107](https://vuldb.com/?ip.5.42.65.107) | - | - | High
7 | [5.42.65.108](https://vuldb.com/?ip.5.42.65.108) | - | - | High
8 | [5.42.66.22](https://vuldb.com/?ip.5.42.66.22) | - | - | High
9 | [5.42.67.1](https://vuldb.com/?ip.5.42.67.1) | - | - | High
10 | [5.42.96.124](https://vuldb.com/?ip.5.42.96.124) | - | - | High
11 | [5.42.96.184](https://vuldb.com/?ip.5.42.96.184) | - | - | High
12 | [5.182.86.8](https://vuldb.com/?ip.5.182.86.8) | frequent-minute.aeza.network | - | High
13 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _AMOS_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-27 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by AMOS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/add_ikev2.php` | High
3 | File | `/admin/category_save.php` | High
4 | File | `/admin/dialog/select_images_post.php` | High
5 | File | `/admin/list_ipAddressPolicy.php` | High
6 | File | `/admin/manage_model.php` | High
7 | File | `/admin/manage_user.php` | High
8 | File | `/admin/subject.php` | High
9 | File | `/admin/user/manage_user.php` | High
10 | File | `/api/deploy/upload` | High
11 | File | `/api/deploy/upload /api/database/upload` | High
12 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
13 | File | `/catalog/all-products` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/changePassword` | High
16 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
17 | File | `/edit-subject.php` | High
18 | File | `/Employee/changepassword.php` | High
19 | File | `/endpoint/add-user.php` | High
20 | File | `/etc/postfix/sender_login` | High
21 | File | `/foms/routers/place-order.php` | High
22 | File | `/forum/away.php` | High
23 | File | `/goform/SetSysTimeCfg` | High
24 | File | `/index.php` | Medium
25 | File | `/labvantage/rc?command=page&page=SampleList&_iframename=list` | High
26 | ... | ... | ...

There are 219 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/5.42.65.55
* https://search.censys.io/hosts/79.137.198.170
* https://search.censys.io/hosts/89.208.105.191
* https://search.censys.io/hosts/185.172.128.31/
* https://search.censys.io/hosts/185.172.128.163
* https://search.censys.io/hosts/185.215.113.71/
* https://threatfox.abuse.ch
* https://tracker.viriback.com/index.php?q=5.182.86.8
* https://tria.ge/240131-bq8nfsghb7/behavioral1
* https://tria.ge/240204-mqbt9sfdg3
* https://tria.ge/240310-nyz3hacd2y/behavioral1
* https://tria.ge/240319-ld769sgb35/behavioral1
* https://tria.ge/240319-mgpd1ahe93/behavioral1
* https://tria.ge/240319-mpvwrahh42/behavioral1
* https://tria.ge/240410-n1cd8aef57/behavioral1
* https://tria.ge/240417-dt3mqadg4x/behavioral1
* https://tria.ge/240501-c1bl5sdh6w/behavioral1
* https://tria.ge/240507-l4a98aeb53/behavioral1
* https://tria.ge/240507-mg4hxscb3w/behavioral1
* https://tria.ge/240513-c6wt9scd97/behavioral1
* https://tria.ge/240519-mzd1zseg72/behavioral1
* https://tria.ge/240519-p9jqbshh53/behavioral1
* https://tria.ge/240519-pfn3ysgg7z/behavioral1
* https://tria.ge/240524-fl1jhaec5t/behavioral1
* https://tria.ge/240525-m61tbseb9z/behavioral1
* https://tria.ge/240527-l4le7afh91/behavioral1
* https://tria.ge/240530-lf792sea64/behavioral1
* https://tria.ge/240531-lt84hadh41/behavioral1
* https://tria.ge/240603-tdf2sabe7y
* https://tria.ge/240614-r43blavelg/behavioral1
* https://tria.ge/240618-mnmhzstfkp/behavioral1
* https://tria.ge/240716-lvpfgswfrj/behavioral1
* https://tria.ge/240720-lll9rszejc/behavioral1
* https://tria.ge/240728-fxbphszdkq/behavioral3
* https://tria.ge/240803-m8swhawdjc/behavioral1
* https://tria.ge/240806-sahwjasark/behavioral1
* https://tria.ge/240810-q2exvawdjb/behavioral1
* https://tria.ge/240811-l2tnsavdkk/behavioral1
* https://twitter.com/phd_phuc/status/1651002681798926337
* https://www.infosecurity-magazine.com/news/russian-legitimate-services/
* https://www.malwarebytes.com/blog/threat-intelligence/2024/01/atomic-stealer-rings-in-the-new-year-with-updated-version
* https://www.recordedfuture.com/cybercriminal-campaign-spreads-infostealers-highlighting-risks-to-web3-gaming

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
