# Gozi - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Gozi](https://vuldb.com/?actor.gozi). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.gozi](https://vuldb.com/?actor.gozi)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Gozi:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Gozi.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.42.199.57](https://vuldb.com/?ip.5.42.199.57) | - | - | High
2 | [23.227.202.64](https://vuldb.com/?ip.23.227.202.64) | 23-227-202-64.static.hvvc.us | - | High
3 | [31.41.44.60](https://vuldb.com/?ip.31.41.44.60) | free.cishost.ru | - | High
4 | [31.41.44.63](https://vuldb.com/?ip.31.41.44.63) | free.cishost.ru | - | High
5 | [31.41.44.112](https://vuldb.com/?ip.31.41.44.112) | free.cishost.ru | - | High
6 | [31.41.44.124](https://vuldb.com/?ip.31.41.44.124) | free.cishost.ru | - | High
7 | [31.41.44.125](https://vuldb.com/?ip.31.41.44.125) | free.cishost.ru | - | High
8 | [31.41.46.120](https://vuldb.com/?ip.31.41.46.120) | free.cishost.ru | - | High
9 | [31.41.46.132](https://vuldb.com/?ip.31.41.46.132) | free.cishost.ru | - | High
10 | [31.148.99.142](https://vuldb.com/?ip.31.148.99.142) | - | - | High
11 | [31.148.99.193](https://vuldb.com/?ip.31.148.99.193) | - | - | High
12 | [31.207.46.12](https://vuldb.com/?ip.31.207.46.12) | - | - | High
13 | [31.214.157.235](https://vuldb.com/?ip.31.214.157.235) | kuhit.rdfew.com | - | High
14 | [37.10.71.221](https://vuldb.com/?ip.37.10.71.221) | smtp1.cloudmailsys.com | - | High
15 | [37.120.206.71](https://vuldb.com/?ip.37.120.206.71) | - | - | High
16 | [37.120.206.84](https://vuldb.com/?ip.37.120.206.84) | - | - | High
17 | ... | ... | ... | ...

There are 66 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Gozi_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Gozi. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.../gogo/` | Medium
2 | File | `.htaccess` | Medium
3 | File | `/+CSCOE+/logon.html` | High
4 | File | `/about.php` | Medium
5 | File | `/addnews.html` | High
6 | File | `/admin` | Low
7 | File | `/admin.add` | Medium
8 | File | `/admin/add_exercises.php` | High
9 | File | `/admin/admin.php?module=admin_access_group_edit&aagID` | High
10 | File | `/admin/admin.php?module=admin_group_edit&agID` | High
11 | File | `/admin/edit.php` | High
12 | File | `/admin/index.php` | High
13 | File | `/api/v2/labels/` | High
14 | File | `/category.php` | High
15 | File | `/category_view.php` | High
16 | File | `/cimom` | Low
17 | File | `/ci_hms/search` | High
18 | File | `/dashboard/add-portfolio.php` | High
19 | File | `/dashboard/updatelogo.php` | High
20 | File | `/debug/pprof` | Medium
21 | File | `/dev/snd/seq` | Medium
22 | File | `/etc/controller-agent/agent.conf` | High
23 | File | `/index.php` | Medium
24 | File | `/info.xml` | Medium
25 | File | `/jeecg-boot/sys/user/queryUserByDepId` | High
26 | File | `/login.php` | Medium
27 | File | `/manage-apartment.php` | High
28 | File | `/members/view_member.php` | High
29 | File | `/mgmt/tm/util/bash` | High
30 | File | `/mygym/admin/index.php?view_exercises` | High
31 | File | `/out.php` | Medium
32 | File | `/owa/auth/logon.aspx` | High
33 | File | `/php-jms/review_se_result.php` | High
34 | File | `/plesk-site-preview/` | High
35 | File | `/plugins/servlet/gadgets/makeRequest` | High
36 | File | `/ptms/classes/Users.php` | High
37 | File | `/REBOOTSYSTEM` | High
38 | File | `/rest/project-templates/1.0/createshared` | High
39 | File | `/secure/admin/ImporterFinishedPage.jspa` | High
40 | File | `/secure/QueryComponent!Default.jspa` | High
41 | File | `/see_more_details.php` | High
42 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
43 | File | `/tmp` | Low
44 | File | `/tmp/csman/0` | Medium
45 | File | `/uncpath/` | Medium
46 | File | `/usr/bin/at` | Medium
47 | File | `/v3/credentials` | High
48 | File | `/var/run/jboss-eap/` | High
49 | File | `/vdesk` | Low
50 | ... | ... | ...

There are 436 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/aa8a59aaed89dd7c8696a7d63fa2763689be023a4a7692f63d950d8b923b6154/
* https://bazaar.abuse.ch/sample/eb617fa7cba6309640cda1035eee2fc79fa77c44b229e3c0213d44d97f1b4426/
* https://blog.talosintelligence.com/2019/10/threat-roundup-1011-1018.html
* https://threatfox.abuse.ch
* https://twitter.com/reecdeep/status/1407262328140320769

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
