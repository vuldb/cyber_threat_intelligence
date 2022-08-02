# Kinsing - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kinsing](https://vuldb.com/?actor.kinsing). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kinsing](https://vuldb.com/?actor.kinsing)

## Campaigns

The following _campaigns_ are known and can be associated with Kinsing:

* Log4Shell

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kinsing:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [LA](https://vuldb.com/?country.la)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kinsing.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.215.110.66](https://vuldb.com/?ip.3.215.110.66) | ec2-3-215-110-66.compute-1.amazonaws.com | Log4Shell | Medium
2 | [5.34.183.14](https://vuldb.com/?ip.5.34.183.14) | vds-904894.hosted-by-itldc.com | - | High
3 | [5.34.183.145](https://vuldb.com/?ip.5.34.183.145) | a.sadeghi | - | High
4 | [31.210.20.181](https://vuldb.com/?ip.31.210.20.181) | - | Log4Shell | High
5 | [34.81.218.76](https://vuldb.com/?ip.34.81.218.76) | 76.218.81.34.bc.googleusercontent.com | Log4Shell | Medium
6 | [42.112.28.216](https://vuldb.com/?ip.42.112.28.216) | midp.highlatrol.com | Log4Shell | High
7 | [45.10.88.124](https://vuldb.com/?ip.45.10.88.124) | - | - | High
8 | [45.67.230.68](https://vuldb.com/?ip.45.67.230.68) | vm330138.pq.hosting | - | High
9 | [45.129.2.107](https://vuldb.com/?ip.45.129.2.107) | - | Log4Shell | High
10 | [45.137.151.106](https://vuldb.com/?ip.45.137.151.106) | - | Log4Shell | High
11 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kinsing_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kinsing. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/contenttemp` | High
2 | File | `/admin/dl_sendmail.php` | High
3 | File | `/api/files/` | Medium
4 | File | `/api/trackedEntityInstances` | High
5 | File | `/app/Http/Controllers/Admin/NEditorController.php` | High
6 | File | `/de/cgi/dfs_guest/` | High
7 | File | `/filemanager/upload.php` | High
8 | File | `/GponForm/fsetup_Form` | High
9 | File | `/include/makecvs.php` | High
10 | File | `/includes/event-management/index.php` | High
11 | File | `/index.php` | Medium
12 | File | `/Main_AdmStatus_Content.asp` | High
13 | File | `/member/picture/album` | High
14 | File | `/mgmt/tm/util/bash` | High
15 | File | `/mifs/c/i/reg/reg.html` | High
16 | File | `/modules/profile/index.php` | High
17 | File | `/products/details.asp` | High
18 | File | `/secure/ViewCollectors` | High
19 | File | `/services/details.asp` | High
20 | File | `/spip.php` | Medium
21 | File | `/uncpath/` | Medium
22 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
23 | File | `/usr/syno/etc/mount.conf` | High
24 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
25 | File | `/wp-admin/admin.php?page=wp_file_manager_properties` | High
26 | File | `/xAdmin/html/cm_doclist_view_uc.jsp` | High
27 | File | `a-b-membres.php` | High
28 | File | `actions.php` | Medium
29 | File | `adclick.php` | Medium
30 | File | `add.php` | Low
31 | File | `add_2_basket.asp` | High
32 | File | `add_comment.php` | High
33 | File | `admin.php` | Medium
34 | File | `admin.php/comments/batchdel/` | High
35 | File | `admin/aboutus.php` | High
36 | File | `admin/conf_users_edit.php` | High
37 | File | `admin\controller\uploadfile.php` | High
38 | File | `album_portal.php` | High
39 | File | `al_initialize.php` | High
40 | File | `application/modules/admin/views/ecommerce/products.php` | High
41 | ... | ... | ...

There are 357 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.infoblox.com/cyber-threat-intelligence/cyber-campaign-briefs/log4j-indicators-of-compromise-to-date/
* https://gist.github.com/Iansus/050e121170a864c37b13f979c1883ad4
* https://twitter.com/iansus/status/1472867647410819073
* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/l/patch-now-apache-log4j-vulnerability-called-log4shell-being-actively-exploited/IOCs-PatchNow-Log4Shell-Vulnerability.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
