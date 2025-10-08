# Dealply - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dealply](https://vuldb.com/?actor.dealply). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dealply](https://vuldb.com/?actor.dealply)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dealply:

* [IT](https://vuldb.com/?country.it)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dealply.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.9.18](https://vuldb.com/?ip.5.9.9.18) | static.18.9.9.5.clients.your-server.de | - | High
2 | [13.248.196.204](https://vuldb.com/?ip.13.248.196.204) | a64c2b794233c60a6.awsglobalaccelerator.com | - | High
3 | [23.0.52.194](https://vuldb.com/?ip.23.0.52.194) | a23-0-52-194.deploy.static.akamaitechnologies.com | - | High
4 | [23.3.126.219](https://vuldb.com/?ip.23.3.126.219) | a23-3-126-219.deploy.static.akamaitechnologies.com | - | High
5 | [23.54.219.51](https://vuldb.com/?ip.23.54.219.51) | a23-54-219-51.deploy.static.akamaitechnologies.com | - | High
6 | [23.221.50.122](https://vuldb.com/?ip.23.221.50.122) | a23-221-50-122.deploy.static.akamaitechnologies.com | - | High
7 | [34.231.131.84](https://vuldb.com/?ip.34.231.131.84) | ec2-34-231-131-84.compute-1.amazonaws.com | - | Medium
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dealply_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-29, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dealply. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$SPLUNK_HOME/var/run/splunk/apptemp` | High
2 | File | `../mtd/Config/Sha1Account1` | High
3 | File | `/admin/ajax.php?action=delete_user` | High
4 | File | `/admin/ajax.php?action=save_settings` | High
5 | File | `/admin/bookList?page=1&limit=10` | High
6 | File | `/admin/bwdates-passreports-details.php` | High
7 | File | `/admin/config_time_sync.php` | High
8 | File | `/admin/course_action.php` | High
9 | File | `/admin/manage-art-medium.php` | High
10 | File | `/admin/robot.php` | High
11 | File | `/admin/sales-reports-detail.php` | High
12 | File | `/admin/search-pass.php` | High
13 | File | `/admin/system.html` | High
14 | File | `/api/files/recipepictures/` | High
15 | File | `/api/user` | Medium
16 | File | `/api/wizard/getLanguage` | High
17 | File | `/api/wizard/getWifiNeighbour` | High
18 | File | `/appy.cgi` | Medium
19 | File | `/auth.asp` | Medium
20 | File | `/auth/register` | High
21 | File | `/bin/boa` | Medium
22 | File | `/bin/httpd` | Medium
23 | File | `/bin/main` | Medium
24 | File | `/biurl_grou` | Medium
25 | File | `/boafrm/formDMZ` | High
26 | File | `/boafrm/formMultiAP` | High
27 | File | `/boafrm/formSaveConfig` | High
28 | File | `/boafrm/formStaticDHCP` | High
29 | File | `/boafrm/formTmultiAP` | High
30 | File | `/boafrm/formWsc` | High
31 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
34 | File | `/cgi-bin/photocenter_mgr.cgi` | High
35 | File | `/classes/Master.php` | High
36 | File | `/classes/Master.php?f=save_medicine` | High
37 | File | `/classes/Master.php?f=save_package` | High
38 | File | `/classes/SystemSettings.php?f=update_settings` | High
39 | File | `/classes/Users.php?f=register_user` | High
40 | File | `/contact.php` | Medium
41 | File | `/dbsrv.asp` | Medium
42 | File | `/dev/ttyACM*` | Medium
43 | File | `/discuss/uploadMdPic` | High
44 | File | `/dtale/chart-data/1` | High
45 | File | `/emgui/rest/preferences/PREF_HOME_PAGE/sponsor/3/` | High
46 | ... | ... | ...

There are 399 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0522-0529.html
* https://blog.talosintelligence.com/2020/08/threat-roundup-0821-0827.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
