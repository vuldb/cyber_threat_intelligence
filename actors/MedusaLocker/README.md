# MedusaLocker - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MedusaLocker](https://vuldb.com/?actor.medusalocker). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.medusalocker](https://vuldb.com/?actor.medusalocker)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MedusaLocker:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MedusaLocker.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [40.92.90.105](https://vuldb.com/?ip.40.92.90.105) | mail-vi1eur05olkn2105.outbound.protection.outlook.com | - | High
2 | [45.146.164.141](https://vuldb.com/?ip.45.146.164.141) | - | - | High
3 | [50.80.219.149](https://vuldb.com/?ip.50.80.219.149) | 50-80-219-149.client.mchsi.com | - | High
4 | [84.38.189.52](https://vuldb.com/?ip.84.38.189.52) | wmw10.empresagozalez.miami | - | High
5 | [87.251.75.71](https://vuldb.com/?ip.87.251.75.71) | - | - | High
6 | ... | ... | ... | ...

There are 19 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MedusaLocker_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MedusaLocker. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/action/import_https_cert_file/` | High
2 | File | `/action/remove/` | High
3 | File | `/admin/featured.php` | High
4 | File | `/admin/scheprofile.cgi` | High
5 | File | `/admin/showbad.php` | High
6 | File | `/admin/ztliuyan_sendmail.php` | High
7 | File | `/ajax/config_rollback/` | High
8 | File | `/alarm_pi/alarmService.php` | High
9 | File | `/cgi-bin/webproc` | High
10 | File | `/ci_hms/massage_room/edit/1` | High
11 | File | `/ci_hms/search` | High
12 | File | `/company` | Medium
13 | File | `/company/service/increment/add/im` | High
14 | File | `/dashboard/blocks/stacks/view_details/` | High
15 | File | `/dashboard/reports/logs/view` | High
16 | File | `/dashboard/snapshot/*?orgId=0` | High
17 | File | `/dashboard/system/express/entities/forms/save_control/[GUID]` | High
18 | File | `/dl/dl_sendmail.php` | High
19 | File | `/dl/dl_sendsms.php` | High
20 | File | `/home/campus/campus_job` | High
21 | File | `/home/job/index` | High
22 | File | `/IISADMPWD` | Medium
23 | File | `/images/background/1.php` | High
24 | File | `/irj/servlet/prt/portal/prtroot/com.sap.portal.usermanagement.admin.UserMapping` | High
25 | File | `/job` | Low
26 | File | `/linkedcontent/editfolder.php` | High
27 | File | `/loginsave.php` | High
28 | File | `/mobilebroker/ServiceToBroker.svc/Json/Connect` | High
29 | File | `/modules/mindmap/index.php` | High
30 | File | `/odfs/posts/view_post.php` | High
31 | ... | ... | ...

There are 259 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cisa.gov/uscert/ncas/alerts/aa22-181a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
