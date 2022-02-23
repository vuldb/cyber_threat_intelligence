# FIN7 - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [FIN7](https://vuldb.com/?actor.fin7). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fin7](https://vuldb.com/?actor.fin7)

## Campaigns

The following _campaigns_ are known and can be associated with FIN7:

* AveMaria
* OpBlueRaven

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with FIN7:

* US
* CN
* DE
* ...

There are 26 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of FIN7.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 1.3.6.1 | - | - | High
2 | 2.16.840.1 | - | - | High
3 | 4.1.311.10 | - | - | High
4 | 5.8.88.64 | - | - | High
5 | 5.9.189.40 | static.40.189.9.5.clients.your-server.de | - | High
6 | 5.10.40.54 | dsl-5-10-40-54.pool.bitel.net | - | High
7 | 5.61.32.118 | - | - | High
8 | 5.61.38.52 | - | - | High
9 | 5.135.73.113 | - | - | High
10 | 5.149.250.235 | snigist.co.uk | - | High
11 | 5.149.250.241 | flipveranda.co.uk | - | High
12 | 5.149.252.144 | - | - | High
13 | 5.149.253.126 | - | - | High
14 | 5.188.10.102 | - | - | High
15 | 5.188.10.248 | - | - | High
16 | 5.199.169.188 | - | - | High
17 | 5.252.177.23 | 5-252-177-23.mivocloud.com | OpBlueRaven | High
18 | 5.252.177.37 | no-rdns.mivocloud.com | OpBlueRaven | High
19 | 8.28.175.68 | phoenixartisanacoutrements.com | - | High
20 | 23.83.133.119 | - | OpBlueRaven | High
21 | 23.249.162.161 | - | - | High
22 | 31.7.61.136 | hosted-by.securefastserver.com | - | High
23 | 31.18.219.133 | ip1f12db85.dynamic.kabel-deutschland.de | - | High
24 | 31.131.17.125 | - | - | High
25 | 31.131.17.127 | automarinetechnology.com | - | High
26 | 31.131.17.128 | - | - | High
27 | 31.148.219.18 | - | - | High
28 | 31.148.219.44 | - | - | High
29 | 31.148.219.126 | - | - | High
30 | 31.148.219.141 | - | - | High
31 | 31.148.220.107 | - | - | High
32 | 31.148.220.215 | - | - | High
33 | 31.184.234.66 | - | - | High
34 | 31.184.234.71 | - | - | High
35 | 37.1.211.239 | ourdrops.org | OpBlueRaven | High
36 | 37.1.215.4 | - | OpBlueRaven | High
37 | 37.1.215.72 | - | OpBlueRaven | High
38 | 37.235.54.48 | 48.54.235.37.in-addr.arpa | - | High
39 | 37.252.4.131 | - | OpBlueRaven | High
40 | 45.77.60.230 | 45.77.60.230.vultr.com | OpBlueRaven | Medium
41 | 45.77.204.130 | 45.77.204.130.vultr.com | OpBlueRaven | Medium
42 | 45.87.152.64 | free.pq.hosting | OpBlueRaven | High
43 | 45.133.216.25 | lisulisimp.example.com | OpBlueRaven | High
44 | ... | ... | ... | ...

There are 172 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by FIN7. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by FIN7. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/context/%2e/WEB-INF/web.xml` | High
3 | File | `/ext/phar/phar_object.c` | High
4 | File | `/filemanager/php/connector.php` | High
5 | File | `/get_getnetworkconf.cgi` | High
6 | File | `/HNAP1` | Low
7 | File | `/modx/manager/index.php` | High
8 | File | `/monitoring` | Medium
9 | File | `/new` | Low
10 | File | `/proc/<pid>/status` | High
11 | File | `/public/plugins/` | High
12 | File | `/replication` | Medium
13 | File | `/secure/QueryComponent!Default.jspa` | High
14 | File | `/siteminderagent/pwcgi/smpwservicescgi.exe` | High
15 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
16 | File | `/tmp` | Low
17 | File | `/type.php` | Medium
18 | File | `/uncpath/` | Medium
19 | File | `/usr/bin/pkexec` | High
20 | File | `/wp-json/wc/v3/webhooks` | High
21 | File | `4.2.0.CP09` | Medium
22 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
23 | File | `802dot1xclientcert.cgi` | High
24 | File | `AccountManagerService.java` | High
25 | File | `actions/CompanyDetailsSave.php` | High
26 | File | `add.exe` | Low
27 | File | `admin.color.php` | High
28 | File | `admin.cropcanvas.php` | High
29 | File | `admin.joomlaradiov5.php` | High
30 | File | `admin.php` | Medium
31 | File | `admin.php?m=Food&a=addsave` | High
32 | File | `admin/add-glossary.php` | High
33 | File | `admin/conf_users_edit.php` | High
34 | File | `admin/edit-comments.php` | High
35 | File | `admin/index.php` | High
36 | File | `admin/src/containers/InputModalStepperProvider/index.js` | High
37 | File | `admin/write-post.php` | High
38 | File | `administrator/components/com_media/helpers/media.php` | High
39 | File | `admin_events.php` | High
40 | File | `AjaxApplication.java` | High
41 | File | `akocomments.php` | High
42 | File | `allopass-error.php` | High
43 | File | `AllowBindAppWidgetActivity.java` | High
44 | File | `android/webkit/SearchBoxImpl.java` | High
45 | File | `AndroidManifest.xml` | High
46 | File | `announcement.php` | High
47 | File | `api/settings/values` | High
48 | File | `app/topic/action/admin/topic.php` | High
49 | File | `apply.cgi` | Medium
50 | File | `artlinks.dispnew.php` | High
51 | File | `auth.inc.php` | Medium
52 | File | `awstats.pl` | Medium
53 | ... | ... | ...

There are 458 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/OpBlueRaven
* https://securelist.com/fin7-5-the-infamous-cybercrime-rig-fin7-continues-its-activities/90703/
* https://www.anomali.com/blog/cybercrime-group-fin7-using-windows-11-alpha-themed-docs-to-drop-javascript-backdoor
* https://www.fireeye.com/blog/threat-research/2017/04/fin7-phishing-lnk.html
* https://www.fireeye.com/blog/threat-research/2018/08/fin7-pursuing-an-enigmatic-and-evasive-global-criminal-operation.html
* https://www.flashpoint-intel.com/blog/fin7-revisited-inside-astra-panel-and-sqlrat-malware/
* https://www.threatminer.org/report.php?q=the-carbanak-fin7-syndicate_RSA.pdf&y=2017

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
