# ProxyShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _ProxyShell_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ProxyShell:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [BR](https://vuldb.com/?country.br)
* ...

There are 24 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ProxyShell or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ProxyShell.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.111.163.242](https://vuldb.com/?ip.23.111.163.242) | 23-111-163-242.static.hvvc.us | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
2 | [24.229.150.54](https://vuldb.com/?ip.24.229.150.54) | 24.229.150.54.cmts-static.sm.ptd.net | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
3 | [69.192.185.238](https://vuldb.com/?ip.69.192.185.238) | a69-192-185-238.deploy.static.akamaitechnologies.com | [Squirrelwaffle](https://vuldb.com/?actor.squirrelwaffle) | High
4 | ... | ... | ... | ...

There are 6 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ProxyShell. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-250, CWE-264, CWE-266, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ProxyShell. This data is unique as it uses our predictive model for actor profiling.

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
13 | File | `/etc/passwd` | Medium
14 | File | `/filemanager/upload.php` | High
15 | File | `/forum/away.php` | High
16 | File | `/index_amp.php` | High
17 | File | `/login` | Low
18 | File | `/navigate/navigate_download.php` | High
19 | File | `/out.php` | Medium
20 | File | `/owa/auth/logon.aspx` | High
21 | File | `/p` | Low
22 | File | `/password.html` | High
23 | File | `/proc/ioports` | High
24 | File | `/property-list/property_view.php` | High
25 | File | `/rest` | Low
26 | File | `/rest/api/2/search` | High
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
41 | File | `addressbook.php` | High
42 | File | `add_comment.php` | High
43 | File | `add_edit_user.asp` | High
44 | File | `admin/category.inc.php` | High
45 | File | `admin/conf_users_edit.php` | High
46 | File | `admin/dl_sendmail.php` | High
47 | File | `admin/index.php` | High
48 | ... | ... | ...

There are 414 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/21/k/squirrelwaffle-exploits-proxyshell-and-proxylogon-vulnerabilities-in-microsoft-exchange-to-hijack-email-chains/IOCs-squirrelwaffle-exploits-proxyshell-and-proxylogon-to-hijack-email
* https://www.trendmicro.com/en_us/research/21/k/analyzing-proxyshell-related-incidents-via-trend-micro-managed-x.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
