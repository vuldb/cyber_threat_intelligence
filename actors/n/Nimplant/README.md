# Nimplant - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nimplant](https://vuldb.com/?actor.nimplant). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nimplant](https://vuldb.com/?actor.nimplant)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nimplant:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [DK](https://vuldb.com/?country.dk)
* ...

There are 4 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nimplant.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.147.54](https://vuldb.com/?ip.3.0.147.54) | ec2-3-0-147-54.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.17.181.161](https://vuldb.com/?ip.3.17.181.161) | ec2-3-17-181-161.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.226.6.113](https://vuldb.com/?ip.3.226.6.113) | ec2-3-226-6-113.compute-1.amazonaws.com | - | Medium
4 | [3.239.44.147](https://vuldb.com/?ip.3.239.44.147) | ec2-3-239-44-147.compute-1.amazonaws.com | - | Medium
5 | [13.70.157.121](https://vuldb.com/?ip.13.70.157.121) | - | - | High
6 | [14.225.206.107](https://vuldb.com/?ip.14.225.206.107) | static.vnpt.vn | - | High
7 | [20.93.3.210](https://vuldb.com/?ip.20.93.3.210) | - | - | High
8 | [23.106.215.199](https://vuldb.com/?ip.23.106.215.199) | - | - | High
9 | ... | ... | ... | ...

There are 31 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-36, CWE-37, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abcd/opac/php/otros_sitios.php` | High
2 | File | `/admin/aboutus.php` | High
3 | File | `/admin/admin_log.php?clear=1` | High
4 | File | `/admin/admin_widgets.php?action=install/widget=akismet` | High
5 | File | `/admin/config_time_sync.php` | High
6 | File | `/admin/contacts/organizations/edit/2` | High
7 | File | `/admin/dialog/select_images_post.php` | High
8 | File | `/admin/forms/option_lists/edit.php` | High
9 | File | `/admin/login.php` | High
10 | File | `/admin/pages/list` | High
11 | File | `/admin/quizquestion.php` | High
12 | File | `/admin/robot.php` | High
13 | File | `/admin/system.php` | High
14 | File | `/admins/{adminId}` | High
15 | File | `/api/swaggerui/static` | High
16 | File | `/api/sys/set_passwd` | High
17 | File | `/articles/welcome-to-your-site#comments-head` | High
18 | File | `/boafrm/formSystemCheck` | High
19 | File | `/buscar_integrada.php` | High
20 | File | `/cgi-bin/alexserv` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/cgi-bin/hd_config.cgi` | High
23 | File | `/cgi-bin/photocenter_mgr.cgi` | High
24 | File | `/cgi-bin/tosei_kikai.php` | High
25 | File | `/cgi-bin/webfile_mgr.cgi` | High
26 | File | `/classes/Master.php` | High
27 | File | `/classes/Master.php?f=save_package` | High
28 | File | `/contact.php` | Medium
29 | File | `/controllers/add_user.php` | High
30 | File | `/core/config-revisions` | High
31 | File | `/core/tools/delete_place.php` | High
32 | File | `/dcim/power-ports/add/` | High
33 | File | `/debug/pprof` | Medium
34 | File | `/DXR.axd` | Medium
35 | File | `/ecommerce/admin/login.php` | High
36 | File | `/ejbca/ra/cert` | High
37 | File | `/endpoint/add-calorie.php` | High
38 | File | `/endpoint/delete-account.php` | High
39 | File | `/endpoint/update.php` | High
40 | File | `/etc/passwd` | Medium
41 | File | `/files/` | Low
42 | File | `/film-rating.php` | High
43 | File | `/forum/away.php` | High
44 | File | `/goform/formEasySetTimezone` | High
45 | File | `/goform/formSetDomainFilter` | High
46 | File | `/goform/formSetQoS` | High
47 | File | `/goform/formSetWanPPPoE` | High
48 | File | `/goform/qossetting` | High
49 | File | `/goform/setDeviceSettings` | High
50 | File | `/guestbook` | Medium
51 | File | `/hardware` | Medium
52 | File | `/ims/login.php` | High
53 | ... | ... | ...

There are 466 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.226.6.113
* https://search.censys.io/hosts/3.239.44.147
* https://search.censys.io/hosts/13.70.157.121
* https://search.censys.io/hosts/14.225.206.107
* https://search.censys.io/hosts/20.93.3.210
* https://search.censys.io/hosts/23.106.215.199
* https://search.censys.io/hosts/51.68.222.10
* https://search.censys.io/hosts/54.38.242.131
* https://search.censys.io/hosts/54.202.46.22
* https://search.censys.io/hosts/89.73.53.34
* https://search.censys.io/hosts/94.102.49.16
* https://search.censys.io/hosts/94.102.49.106
* https://search.censys.io/hosts/142.93.226.220
* https://search.censys.io/hosts/146.190.241.166
* https://search.censys.io/hosts/149.248.79.215
* https://search.censys.io/hosts/167.88.160.211
* https://search.censys.io/hosts/167.88.170.172
* https://search.censys.io/hosts/185.196.10.245
* https://search.censys.io/hosts/207.154.192.30
* https://search.censys.io/hosts/207.180.253.60
* https://search.censys.io/hosts/210.2.169.231
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
