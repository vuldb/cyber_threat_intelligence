# Campaign D - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign D_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign D:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 2 more country items available. Please use our online service to access the data.

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
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 6 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign D. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.htpasswd` | Medium
2 | File | `//etc/RT2870STA.dat` | High
3 | File | `/cgi-bin/login_action.cgi` | High
4 | File | `/download` | Medium
5 | File | `/etc/tomcat8/Catalina/attack` | High
6 | File | `/forum/away.php` | High
7 | File | `/getcfg.php` | Medium
8 | File | `/modules/profile/index.php` | High
9 | File | `/modules/registration_admission/patient_register.php` | High
10 | File | `/news.dtl.php` | High
11 | File | `/public/plugins/` | High
12 | File | `/rapi/read_url` | High
13 | File | `/rest/api/2/user/picker` | High
14 | File | `/scripts/iisadmin/bdir.htr` | High
15 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
16 | File | `/squashfs-root/www/HNAP1/control/SetWizardConfig.php` | High
17 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
18 | File | `/uncpath/` | Medium
19 | File | `/usr/bin/pkexec` | High
20 | File | `/ViewUserHover.jspa` | High
21 | File | `/WEB-INF/web.xml` | High
22 | File | `/wp-json/oembed/1.0/embed?url` | High
23 | File | `5.2.9\syscrb.exe` | High
24 | File | `ad.cgi` | Low
25 | File | `adclick.php` | Medium
26 | File | `add-category.php` | High
27 | File | `add_comment.php` | High
28 | File | `admin.php` | Medium
29 | File | `admin/config/confmgr.php` | High
30 | ... | ... | ...

There are 256 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_D_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
