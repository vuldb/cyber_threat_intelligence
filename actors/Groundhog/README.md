# Groundhog - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Groundhog](https://vuldb.com/?actor.groundhog). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.groundhog](https://vuldb.com/?actor.groundhog)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Groundhog:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 27 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Groundhog.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.93.16.186](https://vuldb.com/?ip.1.93.16.186) | - | - | High
2 | [1.93.18.99](https://vuldb.com/?ip.1.93.18.99) | - | - | High
3 | [1.93.60.81](https://vuldb.com/?ip.1.93.60.81) | - | - | High
4 | [1.93.62.132](https://vuldb.com/?ip.1.93.62.132) | - | - | High
5 | [8.8.4.4](https://vuldb.com/?ip.8.8.4.4) | dns.google | - | High
6 | [8.23.224.120](https://vuldb.com/?ip.8.23.224.120) | dynupdate.no-ip.com | - | High
7 | [14.17.93.147](https://vuldb.com/?ip.14.17.93.147) | - | - | High
8 | [14.19.222.76](https://vuldb.com/?ip.14.19.222.76) | - | - | High
9 | [23.234.28.5](https://vuldb.com/?ip.23.234.28.5) | - | - | High
10 | [23.234.41.199](https://vuldb.com/?ip.23.234.41.199) | - | - | High
11 | [23.234.41.219](https://vuldb.com/?ip.23.234.41.219) | - | - | High
12 | [23.234.43.134](https://vuldb.com/?ip.23.234.43.134) | - | - | High
13 | [23.234.60.140](https://vuldb.com/?ip.23.234.60.140) | - | - | High
14 | [23.252.162.178](https://vuldb.com/?ip.23.252.162.178) | - | - | High
15 | [23.252.164.225](https://vuldb.com/?ip.23.252.164.225) | - | - | High
16 | [27.152.183.116](https://vuldb.com/?ip.27.152.183.116) | - | - | High
17 | [36.251.136.189](https://vuldb.com/?ip.36.251.136.189) | - | - | High
18 | [37.59.210.99](https://vuldb.com/?ip.37.59.210.99) | - | - | High
19 | [43.225.59.7](https://vuldb.com/?ip.43.225.59.7) | - | - | High
20 | [43.240.51.113](https://vuldb.com/?ip.43.240.51.113) | - | - | High
21 | [46.229.169.89](https://vuldb.com/?ip.46.229.169.89) | - | - | High
22 | [58.64.187.29](https://vuldb.com/?ip.58.64.187.29) | - | - | High
23 | [58.218.213.237](https://vuldb.com/?ip.58.218.213.237) | - | - | High
24 | [58.221.35.5](https://vuldb.com/?ip.58.221.35.5) | - | - | High
25 | [58.221.45.242](https://vuldb.com/?ip.58.221.45.242) | - | - | High
26 | [59.56.64.169](https://vuldb.com/?ip.59.56.64.169) | - | - | High
27 | [59.188.86.215](https://vuldb.com/?ip.59.188.86.215) | - | - | High
28 | [59.188.86.222](https://vuldb.com/?ip.59.188.86.222) | - | - | High
29 | ... | ... | ... | ...

There are 113 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Groundhog_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Groundhog. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.env` | Low
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/admin.php?&m=Public&a=login` | High
5 | File | `/admin/default.asp` | High
6 | File | `/ajax/networking/get_netcfg.php` | High
7 | File | `/assets/ctx` | Medium
8 | File | `/checkLogin.cgi` | High
9 | File | `/cms/print.php` | High
10 | File | `/concat?/%2557EB-INF/web.xml` | High
11 | File | `/config/getuser` | High
12 | File | `/Content/Template/root/reverse-shell.aspx` | High
13 | File | `/data/remove` | Medium
14 | File | `/etc/ajenti/config.yml` | High
15 | File | `/etc/passwd` | Medium
16 | File | `/goform/telnet` | High
17 | File | `/goforms/rlminfo` | High
18 | File | `/login` | Low
19 | File | `/modules/profile/index.php` | High
20 | File | `/navigate/navigate_download.php` | High
21 | File | `/owa/auth/logon.aspx` | High
22 | File | `/p` | Low
23 | File | `/password.html` | High
24 | File | `/proc/ioports` | High
25 | File | `/property-list/property_view.php` | High
26 | File | `/ptms/classes/Users.php` | High
27 | File | `/rest` | Low
28 | File | `/rest/api/2/search` | High
29 | File | `/s/` | Low
30 | File | `/scripts/cpan_config` | High
31 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
32 | File | `/services/system/setup.json` | High
33 | File | `/ucms/index.php?do=list_edit` | High
34 | File | `/uncpath/` | Medium
35 | File | `/vloggers_merch/?p=view_product` | High
36 | File | `/webconsole/APIController` | High
37 | File | `/websocket/exec` | High
38 | File | `/wp-admin/admin-ajax.php` | High
39 | File | `/wp-json` | Medium
40 | File | `/wp-json/oembed/1.0/embed?url` | High
41 | File | `/_next` | Low
42 | File | `4.edu.php\conn\function.php` | High
43 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
44 | File | `actions/beats_uploader.php` | High
45 | File | `adclick.php` | Medium
46 | File | `addentry.php` | Medium
47 | File | `admin/admin.php` | High
48 | File | `admin/category.inc.php` | High
49 | ... | ... | ...

There are 430 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.threatminer.org/report.php?q=sb-report-threat-intelligence-groundhog.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
