# Spark - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Spark_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Spark:

* [US](https://vuldb.com/?country.us)
* [HU](https://vuldb.com/?country.hu)
* [ES](https://vuldb.com/?country.es)
* ...

There are 5 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Spark or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Molerats](https://vuldb.com/?actor.molerats) | High
2 | [SparklingGoblin](https://vuldb.com/?actor.sparklinggoblin) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Spark.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [66.42.103.222](https://vuldb.com/?ip.66.42.103.222) | 66.42.103.222.vultrusercontent.com | [SparklingGoblin](https://vuldb.com/?actor.sparklinggoblin) | High
2 | [80.85.155.80](https://vuldb.com/?ip.80.85.155.80) | svr4.pcloud.ru.g.kwwwy.com | [SparklingGoblin](https://vuldb.com/?actor.sparklinggoblin) | High
3 | [91.219.237.99](https://vuldb.com/?ip.91.219.237.99) | sa1286.azar-a.net | [Molerats](https://vuldb.com/?actor.molerats) | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Spark. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Spark. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.encfs6.xml` | Medium
2 | File | `.htaccess` | Medium
3 | File | `/admin/admin_manage/delete` | High
4 | File | `/admin/video/list` | High
5 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
6 | File | `/dl/dl_sendmail.php` | High
7 | File | `/drivers/net/ethernet/broadcom/tg3.c` | High
8 | File | `/etc/passwd` | Medium
9 | File | `/etc/qci/answers` | High
10 | File | `/function/booksave.php` | High
11 | File | `/inc/campaign/campaign-delete.php` | High
12 | File | `/sgmi/` | Low
13 | File | `/tmp` | Low
14 | File | `/usr/lib/print/conv_fix` | High
15 | File | `add_comment.php` | High
16 | File | `admin.php` | Medium
17 | File | `admin/plugin.php` | High
18 | File | `admin/write-post.php` | High
19 | File | `admin\addgroup.php` | High
20 | File | `agents.php` | Medium
21 | File | `app/View/Helper/CommandHelper.php` | High
22 | File | `apport/hookutils.py` | High
23 | File | `auth_changepassword.php` | High
24 | ... | ... | ...

There are 201 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/sparklinggoblin
* https://unit42.paloaltonetworks.com/molerats-delivers-spark-backdoor/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
