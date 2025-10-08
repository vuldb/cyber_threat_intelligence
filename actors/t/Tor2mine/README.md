# Tor2mine - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Tor2mine](https://vuldb.com/?actor.tor2mine). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tor2mine](https://vuldb.com/?actor.tor2mine)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tor2mine:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Tor2mine.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [83.97.20.81](https://vuldb.com/?ip.83.97.20.81) | 81.20.97.83.ro.ovo.sc | - | High
2 | [83.97.20.83](https://vuldb.com/?ip.83.97.20.83) | 83.20.97.83.ro.ovo.sc | - | High
3 | [107.181.160.197](https://vuldb.com/?ip.107.181.160.197) | unallocated.layer6.net | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Tor2mine_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Tor2mine. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/.xsession-errors` | High
3 | File | `/admin/check_availability.php` | High
4 | File | `/admin/eligibility.php` | High
5 | File | `/admin/sysmon.php` | High
6 | File | `/api/content/posts/comments` | High
7 | File | `/API/info` | Medium
8 | File | `/asms/classes/Master.php?f=delete_transaction` | High
9 | File | `/cgi-bin/editBookmark` | High
10 | File | `/controllers/updatesettings.php` | High
11 | File | `/ControlManager/cgi-bin/VA/isaNVWRequest.dll` | High
12 | File | `/debug/pprof` | Medium
13 | File | `/goform/addressNat` | High
14 | File | `/goform/aspForm` | High
15 | File | `/Home/GetAttachment` | High
16 | File | `/include/menu_v.inc.php` | High
17 | File | `/librarian/lab.php` | High
18 | File | `/login/` | Low
19 | File | `/modules/projects/vw_files.php` | High
20 | File | `/omos/admin/?page=user/list` | High
21 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
22 | File | `/p` | Low
23 | File | `/panel/fields/add` | High
24 | File | `/patient/settings.php` | High
25 | File | `/proc/*/cmdline"` | High
26 | File | `/proc/pid/syscall` | High
27 | File | `/sbin/acos_service` | High
28 | File | `/secure/QueryComponent!Default.jspa` | High
29 | File | `/src/c-blosc2/plugins/codecs/ndlz/ndlz8x8.c` | High
30 | File | `/uncpath/` | Medium
31 | File | `/var/log/pcp/configs.sh` | High
32 | File | `/var/tmp/abrt/*/maps` | High
33 | File | `action.php` | Medium
34 | File | `add.asp` | Low
35 | File | `addinterviewsform.php` | High
36 | File | `admin-files/ad.php` | High
37 | File | `admin.php` | Medium
38 | File | `admin/addsptemplate.php` | High
39 | File | `admin/admin.php` | High
40 | File | `admin/index.php` | High
41 | File | `admin/limits.php` | High
42 | File | `admin/membership_pricing.php` | High
43 | File | `admin/picture/picture_real_edit.asp` | High
44 | File | `admin/plugin.php` | High
45 | File | `admin/view.asp` | High
46 | File | `adminfoot.php` | High
47 | File | `administration.php` | High
48 | File | `advertise.php` | High
49 | File | `api.php` | Low
50 | File | `appl/user_user/server.c` | High
51 | ... | ... | ...

There are 447 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/12/cryptomining-campaigns-2018.html
* https://blog.talosintelligence.com/2020/06/tor2mine-is-up-to-their-old-tricks-and_11.html
* https://github.com/sophoslabs/IoCs/blob/master/Miner-Tor2Mine.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
