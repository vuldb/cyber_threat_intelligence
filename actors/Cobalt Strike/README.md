# Cobalt Strike - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cobalt Strike](https://vuldb.com/?actor.cobalt_strike). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cobalt_strike](https://vuldb.com/?actor.cobalt_strike)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cobalt Strike:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cobalt Strike.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.255.98.144](https://vuldb.com/?ip.5.255.98.144) | - | - | High
2 | [23.19.227.147](https://vuldb.com/?ip.23.19.227.147) | - | - | High
3 | [23.81.246.32](https://vuldb.com/?ip.23.81.246.32) | - | - | High
4 | [23.82.140.91](https://vuldb.com/?ip.23.82.140.91) | - | - | High
5 | [23.108.57.39](https://vuldb.com/?ip.23.108.57.39) | - | - | High
6 | [23.108.57.108](https://vuldb.com/?ip.23.108.57.108) | - | - | High
7 | [23.227.199.10](https://vuldb.com/?ip.23.227.199.10) | 23-227-199-10.static.hvvc.us | - | High
8 | [45.134.26.174](https://vuldb.com/?ip.45.134.26.174) | - | - | High
9 | ... | ... | ... | ...

There are 33 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cobalt Strike_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cobalt Strike. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/success_story.php` | High
2 | File | `/category.php` | High
3 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
4 | File | `/etc/tomcat8/Catalina/attack` | High
5 | File | `/movie-portal-script/movie.php` | High
6 | File | `/notice-edit.php` | High
7 | File | `/objects/getSpiritsFromVideo.php` | High
8 | File | `/servlet/webacc` | High
9 | File | `/TeamMate/Upload/DomainObjectDocumentUpload.ashx` | High
10 | File | `/tmp` | Low
11 | File | `/uncpath/` | Medium
12 | File | `/wp-admin/admin-ajax.php` | High
13 | File | `/wp-content/plugins/updraftplus/admin.php` | High
14 | File | `4.2.0.CP08` | Medium
15 | File | `account.asp` | Medium
16 | File | `acerctrl.ocx` | Medium
17 | File | `activate.php` | Medium
18 | File | `add.php` | Low
19 | File | `admin.php` | Medium
20 | File | `admin/admin.php` | High
21 | File | `admin/adminaddeditdetails.php` | High
22 | File | `admin/class-jtrt-responsive-tables-admin.php` | High
23 | File | `admin/images.php` | High
24 | File | `admin/import/class-import-settings.php` | High
25 | File | `admin/infoclass_update.php` | High
26 | File | `admin/member_details.php` | High
27 | File | `admin/preview.php` | High
28 | File | `ajax/addComment.php` | High
29 | File | `allocate_block.cpp` | High
30 | File | `and/or` | Low
31 | File | `app/code/core/Mage/Rss/Helper/Order.php` | High
32 | File | `arch/powerpc/kernel/entry_64.S` | High
33 | File | `archive_read_support_format_rar5.c` | High
34 | File | `article.php` | Medium
35 | File | `asmjs/asmangle.cpp` | High
36 | File | `asp:.jpg` | Medium
37 | File | `auth2-gss.c` | Medium
38 | File | `backup.php` | Medium
39 | File | `bios.php` | Medium
40 | File | `blanko.preview.php` | High
41 | File | `block/bfq-iosched.c` | High
42 | File | `books.php` | Medium
43 | File | `browse_ladies.php` | High
44 | File | `burl.c` | Low
45 | File | `cadena_ofertas_ext.php` | High
46 | File | `category-delete.php` | High
47 | File | `category.php` | Medium
48 | File | `CFM File Handler` | High
49 | File | `cgi-bin/awstats.pl` | High
50 | File | `cgi-bin/write.cgi` | High
51 | File | `Change-password.php` | High
52 | File | `chat.php` | Medium
53 | ... | ... | ...

There are 460 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/forums/diary/April+2021+Forensic+Quiz+Answers+and+Analysis/27308/
* https://isc.sans.edu/forums/diary/Attackers+Exploiting+WebLogic+Servers+via+CVE202014882+to+install+Cobalt+Strike/26752/
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
* https://twitter.com/malware_traffic/status/1400876426497253379
* https://twitter.com/malware_traffic/status/1415740795622248452
* https://twitter.com/TheDFIRReport/status/1508451341844168706
* https://twitter.com/Unit42_Intel/status/1392174941181812737
* https://us-cert.cisa.gov/ncas/alerts/aa21-148a
* https://www.welivesecurity.com/2021/03/10/exchange-servers-under-siege-10-apt-groups/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
