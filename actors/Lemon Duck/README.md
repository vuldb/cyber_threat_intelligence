# Lemon Duck - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lemon Duck](https://vuldb.com/?actor.lemon_duck). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lemon_duck](https://vuldb.com/?actor.lemon_duck)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lemon Duck:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lemon Duck.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.202.15.246](https://vuldb.com/?ip.1.202.15.246) | 246.15.202.1.static.bjtelecom.net | - | High
2 | [27.195.157.70](https://vuldb.com/?ip.27.195.157.70) | - | - | High
3 | [36.48.94.254](https://vuldb.com/?ip.36.48.94.254) | - | - | High
4 | [36.110.1.222](https://vuldb.com/?ip.36.110.1.222) | 222.1.110.36.static.bjtelecom.net | - | High
5 | [40.68.42.171](https://vuldb.com/?ip.40.68.42.171) | - | - | High
6 | [42.7.4.88](https://vuldb.com/?ip.42.7.4.88) | - | - | High
7 | [42.7.31.243](https://vuldb.com/?ip.42.7.31.243) | - | - | High
8 | [42.176.133.183](https://vuldb.com/?ip.42.176.133.183) | - | - | High
9 | [49.71.208.124](https://vuldb.com/?ip.49.71.208.124) | - | - | High
10 | [49.147.72.67](https://vuldb.com/?ip.49.147.72.67) | dsl.49.148.72.67.pldt.net | - | High
11 | [51.36.170.221](https://vuldb.com/?ip.51.36.170.221) | - | - | High
12 | [58.56.135.198](https://vuldb.com/?ip.58.56.135.198) | - | - | High
13 | [58.62.125.245](https://vuldb.com/?ip.58.62.125.245) | - | - | High
14 | [58.221.24.178](https://vuldb.com/?ip.58.221.24.178) | - | - | High
15 | [58.251.2.115](https://vuldb.com/?ip.58.251.2.115) | reverse.gdsz.cncnet.net | - | High
16 | [59.111.181.116](https://vuldb.com/?ip.59.111.181.116) | - | - | High
17 | [59.175.154.97](https://vuldb.com/?ip.59.175.154.97) | - | - | High
18 | [60.10.56.169](https://vuldb.com/?ip.60.10.56.169) | hebei.10.60.in-addr.arpa | - | High
19 | [60.10.134.93](https://vuldb.com/?ip.60.10.134.93) | hebei.10.60.in-addr.arpa | - | High
20 | [60.19.236.50](https://vuldb.com/?ip.60.19.236.50) | - | - | High
21 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lemon Duck_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29 | Path Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lemon Duck. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/act/ActDao.xml` | High
3 | File | `/admin/action/new-father.php` | High
4 | File | `/admin/clientview.php` | High
5 | File | `/admin/edit_teacher.php` | High
6 | File | `/admin/fields/manage_field.php` | High
7 | File | `/admin/orders/view_order.php` | High
8 | File | `/admin/regester.php` | High
9 | File | `/admin/update-clients.php` | High
10 | File | `/admin_ping.htm` | High
11 | File | `/admin_route/dec_service_credits.php` | High
12 | File | `/admin_route/inc_service_credits.php` | High
13 | File | `/api/cron/settings/setJob/` | High
14 | File | `/api/sys/set_passwd` | High
15 | File | `/api/v1/terminal/sessions/?limit=1` | High
16 | File | `/app/api/controller/default/Sqlite.php` | High
17 | File | `/application/index/controller/Databasesource.php` | High
18 | File | `/application/index/controller/Icon.php` | High
19 | File | `/application/index/controller/Screen.php` | High
20 | File | `/application/plugins/controller/Upload.php` | High
21 | File | `/apply.cgi` | Medium
22 | File | `/arch/x86/mm/cpu_entry_area.c` | High
23 | File | `/authenticationendpoint/login.do` | High
24 | File | `/bin/boa` | Medium
25 | File | `/boaform/device_reset.cgi` | High
26 | File | `/boafrm/formMapDelDevice` | High
27 | File | `/bsms_ci/index.php/user/edit_user/` | High
28 | File | `/cgi-bin/cstecgi.cgi` | High
29 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
30 | File | `/cgi-bin/kerbynet` | High
31 | File | `/cgi-bin/koha/catalogue/search.pl` | High
32 | File | `/cgi-bin/mainfunction.cgi` | High
33 | File | `/cgi-bin/R14.2/cgi-bin/R14.2/host.pl` | High
34 | File | `/cgi-bin/R14.2/easy1350.pl` | High
35 | File | `/cgi-bin/wlogin.cgi` | High
36 | File | `/clinic/disease_symptoms_view.php` | High
37 | File | `/config/getuser` | High
38 | File | `/core/redirect` | High
39 | File | `/dashboard/snapshot/*?orgId=0` | High
40 | File | `/debug/pprof` | Medium
41 | File | `/DXR.axd` | Medium
42 | File | `/ECT_Provider/` | High
43 | File | `/fax/fax_send.php` | High
44 | File | `/forum/away.php` | High
45 | File | `/general/attendance/manage/ask_duty/delete.php` | High
46 | ... | ... | ...

There are 400 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/10/lemon-duck-brings-cryptocurrency-miners.html
* https://github.com/guardicore/labs_campaigns/tree/master/Lemon_Duck

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
