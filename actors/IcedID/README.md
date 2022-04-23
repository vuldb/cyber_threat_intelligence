# IcedID - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [IcedID](https://vuldb.com/?actor.icedid). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.icedid](https://vuldb.com/?actor.icedid)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with IcedID:

* [US](https://vuldb.com/?country.us)
* [SC](https://vuldb.com/?country.sc)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of IcedID.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.149.252.179](https://vuldb.com/?ip.5.149.252.179) | hnh7.arenal.xyz | - | High
2 | [31.24.224.12](https://vuldb.com/?ip.31.24.224.12) | 1f18e00c.setaptr.net | - | High
3 | [31.24.228.170](https://vuldb.com/?ip.31.24.228.170) | 31.24.228.170.static.midphase.com | - | High
4 | [31.184.199.11](https://vuldb.com/?ip.31.184.199.11) | dalesmanager.com | - | High
5 | [45.129.99.241](https://vuldb.com/?ip.45.129.99.241) | 354851-vds-mamozw.gmhost.pp.ua | - | High
6 | [45.138.172.179](https://vuldb.com/?ip.45.138.172.179) | - | - | High
7 | [45.147.228.198](https://vuldb.com/?ip.45.147.228.198) | - | - | High
8 | [45.147.230.82](https://vuldb.com/?ip.45.147.230.82) | - | - | High
9 | [45.147.230.88](https://vuldb.com/?ip.45.147.230.88) | mailnode7.bulletproof-mail.biz | - | High
10 | [45.147.231.113](https://vuldb.com/?ip.45.147.231.113) | - | - | High
11 | [45.153.240.135](https://vuldb.com/?ip.45.153.240.135) | - | - | High
12 | [45.153.241.115](https://vuldb.com/?ip.45.153.241.115) | - | - | High
13 | [46.17.98.191](https://vuldb.com/?ip.46.17.98.191) | - | - | High
14 | [46.249.62.199](https://vuldb.com/?ip.46.249.62.199) | - | - | High
15 | [79.141.161.176](https://vuldb.com/?ip.79.141.161.176) | zzs7bp73.copycomdigital.com | - | High
16 | [79.141.164.241](https://vuldb.com/?ip.79.141.164.241) | x6ts.mtsgamingpro.fun | - | High
17 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _IcedID_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
2 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
3 | T1068 | CWE-264, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by IcedID. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.vnc/sesman_${username}_passwd` | High
2 | File | `/admin-document/@@share` | High
3 | File | `/admin/index.php` | High
4 | File | `/anony/mjpg.cgi` | High
5 | File | `/bin/sh` | Low
6 | File | `/cgi-bin/editBookmark` | High
7 | File | `/etc/shadow` | Medium
8 | File | `/EXCU_SHELL` | Medium
9 | File | `/export` | Low
10 | File | `/GetSimpleCMS-3.3.15/admin/log.php` | High
11 | File | `/goform/addressNat` | High
12 | File | `/iisadmpwd` | Medium
13 | File | `/include/menu_v.inc.php` | High
14 | File | `/lms/admin.php` | High
15 | File | `/mc` | Low
16 | File | `/opt/IBM/es/lib/libffq.cryptionjni.so` | High
17 | File | `/opt/novell/ncl/bin/nwrights` | High
18 | File | `/out.php` | Medium
19 | File | `/proc/*/cmdline"` | High
20 | File | `/proc/pid/syscall` | High
21 | File | `/rest/review-coverage-chart/1.0/data/<repository_name>/.json` | High
22 | File | `/uncpath/` | Medium
23 | File | `/var/log/pcp/configs.sh` | High
24 | File | `/webconsole/APIController` | High
25 | File | `/WWW//app/admin/controller/admincontroller.php` | High
26 | File | `a-b-membres.php` | High
27 | File | `action.php` | Medium
28 | File | `admin-search.php` | High
29 | File | `admin.jcomments.php` | High
30 | File | `admin/adminsignin.html` | High
31 | File | `admin/index.php` | High
32 | File | `admin/plugin.php` | High
33 | File | `admin/test.php` | High
34 | File | `admin/versions.html` | High
35 | File | `administrator/index.php?option=com_pago&view=comments` | High
36 | File | `Adminlog.asp` | Medium
37 | File | `admin_iplog.php` | High
38 | File | `ajax.php` | Medium
39 | File | `ajax_admin_apis.php` | High
40 | File | `ajax_php_pecl.php` | High
41 | File | `antserver.exe` | High
42 | File | `api.cc` | Low
43 | File | `api/ApiQueryCheckUser.php` | High
44 | File | `app/helpers/application_helper.rb` | High
45 | File | `app\conference_controls\conference_control_details.php` | High
46 | File | `apt/package.py` | High
47 | File | `arch/x86/include/asm/uaccess.h` | High
48 | File | `architext.conf` | High
49 | File | `archive/savedqueries/savequeryfinish.html` | High
50 | ... | ... | ...

There are 432 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/04/icedid-banking-trojan.html
* https://isc.sans.edu/forums/diary/Analysis+from+March+2021+Traffic+Analysis+Quiz/27232/
* https://isc.sans.edu/forums/diary/Emotet+infection+with+IcedID+banking+Trojan/24312/
* https://isc.sans.edu/forums/diary/Emotet+infections+and+followup+malware/24532/
* https://isc.sans.edu/forums/diary/Malspam+links+to+passwordprotected+Word+docs+that+push+IcedID+Bokbot/24428/
* https://isc.sans.edu/forums/diary/Malspam+with+links+to+Word+docs+pushes+IcedID+Bokbot/25640/
* https://isc.sans.edu/forums/diary/Malspam+with+passwordprotected+word+docs+still+pushing+IcedID+Bokbot+with+Trickbot/24708/
* https://isc.sans.edu/forums/diary/Microsoft+Word+document+with+malicious+macro+pushes+IcedID+Bokbot/26146/
* https://isc.sans.edu/forums/diary/One+Emotet+infection+leads+to+three+followup+malware+infections/24140/
* https://research.checkpoint.com/2021/melting-ice-tracking-icedid-servers-with-a-few-simple-steps/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
