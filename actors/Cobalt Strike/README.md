# Cobalt Strike - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cobalt Strike](https://vuldb.com/?actor.cobalt_strike). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cobalt_strike](https://vuldb.com/?actor.cobalt_strike)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cobalt Strike:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [JP](https://vuldb.com/?country.jp)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cobalt Strike.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.252.177.199](https://vuldb.com/?ip.5.252.177.199) | 5-252-177-199.mivocloud.com | - | High
2 | [5.255.98.144](https://vuldb.com/?ip.5.255.98.144) | - | - | High
3 | [23.19.227.147](https://vuldb.com/?ip.23.19.227.147) | - | - | High
4 | [23.81.246.32](https://vuldb.com/?ip.23.81.246.32) | - | - | High
5 | [23.82.140.91](https://vuldb.com/?ip.23.82.140.91) | - | - | High
6 | [23.108.57.39](https://vuldb.com/?ip.23.108.57.39) | - | - | High
7 | [23.108.57.108](https://vuldb.com/?ip.23.108.57.108) | - | - | High
8 | [23.160.193.55](https://vuldb.com/?ip.23.160.193.55) | unknown.ip-xfer.net | - | High
9 | [23.227.194.86](https://vuldb.com/?ip.23.227.194.86) | 23-227-194-86.static.hvvc.us | - | High
10 | [23.227.199.10](https://vuldb.com/?ip.23.227.199.10) | 23-227-199-10.static.hvvc.us | - | High
11 | [37.0.8.252](https://vuldb.com/?ip.37.0.8.252) | - | - | High
12 | [37.120.198.225](https://vuldb.com/?ip.37.120.198.225) | - | - | High
13 | [45.15.131.96](https://vuldb.com/?ip.45.15.131.96) | - | - | High
14 | [45.66.158.14](https://vuldb.com/?ip.45.66.158.14) | 14.158-66-45.rdns.scalabledns.com | - | High
15 | [45.134.26.174](https://vuldb.com/?ip.45.134.26.174) | - | - | High
16 | [45.144.29.185](https://vuldb.com/?ip.45.144.29.185) | master.pisyandriy.com | - | High
17 | [45.197.132.72](https://vuldb.com/?ip.45.197.132.72) | - | - | High
18 | [46.165.254.166](https://vuldb.com/?ip.46.165.254.166) | - | - | High
19 | [51.15.76.60](https://vuldb.com/?ip.51.15.76.60) | 60-76-15-51.instances.scw.cloud | - | High
20 | [51.68.91.152](https://vuldb.com/?ip.51.68.91.152) | - | - | High
21 | [51.68.93.185](https://vuldb.com/?ip.51.68.93.185) | - | - | High
22 | ... | ... | ... | ...

There are 85 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cobalt Strike_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cobalt Strike. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/.dbus-keyrings` | High
3 | File | `//proc/kcore` | Medium
4 | File | `/acms/classes/Master.php?f=delete_img` | High
5 | File | `/admin.php/Label/page_del` | High
6 | File | `/admin.php/vod/admin/topic/del` | High
7 | File | `/admin/dl_sendmail.php` | High
8 | File | `/admin/dl_sendsms.php` | High
9 | File | `/admin/edit_admin_details.php?id=admin` | High
10 | File | `/admin/generalsettings.php` | High
11 | File | `/admin/payment.php` | High
12 | File | `/admin/reports.php` | High
13 | File | `/admin_page/all-files-update-ajax.php` | High
14 | File | `/api/part_categories` | High
15 | File | `/api/programs/orgUnits?programs` | High
16 | File | `/api/students/me/courses/` | High
17 | File | `/api/user/userData?userCode=admin` | High
18 | File | `/Applications/Utilities/Terminal` | High
19 | File | `/asms/classes/Master.php?f=delete_product` | High
20 | File | `/asms/classes/Master.php?f=save_product` | High
21 | File | `/bcms/admin/?page=reports/daily_court_rental_report` | High
22 | File | `/bsms/?page=manage_account` | High
23 | File | `/cgi-bin/kerbynet` | High
24 | File | `/checklogin.jsp` | High
25 | File | `/classes/master.php?f=delete_facility` | High
26 | File | `/classes/Master.php?f=delete_reservation` | High
27 | File | `/classes/Master.php?f=delete_schedule` | High
28 | File | `/College_Management_System/admin/display-teacher.php` | High
29 | File | `/company` | Medium
30 | File | `/company/service/increment/add/im` | High
31 | File | `/ctpms/admin/?page=applications/view_application` | High
32 | File | `/ctpms/admin/?page=individuals/view_individual` | High
33 | File | `/ctpms/admin/individuals/update_status.php` | High
34 | File | `/dashboard/system/express/entities/forms/save_control/[GUID]` | High
35 | File | `/dms/admin/reports/daily_collection_report.php` | High
36 | File | `/ecrire` | Low
37 | File | `/forum/away.php` | High
38 | File | `/goform/aspForm` | High
39 | File | `/goform/saveParentControlInfo` | High
40 | ... | ... | ...

There are 340 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/20130/
* https://asec.ahnlab.com/en/27646/
* https://blog.cyble.com/2022/05/20/malware-campaign-targets-infosec-community-threat-actor-uses-fake-proof-of-concept-to-deliver-cobalt-strike-beacon/
* https://blog.morphisec.com/log4j-exploit-targets-vulnerable-unifi-network-applications
* https://blog.talosintelligence.com/2020/06/indigodrop-maldocs-cobalt-strike.html
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-17%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-18%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-26%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-08-31%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-02%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-08%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-09%20Hancitor%20IOCd
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-13%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-14%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-15%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-16%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-22%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-23%20Hancitor%20IOCs
* https://github.com/executemalware/Malware-IOCs/blob/main/2021-09-29%20Hancitor%20IOCs
* https://isc.sans.edu/forums/diary/April+2021+Forensic+Quiz+Answers+and+Analysis/27308/
* https://isc.sans.edu/forums/diary/Attackers+Exploiting+WebLogic+Servers+via+CVE202014882+to+install+Cobalt+Strike/26752/
* https://isc.sans.edu/forums/diary/Case+Study+Cobalt+Strike+Server+Lives+on+After+Its+Domain+Is+Suspended/28804/
* https://isc.sans.edu/forums/diary/Example+of+Cobalt+Strike+from+Emotet+infection/28318/
* https://isc.sans.edu/forums/diary/Excel+spreadsheets+push+SystemBC+malware/27060/
* https://isc.sans.edu/forums/diary/June+2021+Forensic+Contest+Answers+and+Analysis/27582/
* https://isc.sans.edu/forums/diary/Qakbot+infection+with+Cobalt+Strike+and+VNC+activity/28448/
* https://isc.sans.edu/forums/diary/Qakbot+infection+with+Cobalt+Strike/27158/
* https://research.checkpoint.com/2019/cobalt-group-returns-to-kazakhstan/
* https://securelist.com/owowa-credential-stealer-and-remote-access/105219/
* https://thedfirreport.com/2021/01/11/trickbot-still-alive-and-well/
* https://thedfirreport.com/2021/05/02/trickbot-brief-creds-and-beacons/
* https://thedfirreport.com/2021/05/12/conti-ransomware/
* https://thedfirreport.com/2021/06/20/from-word-to-lateral-movement-in-1-hour/
* https://thedfirreport.com/2021/08/01/bazarcall-to-conti-ransomware-via-trickbot-and-cobalt-strike/
* https://thedfirreport.com/2021/08/16/trickbot-leads-up-to-fake-1password-installation/
* https://thedfirreport.com/2021/10/18/icedid-to-xinglocker-ransomware-in-24-hours/
* https://thedfirreport.com/2021/11/29/continuing-the-bazar-ransomware-story/
* https://thedfirreport.com/2021/12/13/diavol-ransomware/
* https://thedfirreport.com/2022/02/21/qbot-and-zerologon-lead-to-full-domain-compromise/
* https://thedfirreport.com/2022/05/09/seo-poisoning-a-gootloader-story/
* https://twitter.com/malware_traffic/status/1400876426497253379
* https://twitter.com/malware_traffic/status/1415740795622248452
* https://twitter.com/TheDFIRReport/status/1508451341844168706
* https://twitter.com/Unit42_Intel/status/1392174941181812737
* https://us-cert.cisa.gov/ncas/alerts/aa21-148a
* https://www.malware-traffic-analysis.net/2022/06/07/index2.html
* https://www.welivesecurity.com/2021/03/10/exchange-servers-under-siege-10-apt-groups/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
