# Sunburst - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Sunburst](https://vuldb.com/?actor.sunburst). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.sunburst](https://vuldb.com/?actor.sunburst)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sunburst:

* [JP](https://vuldb.com/?country.jp)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sunburst.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [144.86.226.0](https://vuldb.com/?ip.144.86.226.0) | - | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sunburst_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sunburst. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%WINDIR%\temp` | High
2 | File | `/Account/EditProfile` | High
3 | File | `/activity/newActivityedit.php?DontCheckLogin=1&id=null&ret=mod1` | High
4 | File | `/add-pig.php` | Medium
5 | File | `/adm/index.php` | High
6 | File | `/admin.php?mod=brand&act=del` | High
7 | File | `/admin/aboutPost.php` | High
8 | File | `/admin/AdminLogin.php` | High
9 | File | `/admin/admin_addnew_product.php` | High
10 | File | `/admin/ajax.php?action=login` | High
11 | File | `/admin/all-request.php` | High
12 | File | `/admin/article.php` | High
13 | File | `/admin/betweendates-detailsreports.php` | High
14 | File | `/admin/campsdetails.php` | High
15 | File | `/admin/contactus.php` | High
16 | File | `/admin/course.php` | High
17 | File | `/admin/department.php` | High
18 | File | `/admin/edit-customer-detailed.php` | High
19 | File | `/admin/edit-services.php` | High
20 | File | `/admin/forgot-password.php` | High
21 | File | `/admin/gallery.php` | High
22 | File | `/admin/level.php` | High
23 | File | `/admin/registration.php` | High
24 | File | `/admin/search-report-details.php` | High
25 | File | `/admin/setup.cgi` | High
26 | File | `/admin/view-pass-detail.php` | High
27 | File | `/admin/View_user.php` | High
28 | File | `/ajax_state.php` | High
29 | File | `/api/browserextension/UpdatePassword/` | High
30 | File | `/api/discoveries/` | High
31 | File | `/api/esps` | Medium
32 | File | `/api/wizard/getDualbandSync` | High
33 | File | `/api/wizard/getNetworkConf` | High
34 | File | `/api/wizard/networkSetup` | High
35 | File | `/app/api/controller/caiji.php` | High
36 | File | `/app/api/controller/collect.php` | High
37 | File | `/app/controller/Setup.php` | High
38 | File | `/application/models/ApplicationDataObject.class.php` | High
39 | File | `/auth.asp` | Medium
40 | File | `/auth/setup` | Medium
41 | File | `/auth/soup-auth-digest.c` | High
42 | File | `/bin/goahead` | Medium
43 | File | `/bin/gpio` | Medium
44 | File | `/bin/httpd` | Medium
45 | File | `/bin/main` | Medium
46 | File | `/binutils/debug.c` | High
47 | File | `/biurl_grou` | Medium
48 | File | `/boa/formWSC` | Medium
49 | File | `/boafrm/formDMZ` | High
50 | File | `/boafrm/formDosCfg` | High
51 | File | `/boafrm/formFilter` | High
52 | File | `/boafrm/formIpQoS` | High
53 | File | `/boafrm/formIPv6Addr` | High
54 | File | `/boafrm/formMapDelDevice` | High
55 | File | `/boafrm/formMultiAP` | High
56 | File | `/boafrm/formNtp` | High
57 | File | `/boafrm/formParentControl` | High
58 | File | `/boafrm/formPortFw` | High
59 | File | `/boafrm/formReflashClientTbl` | High
60 | File | `/boafrm/formSaveConfig` | High
61 | File | `/boafrm/formSetLg` | High
62 | File | `/boafrm/formSiteSurveyProfile` | High
63 | File | `/boafrm/formStaticDHCP` | High
64 | File | `/boafrm/formStats` | High
65 | File | `/boafrm/formSysCmd` | High
66 | ... | ... | ...

There are 577 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://exchange.xforce.ibmcloud.com/report/details/guid:4455546d71ef4423b420ab09ebbc3311

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
