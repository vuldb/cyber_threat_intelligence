# Cobalt Strike - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cobalt Strike](https://vuldb.com/?actor.cobalt_strike). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cobalt_strike](https://vuldb.com/?actor.cobalt_strike)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cobalt Strike:

* [SV](https://vuldb.com/?country.sv)
* [US](https://vuldb.com/?country.us)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cobalt Strike.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.82.140.91](https://vuldb.com/?ip.23.82.140.91) | - | - | High
2 | [23.108.57.108](https://vuldb.com/?ip.23.108.57.108) | - | - | High
3 | [62.128.111.176](https://vuldb.com/?ip.62.128.111.176) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cobalt Strike_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1222 | CWE-275 | Permission Issues | High
4 | ... | ... | ... | ...

There are 3 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cobalt Strike. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.ssh/authorized_keys` | High
2 | File | `/?admin/user.html` | High
3 | File | `/admin/success_story.php` | High
4 | File | `/configuration/httpListenerEdit.jsf` | High
5 | File | `/etc/tomcat8/Catalina/attack` | High
6 | File | `/movie-portal-script/movie.php` | High
7 | File | `/notice-edit.php` | High
8 | File | `/resourceNode/jdbcResourceEdit.jsf` | High
9 | File | `/tmp` | Low
10 | File | `/wp-content/plugins/updraftplus/admin.php` | High
11 | File | `4.2.0.CP08` | Medium
12 | File | `account.asp` | Medium
13 | File | `acerctrl.ocx` | Medium
14 | File | `activate.php` | Medium
15 | File | `add.php` | Low
16 | File | `addressbook/csv_import.php` | High
17 | File | `adm/krgourl.php` | High
18 | File | `admin.php` | Medium
19 | File | `admin/admin.php` | High
20 | File | `admin/adminaddeditdetails.php` | High
21 | File | `admin/ajaxsave.php` | High
22 | File | `admin/auth.php` | High
23 | File | `admin/config.php` | High
24 | File | `admin/images.php` | High
25 | File | `ADMIN/loginaction.php` | High
26 | File | `admin/member_details.php` | High
27 | File | `admin/preview.php` | High
28 | File | `ajax/addComment.php` | High
29 | File | `App_Data/sb.mdb` | High
30 | File | `archive_read_support_format_rar5.c` | High
31 | File | `article.php` | Medium
32 | File | `asp:.jpg` | Medium
33 | File | `auth-options.c` | High
34 | File | `auth2-gss.c` | Medium
35 | File | `aviso.php` | Medium
36 | File | `backup.php` | Medium
37 | File | `bios.php` | Medium
38 | File | `blanko.preview.php` | High
39 | File | `blocks.php` | Medium
40 | File | `breadcrumbs_create.php` | High
41 | File | `browse.php` | Medium
42 | File | `browse_ladies.php` | High
43 | File | `burl.c` | Low
44 | File | `cadena_ofertas_ext.php` | High
45 | File | `cal_popup.php` | High
46 | File | `category-delete.php` | High
47 | File | `category.php` | Medium
48 | File | `CFM File Handler` | High
49 | File | `cgi-bin/awstats.pl` | High
50 | File | `Change-password.php` | High
51 | File | `charts.php` | Medium
52 | File | `classified.php` | High
53 | File | `client.c` | Medium
54 | File | `cmd.php` | Low
55 | File | `comment.php` | Medium
56 | File | `comments.php` | Medium
57 | File | `config.php` | Medium
58 | File | `controller/fetchpwd.php` | High
59 | File | `core/stack/l2cap/l2cap_sm.c` | High
60 | File | `country_escorts.php` | High
61 | File | `cource.php` | Medium
62 | ... | ... | ...

There are 547 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://isc.sans.edu/forums/diary/Example+of+Cobalt+Strike+from+Emotet+infection/28318/
* https://isc.sans.edu/forums/diary/Qakbot+infection+with+Cobalt+Strike+and+VNC+activity/28448/
* https://research.checkpoint.com/2019/cobalt-group-returns-to-kazakhstan/
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
