# Void Balaur - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Void Balaur](https://vuldb.com/?actor.void_balaur). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.void_balaur](https://vuldb.com/?actor.void_balaur)

## Campaigns

The following _campaigns_ are known and can be associated with Void Balaur:

* Phishing

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Void Balaur:

* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)
* [US](https://vuldb.com/?country.us)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Void Balaur.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.188.206.201](https://vuldb.com/?ip.5.188.206.201) | - | Phishing | High
2 | [23.88.228.248](https://vuldb.com/?ip.23.88.228.248) | - | - | High
3 | [46.45.137.74](https://vuldb.com/?ip.46.45.137.74) | . | - | High
4 | [51.15.94.245](https://vuldb.com/?ip.51.15.94.245) | 245-94-15-51.instances.scw.cloud | - | High
5 | [54.241.4.132](https://vuldb.com/?ip.54.241.4.132) | ec2-54-241-4-132.us-west-1.compute.amazonaws.com | Phishing | Medium
6 | [75.2.110.227](https://vuldb.com/?ip.75.2.110.227) | a7e73d307bf50678b.awsglobalaccelerator.com | Phishing | High
7 | [95.173.132.1](https://vuldb.com/?ip.95.173.132.1) | gw.council.gov.ru | Phishing | High
8 | [99.83.178.7](https://vuldb.com/?ip.99.83.178.7) | a7e73d307bf50678b.awsglobalaccelerator.com | Phishing | High
9 | [139.60.163.29](https://vuldb.com/?ip.139.60.163.29) | - | - | High
10 | [139.60.163.34](https://vuldb.com/?ip.139.60.163.34) | sprywing.com | - | High
11 | [139.60.163.35](https://vuldb.com/?ip.139.60.163.35) | - | - | High
12 | [139.60.163.38](https://vuldb.com/?ip.139.60.163.38) | - | - | High
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Void Balaur_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Void Balaur. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/admin/submit-articles` | High
3 | File | `/ad_js.php` | Medium
4 | File | `/app/options.py` | High
5 | File | `/attachments` | Medium
6 | File | `/bsms/?page=manage_account` | High
7 | File | `/bsms_ci/index.php/book` | High
8 | File | `/cgi-bin/login.cgi` | High
9 | File | `/cgi-bin/luci/api/wireless` | High
10 | File | `/ci_hms/massage_room/edit/1` | High
11 | File | `/context/%2e/WEB-INF/web.xml` | High
12 | File | `/dashboard/reports/logs/view` | High
13 | File | `/debian/patches/load_ppp_generic_if_needed` | High
14 | File | `/debug/pprof` | Medium
15 | File | `/etc/hosts` | Medium
16 | File | `/forum/away.php` | High
17 | File | `/goform/formSetEmail` | High
18 | File | `/goform/setmac` | High
19 | File | `/goform/wizard_end` | High
20 | File | `/hprms/admin/doctors/manage_doctor.php` | High
21 | File | `/index/jobfairol/show/` | High
22 | File | `/librarian/bookdetails.php` | High
23 | File | `/manage-apartment.php` | High
24 | File | `/medicines/profile.php` | High
25 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
26 | File | `/pages/apply_vacancy.php` | High
27 | File | `/proc/<PID>/mem` | High
28 | File | `/proxy` | Low
29 | File | `/spip.php` | Medium
30 | File | `/tmp` | Low
31 | File | `/uncpath/` | Medium
32 | File | `/upload` | Low
33 | ... | ... | ...

There are 280 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://ddanchev.blogspot.com/2022/11/profiling-typosquatted-googles-gmail.html
* https://documents.trendmicro.com/assets/white_papers/wp-void-balaur-tracking-a-cybermercenarys-activities.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
