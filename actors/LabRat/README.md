# LabRat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LabRat](https://vuldb.com/?actor.labrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.labrat](https://vuldb.com/?actor.labrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LabRat:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LabRat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.234.16.54](https://vuldb.com/?ip.1.234.16.54) | - | - | High
2 | [23.94.204.157](https://vuldb.com/?ip.23.94.204.157) | 23-94-204-157-host.colocrossing.com | - | High
3 | [107.173.154.7](https://vuldb.com/?ip.107.173.154.7) | 107-173-154-7-host.colocrossing.com | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LabRat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LabRat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?ajax-request=jnews` | High
2 | File | `/accounts/password_change/` | High
3 | File | `/act/ActDao.xml` | High
4 | File | `/admin/ajax.php?action=confirm_order` | High
5 | File | `/api/addusers` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/v1/terminal/sessions/?limit=1` | High
8 | File | `/assets/something/services/AppModule.class` | High
9 | File | `/authenticationendpoint/login.do` | High
10 | File | `/b2b-supermarket/shopping-cart` | High
11 | File | `/blog/comment` | High
12 | File | `/bsms_ci/index.php` | High
13 | File | `/catalog/compare` | High
14 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
15 | File | `/cgi-bin/downloadFile.cgi` | High
16 | File | `/cgi-bin/kerbynet` | High
17 | File | `/cgi-bin/wlogin.cgi` | High
18 | File | `/classes/Users.php` | High
19 | File | `/clinic/disease_symptoms_view.php` | High
20 | File | `/debug/pprof` | Medium
21 | File | `/DXR.axd` | Medium
22 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
23 | File | `/forum/away.php` | High
24 | File | `/geoserver/gwc/rest.html` | High
25 | File | `/importexport.php` | High
26 | File | `/index.php/client/message/message_read/xxxxxxxx[random-msg-hash]` | High
27 | File | `/login` | Low
28 | File | `/mhds/clinic/view_details.php` | High
29 | File | `/modals/class_form.php` | High
30 | File | `/oauth/idp/.well-known/openid-configuration` | High
31 | File | `/php-opos/index.php` | High
32 | File | `/php/exportrecord.php` | High
33 | File | `/php/ping.php` | High
34 | File | `/plain` | Low
35 | File | `/proc/#####/fd/3` | High
36 | File | `/shell` | Low
37 | File | `/showfile.php` | High
38 | ... | ... | ...

There are 331 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://sysdig.com/blog/labrat-cryptojacking-proxyjacking-campaign/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
