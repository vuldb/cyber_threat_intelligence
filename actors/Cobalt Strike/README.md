# Cobalt Strike - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cobalt Strike](https://vuldb.com/?actor.cobalt_strike). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cobalt_strike](https://vuldb.com/?actor.cobalt_strike)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cobalt Strike:

* [US](https://vuldb.com/?country.us)
* [SV](https://vuldb.com/?country.sv)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cobalt Strike.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.82.140.91](https://vuldb.com/?ip.23.82.140.91) | - | - | High
2 | [23.108.57.108](https://vuldb.com/?ip.23.108.57.108) | - | - | High
3 | [45.134.26.174](https://vuldb.com/?ip.45.134.26.174) | - | - | High
4 | [45.144.29.185](https://vuldb.com/?ip.45.144.29.185) | master.pisyandriy.com | - | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cobalt Strike_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 4 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cobalt Strike. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?admin/user.html` | High
2 | File | `/admin/success_story.php` | High
3 | File | `/configuration/httpListenerEdit.jsf` | High
4 | File | `/etc/tomcat8/Catalina/attack` | High
5 | File | `/movie-portal-script/movie.php` | High
6 | File | `/notice-edit.php` | High
7 | File | `/resourceNode/jdbcResourceEdit.jsf` | High
8 | File | `/tmp` | Low
9 | File | `/wp-content/plugins/updraftplus/admin.php` | High
10 | File | `4.2.0.CP08` | Medium
11 | File | `account.asp` | Medium
12 | File | `acerctrl.ocx` | Medium
13 | File | `activate.php` | Medium
14 | File | `add.php` | Low
15 | File | `adm/krgourl.php` | High
16 | File | `admin.php` | Medium
17 | File | `admin/admin.php` | High
18 | File | `admin/adminaddeditdetails.php` | High
19 | File | `admin/ajaxsave.php` | High
20 | File | `admin/auth.php` | High
21 | File | `admin/images.php` | High
22 | File | `admin/import/class-import-settings.php` | High
23 | File | `ADMIN/loginaction.php` | High
24 | File | `admin/member_details.php` | High
25 | File | `admin/preview.php` | High
26 | File | `ajax/addComment.php` | High
27 | File | `and/or` | Low
28 | File | `arch/powerpc/kernel/entry_64.S` | High
29 | File | `archive_read_support_format_rar5.c` | High
30 | File | `article.php` | Medium
31 | File | `asp:.jpg` | Medium
32 | File | `auth2-gss.c` | Medium
33 | File | `backup.php` | Medium
34 | File | `bios.php` | Medium
35 | File | `blanko.preview.php` | High
36 | File | `block/bfq-iosched.c` | High
37 | File | `browse.php` | Medium
38 | File | `browse_ladies.php` | High
39 | File | `burl.c` | Low
40 | File | `cadena_ofertas_ext.php` | High
41 | File | `cal_popup.php` | High
42 | File | `category-delete.php` | High
43 | File | `category.php` | Medium
44 | File | `CFM File Handler` | High
45 | File | `cgi-bin/awstats.pl` | High
46 | File | `Change-password.php` | High
47 | File | `charts.php` | Medium
48 | File | `chat.php` | Medium
49 | File | `classified.php` | High
50 | File | `comments.php` | Medium
51 | File | `config.php` | Medium
52 | File | `core/stack/l2cap/l2cap_sm.c` | High
53 | File | `country_escorts.php` | High
54 | File | `cource.php` | Medium
55 | File | `Crypt32.dll` | Medium
56 | File | `dapur/index.php` | High
57 | File | `default.asp` | Medium
58 | ... | ... | ...

There are 509 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
* https://twitter.com/malware_traffic/status/1400876426497253379
* https://twitter.com/malware_traffic/status/1415740795622248452
* https://twitter.com/Unit42_Intel/status/1392174941181812737
* https://us-cert.cisa.gov/ncas/alerts/aa21-148a
* https://www.welivesecurity.com/2021/03/10/exchange-servers-under-siege-10-apt-groups/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
