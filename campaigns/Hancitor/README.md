# Hancitor - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Hancitor_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Hancitor:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [FR](https://vuldb.com/?country.fr)
* ...

There are 8 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Hancitor or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TA551](https://vuldb.com/?actor.ta551) | High
2 | [Hancitor](https://vuldb.com/?actor.hancitor) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Hancitor.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [8.208.9.98](https://vuldb.com/?ip.8.208.9.98) | - | [Hancitor](https://vuldb.com/?actor.hancitor) | High
2 | [8.208.77.171](https://vuldb.com/?ip.8.208.77.171) | - | [Hancitor](https://vuldb.com/?actor.hancitor) | High
3 | [8.209.76.110](https://vuldb.com/?ip.8.209.76.110) | - | [TA551](https://vuldb.com/?actor.ta551) | High
4 | [8.209.119.208](https://vuldb.com/?ip.8.209.119.208) | - | [Hancitor](https://vuldb.com/?actor.hancitor) | High
5 | [8.211.241.0](https://vuldb.com/?ip.8.211.241.0) | - | [Hancitor](https://vuldb.com/?actor.hancitor) | High
6 | [23.236.75.32](https://vuldb.com/?ip.23.236.75.32) | - | [Hancitor](https://vuldb.com/?actor.hancitor) | High
7 | [31.44.184.36](https://vuldb.com/?ip.31.44.184.36) | - | [Hancitor](https://vuldb.com/?actor.hancitor) | High
8 | [43.128.225.230](https://vuldb.com/?ip.43.128.225.230) | - | [TA551](https://vuldb.com/?actor.ta551) | High
9 | [43.128.229.136](https://vuldb.com/?ip.43.128.229.136) | - | [TA551](https://vuldb.com/?actor.ta551) | High
10 | [43.128.232.152](https://vuldb.com/?ip.43.128.232.152) | - | [TA551](https://vuldb.com/?actor.ta551) | High
11 | [43.129.239.78](https://vuldb.com/?ip.43.129.239.78) | - | [TA551](https://vuldb.com/?actor.ta551) | High
12 | ... | ... | ... | ...

There are 45 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Hancitor. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 3 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Hancitor. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htpasswd` | Medium
2 | File | `/../conf/config.properties` | High
3 | File | `/drivers/infiniband/core/cm.c` | High
4 | File | `/find_v2/_click` | High
5 | File | `/forum/away.php` | High
6 | File | `/horde/util/go.php` | High
7 | File | `/images/` | Medium
8 | File | `/inc/parser/xhtml.php` | High
9 | File | `/login` | Low
10 | File | `/modules/profile/index.php` | High
11 | File | `/objects/getImageMP4.php` | High
12 | File | `/one_church/userregister.php` | High
13 | File | `/out.php` | Medium
14 | File | `/public/plugins/` | High
15 | File | `/SASWebReportStudio/logonAndRender.do` | High
16 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
17 | File | `/secure/admin/ViewInstrumentation.jspa` | High
18 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
19 | File | `/system/proxy` | High
20 | File | `/tmp/phpglibccheck` | High
21 | File | `/uncpath/` | Medium
22 | File | `adclick.php` | Medium
23 | File | `add.php` | Low
24 | File | `addentry.php` | Medium
25 | File | `addressbookprovider.php` | High
26 | File | `admin.cropcanvas.php` | High
27 | File | `admin.jcomments.php` | High
28 | File | `admin.php` | Medium
29 | File | `admin/dashboard.php` | High
30 | File | `admin/pageUploadCSV.php` | High
31 | File | `ajax_udf.php` | Medium
32 | File | `AppCompatCache.exe` | High
33 | File | `application.js.php` | High
34 | ... | ... | ...

There are 295 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://isc.sans.edu/forums/diary/Campaign+evolution+Hancitor+changes+its+Word+macros/24376/
* https://isc.sans.edu/forums/diary/Campaign+evolution+Hancitor+malspam+starts+pushing+Ursnif+this+week/24256/
* https://isc.sans.edu/forums/diary/Hancitor+activity+resumes+after+a+hoilday+break/26980/
* https://isc.sans.edu/forums/diary/Hancitor+distributed+through+coronavirusthemed+malspam/25892/
* https://isc.sans.edu/forums/diary/Hancitor+tries+XLL+as+initial+malware+file/27618/
* https://isc.sans.edu/forums/diary/June+2021+Forensic+Contest+Answers+and+Analysis/27582/
* https://www.malware-traffic-analysis.net/2021/09/14/index.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
