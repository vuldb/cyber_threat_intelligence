# Dofoil - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dofoil](https://vuldb.com/?actor.dofoil). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dofoil](https://vuldb.com/?actor.dofoil)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dofoil:

* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dofoil.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.149.253.100](https://vuldb.com/?ip.5.149.253.100) | enappiv.com | - | High
2 | [8.110.105.136](https://vuldb.com/?ip.8.110.105.136) | - | - | High
3 | [8.123.232.109](https://vuldb.com/?ip.8.123.232.109) | - | - | High
4 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
5 | [23.3.13.137](https://vuldb.com/?ip.23.3.13.137) | a23-3-13-137.deploy.static.akamaitechnologies.com | - | High
6 | [23.6.24.15](https://vuldb.com/?ip.23.6.24.15) | a23-6-24-15.deploy.static.akamaitechnologies.com | - | High
7 | [23.6.65.194](https://vuldb.com/?ip.23.6.65.194) | a23-6-65-194.deploy.static.akamaitechnologies.com | - | High
8 | [23.209.185.159](https://vuldb.com/?ip.23.209.185.159) | a23-209-185-159.deploy.static.akamaitechnologies.com | - | High
9 | [27.100.36.191](https://vuldb.com/?ip.27.100.36.191) | - | - | High
10 | [37.230.112.146](https://vuldb.com/?ip.37.230.112.146) | audiotop.ru | - | High
11 | [45.63.25.55](https://vuldb.com/?ip.45.63.25.55) | 45.63.25.55.vultr.com | - | Medium
12 | [50.3.75.246](https://vuldb.com/?ip.50.3.75.246) | web.netkolik.org | - | High
13 | ... | ... | ... | ...

There are 49 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dofoil_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-28, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dofoil. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin/config.php?display=disa&view=form` | High
4 | File | `/admin/submit-articles` | High
5 | File | `/ad_js.php` | Medium
6 | File | `/Ap4RtpAtom.cpp` | High
7 | File | `/app/options.py` | High
8 | File | `/attachments` | Medium
9 | File | `/bsms/?page=manage_account` | High
10 | File | `/bsms_ci/index.php/book` | High
11 | File | `/cgi-bin/login.cgi` | High
12 | File | `/cgi-bin/luci/api/wireless` | High
13 | File | `/ci_hms/massage_room/edit/1` | High
14 | File | `/context/%2e/WEB-INF/web.xml` | High
15 | File | `/dashboard/reports/logs/view` | High
16 | File | `/debian/patches/load_ppp_generic_if_needed` | High
17 | File | `/debug/pprof` | Medium
18 | File | `/etc/hosts` | Medium
19 | File | `/forum/away.php` | High
20 | File | `/fuel/sitevariables/delete/4` | High
21 | File | `/goform/setmac` | High
22 | File | `/goform/wizard_end` | High
23 | File | `/hprms/admin/doctors/manage_doctor.php` | High
24 | File | `/index/jobfairol/show/` | High
25 | File | `/librarian/bookdetails.php` | High
26 | File | `/manage-apartment.php` | High
27 | File | `/medicines/profile.php` | High
28 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
29 | File | `/pages/apply_vacancy.php` | High
30 | File | `/proc/<PID>/mem` | High
31 | ... | ... | ...

There are 268 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2018/09/threat-roundup-0914-0921.html
* https://blog.talosintelligence.com/2018/10/threat-roundup-1005-1012.html
* https://blog.talosintelligence.com/2019/03/threat-roundup-0308-0315.html
* https://blog.talosintelligence.com/2021/04/threat-roundup-0326-0402.html
* https://blogs.blackberry.com/en/2018/07/threat-spotlight-resurgent-smoke-loader-malware-dissected

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
