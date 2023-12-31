# Applejeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Applejeus](https://vuldb.com/?actor.applejeus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.applejeus](https://vuldb.com/?actor.applejeus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Applejeus:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 8 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Applejeus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | - | High
2 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | - | High
3 | [95.213.232.170](https://vuldb.com/?ip.95.213.232.170) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Applejeus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-25, CWE-29, CWE-36 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Applejeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.terminfo` | High
2 | File | `/?ajax-request=jnews` | High
3 | File | `/admin/category/save` | High
4 | File | `/admin/subject.php` | High
5 | File | `/api/baskets/{name}` | High
6 | File | `/api/gen/clients/{language}` | High
7 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
8 | File | `/auth/auth.php?user=1` | High
9 | File | `/bin/login` | Medium
10 | File | `/bin/mini_upnpd` | High
11 | File | `/cgi-bin/wlogin.cgi` | High
12 | File | `/classes/Users.php` | High
13 | File | `/config/getuser` | High
14 | File | `/DXR.axd` | Medium
15 | File | `/forum/away.php` | High
16 | File | `/goform/goform_get_cmd_process` | High
17 | File | `/goform/set_LimitClient_cfg` | High
18 | File | `/h/autoSaveDraft` | High
19 | File | `/h/search?action` | High
20 | File | `/HNAP1` | Low
21 | File | `/HNAP1/` | Low
22 | File | `/hss/admin/?page=products/view_product` | High
23 | File | `/importexport.php` | High
24 | File | `/index.php?app=main&func=passport&action=login` | High
25 | File | `/main/doctype.php` | High
26 | File | `/main/webservices/additional_webservices.php` | High
27 | File | `/mc` | Low
28 | File | `/mgmt/` | Low
29 | File | `/oauth/idp/.well-known/openid-configuration` | High
30 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
31 | File | `/owa/auth/logon.aspx` | High
32 | File | `/preview.php` | Medium
33 | File | `/register.php` | High
34 | File | `/secure/ViewCollectors` | High
35 | File | `/server-status` | High
36 | ... | ... | ...

There are 309 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
