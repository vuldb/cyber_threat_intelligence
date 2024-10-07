# Bandook - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Bandook](https://vuldb.com/?actor.bandook). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bandook](https://vuldb.com/?actor.bandook)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bandook:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Bandook.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.34.182.29](https://vuldb.com/?ip.5.34.182.29) | m.ashori | - | High
2 | [41.41.255.235](https://vuldb.com/?ip.41.41.255.235) | host-41.41.255.235.tedata.net | - | High
3 | [45.67.34.219](https://vuldb.com/?ip.45.67.34.219) | vm1684766.stark-industries.solutions | - | High
4 | [45.142.213.108](https://vuldb.com/?ip.45.142.213.108) | lv-ira.client | - | High
5 | [45.142.214.31](https://vuldb.com/?ip.45.142.214.31) | vm341765.pq.hosting | - | High
6 | [58.235.189.192](https://vuldb.com/?ip.58.235.189.192) | - | - | High
7 | [77.91.100.237](https://vuldb.com/?ip.77.91.100.237) | vm1792557.stark-industries.solutions | - | High
8 | [80.233.134.242](https://vuldb.com/?ip.80.233.134.242) | - | - | High
9 | ... | ... | ... | ...

There are 30 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Bandook_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bandook. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/adfs/ls` | Medium
3 | File | `/admin/settings/index.php?page=accounts` | High
4 | File | `/admin/sysmon.php` | High
5 | File | `/api/content/posts/comments` | High
6 | File | `/asms/classes/Master.php?f=delete_transaction` | High
7 | File | `/bin/posix/src/ports/POSIX/OpENer` | High
8 | File | `/cgi-bin/cstecgi.cgi` | High
9 | File | `/cgi-bin/editBookmark` | High
10 | File | `/cgi-bin/kerbynet` | High
11 | File | `/cgi-bin/nas_sharing.cgi` | High
12 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
13 | File | `/cgi-bin/wlogin.cgi` | High
14 | File | `/cimom` | Low
15 | File | `/classes/SystemSettings.php?f=update_settings` | High
16 | File | `/debug/pprof` | Medium
17 | File | `/domain/add` | Medium
18 | File | `/etc/pki/pesign` | High
19 | File | `/etc/sudoers` | Medium
20 | File | `/goform/addressNat` | High
21 | File | `/goform/aspForm` | High
22 | File | `/group1/uploa` | High
23 | File | `/Home/GetAttachment` | High
24 | File | `/include/menu_v.inc.php` | High
25 | File | `/index.php/weblinks-categories` | High
26 | File | `/index.php?action=profile;u=2;area=showalerts;do=remove` | High
27 | File | `/librarian/lab.php` | High
28 | File | `/login/` | Low
29 | File | `/main?cmd=invalid_browser` | High
30 | File | `/me` | Low
31 | File | `/modules/projects/vw_files.php` | High
32 | File | `/omos/admin/?page=user/list` | High
33 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
34 | File | `/out.php` | Medium
35 | File | `/panel/fields/add` | High
36 | File | `/patient/settings.php` | High
37 | File | `/proc/*/cmdline"` | High
38 | File | `/proc/pid/syscall` | High
39 | ... | ... | ...

There are 335 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/09/threat-roundup-0826-0902.html
* https://github.com/eset/malware-ioc/tree/master/bandook
* https://threatfox.abuse.ch
* https://www.fortinet.com/blog/threat-research/bandook-persistent-threat-that-keeps-evolving

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
