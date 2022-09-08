# Lyceum - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lyceum](https://vuldb.com/?actor.lyceum). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lyceum](https://vuldb.com/?actor.lyceum)

## Campaigns

The following _campaigns_ are known and can be associated with Lyceum:

* DanBot

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lyceum:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 30 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lyceum.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [62.113.196.37](https://vuldb.com/?ip.62.113.196.37) | aeroplan-redirect.online | DanBot | High
2 | [62.113.207.181](https://vuldb.com/?ip.62.113.207.181) | - | DanBot | High
3 | [75.87.185.45](https://vuldb.com/?ip.75.87.185.45) | cpe-75-87-185-45.kc.res.rr.com | DanBot | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lyceum_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lyceum. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.env` | Low
3 | File | `/.ssh/authorized_keys` | High
4 | File | `/admin/default.asp` | High
5 | File | `/ajax/networking/get_netcfg.php` | High
6 | File | `/app/options.py` | High
7 | File | `/assets/ctx` | Medium
8 | File | `/ci_spms/admin/category` | High
9 | File | `/ci_spms/admin/search/searching/` | High
10 | File | `/classes/Master.php?f=delete_train` | High
11 | File | `/cms/print.php` | High
12 | File | `/concat?/%2557EB-INF/web.xml` | High
13 | File | `/Content/Template/root/reverse-shell.aspx` | High
14 | File | `/course/api/upload/pic` | High
15 | File | `/dashboard/menu-list.php` | High
16 | File | `/data/remove` | Medium
17 | File | `/etc/passwd` | Medium
18 | File | `/ffos/classes/Master.php?f=save_category` | High
19 | File | `/goforms/rlminfo` | High
20 | File | `/Items/*/RemoteImages/Download` | High
21 | File | `/login` | Low
22 | File | `/navigate/navigate_download.php` | High
23 | File | `/ocwbs/admin/?page=user/manage_user` | High
24 | File | `/ofrs/admin/?page=user/manage_user` | High
25 | File | `/owa/auth/logon.aspx` | High
26 | File | `/password.html` | High
27 | File | `/pms/index.php` | High
28 | File | `/proc/ioports` | High
29 | File | `/property-list/property_view.php` | High
30 | File | `/ptms/classes/Users.php` | High
31 | File | `/rest/api/2/search` | High
32 | File | `/s/` | Low
33 | File | `/scripts/cpan_config` | High
34 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
35 | File | `/services/system/setup.json` | High
36 | File | `/spip.php` | Medium
37 | File | `/uncpath/` | Medium
38 | File | `/vloggers_merch/?p=view_product` | High
39 | File | `/webconsole/APIController` | High
40 | File | `/websocket/exec` | High
41 | File | `/whbs/?page=my_bookings` | High
42 | File | `/wp-admin/admin-ajax.php` | High
43 | File | `/wp-content/plugins/updraftplus/admin.php` | High
44 | File | `/wp-json` | Medium
45 | ... | ... | ...

There are 388 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://research.checkpoint.com/2022/state-sponsored-attack-groups-capitalise-on-russia-ukraine-war-for-cyber-espionage/
* https://www.secureworks.com/blog/lyceum-takes-center-stage-in-middle-east-campaign

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
