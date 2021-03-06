# Double Tap - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Double Tap_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Double Tap:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 27 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Double Tap or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT3](https://vuldb.com/?actor.apt3) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Double Tap.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [104.151.248.173](https://vuldb.com/?ip.104.151.248.173) | 173.248-151-104.rdns.scalabledns.com | [APT3](https://vuldb.com/?actor.apt3) | High
2 | [192.184.60.229](https://vuldb.com/?ip.192.184.60.229) | unassigned.psychz.net | [APT3](https://vuldb.com/?actor.apt3) | High
3 | [198.55.115.71](https://vuldb.com/?ip.198.55.115.71) | hosted-by.securefastserver.com | [APT3](https://vuldb.com/?actor.apt3) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Double Tap. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 9 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Double Tap. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.env` | Low
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/admin/default.asp` | High
5 | File | `/ajax/networking/get_netcfg.php` | High
6 | File | `/assets/ctx` | Medium
7 | File | `/cgi-bin/login_action.cgi` | High
8 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
9 | File | `/checkLogin.cgi` | High
10 | File | `/cms/print.php` | High
11 | File | `/concat?/%2557EB-INF/web.xml` | High
12 | File | `/Content/Template/root/reverse-shell.aspx` | High
13 | File | `/data/remove` | Medium
14 | File | `/etc/passwd` | Medium
15 | File | `/goforms/rlminfo` | High
16 | File | `/login` | Low
17 | File | `/navigate/navigate_download.php` | High
18 | File | `/ocwbs/admin/?page=user/manage_user` | High
19 | File | `/ofrs/admin/?page=user/manage_user` | High
20 | File | `/out.php` | Medium
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
33 | File | `/uncpath/` | Medium
34 | File | `/vloggers_merch/?p=view_product` | High
35 | File | `/webconsole/APIController` | High
36 | File | `/websocket/exec` | High
37 | File | `/wp-admin/admin-ajax.php` | High
38 | File | `/wp-json` | Medium
39 | File | `/wp-json/oembed/1.0/embed?url` | High
40 | File | `/_next` | Low
41 | File | `4.edu.php\conn\function.php` | High
42 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
43 | File | `adclick.php` | Medium
44 | File | `addentry.php` | Medium
45 | File | `admin/category.inc.php` | High
46 | File | `admin/conf_users_edit.php` | High
47 | ... | ... | ...

There are 403 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.fireeye.com/blog/threat-research/2014/11/operation_doubletap.html
* https://www.threatminer.org/report.php?q=OperationDoubleTap.pdf&y=2014

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
