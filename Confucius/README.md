# Confucius - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Confucius](https://vuldb.com/?actor.confucius). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.confucius](https://vuldb.com/?actor.confucius)

## Campaigns

The following _campaigns_ are known and can be associated with Confucius:

* Tibbar

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Confucius:

* US
* CN
* GB
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Confucius.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 5.39.23.192 | ip192.ip-5-39-23.eu | - | High
2 | 5.135.85.16 | flotweb-o20.bestonthenet.fr | - | High
3 | 46.165.207.98 | - | - | High
4 | 46.165.207.99 | - | - | High
5 | 46.165.207.108 | - | - | High
6 | 46.165.207.109 | - | - | High
7 | 46.165.207.112 | - | - | High
8 | 46.165.207.113 | - | - | High
9 | ... | ... | ... | ...

There are 33 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Confucius. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Confucius. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$SPLUNK_HOME/etc/splunk-launch.conf` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin/index.php` | High
4 | File | `/admin/model/database.class.php` | High
5 | File | `/ajax/ImportCertificate` | High
6 | File | `/assets/ctx` | Medium
7 | File | `/concat?/%2557EB-INF/web.xml` | High
8 | File | `/config/getuser` | High
9 | File | `/contact/update.php` | High
10 | File | `/ext/phar/phar_object.c` | High
11 | File | `/get_getnetworkconf.cgi` | High
12 | File | `/HNAP1` | Low
13 | File | `/index.php?controller=calendar&format=raw&cat[0]=SQLi&task=events` | High
14 | File | `/login` | Low
15 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
16 | File | `/osm/REGISTER.cmd` | High
17 | File | `/product_list.php` | High
18 | File | `/replication` | Medium
19 | File | `/see_more_details.php` | High
20 | File | `/supervisor/procesa_carga.php` | High
21 | File | `/type.php` | Medium
22 | File | `/uncpath/` | Medium
23 | File | `/usr/bin/pkexec` | High
24 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
25 | File | `/zm/index.php` | High
26 | File | `4.2.0.CP09` | Medium
27 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
28 | File | `802dot1xclientcert.cgi` | High
29 | File | `addentry.php` | Medium
30 | File | `add_edit_user.asp` | High
31 | File | `admin-ajax.php` | High
32 | File | `admin.color.php` | High
33 | File | `admin.cropcanvas.php` | High
34 | File | `admin.joomlaradiov5.php` | High
35 | File | `admin.php` | Medium
36 | File | `admin/category.inc.php` | High
37 | File | `admin/conf_users_edit.php` | High
38 | File | `admin/user.php` | High
39 | File | `admin/write-post.php` | High
40 | File | `administrator/components/com_media/helpers/media.php` | High
41 | File | `admin_events.php` | High
42 | File | `ajax_new_account.php` | High
43 | File | `akocomments.php` | High
44 | File | `allopass-error.php` | High
45 | File | `announcement.php` | High
46 | File | `api_poller.php` | High
47 | File | `app.php` | Low
48 | File | `apply.cgi` | Medium
49 | File | `archiver\index.php` | High
50 | File | `artlinks.dispnew.php` | High
51 | File | `authorization.do` | High
52 | File | `awstats.pl` | Medium
53 | File | `backoffice/login.asp` | High
54 | File | `bb_usage_stats.php` | High
55 | File | `binder.c` | Medium
56 | File | `bl-kernel/ajax/upload-images.php` | High
57 | ... | ... | ...

There are 502 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/Confucius/OperationTibbar-A-retaliatory-targeted-attack-from-SouthAsian-APT-Group-Confucius.pdf
* https://www.threatminer.org/report.php?q=Confucius%C2%A0Says%E2%80%A6Malware%C2%A0Families%C2%A0Get%C2%A0Further-PaloAltoNetworks.pdf&y=2016

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
