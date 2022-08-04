# Campaign D - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign D_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign D:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Campaign D or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign D.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [9.11.63.89](https://vuldb.com/?ip.9.11.63.89) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [11.89.101.8](https://vuldb.com/?ip.11.89.101.8) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [11.100.81.69](https://vuldb.com/?ip.11.100.81.69) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [13.44.61.126](https://vuldb.com/?ip.13.44.61.126) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [23.129.12.17](https://vuldb.com/?ip.23.129.12.17) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
6 | [25.17.137.61](https://vuldb.com/?ip.25.17.137.61) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [26.57.67.114](https://vuldb.com/?ip.26.57.67.114) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [26.79.14.142](https://vuldb.com/?ip.26.79.14.142) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [31.15.122.99](https://vuldb.com/?ip.31.15.122.99) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | [33.31.20.86](https://vuldb.com/?ip.33.31.20.86) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
11 | ... | ... | ... | ...

There are 39 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign D. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign D. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.htpasswd` | Medium
2 | File | `//etc/RT2870STA.dat` | High
3 | File | `/api/user/{ID}` | High
4 | File | `/cgi-bin/login_action.cgi` | High
5 | File | `/data/vendor/tcl` | High
6 | File | `/download` | Medium
7 | File | `/etc/tomcat8/Catalina/attack` | High
8 | File | `/forum/away.php` | High
9 | File | `/getcfg.php` | Medium
10 | File | `/modules/profile/index.php` | High
11 | File | `/modules/registration_admission/patient_register.php` | High
12 | File | `/news.dtl.php` | High
13 | File | `/public/plugins/` | High
14 | File | `/rapi/read_url` | High
15 | File | `/rest/api/2/user/picker` | High
16 | File | `/scripts/iisadmin/bdir.htr` | High
17 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
18 | File | `/squashfs-root/www/HNAP1/control/SetWizardConfig.php` | High
19 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
20 | File | `/uncpath/` | Medium
21 | File | `/usr/bin/pkexec` | High
22 | File | `/ViewUserHover.jspa` | High
23 | File | `/WEB-INF/web.xml` | High
24 | File | `/wp-admin/admin-ajax.php` | High
25 | File | `/wp-json/oembed/1.0/embed?url` | High
26 | File | `5.2.9\syscrb.exe` | High
27 | File | `ad.cgi` | Low
28 | File | `adclick.php` | Medium
29 | File | `add-category.php` | High
30 | File | `add_comment.php` | High
31 | ... | ... | ...

There are 266 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_D_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
