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
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1059 | CWE-94 | Cross Site Scripting | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign 1. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/admin.php` | High
2 | File | `/api/upload.php` | High
3 | File | `/api /v3/auth` | High
4 | File | `/cgi-bin/cstecgi.cgi` | High
5 | File | `/data/remove` | Medium
6 | File | `/debug/pprof` | Medium
7 | File | `/dev/cpu/*/msr` | High
8 | File | `/filemanager/upload/drop` | High
9 | File | `/goform/NatStaticSetting` | High
10 | File | `/include/lang-en.php` | High
11 | File | `/navigation/create?ParentID=%23` | High
12 | File | `/oauth/idp/.well-known/openid-configuration` | High
13 | File | `/preview.php` | Medium
14 | File | `/sbin/conf.d/SuSEconfig.javarunt` | High
15 | File | `/status/` | Medium
16 | File | `/usr/bin/write` | High
17 | File | `/var/spool/fax/outgoing/.last_run` | High
18 | File | `/WebArticle/articles/` | High
19 | File | `3G/UMTS` | Low
20 | File | `400.htm/500.htm` | High
21 | File | `abitwhizzy.php` | High
22 | File | `acc.php` | Low
23 | File | `accton` | Low
24 | File | `acloudCosAction.php.SQL` | High
25 | File | `adduser` | Low
26 | File | `add_comment.php` | High
27 | File | `add_post.php3` | High
28 | File | `admin/auth.php` | High
29 | File | `admin/index.php` | High
30 | File | `admin/TemplateController.java` | High
31 | File | `ApiController.class.php` | High
32 | File | `app/ctrl/admin/User.php` | High
33 | File | `avatar.php` | Medium
34 | File | `bb-includes/formatting-functions.php` | High
35 | File | `BBStore.php` | Medium
36 | File | `brokenlink.php` | High
37 | File | `browse.php` | Medium
38 | File | `bsc_sms_send.php` | High
39 | File | `cal2.jsp` | Medium
40 | File | `calendar.php` | Medium
41 | File | `categos.php` | Medium
42 | File | `centre.php` | Medium
43 | ... | ... | ...

There are 372 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_1_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
