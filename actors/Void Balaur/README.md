# Void Balaur - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Void Balaur](https://vuldb.com/?actor.void_balaur). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.void_balaur](https://vuldb.com/?actor.void_balaur)

## Campaigns

The following _campaigns_ are known and can be associated with Void Balaur:

* Phishing

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Void Balaur:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 10 more country items available. Please use our online service to access the data.

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

There are 47 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Void Balaur_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Void Balaur. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin/?page=user/manage` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/controller/JobLogController.java` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/alphaware/summary.php` | High
8 | File | `/api/` | Low
9 | File | `/api/admin/store/product/list` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/api/stl/actions/search` | High
12 | File | `/api/sys/login` | High
13 | File | `/api/sys/set_passwd` | High
14 | File | `/api/trackedEntityInstances` | High
15 | File | `/api/v2/cli/commands` | High
16 | File | `/aux` | Low
17 | File | `/bin/ate` | Medium
18 | File | `/boat/login.php` | High
19 | File | `/booking/show_bookings/` | High
20 | File | `/bsms_ci/index.php/book` | High
21 | File | `/cgi-bin` | Medium
22 | File | `/cgi-bin/wlogin.cgi` | High
23 | File | `/changePassword` | High
24 | File | `/Content/Template/root/reverse-shell.aspx` | High
25 | File | `/dashboard/add-blog.php` | High
26 | File | `/data/remove` | Medium
27 | File | `/debug/pprof` | Medium
28 | File | `/ecshop/admin/template.php` | High
29 | File | `/env` | Low
30 | File | `/etc/passwd` | Medium
31 | File | `/forum/away.php` | High
32 | File | `/goform/formSetEmail` | High
33 | File | `/group1/uploa` | High
34 | File | `/index.php` | Medium
35 | File | `/medicines/profile.php` | High
36 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
37 | File | `/php-sms/admin/?page=user/manage_user` | High
38 | File | `/reservation/add_message.php` | High
39 | File | `/resources//../` | High
40 | File | `/spip.php` | Medium
41 | File | `/testConnection` | High
42 | File | `/tmp` | Low
43 | File | `/tmp/ppd.trace` | High
44 | File | `/user/inc/workidajax.php` | High
45 | ... | ... | ...

There are 394 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://ddanchev.blogspot.com/2022/11/profiling-typosquatted-googles-gmail.html
* https://documents.trendmicro.com/assets/white_papers/wp-void-balaur-tracking-a-cybermercenarys-activities.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
