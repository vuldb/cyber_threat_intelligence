# Lockbit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lockbit](https://vuldb.com/?actor.lockbit). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lockbit](https://vuldb.com/?actor.lockbit)

## Campaigns

The following _campaigns_ are known and can be associated with Lockbit:

* South Korea

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lockbit:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lockbit.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [35.194.251.0](https://vuldb.com/?ip.35.194.251.0) | 0.251.194.35.bc.googleusercontent.com | - | Medium
2 | [45.32.108.54](https://vuldb.com/?ip.45.32.108.54) | 45.32.108.54.vultrusercontent.com | - | High
3 | [45.91.83.176](https://vuldb.com/?ip.45.91.83.176) | - | - | High
4 | [45.227.255.190](https://vuldb.com/?ip.45.227.255.190) | - | - | High
5 | [51.15.18.180](https://vuldb.com/?ip.51.15.18.180) | 51-15-18-180.rev.poneytelecom.eu | - | High
6 | [51.89.134.150](https://vuldb.com/?ip.51.89.134.150) | postal.sendovo.net | - | High
7 | [52.237.96.13](https://vuldb.com/?ip.52.237.96.13) | - | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lockbit_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lockbit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/config.php?display=disa&view=form` | High
2 | File | `/admin/link/link_ok.php` | High
3 | File | `/advanced-tools/nova/bin/netwatch` | High
4 | File | `/cameras/XXXX/clips` | High
5 | File | `/category_view.php` | High
6 | File | `/cgi-bin/admin/testserver.cgi` | High
7 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
8 | File | `/cimom` | Low
9 | File | `/download` | Medium
10 | File | `/etc/sudoers` | Medium
11 | File | `/export` | Low
12 | File | `/forum/away.php` | High
13 | File | `/getcfg.php` | Medium
14 | File | `/icingaweb2/navigation/add` | High
15 | File | `/modules/projects/vw_files.php` | High
16 | File | `/netflow/jspui/addMailSettings.jsp` | High
17 | File | `/out.php` | Medium
18 | File | `/owa/auth/logon.aspx` | High
19 | File | `/recordings/index.php` | High
20 | File | `/sec/content/sec_asa_users_local_db_add.html` | High
21 | File | `/secure/QueryComponent!Default.jspa` | High
22 | File | `/spip.php` | Medium
23 | File | `/src/Illuminate/Laravel.php` | High
24 | File | `/student/bookdetails.php` | High
25 | File | `/uncpath/` | Medium
26 | File | `/usr/bin/pkexec` | High
27 | File | `/var/log/nginx` | High
28 | File | `/webmail/` | Medium
29 | File | `/wp-admin/admin-ajax.php` | High
30 | File | `/wp-admin/options.php` | High
31 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
32 | File | `adclick.php` | Medium
33 | File | `addmem.php` | Medium
34 | File | `add_user.php` | Medium
35 | File | `admin.php` | Medium
36 | File | `admin.remository.php` | High
37 | File | `admin/admin.asp` | High
38 | File | `adminHome.php` | High
39 | File | `admin_add.php` | High
40 | File | `affich.php` | Medium
41 | ... | ... | ...

There are 354 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/158/lockbit-ransomware-iocs/
* https://blog.cyble.com/2023/06/06/lockbit-2-0-ransomware-resurfaces/
* https://github.com/hvs-consulting/ioc_signatures/blob/main/Proxyshell/HvS_Proxyshell_2021_09_IOCs.csv
* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-LockBit.csv
* https://thedfirreport.com/2020/06/10/lockbit-ransomware-why-you-no-spread/
* https://threatfox.abuse.ch
* https://twitter.com/OscarAldana/status/1548457335852437506
* https://www.cybereason.com/blog/threat-analysis-report-lockbit-2.0-all-paths-lead-to-ransom
* https://www.ic3.gov/Media/News/2022/220204.pdf
* https://www.mcafee.com/blogs/other-blogs/mcafee-labs/tales-from-the-trenches-a-lockbit-ransomware-story/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
