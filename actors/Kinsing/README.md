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
* [CN](https://vuldb.com/?country.cn)
* ...

There are 13 more country items available. Please use our online service to access the data.

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
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kinsing. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api/files/` | Medium
2 | File | `/api/trackedEntityInstances` | High
3 | File | `/app/Http/Controllers/Admin/NEditorController.php` | High
4 | File | `/de/cgi/dfs_guest/` | High
5 | File | `/filemanager/upload.php` | High
6 | File | `/include/makecvs.php` | High
7 | File | `/includes/event-management/index.php` | High
8 | File | `/Main_AdmStatus_Content.asp` | High
9 | File | `/member/picture/album` | High
10 | File | `/mifs/c/i/reg/reg.html` | High
11 | File | `/modules/profile/index.php` | High
12 | File | `/products/details.asp` | High
13 | File | `/services/details.asp` | High
14 | File | `/uncpath/` | Medium
15 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
16 | File | `/usr/syno/etc/mount.conf` | High
17 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
18 | File | `/xAdmin/html/cm_doclist_view_uc.jsp` | High
19 | File | `a-b-membres.php` | High
20 | File | `actions.php` | Medium
21 | File | `adclick.php` | Medium
22 | File | `add.php` | Low
23 | File | `add_2_basket.asp` | High
24 | File | `add_comment.php` | High
25 | File | `admin.php` | Medium
26 | File | `admin.php/comments/batchdel/` | High
27 | File | `admin/aboutus.php` | High
28 | File | `admin\controller\uploadfile.php` | High
29 | File | `album_portal.php` | High
30 | File | `al_initialize.php` | High
31 | File | `application/modules/admin/views/ecommerce/products.php` | High
32 | File | `ArchiveNews.aspx` | High
33 | File | `ashnews.php/ashheadlines.php` | High
34 | File | `base/ErrorHandler.php` | High
35 | File | `blog.php` | Medium
36 | File | `board.php` | Medium
37 | ... | ... | ...

There are 317 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
