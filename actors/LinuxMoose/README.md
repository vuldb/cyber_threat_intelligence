# LinuxMoose - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LinuxMoose](https://vuldb.com/?actor.linuxmoose). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.linuxmoose](https://vuldb.com/?actor.linuxmoose)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LinuxMoose:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LinuxMoose.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.124.41.11](https://vuldb.com/?ip.27.124.41.11) | - | - | High
2 | [27.124.41.31](https://vuldb.com/?ip.27.124.41.31) | - | - | High
3 | [27.124.41.33](https://vuldb.com/?ip.27.124.41.33) | - | - | High
4 | [27.124.41.52](https://vuldb.com/?ip.27.124.41.52) | - | - | High
5 | [42.119.173.138](https://vuldb.com/?ip.42.119.173.138) | - | - | High
6 | [62.210.6.34](https://vuldb.com/?ip.62.210.6.34) | 62-210-6-34.rev.poneytelecom.eu | - | High
7 | [77.247.177.31](https://vuldb.com/?ip.77.247.177.31) | - | - | High
8 | [77.247.177.36](https://vuldb.com/?ip.77.247.177.36) | - | - | High
9 | [77.247.177.87](https://vuldb.com/?ip.77.247.177.87) | - | - | High
10 | [77.247.178.177](https://vuldb.com/?ip.77.247.178.177) | - | - | High
11 | [79.176.26.142](https://vuldb.com/?ip.79.176.26.142) | bzq-79-176-26-142.red.bezeqint.net | - | High
12 | [82.146.63.15](https://vuldb.com/?ip.82.146.63.15) | ebay2.com | - | High
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LinuxMoose_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LinuxMoose. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin.php/accessory/filesdel.html` | High
3 | File | `/admin/?page=user/manage` | High
4 | File | `/admin/add-new.php` | High
5 | File | `/admin/controller/JobLogController.java` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/admin/submit-articles` | High
8 | File | `/alphaware/summary.php` | High
9 | File | `/api/` | Low
10 | File | `/api/admin/store/product/list` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/api/stl/actions/search` | High
13 | File | `/api/sys/login` | High
14 | File | `/api/sys/set_passwd` | High
15 | File | `/api/trackedEntityInstances` | High
16 | File | `/api/v2/cli/commands` | High
17 | File | `/apply.cgi` | Medium
18 | File | `/attachments` | Medium
19 | File | `/bin/ate` | Medium
20 | File | `/bin/boa` | Medium
21 | File | `/boat/login.php` | High
22 | File | `/booking/show_bookings/` | High
23 | File | `/bsms_ci/index.php/book` | High
24 | File | `/cgi-bin` | Medium
25 | File | `/cgi-bin/wlogin.cgi` | High
26 | File | `/changePassword` | High
27 | File | `/comments` | Medium
28 | File | `/Content/Template/root/reverse-shell.aspx` | High
29 | File | `/dashboard/add-blog.php` | High
30 | File | `/dcim/sites/add/` | High
31 | File | `/debug/pprof` | Medium
32 | File | `/ecshop/admin/template.php` | High
33 | File | `/env` | Low
34 | File | `/etc/hosts` | Medium
35 | File | `/etc/shadow` | Medium
36 | File | `/forum/away.php` | High
37 | File | `/group1/uploa` | High
38 | File | `/hardware` | Medium
39 | File | `/include/makecvs.php` | High
40 | File | `/librarian/bookdetails.php` | High
41 | File | `/medicines/profile.php` | High
42 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
43 | File | `/out.php` | Medium
44 | File | `/php-sms/admin/?page=user/manage_user` | High
45 | File | `/products/view_product.php` | High
46 | File | `/proxy` | Low
47 | ... | ... | ...

There are 404 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/moose
* https://ioc.hatenablog.com/entry/2015/05/28/000000
* https://www.threatminer.org/report.php?q=Dissecting-LinuxMoose.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
