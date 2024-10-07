# Hajime - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Hajime](https://vuldb.com/?actor.hajime). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hajime](https://vuldb.com/?actor.hajime)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Hajime:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [AT](https://vuldb.com/?country.at)
* ...

There are 30 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Hajime.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.154.33.123](https://vuldb.com/?ip.2.154.33.123) | 2.154.33.123.dyn.user.ono.com | - | High
2 | [5.43.222.180](https://vuldb.com/?ip.5.43.222.180) | ADSL-5.43.222.180.mada.ps | - | High
3 | [5.59.145.140](https://vuldb.com/?ip.5.59.145.140) | - | - | High
4 | [5.182.69.230](https://vuldb.com/?ip.5.182.69.230) | - | - | High
5 | [31.166.23.67](https://vuldb.com/?ip.31.166.23.67) | - | - | High
6 | [37.75.219.61](https://vuldb.com/?ip.37.75.219.61) | 61-219.plus.kerch.net | - | High
7 | [37.110.18.77](https://vuldb.com/?ip.37.110.18.77) | broadband-37-110-18-77.ip.moscow.rt.ru | - | High
8 | [41.72.17.99](https://vuldb.com/?ip.41.72.17.99) | - | - | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Hajime_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Hajime. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//etc/RT2870STA.dat` | High
2 | File | `/Admin/News.php` | High
3 | File | `/admin/sign/out` | High
4 | File | `/application/index/controller/Service.php` | High
5 | File | `/categorypage.php` | High
6 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
7 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
8 | File | `/cgi-bin/user/Config.cgi` | High
9 | File | `/cgi-bin/viewcert` | High
10 | File | `/common/info.cgi` | High
11 | File | `/config/getuser` | High
12 | File | `/configs/application.ini` | High
13 | File | `/core/vb/vurl.php` | High
14 | File | `/debug/pprof` | Medium
15 | File | `/defaultui/player/modern.html` | High
16 | File | `/etc/shadow.sample` | High
17 | File | `/eval/admin/manage_class.php` | High
18 | File | `/forum/away.php` | High
19 | File | `/lms/classes/Master.php?f=save_record` | High
20 | File | `/modules/projects/vw_files.php` | High
21 | File | `/nagiosxi/admin/graphtemplates.php` | High
22 | File | `/ndmComponents.js` | High
23 | File | `/oauth/idp/.well-known/openid-configuration` | High
24 | File | `/pro-school/indexphp?student/message/send_reply/` | High
25 | File | `/server-status` | High
26 | File | `/squashfs-root/www/HNAP1/control/SetMasterWLanSettings.php` | High
27 | File | `/tools/required/files/importers/imageeditor` | High
28 | File | `/uncpath/` | Medium
29 | File | `/usr/bin/pkexec` | High
30 | File | `/usr/local/nagiosxi/html/admin/sshterm.php` | High
31 | File | `/vpn/list_service_manage.php` | High
32 | File | `/vpn/list_vpn_web_custom.php` | High
33 | File | `/vpn/vpn_template_style.php` | High
34 | File | `/wp-admin/admin-ajax.php` | High
35 | File | `/wp-content/plugins/woocommerce/templates/emails/plain/` | High
36 | ... | ... | ...

There are 306 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/5bc4b2cc64f3b484562ea238bdcba533912921f5a6b0c7d4509d7dc0ad8e3f66/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
