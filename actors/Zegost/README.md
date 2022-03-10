# Zegost - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Zegost](https://vuldb.com/?actor.zegost). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.zegost](https://vuldb.com/?actor.zegost)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Zegost:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Zegost.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.17.74.162](https://vuldb.com/?ip.14.17.74.162) | - | - | High
2 | [14.113.128.7](https://vuldb.com/?ip.14.113.128.7) | - | - | High
3 | [14.113.128.191](https://vuldb.com/?ip.14.113.128.191) | - | - | High
4 | [14.210.50.189](https://vuldb.com/?ip.14.210.50.189) | - | - | High
5 | [14.210.91.15](https://vuldb.com/?ip.14.210.91.15) | - | - | High
6 | [14.210.95.203](https://vuldb.com/?ip.14.210.95.203) | - | - | High
7 | [14.210.98.141](https://vuldb.com/?ip.14.210.98.141) | - | - | High
8 | [14.210.109.122](https://vuldb.com/?ip.14.210.109.122) | - | - | High
9 | [14.210.222.241](https://vuldb.com/?ip.14.210.222.241) | - | - | High
10 | [20.210.205.20](https://vuldb.com/?ip.20.210.205.20) | - | - | High
11 | [23.89.5.60](https://vuldb.com/?ip.23.89.5.60) | mtx77mcs683.webex.com | - | High
12 | [27.40.253.131](https://vuldb.com/?ip.27.40.253.131) | - | - | High
13 | [43.248.201.133](https://vuldb.com/?ip.43.248.201.133) | - | - | High
14 | [45.35.20.197](https://vuldb.com/?ip.45.35.20.197) | unassigned.psychz.net | - | High
15 | [45.119.125.223](https://vuldb.com/?ip.45.119.125.223) | - | - | High
16 | [49.2.123.56](https://vuldb.com/?ip.49.2.123.56) | - | - | High
17 | [54.76.135.1](https://vuldb.com/?ip.54.76.135.1) | ec2-54-76-135-1.eu-west-1.compute.amazonaws.com | - | Medium
18 | ... | ... | ... | ...

There are 70 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by _Zegost_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Zegost. This data is unique as it uses our predictive model for actor profiling.

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
12 | File | `/data/remove` | Medium
13 | File | `/etc/ajenti/config.yml` | High
14 | File | `/etc/passwd` | Medium
15 | File | `/goform/telnet` | High
16 | File | `/login` | Low
17 | File | `/modules/profile/index.php` | High
18 | File | `/navigate/navigate_download.php` | High
19 | File | `/owa/auth/logon.aspx` | High
20 | File | `/p` | Low
21 | File | `/password.html` | High
22 | File | `/proc/ioports` | High
23 | File | `/property-list/property_view.php` | High
24 | File | `/rest` | Low
25 | File | `/rest/api/2/search` | High
26 | File | `/rom-0` | Low
27 | File | `/s/` | Low
28 | File | `/scripts/cpan_config` | High
29 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
30 | File | `/services/system/setup.json` | High
31 | File | `/uncpath/` | Medium
32 | File | `/webconsole/APIController` | High
33 | File | `/websocket/exec` | High
34 | File | `/wp-admin/admin-ajax.php` | High
35 | File | `/wp-json/oembed/1.0/embed?url` | High
36 | File | `/_next` | Low
37 | File | `4.edu.php\conn\function.php` | High
38 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
39 | File | `adclick.php` | Medium
40 | File | `addentry.php` | Medium
41 | File | `add_comment.php` | High
42 | File | `admin/admin.php` | High
43 | File | `admin/category.inc.php` | High
44 | File | `admin/conf_users_edit.php` | High
45 | File | `admin/dl_sendmail.php` | High
46 | File | `admin/index.php` | High
47 | File | `admin/index.php?id=users/action=edit/user_id=1` | High
48 | ... | ... | ...

There are 418 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/03/threat-roundup-0226-0305.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0305-0312.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0409-0416.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0416-0423.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0507-0514.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0514-0521.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0521-0528.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0528-0604.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0604-0611.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0702-0709.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0716-0723.html
* https://blog.talosintelligence.com/2021/11/threat-roundup-1112-1119.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0211-0218.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
