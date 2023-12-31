# Cuba Ransomware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cuba Ransomware](https://vuldb.com/?actor.cuba_ransomware). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cuba_ransomware](https://vuldb.com/?actor.cuba_ransomware)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cuba Ransomware:

* [VN](https://vuldb.com/?country.vn)
* [LU](https://vuldb.com/?country.lu)
* [US](https://vuldb.com/?country.us)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cuba Ransomware.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [10.13.102.1](https://vuldb.com/?ip.10.13.102.1) | - | - | High
2 | [10.13.102.58](https://vuldb.com/?ip.10.13.102.58) | - | - | High
3 | [10.14.100.20](https://vuldb.com/?ip.10.14.100.20) | - | - | High
4 | [10.133.78.41](https://vuldb.com/?ip.10.133.78.41) | - | - | High
5 | [23.160.193.145](https://vuldb.com/?ip.23.160.193.145) | server1.wlook.com | - | High
6 | [23.227.198.246](https://vuldb.com/?ip.23.227.198.246) | 23-227-198-246.static.hvvc.us | - | High
7 | [31.44.184.84](https://vuldb.com/?ip.31.44.184.84) | - | - | High
8 | [31.44.184.100](https://vuldb.com/?ip.31.44.184.100) | - | - | High
9 | [31.184.192.44](https://vuldb.com/?ip.31.184.192.44) | - | - | High
10 | [31.184.194.42](https://vuldb.com/?ip.31.184.194.42) | - | - | High
11 | [31.184.198.74](https://vuldb.com/?ip.31.184.198.74) | - | - | High
12 | [31.184.198.80](https://vuldb.com/?ip.31.184.198.80) | directingme.com | - | High
13 | [31.184.198.82](https://vuldb.com/?ip.31.184.198.82) | harms.directingme.com | - | High
14 | [31.184.198.83](https://vuldb.com/?ip.31.184.198.83) | - | - | High
15 | [31.184.198.84](https://vuldb.com/?ip.31.184.198.84) | - | - | High
16 | ... | ... | ... | ...

There are 60 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cuba Ransomware_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cuba Ransomware. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?ajax-request=jnews` | High
2 | File | `/accounts/password_change/` | High
3 | File | `/activate_hook.php` | High
4 | File | `/admin/ajax.php?action=confirm_order` | High
5 | File | `/admin/courses/manage_course.php` | High
6 | File | `/admin/departments/manage_department.php` | High
7 | File | `/admin/students/manage_academic.php` | High
8 | File | `/api/addusers` | High
9 | File | `/api/baskets/{name}` | High
10 | File | `/api/v1/terminal/sessions/?limit=1` | High
11 | File | `/assets/something/services/AppModule.class` | High
12 | File | `/audit/log/log_management.php` | High
13 | File | `/authenticationendpoint/login.do` | High
14 | File | `/b2b-supermarket/shopping-cart` | High
15 | File | `/blog/comment` | High
16 | File | `/bsms_ci/index.php` | High
17 | File | `/catalog/compare` | High
18 | File | `/cgi-bin/downloadFile.cgi` | High
19 | File | `/cgi-bin/wlogin.cgi` | High
20 | File | `/classes/Users.php` | High
21 | File | `/debug/pprof` | Medium
22 | File | `/DXR.axd` | Medium
23 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
24 | File | `/env` | Low
25 | File | `/forms/doLogin` | High
26 | File | `/forum/away.php` | High
27 | File | `/geoserver/gwc/rest.html` | High
28 | File | `/importexport.php` | High
29 | File | `/index.php` | Medium
30 | File | `/index.php/client/message/message_read/xxxxxxxx[random-msg-hash]` | High
31 | File | `/librarian/bookdetails.php` | High
32 | File | `/login` | Low
33 | File | `/MailAdmin_dll.htm` | High
34 | File | `/mhds/clinic/view_details.php` | High
35 | ... | ... | ...

There are 298 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/cuba-ransomware/110533/
* https://www.cisa.gov/uscert/ncas/alerts/aa22-335a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
