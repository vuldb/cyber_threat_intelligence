# APT-C-36 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT-C-36](https://vuldb.com/?actor.apt-c-36). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt-c-36](https://vuldb.com/?actor.apt-c-36)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT-C-36:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT-C-36.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [128.90.106.22](https://vuldb.com/?ip.128.90.106.22) | undefined.hostname.localhost | - | High
2 | [128.90.107.21](https://vuldb.com/?ip.128.90.107.21) | undefined.hostname.localhost | - | High
3 | [128.90.107.189](https://vuldb.com/?ip.128.90.107.189) | undefined.hostname.localhost | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT-C-36_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT-C-36. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$SPLUNK_HOME/etc/splunk-launch.conf` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin_page/all-files-update-ajax.php` | High
4 | File | `/assets/ctx` | Medium
5 | File | `/bsms/?page=products` | High
6 | File | `/cgi-bin/system_mgr.cgi` | High
7 | File | `/cloud_config/router_post/check_reg_verify_code` | High
8 | File | `/concat?/%2557EB-INF/web.xml` | High
9 | File | `/config/getuser` | High
10 | File | `/debug/pprof` | Medium
11 | File | `/dms/admin/reports/daily_collection_report.php` | High
12 | File | `/ext/phar/phar_object.c` | High
13 | File | `/filemanager/php/connector.php` | High
14 | File | `/get_getnetworkconf.cgi` | High
15 | File | `/HNAP1` | Low
16 | File | `/include/chart_generator.php` | High
17 | File | `/index.php?controller=calendar&format=raw&cat[0]=SQLi&task=events` | High
18 | File | `/info.cgi` | Medium
19 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
20 | File | `/mgmt/tm/util/bash` | High
21 | File | `/modx/manager/index.php` | High
22 | File | `/osm/REGISTER.cmd` | High
23 | File | `/replication` | Medium
24 | File | `/siteminderagent/pwcgi/smpwservicescgi.exe` | High
25 | File | `/spip.php` | Medium
26 | File | `/supervisor/procesa_carga.php` | High
27 | File | `/type.php` | Medium
28 | File | `/uncpath/` | Medium
29 | File | `/usr/bin/pkexec` | High
30 | File | `/Wedding-Management/package_detail.php` | High
31 | File | `/zm/index.php` | High
32 | File | `4.2.0.CP09` | Medium
33 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
34 | File | `802dot1xclientcert.cgi` | High
35 | File | `a2billing/customer/iridium_threed.php` | High
36 | File | `add.exe` | Low
37 | File | `admin-ajax.php` | High
38 | File | `admin.color.php` | High
39 | File | `admin.cropcanvas.php` | High
40 | File | `admin.joomlaradiov5.php` | High
41 | File | `admin.php` | Medium
42 | File | `admin.php?m=Food&a=addsave` | High
43 | File | `admin/conf_users_edit.php` | High
44 | File | `admin/index.php` | High
45 | File | `admin/limits.php` | High
46 | File | `admin/user.php` | High
47 | File | `admin/write-post.php` | High
48 | File | `administrator/components/com_media/helpers/media.php` | High
49 | File | `admin_events.php` | High
50 | File | `akocomments.php` | High
51 | File | `allopass-error.php` | High
52 | File | `announcement.php` | High
53 | File | `apply.cgi` | Medium
54 | File | `appointment.php` | High
55 | File | `archiver\index.php` | High
56 | File | `artlinks.dispnew.php` | High
57 | File | `auth.inc.php` | Medium
58 | File | `authorization.do` | High
59 | File | `bb_usage_stats.php` | High
60 | File | `binder.c` | Medium
61 | ... | ... | ...

There are 530 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://web.archive.org/web/20190625182633if_/https://ti.360.net/blog/articles/apt-c-36-continuous-attacks-targeting-colombian-government-institutions-and-corporations-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
