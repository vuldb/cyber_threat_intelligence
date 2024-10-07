# Dealply - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dealply](https://vuldb.com/?actor.dealply). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dealply](https://vuldb.com/?actor.dealply)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dealply:

* [IT](https://vuldb.com/?country.it)
* [DE](https://vuldb.com/?country.de)
* [US](https://vuldb.com/?country.us)
* ...

There are 1 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-22, CWE-23, CWE-29, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-267, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dealply. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/activate_hook.php` | High
2 | File | `/admin/` | Low
3 | File | `/admin/ajax.php?action=delete_user` | High
4 | File | `/admin/ajax.php?action=save_settings` | High
5 | File | `/admin/config_time_sync.php` | High
6 | File | `/admin/index.php` | High
7 | File | `/admin/robot.php` | High
8 | File | `/admin/singlelogin.php?submit=1` | High
9 | File | `/admin/system.html` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/api/files/recipepictures/` | High
12 | File | `/api/user` | Medium
13 | File | `/apply/index.php` | High
14 | File | `/bin/webs` | Medium
15 | File | `/boaform/device_reset.cgi` | High
16 | File | `/boaform/wlan_basic_set.cgi` | High
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
19 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
20 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
21 | File | `/cgi-bin/nas_sharing.cgi` | High
22 | File | `/cgi-bin/photocenter_mgr.cgi` | High
23 | File | `/cgi-bin/ping.cgi` | High
24 | File | `/classes/Master.php` | High
25 | File | `/classes/Master.php?f=save_medicine` | High
26 | File | `/classes/Master.php?f=save_package` | High
27 | File | `/classes/SystemSettings.php?f=update_settings` | High
28 | File | `/classes/Users.php?f=register_user` | High
29 | File | `/collection/all` | High
30 | File | `/control/register_case.php` | High
31 | File | `/dosen/data` | Medium
32 | File | `/dtale/chart-data/1` | High
33 | File | `/ecommerce/support_ticket` | High
34 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
35 | File | `/emgui/rest/preferences/PREF_HOME_PAGE/sponsor/3/` | High
36 | File | `/etc/shadow.sample` | High
37 | File | `/file_manager/admin/save_user.php` | High
38 | File | `/foms/routers/place-order.php` | High
39 | File | `/goform/addressNat` | High
40 | ... | ... | ...

There are 344 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
