# Wocao - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Wocao_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wocao:

* [DE](https://vuldb.com/?country.de)
* [ES](https://vuldb.com/?country.es)
* [IT](https://vuldb.com/?country.it)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Wocao or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Wocao](https://vuldb.com/?actor.wocao) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wocao.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.211.108](https://vuldb.com/?ip.23.254.211.108) | hwsrv-871243.hostwindsdns.com | [Wocao](https://vuldb.com/?actor.wocao) | High
2 | [31.222.185.215](https://vuldb.com/?ip.31.222.185.215) | 31-222-185-215.static.cloud-ips.co.uk | [Wocao](https://vuldb.com/?actor.wocao) | High
3 | [45.77.229.10](https://vuldb.com/?ip.45.77.229.10) | 45.77.229.10.vultr.com | [Wocao](https://vuldb.com/?actor.wocao) | Medium
4 | ... | ... | ... | ...

There are 13 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/&quot` | Low
3 | File | `/admin/subnets/ripe-query.php` | High
4 | File | `/adminui/error_details.php` | High
5 | File | `/adminui/history_log.php` | High
6 | File | `/auth/register` | High
7 | File | `/binbloom-master/src/helpers.c` | High
8 | File | `/dev/kmem` | Medium
9 | File | `/dev/tty` | Medium
10 | File | `/etc/gsissh/sshd_config` | High
11 | File | `/etc/passwd` | Medium
12 | File | `/face-recognition-php/facepay-master/camera.php` | High
13 | File | `/goform/dir_setWanWifi` | High
14 | File | `/goform/WifiBasicSet` | High
15 | File | `/hss/?page=view_product` | High
16 | File | `/hss/admin/categories/view_category.php` | High
17 | File | `/lab.html` | Medium
18 | File | `/login/index.php` | High
19 | File | `/menu.html` | Medium
20 | File | `/modules/profile/index.php` | High
21 | File | `/out.php` | Medium
22 | File | `/output/outdbg.c` | High
23 | File | `/output/outieee.c` | High
24 | File | `/SAFESEH` | Medium
25 | File | `/Upload/admin/admin_notify.php` | High
26 | File | `/usr/sbin/httpd` | High
27 | File | `/var/log/nginx` | High
28 | File | `/wp-json/wc/v3/webhooks` | High
29 | File | `0_change-gallery.php` | High
30 | File | `4.edu.php` | Medium
31 | File | `5.2.9\syscrb.exe` | High
32 | File | `AbstractScheduleJob.java` | High
33 | File | `account-inbox.php` | High
34 | File | `acme_certificate_edit.php` | High
35 | File | `action/Core.class.php` | High
36 | File | `adclick.php` | Medium
37 | File | `add-blog.php` | Medium
38 | File | `addToWishlist.asp` | High
39 | ... | ... | ...

There are 335 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/fox-it/operation-wocao

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
