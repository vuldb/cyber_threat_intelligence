# Nimplant - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nimplant](https://vuldb.com/?actor.nimplant). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nimplant](https://vuldb.com/?actor.nimplant)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nimplant:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nimplant.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.147.54](https://vuldb.com/?ip.3.0.147.54) | ec2-3-0-147-54.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.226.6.113](https://vuldb.com/?ip.3.226.6.113) | ec2-3-226-6-113.compute-1.amazonaws.com | - | Medium
3 | [14.225.206.107](https://vuldb.com/?ip.14.225.206.107) | static.vnpt.vn | - | High
4 | ... | ... | ... | ...

There are 11 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.env` | Low
2 | File | `/accounts/password_change/` | High
3 | File | `/act/ActDao.xml` | High
4 | File | `/admin/action/new-father.php` | High
5 | File | `/admin/clientview.php` | High
6 | File | `/admin/edit_teacher.php` | High
7 | File | `/admin/fields/manage_field.php` | High
8 | File | `/admin/regester.php` | High
9 | File | `/admin/update-clients.php` | High
10 | File | `/admin_route/dec_service_credits.php` | High
11 | File | `/admin_route/inc_service_credits.php` | High
12 | File | `/api/baskets/{name}` | High
13 | File | `/api/cron/settings/setJob/` | High
14 | File | `/api/sys/set_passwd` | High
15 | File | `/api/v1/terminal/sessions/?limit=1` | High
16 | File | `/app/api/controller/default/Sqlite.php` | High
17 | File | `/apply.cgi` | Medium
18 | File | `/arch/x86/mm/cpu_entry_area.c` | High
19 | File | `/authenticationendpoint/login.do` | High
20 | File | `/b2b-supermarket/shopping-cart` | High
21 | File | `/bin/boa` | Medium
22 | File | `/boaform/device_reset.cgi` | High
23 | File | `/bsms_ci/index.php` | High
24 | File | `/bsms_ci/index.php/user/edit_user/` | High
25 | File | `/catalog/compare` | High
26 | File | `/cgi-bin/cstecgi.cgi` | High
27 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
28 | File | `/cgi-bin/downloadFile.cgi` | High
29 | File | `/cgi-bin/kerbynet` | High
30 | File | `/cgi-bin/koha/catalogue/search.pl` | High
31 | File | `/cgi-bin/R14.2/cgi-bin/R14.2/host.pl` | High
32 | File | `/cgi-bin/R14.2/easy1350.pl` | High
33 | File | `/cgi-bin/wlogin.cgi` | High
34 | File | `/clinic/disease_symptoms_view.php` | High
35 | File | `/config/getuser` | High
36 | File | `/dashboard/snapshot/*?orgId=0` | High
37 | File | `/debug/pprof` | Medium
38 | File | `/DXR.axd` | Medium
39 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
40 | File | `/forum/away.php` | High
41 | File | `/geoserver/gwc/rest.html` | High
42 | File | `/importexport.php` | High
43 | ... | ... | ...

There are 368 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.226.6.113
* https://search.censys.io/hosts/14.225.206.107
* https://search.censys.io/hosts/23.106.215.199
* https://search.censys.io/hosts/54.202.46.22
* https://search.censys.io/hosts/142.93.226.220
* https://search.censys.io/hosts/167.88.160.211
* https://search.censys.io/hosts/167.88.170.172
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
