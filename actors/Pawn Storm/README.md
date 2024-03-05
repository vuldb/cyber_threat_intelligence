# Pawn Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Pawn Storm](https://vuldb.com/?actor.pawn_storm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.pawn_storm](https://vuldb.com/?actor.pawn_storm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Pawn Storm:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Pawn Storm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [14.198.168.140](https://vuldb.com/?ip.14.198.168.140) | 014198168140.ctinets.com | - | High
2 | [24.11.70.85](https://vuldb.com/?ip.24.11.70.85) | c-24-11-70-85.hsd1.ut.comcast.net | - | High
3 | [24.142.165.2](https://vuldb.com/?ip.24.142.165.2) | 024-142-165-002.biz.spectrum.com | - | High
4 | [42.98.5.225](https://vuldb.com/?ip.42.98.5.225) | 42-98-5-225.static.netvigator.com | - | High
5 | [45.83.90.11](https://vuldb.com/?ip.45.83.90.11) | - | - | High
6 | [45.91.95.181](https://vuldb.com/?ip.45.91.95.181) | sks3.simoxap.xyz | - | High
7 | [50.173.136.70](https://vuldb.com/?ip.50.173.136.70) | c-50-173-136-70.unallocated.comcastbusiness.net | - | High
8 | [61.14.68.33](https://vuldb.com/?ip.61.14.68.33) | - | - | High
9 | [62.4.36.126](https://vuldb.com/?ip.62.4.36.126) | - | - | High
10 | [68.76.150.97](https://vuldb.com/?ip.68.76.150.97) | 68-76-150-97.lightspeed.hstntx.sbcglobal.net | - | High
11 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Pawn Storm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Pawn Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/accounts/password_change/` | High
3 | File | `/act/ActDao.xml` | High
4 | File | `/adm/syscmd.asp` | High
5 | File | `/admin/action/new-father.php` | High
6 | File | `/admin/clientview.php` | High
7 | File | `/admin/edit_teacher.php` | High
8 | File | `/admin/fields/manage_field.php` | High
9 | File | `/admin/regester.php` | High
10 | File | `/admin/update-clients.php` | High
11 | File | `/admin/view_order.php` | High
12 | File | `/admin_ping.htm` | High
13 | File | `/admin_route/dec_service_credits.php` | High
14 | File | `/admin_route/inc_service_credits.php` | High
15 | File | `/api/baskets/{name}` | High
16 | File | `/api/cron/settings/setJob/` | High
17 | File | `/api/sys/set_passwd` | High
18 | File | `/api/v1/terminal/sessions/?limit=1` | High
19 | File | `/app/api/controller/default/Sqlite.php` | High
20 | File | `/apply.cgi` | Medium
21 | File | `/arch/x86/mm/cpu_entry_area.c` | High
22 | File | `/authenticationendpoint/login.do` | High
23 | File | `/b2b-supermarket/shopping-cart` | High
24 | File | `/bin/boa` | Medium
25 | File | `/boaform/device_reset.cgi` | High
26 | File | `/boafrm/formMapDelDevice` | High
27 | File | `/bsms_ci/index.php` | High
28 | File | `/bsms_ci/index.php/user/edit_user/` | High
29 | File | `/cgi-bin/cstecgi.cgi` | High
30 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
31 | File | `/cgi-bin/kerbynet` | High
32 | File | `/cgi-bin/koha/catalogue/search.pl` | High
33 | File | `/cgi-bin/R14.2/cgi-bin/R14.2/host.pl` | High
34 | File | `/cgi-bin/R14.2/easy1350.pl` | High
35 | File | `/cgi-bin/webviewer_login_page` | High
36 | File | `/cgi-bin/wlogin.cgi` | High
37 | File | `/clinic/disease_symptoms_view.php` | High
38 | File | `/config/getuser` | High
39 | File | `/core/redirect` | High
40 | File | `/dashboard/snapshot/*?orgId=0` | High
41 | File | `/debug/pprof` | Medium
42 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
43 | File | `/DXR.axd` | Medium
44 | ... | ... | ...

There are 381 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trendmicro.com/content/dam/trendmicro/global/en/research/23/l/pawn-storm-uses-brute-force-and-stealth-against-high-value-targets-/iocs-pawn-storm-uses-brute-force-and-stealth-against-high-value-targets.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
