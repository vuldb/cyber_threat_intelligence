# Orangeworm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Orangeworm](https://vuldb.com/?actor.orangeworm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.orangeworm](https://vuldb.com/?actor.orangeworm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Orangeworm:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Orangeworm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.44.61.126](https://vuldb.com/?ip.13.44.61.126) | - | - | High
2 | [16.48.37.37](https://vuldb.com/?ip.16.48.37.37) | - | - | High
3 | [18.25.62.70](https://vuldb.com/?ip.18.25.62.70) | - | - | High
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Orangeworm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Orangeworm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.htpasswd` | Medium
2 | File | `//etc/RT2870STA.dat` | High
3 | File | `/api/user/{ID}` | High
4 | File | `/bin/proc.cgi` | High
5 | File | `/cgi-bin/login_action.cgi` | High
6 | File | `/data/vendor/tcl` | High
7 | File | `/download` | Medium
8 | File | `/etc/tomcat8/Catalina/attack` | High
9 | File | `/files.md5` | Medium
10 | File | `/forum/away.php` | High
11 | File | `/getcfg.php` | Medium
12 | File | `/modules/profile/index.php` | High
13 | File | `/modules/registration_admission/patient_register.php` | High
14 | File | `/news.dtl.php` | High
15 | File | `/public/plugins/` | High
16 | File | `/rapi/read_url` | High
17 | File | `/rest/api/2/user/picker` | High
18 | File | `/sbin/acos_service` | High
19 | File | `/scripts/iisadmin/bdir.htr` | High
20 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
21 | File | `/squashfs-root/www/HNAP1/control/SetWizardConfig.php` | High
22 | File | `/SSOPOST/metaAlias/%realm%/idpv2` | High
23 | File | `/uncpath/` | Medium
24 | File | `/usr/bin/pkexec` | High
25 | File | `/ViewUserHover.jspa` | High
26 | File | `/WEB-INF/web.xml` | High
27 | File | `/wp-admin/admin-ajax.php` | High
28 | File | `/wp-json/oembed/1.0/embed?url` | High
29 | File | `/www/cgi-bin/popen.cgi` | High
30 | File | `5.2.9\syscrb.exe` | High
31 | File | `ad.cgi` | Low
32 | ... | ... | ...

There are 269 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://symantec-enterprise-blogs.security.com/sites/default/files/2018-04/Orangeworm%20IOCs.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
