# APT-C-36 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT-C-36](https://vuldb.com/?actor.apt-c-36). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt-c-36](https://vuldb.com/?actor.apt-c-36)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT-C-36:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* ...

There are 20 more country items available. Please use our online service to access the data.

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
3 | File | `/assets/ctx` | Medium
4 | File | `/bsms/?page=products` | High
5 | File | `/cgi-bin/system_mgr.cgi` | High
6 | File | `/cloud_config/router_post/check_reg_verify_code` | High
7 | File | `/concat?/%2557EB-INF/web.xml` | High
8 | File | `/config/getuser` | High
9 | File | `/debug/pprof` | Medium
10 | File | `/ext/phar/phar_object.c` | High
11 | File | `/filemanager/php/connector.php` | High
12 | File | `/get_getnetworkconf.cgi` | High
13 | File | `/HNAP1` | Low
14 | File | `/include/chart_generator.php` | High
15 | File | `/index.php?controller=calendar&format=raw&cat[0]=SQLi&task=events` | High
16 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
17 | File | `/modx/manager/index.php` | High
18 | File | `/osm/REGISTER.cmd` | High
19 | File | `/product_list.php` | High
20 | File | `/replication` | Medium
21 | File | `/siteminderagent/pwcgi/smpwservicescgi.exe` | High
22 | File | `/supervisor/procesa_carga.php` | High
23 | File | `/type.php` | Medium
24 | File | `/uncpath/` | Medium
25 | File | `/usr/bin/pkexec` | High
26 | File | `/zm/index.php` | High
27 | File | `4.2.0.CP09` | Medium
28 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
29 | File | `802dot1xclientcert.cgi` | High
30 | File | `add.exe` | Low
31 | File | `addentry.php` | Medium
32 | File | `admin-ajax.php` | High
33 | File | `admin.color.php` | High
34 | File | `admin.cropcanvas.php` | High
35 | File | `admin.joomlaradiov5.php` | High
36 | File | `admin.php` | Medium
37 | File | `admin.php?m=Food&a=addsave` | High
38 | File | `admin/conf_users_edit.php` | High
39 | File | `admin/index.php` | High
40 | File | `admin/user.php` | High
41 | File | `admin/write-post.php` | High
42 | File | `administrator/components/com_media/helpers/media.php` | High
43 | File | `admin_events.php` | High
44 | File | `ajax_new_account.php` | High
45 | File | `akocomments.php` | High
46 | File | `allopass-error.php` | High
47 | File | `announcement.php` | High
48 | File | `apply.cgi` | Medium
49 | File | `archiver\index.php` | High
50 | File | `artlinks.dispnew.php` | High
51 | File | `auth.inc.php` | Medium
52 | File | `authorization.do` | High
53 | File | `awstats.pl` | Medium
54 | File | `bb_usage_stats.php` | High
55 | File | `binder.c` | Medium
56 | File | `books.php` | Medium
57 | File | `C:\Python27` | Medium
58 | ... | ... | ...

There are 510 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://web.archive.org/web/20190625182633if_/https://ti.360.net/blog/articles/apt-c-36-continuous-attacks-targeting-colombian-government-institutions-and-corporations-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
