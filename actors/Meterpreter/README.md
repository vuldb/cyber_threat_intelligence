# Meterpreter - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Meterpreter](https://vuldb.com/?actor.meterpreter). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.meterpreter](https://vuldb.com/?actor.meterpreter)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Meterpreter:

* [US](https://vuldb.com/?country.us)
* [IO](https://vuldb.com/?country.io)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Meterpreter.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.13.17.173](https://vuldb.com/?ip.1.13.17.173) | - | - | High
2 | [1.117.145.220](https://vuldb.com/?ip.1.117.145.220) | - | - | High
3 | [3.70.110.188](https://vuldb.com/?ip.3.70.110.188) | ec2-3-70-110-188.eu-central-1.compute.amazonaws.com | - | Medium
4 | [3.137.123.63](https://vuldb.com/?ip.3.137.123.63) | ec2-3-137-123-63.us-east-2.compute.amazonaws.com | - | Medium
5 | [3.141.126.222](https://vuldb.com/?ip.3.141.126.222) | ec2-3-141-126-222.us-east-2.compute.amazonaws.com | - | Medium
6 | [3.141.204.47](https://vuldb.com/?ip.3.141.204.47) | ec2-3-141-204-47.us-east-2.compute.amazonaws.com | - | Medium
7 | [3.142.71.14](https://vuldb.com/?ip.3.142.71.14) | ec2-3-142-71-14.us-east-2.compute.amazonaws.com | - | Medium
8 | [3.142.157.76](https://vuldb.com/?ip.3.142.157.76) | ec2-3-142-157-76.us-east-2.compute.amazonaws.com | - | Medium
9 | [5.188.86.146](https://vuldb.com/?ip.5.188.86.146) | - | - | High
10 | [8.130.105.57](https://vuldb.com/?ip.8.130.105.57) | - | - | High
11 | [13.234.135.58](https://vuldb.com/?ip.13.234.135.58) | ec2-13-234-135-58.ap-south-1.compute.amazonaws.com | - | Medium
12 | [18.167.109.204](https://vuldb.com/?ip.18.167.109.204) | ec2-18-167-109-204.ap-east-1.compute.amazonaws.com | - | Medium
13 | [23.94.107.211](https://vuldb.com/?ip.23.94.107.211) | read-variation.pickexit.com | - | High
14 | [23.234.200.144](https://vuldb.com/?ip.23.234.200.144) | 144-200-234-23-dedicated.multacom.com | - | High
15 | [35.157.111.131](https://vuldb.com/?ip.35.157.111.131) | ec2-35-157-111-131.eu-central-1.compute.amazonaws.com | - | Medium
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Meterpreter_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-425 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Meterpreter. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin/?page=inmates/view_inmate` | High
4 | File | `/admin/index2.html` | High
5 | File | `/api/` | Low
6 | File | `/Api/ASF` | Medium
7 | File | `/api/v2/cli/commands` | High
8 | File | `/backend/system.html` | High
9 | File | `/debug/pprof` | Medium
10 | File | `/dvcset/sysset/set.cgi` | High
11 | File | `/edit-db.php` | Medium
12 | File | `/en/blog-comment-4` | High
13 | File | `/go/api/config/backup` | High
14 | File | `/goform/aspForm` | High
15 | File | `/goform/RgUrlBlock.asp` | High
16 | File | `/HNAP1` | Low
17 | File | `/include/stat/stat.php` | High
18 | File | `/index.php` | Medium
19 | File | `/mkshope/login.php` | High
20 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
21 | File | `/redpass.cgi` | Medium
22 | File | `/spip.php` | Medium
23 | File | `/uncpath/` | Medium
24 | File | `/user/zs_elite.php` | High
25 | File | `/usr/bin/pkexec` | High
26 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
27 | File | `/vloggers_merch/classes/Master.php?f=delete_order` | High
28 | File | `/VPortal/mgtconsole/Rights.jsp` | High
29 | File | `/webman/info.cgi` | High
30 | File | `/wp-admin/admin-ajax.php` | High
31 | File | `5.2.9\syscrb.exe` | High
32 | File | `abook_database.php` | High
33 | File | `accountrecoveryendpoint/recoverpassword.do` | High
34 | File | `admin/index.php/setting/site?tab=site_attachment` | High
35 | File | `admin/review.php` | High
36 | File | `admin_add.php` | High
37 | File | `api.php/cms/addform?fcode=1` | High
38 | File | `apps/app_article/controller/rating.php` | High
39 | File | `ashnews.php/ashheadlines.php` | High
40 | File | `attachment.do` | High
41 | File | `auth.php` | Medium
42 | File | `auth2-gss.c` | Medium
43 | File | `b/deploy/index.php` | High
44 | ... | ... | ...

There are 380 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/36159/
* https://github.com/blackorbird/APT_REPORT/blob/master/SideCopy/Network_IOCs_list_for_coverage.txt
* https://raw.githubusercontent.com/CronUp/Malware-IOCs/main/2021-12-22_MeterpreterLog4Shell
* https://threatfox.abuse.ch
* https://twitter.com/1zrr4h/status/1687060842007658496?s=46&t=wfL-ZKk9EVmg9rgncGhL4g
* https://twitter.com/500mk500/status/1585993540739665920
* https://twitter.com/pollo290987/status/1658230510617862147

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
