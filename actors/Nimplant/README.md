# Nimplant - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nimplant](https://vuldb.com/?actor.nimplant). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nimplant](https://vuldb.com/?actor.nimplant)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nimplant:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nimplant.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.147.54](https://vuldb.com/?ip.3.0.147.54) | ec2-3-0-147-54.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.226.6.113](https://vuldb.com/?ip.3.226.6.113) | ec2-3-226-6-113.compute-1.amazonaws.com | - | Medium
3 | [14.225.206.107](https://vuldb.com/?ip.14.225.206.107) | static.vnpt.vn | - | High
4 | ... | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?ajax-request=jnews` | High
2 | File | `/admin/admin-profile.php` | High
3 | File | `/admin/ajax.php?action=confirm_order` | High
4 | File | `/admin/sales/view_details.php` | High
5 | File | `/api/addusers` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/cron/settings/setJob/` | High
8 | File | `/api/v1/snapshots` | High
9 | File | `/api/v1/terminal/sessions/?limit=1` | High
10 | File | `/assets/something/services/AppModule.class` | High
11 | File | `/audit/log/log_management.php` | High
12 | File | `/authenticationendpoint/login.do` | High
13 | File | `/blog/comment` | High
14 | File | `/catalog/compare` | High
15 | File | `/cgi-bin/downloadFile.cgi` | High
16 | File | `/cgi-bin/mainfunction.cgi` | High
17 | File | `/cgi-bin/wlogin.cgi` | High
18 | File | `/classes/Users.php` | High
19 | File | `/debug/pprof` | Medium
20 | File | `/dottie.js` | Medium
21 | File | `/DXR.axd` | Medium
22 | File | `/env` | Low
23 | File | `/forms/doLogin` | High
24 | File | `/forum/away.php` | High
25 | File | `/geoserver/gwc/rest.html` | High
26 | File | `/importexport.php` | High
27 | File | `/index.php` | Medium
28 | File | `/librarian/bookdetails.php` | High
29 | File | `/log/webmailattach.php` | High
30 | File | `/login` | Low
31 | File | `/mhds/clinic/view_details.php` | High
32 | File | `/php-opos/index.php` | High
33 | File | `/plain` | Low
34 | File | `/proc/#####/fd/3` | High
35 | ... | ... | ...

There are 297 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
