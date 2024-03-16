# Campaign 1 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign 1_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign 1:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## Actors

These _actors_ are associated with Campaign 1 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign 1.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [10.16.91.131](https://vuldb.com/?ip.10.16.91.131) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [11.24.8.54](https://vuldb.com/?ip.11.24.8.54) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [11.25.41.114](https://vuldb.com/?ip.11.25.41.114) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [13.33.26.95](https://vuldb.com/?ip.13.33.26.95) | server-13-33-26-95.phx50.r.cloudfront.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [13.56.107.66](https://vuldb.com/?ip.13.56.107.66) | ec2-13-56-107-66.us-west-1.compute.amazonaws.com | [Kwampirs](https://vuldb.com/?actor.kwampirs) | Medium
6 | [14.40.57.104](https://vuldb.com/?ip.14.40.57.104) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [15.85.30.84](https://vuldb.com/?ip.15.85.30.84) | atp467w084.sgp.hp.com | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [19.140.139.6](https://vuldb.com/?ip.19.140.139.6) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [20.143.69.60](https://vuldb.com/?ip.20.143.69.60) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | [23.26.60.60](https://vuldb.com/?ip.23.26.60.60) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
11 | [23.92.211.10](https://vuldb.com/?ip.23.92.211.10) | gramwide.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
12 | [25.108.63.68](https://vuldb.com/?ip.25.108.63.68) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
13 | [26.50.108.98](https://vuldb.com/?ip.26.50.108.98) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
14 | [27.22.41.133](https://vuldb.com/?ip.27.22.41.133) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
15 | [29.136.101.40](https://vuldb.com/?ip.29.136.101.40) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
16 | [30.101.13.14](https://vuldb.com/?ip.30.101.13.14) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
17 | [33.9.140.76](https://vuldb.com/?ip.33.9.140.76) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
18 | [36.75.63.47](https://vuldb.com/?ip.36.75.63.47) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
19 | ... | ... | ... | ...

There are 71 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-36 | Path Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | ... | ... | ... | ...

There are 13 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/api /v3/auth` | High
2 | File | `/app/index/controller/Common.php` | High
3 | File | `/belegungsplan/wochenuebersicht.inc.php` | High
4 | File | `/cgi-bin/nobody/VerifyCode.cgi` | High
5 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
6 | File | `/cgi.cgi` | Medium
7 | File | `/counter/index2.php` | High
8 | File | `/data/remove` | Medium
9 | File | `/highlight/index.html` | High
10 | File | `/iisadmin` | Medium
11 | File | `/iissamples` | Medium
12 | File | `/include/dialog/select_templets_post.php` | High
13 | File | `/includes/js/admin.php` | High
14 | File | `/modx/manager/index.php` | High
15 | File | `/search-result/` | High
16 | File | `/search.php` | Medium
17 | File | `/server-status` | High
18 | File | `/sgms/reports/scheduledreports/configure/scheduleProps.jsp` | High
19 | File | `/templates/header.inc.php` | High
20 | File | `/tmp` | Low
21 | File | `a.jsp` | Low
22 | File | `admin/comedit.php` | High
23 | File | `admin/db.php` | Medium
24 | ... | ... | ...

There are 198 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_1_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
