# OceanLotus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [OceanLotus](https://vuldb.com/?actor.oceanlotus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.oceanlotus](https://vuldb.com/?actor.oceanlotus)

## Campaigns

The following _campaigns_ are known and can be associated with OceanLotus:

* MST Transforms
* WateringHole

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with OceanLotus:

* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of OceanLotus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [37.59.198.130](https://vuldb.com/?ip.37.59.198.130) | - | - | High
2 | [37.59.198.131](https://vuldb.com/?ip.37.59.198.131) | - | - | High
3 | [43.251.100.20](https://vuldb.com/?ip.43.251.100.20) | - | - | High
4 | [43.254.217.67](https://vuldb.com/?ip.43.254.217.67) | - | - | High
5 | [45.9.239.34](https://vuldb.com/?ip.45.9.239.34) | 45.9.239.34.deltahost-ptr | - | High
6 | [45.9.239.45](https://vuldb.com/?ip.45.9.239.45) | 45.9.239.45.deltahost-ptr | - | High
7 | [45.9.239.77](https://vuldb.com/?ip.45.9.239.77) | 45.9.239.77.deltahost-ptr | - | High
8 | [45.9.239.110](https://vuldb.com/?ip.45.9.239.110) | 45.9.239.110.deltahost-ptr | - | High
9 | [45.9.239.139](https://vuldb.com/?ip.45.9.239.139) | 45.9.239.139.deltahost-ptr | - | High
10 | [45.32.100.179](https://vuldb.com/?ip.45.32.100.179) | 45.32.100.179.vultr.com | - | Medium
11 | [45.32.114.49](https://vuldb.com/?ip.45.32.114.49) | 45.32.114.49.vultr.com | - | Medium
12 | [45.76.179.28](https://vuldb.com/?ip.45.76.179.28) | 45.76.179.28.vultr.com | - | Medium
13 | [45.76.179.151](https://vuldb.com/?ip.45.76.179.151) | 45.76.179.151.vultr.com | - | Medium
14 | [45.114.117.164](https://vuldb.com/?ip.45.114.117.164) | folien.reisnart.com | - | High
15 | [46.183.220.81](https://vuldb.com/?ip.46.183.220.81) | ip-220-81.dataclub.info | - | High
16 | [46.183.220.82](https://vuldb.com/?ip.46.183.220.82) | ip-220-82.dataclub.info | - | High
17 | [46.183.221.188](https://vuldb.com/?ip.46.183.221.188) | ip-221-188.dataclub.info | - | High
18 | [46.183.221.189](https://vuldb.com/?ip.46.183.221.189) | ip-221-189.dataclub.info | - | High
19 | [46.183.221.190](https://vuldb.com/?ip.46.183.221.190) | ip-221-190.dataclub.info | - | High
20 | [46.183.222.82](https://vuldb.com/?ip.46.183.222.82) | ip-222-82.dataclub.info | - | High
21 | [46.183.222.83](https://vuldb.com/?ip.46.183.222.83) | ip-222-83.dataclub.info | - | High
22 | [46.183.222.84](https://vuldb.com/?ip.46.183.222.84) | ip-222-84.dataclub.info | - | High
23 | [46.183.223.106](https://vuldb.com/?ip.46.183.223.106) | ip-223-106.dataclub.info | - | High
24 | ... | ... | ... | ...

There are 92 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _OceanLotus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by OceanLotus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.jsp` | Low
2 | File | `/admin/categories/view_category.php` | High
3 | File | `/admin/edit.php` | High
4 | File | `/admin/inventory/manage_stock.php` | High
5 | File | `/admin/user/manage_user.php` | High
6 | File | `/app/controller/Books.php` | High
7 | File | `/check` | Low
8 | File | `/classes/Master.php` | High
9 | File | `/classes/Master.php?f=save_sub_category` | High
10 | File | `/ecshop/admin/template.php` | High
11 | File | `/includes/session.php` | High
12 | File | `/kajona/image.php` | High
13 | File | `/op/op.LockDocument.php` | High
14 | File | `/openvpn/pageswitch.htm` | High
15 | File | `/page.php` | Medium
16 | File | `/php-inventory-management-system/categories.php` | High
17 | File | `/php/ajax.php` | High
18 | File | `/post.php` | Medium
19 | File | `/wp-admin/admin-ajax.php` | High
20 | File | `add-family-member.php` | High
21 | File | `admin/ajax.attachment.php` | High
22 | File | `admin/manage-categories.php` | High
23 | File | `admin/ops/reports/ops/news.php` | High
24 | ... | ... | ...

There are 197 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2019/10/mobile-malware-and-apt-espionage-prolific-pervasive-and-cross-platform
* https://dmpdump.github.io/posts/Possible-Ocean-LotusInstaller-Abusing-MST-Transforms/
* https://github.com/blackorbird/APT_REPORT/blob/master/Oceanlotus/apt32_report_2019.pdf
* https://github.com/eset/malware-ioc/tree/master/oceanlotus
* https://www.threatminer.org/report.php?q=ESET_OceanLotus.pdf&y=2018
* https://www.threatminer.org/report.php?q=OceanLotusBlossoms_MassDigitalSurveillanceandAttacksTargetingASEAN,AsianNations,theMedia,HumanRightsGroups,andCivilSociety_Volexity.pdf&y=2017
* https://www.threatminer.org/report.php?q=OceanLotus_NewwateringholeattackinSoutheastAsia.pdf&y=2018
* https://www.threatminer.org/report.php?q=OceanLotus_Report-en-6.2.2_360.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
