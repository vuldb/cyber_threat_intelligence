# LODEINFO - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _LODEINFO_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LODEINFO:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [JP](https://vuldb.com/?country.jp)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with LODEINFO or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lodeinfo](https://vuldb.com/?actor.lodeinfo) | High
2 | [APT10](https://vuldb.com/?actor.apt10) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LODEINFO.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.8.95.174](https://vuldb.com/?ip.5.8.95.174) | sei809753.example.com | [APT10](https://vuldb.com/?actor.apt10) | High
2 | [45.67.231.169](https://vuldb.com/?ip.45.67.231.169) | vm377031.pq.hosting | [Lodeinfo](https://vuldb.com/?actor.lodeinfo) | High
3 | [45.76.216.40](https://vuldb.com/?ip.45.76.216.40) | 45.76.216.40.vultrusercontent.com | [Lodeinfo](https://vuldb.com/?actor.lodeinfo) | High
4 | [45.77.28.124](https://vuldb.com/?ip.45.77.28.124) | 45.77.28.124.vultrusercontent.com | [APT10](https://vuldb.com/?actor.apt10) | High
5 | [103.27.184.27](https://vuldb.com/?ip.103.27.184.27) | - | [Lodeinfo](https://vuldb.com/?actor.lodeinfo) | High
6 | ... | ... | ... | ...

There are 18 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within LODEINFO. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LODEINFO. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/admin/index.php` | High
3 | File | `/app/Http/Controllers/Admin/NEditorController.php` | High
4 | File | `/auth` | Low
5 | File | `/balance/service/list` | High
6 | File | `/config/getuser` | High
7 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
8 | File | `/SiteServer/Ajax/ajaxOtherService.aspx` | High
9 | File | `/uncpath/` | Medium
10 | File | `/upload` | Low
11 | ... | ... | ...

There are 84 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.jpcert.or.jp/en/2021/02/LODEINFO-3.html
* https://blogs.jpcert.or.jp/ja/2020/06/LODEINFO-2.html
* https://files.macnica.co.jp/mnc/mpressioncss_ta_report_2019_2.pdf
* https://securelist.com/apt10-tracking-down-lodeinfo-2022-part-i/
* https://securelist.com/apt10-tracking-down-lodeinfo-2022-part-ii/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
