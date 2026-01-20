# Spark - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Spark_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Spark:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Spark or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [SparklingGoblin](https://vuldb.com/?actor.sparklinggoblin) | High
2 | [SparkRAT](https://vuldb.com/?actor.sparkrat) | High
3 | [Molerats](https://vuldb.com/?actor.molerats) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Spark.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [38.54.94.13](https://vuldb.com/?ip.38.54.94.13) | - | [SparkRAT](https://vuldb.com/?actor.sparkrat) | High
2 | [43.140.252.169](https://vuldb.com/?ip.43.140.252.169) | - | [SparkRAT](https://vuldb.com/?actor.sparkrat) | High
3 | [54.180.27.29](https://vuldb.com/?ip.54.180.27.29) | ec2-54-180-27-29.ap-northeast-2.compute.amazonaws.com | [SparkRAT](https://vuldb.com/?actor.sparkrat) | Medium
4 | [59.22.167.217](https://vuldb.com/?ip.59.22.167.217) | - | [SparkRAT](https://vuldb.com/?actor.sparkrat) | High
5 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Spark. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Spark. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.encfs6.xml` | Medium
2 | File | `.htaccess` | Medium
3 | File | `/.vnc/sesman_${username}_passwd` | High
4 | File | `/admin/action/delete-vaccine.php` | High
5 | File | `/admin/admin_manage/delete` | High
6 | File | `/admin/edit-ambulance.php` | High
7 | File | `/admin/eligibility.php` | High
8 | File | `/admin/operations/travellers.php` | High
9 | File | `/admin/video/list` | High
10 | File | `/ajax.php?action=update_account` | High
11 | File | `/asms/classes/Master.php?f=delete_transaction` | High
12 | File | `/auth/user/all.api` | High
13 | File | `/cgformTemplateController.do?doAdd` | High
14 | File | `/cgi-bin/cstecgi.cgi` | High
15 | File | `/cgi-bin/editBookmark` | High
16 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
17 | File | `/controllers/updatesettings.php` | High
18 | File | `/course.php` | Medium
19 | File | `/dl/dl_sendmail.php` | High
20 | File | `/drivers/net/ethernet/broadcom/tg3.c` | High
21 | File | `/ecommerce/admin/products/controller.php` | High
22 | File | `/etc/passwd` | Medium
23 | File | `/etc/qci/answers` | High
24 | File | `/forum/away.php` | High
25 | File | `/function/booksave.php` | High
26 | File | `/goform/addressNat` | High
27 | File | `/goform/aspForm` | High
28 | File | `/goform/GetParentControlInfo` | High
29 | File | `/H5/versionupdate.data` | High
30 | File | `/inc/campaign/campaign-delete.php` | High
31 | File | `/include/menu_v.inc.php` | High
32 | File | `/librarian/lab.php` | High
33 | File | `/login.aspx` | Medium
34 | File | `/login.php` | Medium
35 | File | `/login/` | Low
36 | File | `/manage_laundry.php` | High
37 | File | `/omos/admin/?page=user/list` | High
38 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
39 | File | `/panel/fields/add` | High
40 | File | `/patient/settings.php` | High
41 | File | `/proc/*/cmdline"` | High
42 | ... | ... | ...

There are 367 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/52899/
* https://asec.ahnlab.com/en/53267/
* https://github.com/eset/malware-ioc/tree/master/sparklinggoblin
* https://threatfox.abuse.ch
* https://twitter.com/suyog41/status/1655524692164214784
* https://twitter.com/suyog41/status/1699438327508734306
* https://unit42.paloaltonetworks.com/molerats-delivers-spark-backdoor/
* https://urlhaus.abuse.ch/url/3612999/
* https://www.f5.com/labs/articles/threat-intelligence/delving-into-the-sparkrat-remote-access-tool
* https://www.trendmicro.com/en_us/research/24/c/teamcity-vulnerability-exploits-lead-to-jasmin-ransomware.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
