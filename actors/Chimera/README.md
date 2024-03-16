# Chimera - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chimera](https://vuldb.com/?actor.chimera). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chimera](https://vuldb.com/?actor.chimera)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chimera:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chimera.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.3.35.342](https://vuldb.com/?ip.1.3.35.342) | - | - | High
2 | [5.254.64.234](https://vuldb.com/?ip.5.254.64.234) | - | - | High
3 | [5.254.112.226](https://vuldb.com/?ip.5.254.112.226) | - | - | High
4 | [14.229.140.66](https://vuldb.com/?ip.14.229.140.66) | static.vnpt.vn | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chimera_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29 | Path Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chimera. This data is unique as it uses our predictive model for actor profiling.

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
24 | File | `/b2b-supermarket/shopping-cart` | High
25 | File | `/bin/boa` | Medium
26 | File | `/boaform/device_reset.cgi` | High
27 | File | `/boafrm/formMapDelDevice` | High
28 | File | `/bsms_ci/index.php` | High
29 | File | `/bsms_ci/index.php/user/edit_user/` | High
30 | File | `/cgi-bin/cstecgi.cgi` | High
31 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
32 | File | `/cgi-bin/kerbynet` | High
33 | File | `/cgi-bin/koha/catalogue/search.pl` | High
34 | File | `/cgi-bin/mainfunction.cgi` | High
35 | File | `/cgi-bin/R14.2/cgi-bin/R14.2/host.pl` | High
36 | File | `/cgi-bin/R14.2/easy1350.pl` | High
37 | File | `/cgi-bin/wlogin.cgi` | High
38 | File | `/clinic/disease_symptoms_view.php` | High
39 | File | `/config/getuser` | High
40 | File | `/core/redirect` | High
41 | File | `/dashboard/snapshot/*?orgId=0` | High
42 | File | `/debug/pprof` | Medium
43 | File | `/DXR.axd` | Medium
44 | File | `/ECT_Provider/` | High
45 | File | `/fax/fax_send.php` | High
46 | ... | ... | ...

There are 399 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cycraft.com/download/%5BTLP-White%5D20200415%20Chimera_V4.1.pdf
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.12/Chimera.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
