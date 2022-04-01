# Ursnif - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Ursnif](https://vuldb.com/?actor.ursnif). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ursnif](https://vuldb.com/?actor.ursnif)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Ursnif:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Ursnif.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.56.73.146](https://vuldb.com/?ip.5.56.73.146) | host-static-5-56-73-146.moldtelecom.md | - | High
2 | [5.134.119.57](https://vuldb.com/?ip.5.134.119.57) | - | - | High
3 | [5.252.179.21](https://vuldb.com/?ip.5.252.179.21) | no-rdns.mivocloud.com | - | High
4 | [8.249.225.254](https://vuldb.com/?ip.8.249.225.254) | - | - | High
5 | [8.249.231.254](https://vuldb.com/?ip.8.249.231.254) | - | - | High
6 | [8.253.45.214](https://vuldb.com/?ip.8.253.45.214) | - | - | High
7 | [23.3.13.88](https://vuldb.com/?ip.23.3.13.88) | a23-3-13-88.deploy.static.akamaitechnologies.com | - | High
8 | [23.3.13.154](https://vuldb.com/?ip.23.3.13.154) | a23-3-13-154.deploy.static.akamaitechnologies.com | - | High
9 | [23.202.231.167](https://vuldb.com/?ip.23.202.231.167) | a23-202-231-167.deploy.static.akamaitechnologies.com | - | High
10 | [31.13.65.174](https://vuldb.com/?ip.31.13.65.174) | instagram-p42-shv-01-atl3.fbcdn.net | - | High
11 | [37.187.0.40](https://vuldb.com/?ip.37.187.0.40) | ns3108067.ip-37-187-0.eu | - | High
12 | [45.141.103.204](https://vuldb.com/?ip.45.141.103.204) | ptr.ruvds.com | - | High
13 | [51.223.47.15](https://vuldb.com/?ip.51.223.47.15) | - | - | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Ursnif_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Ursnif. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\Razer\Synapse3\Service\bin` | High
2 | File | `/?module=users&section=cpanel&page=list` | High
3 | File | `/admin/powerline` | High
4 | File | `/admin/settings/sites/new` | High
5 | File | `/admin/syslog` | High
6 | File | `/api/upload` | Medium
7 | File | `/app/Http/Controllers/Admin/NEditorController.php` | High
8 | File | `/cgi-bin` | Medium
9 | File | `/cgi-bin/ExportALLSettings.sh` | High
10 | File | `/context/%2e/WEB-INF/web.xml` | High
11 | File | `/group/comment` | High
12 | File | `/login` | Low
13 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
14 | File | `/monitoring` | Medium
15 | File | `/new` | Low
16 | File | `/proc/<pid>/status` | High
17 | File | `/public/plugins/` | High
18 | File | `/scripts/killpvhost` | High
19 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
20 | File | `/secure/QueryComponent!Default.jspa` | High
21 | File | `/src/main/java/com/dotmarketing/filters/CMSFilter.java` | High
22 | File | `/tmp` | Low
23 | File | `/tmp/redis.ds` | High
24 | File | `/uncpath/` | Medium
25 | File | `/usr/bin/at` | Medium
26 | File | `/usr/bin/pkexec` | High
27 | File | `/wp-admin` | Medium
28 | File | `/wp-json/wc/v3/webhooks` | High
29 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
30 | File | `AccountManagerService.java` | High
31 | File | `actions/CompanyDetailsSave.php` | High
32 | File | `ActiveServices.java` | High
33 | File | `ActivityManagerService.java` | High
34 | File | `adclick.php` | Medium
35 | File | `admin.php` | Medium
36 | File | `admin/?n=user&c=admin_user&a=doGetUserInfo` | High
37 | ... | ... | ...

There are 314 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/04/threat-roundup-0402-0409.html
* https://blog.talosintelligence.com/2021/08/threat-roundup-0806-0813.html
* https://isc.sans.edu/forums/diary/German+language+malspam+pushes+Ursnif/25732/
* https://isc.sans.edu/forums/diary/Malpsam+pushes+Ursnif+through+Italian+language+Word+docs/25792/
* https://isc.sans.edu/forums/diary/Ursnif+infection+with+Dridex/25566/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
