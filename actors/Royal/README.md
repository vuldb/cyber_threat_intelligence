# Royal - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Royal](https://vuldb.com/?actor.royal). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.royal](https://vuldb.com/?actor.royal)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Royal:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Royal.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.44.42.20](https://vuldb.com/?ip.5.44.42.20) | 4SER-1678212226.ip-ptr.tech | - | High
2 | [5.181.234.58](https://vuldb.com/?ip.5.181.234.58) | - | - | High
3 | [5.188.86.195](https://vuldb.com/?ip.5.188.86.195) | - | - | High
4 | [23.111.114.52](https://vuldb.com/?ip.23.111.114.52) | - | - | High
5 | [41.97.65.51](https://vuldb.com/?ip.41.97.65.51) | - | - | High
6 | [41.100.55.97](https://vuldb.com/?ip.41.100.55.97) | - | - | High
7 | [41.107.77.67](https://vuldb.com/?ip.41.107.77.67) | - | - | High
8 | [41.109.11.80](https://vuldb.com/?ip.41.109.11.80) | - | - | High
9 | [41.251.121.35](https://vuldb.com/?ip.41.251.121.35) | - | - | High
10 | [42.189.12.36](https://vuldb.com/?ip.42.189.12.36) | - | - | High
11 | [45.8.158.104](https://vuldb.com/?ip.45.8.158.104) | - | - | High
12 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Royal_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-29, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Royal. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `//proc/kcore` | Medium
3 | File | `/accounts/password_change/` | High
4 | File | `/act/ActDao.xml` | High
5 | File | `/admin/action/delete-vaccine.php` | High
6 | File | `/admin/action/new-father.php` | High
7 | File | `/admin/clientview.php` | High
8 | File | `/admin/edit_teacher.php` | High
9 | File | `/admin/fields/manage_field.php` | High
10 | File | `/admin/index2.html` | High
11 | File | `/admin/regester.php` | High
12 | File | `/admin/update-clients.php` | High
13 | File | `/admin_route/dec_service_credits.php` | High
14 | File | `/admin_route/inc_service_credits.php` | High
15 | File | `/api/baskets/{name}` | High
16 | File | `/api/cron/settings/setJob/` | High
17 | File | `/api/sys/set_passwd` | High
18 | File | `/api/v1/terminal/sessions/?limit=1` | High
19 | File | `/app/api/controller/default/Sqlite.php` | High
20 | File | `/app/index/controller/Common.php` | High
21 | File | `/apply.cgi` | Medium
22 | File | `/arch/x86/mm/cpu_entry_area.c` | High
23 | File | `/authenticationendpoint/login.do` | High
24 | File | `/b2b-supermarket/shopping-cart` | High
25 | File | `/bin/boa` | Medium
26 | File | `/boaform/device_reset.cgi` | High
27 | File | `/bsms_ci/index.php` | High
28 | File | `/bsms_ci/index.php/user/edit_user/` | High
29 | File | `/catalog/compare` | High
30 | File | `/cgi-bin/cstecgi.cgi` | High
31 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
32 | File | `/cgi-bin/downloadFile.cgi` | High
33 | File | `/cgi-bin/kerbynet` | High
34 | File | `/cgi-bin/koha/catalogue/search.pl` | High
35 | File | `/cgi-bin/R14.2/cgi-bin/R14.2/host.pl` | High
36 | File | `/cgi-bin/R14.2/easy1350.pl` | High
37 | File | `/cgi-bin/system_mgr.cgi` | High
38 | File | `/cgi-bin/wlogin.cgi` | High
39 | File | `/clinic/disease_symptoms_view.php` | High
40 | File | `/config/getuser` | High
41 | File | `/dashboard/snapshot/*?orgId=0` | High
42 | File | `/debug/pprof` | Medium
43 | File | `/DXR.axd` | Medium
44 | ... | ... | ...

There are 376 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-061a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
