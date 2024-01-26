# Revenge RAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Revenge RAT](https://vuldb.com/?actor.revenge_rat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revenge_rat](https://vuldb.com/?actor.revenge_rat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Revenge RAT:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Revenge RAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.138.180.119](https://vuldb.com/?ip.3.138.180.119) | ec2-3-138-180-119.us-east-2.compute.amazonaws.com | - | Medium
2 | [5.39.19.8](https://vuldb.com/?ip.5.39.19.8) | - | - | High
3 | [18.228.214.231](https://vuldb.com/?ip.18.228.214.231) | ec2-18-228-214-231.sa-east-1.compute.amazonaws.com | - | Medium
4 | [23.237.25.123](https://vuldb.com/?ip.23.237.25.123) | - | - | High
5 | [37.0.11.45](https://vuldb.com/?ip.37.0.11.45) | - | - | High
6 | [38.132.101.45](https://vuldb.com/?ip.38.132.101.45) | - | - | High
7 | [40.127.163.74](https://vuldb.com/?ip.40.127.163.74) | - | - | High
8 | [42.118.133.241](https://vuldb.com/?ip.42.118.133.241) | - | - | High
9 | [45.137.22.152](https://vuldb.com/?ip.45.137.22.152) | hosted-by.rootlayer.net | - | High
10 | [45.147.230.231](https://vuldb.com/?ip.45.147.230.231) | - | - | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Revenge RAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Revenge RAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\checkmk\agent\local` | High
2 | File | `/?Key=PhoneRequestAuthorization` | High
3 | File | `/account/ResetPassword` | High
4 | File | `/admin/access` | High
5 | File | `/admin/index.html` | High
6 | File | `/admin/syslog` | High
7 | File | `/admin_giant/add_team_member.php` | High
8 | File | `/bin/login` | Medium
9 | File | `/cgi-bin/ExportALLSettings.sh` | High
10 | File | `/common/info.cgi` | High
11 | File | `/course/filterRecords/` | High
12 | File | `/download/image` | High
13 | File | `/DXR.axd` | Medium
14 | File | `/etc/gsissh/sshd_config` | High
15 | File | `/etc/sudoers` | Medium
16 | File | `/fhconf/umconfig.txt` | High
17 | File | `/forum/away.php` | High
18 | File | `/get_getnetworkconf.cgi` | High
19 | File | `/goform/setmac` | High
20 | File | `/home` | Low
21 | File | `/horde/util/go.php` | High
22 | File | `/hrm/controller/employee.php` | High
23 | File | `/include/chart_generator.php` | High
24 | File | `/integrations.json` | High
25 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
26 | File | `/product.php` | Medium
27 | File | `/public` | Low
28 | File | `/public/login.htm` | High
29 | File | `/spip.php` | Medium
30 | File | `/uncpath/` | Medium
31 | File | `/users/admin/user_activity.php` | High
32 | File | `/usr/local/www/pkg.php` | High
33 | File | `/var/www/rhcert` | High
34 | File | `/vendor/htmlawed/htmlawed/htmLawedTest.php` | High
35 | File | `/web/api/app/Controller/HostController.php` | High
36 | File | `/wp-content/plugins/updraftplus/admin.php` | High
37 | File | `a2billing/customer/iridium_threed.php` | High
38 | File | `adclick.php` | Medium
39 | File | `addentry.php` | Medium
40 | File | `Addmessage.php` | High
41 | File | `admin.php` | Medium
42 | File | `admin.php/comments/batchdel/` | High
43 | File | `admin.php/User/del/ucode/` | High
44 | ... | ... | ...

There are 380 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch
* https://tria.ge/231218-shv6tscgh3

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
