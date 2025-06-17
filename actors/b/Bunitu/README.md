# Bunitu - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Bunitu](https://vuldb.com/?actor.bunitu). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.bunitu](https://vuldb.com/?actor.bunitu)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Bunitu:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Bunitu.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.61.40.13](https://vuldb.com/?ip.5.61.40.13) | - | - | High
2 | [5.61.42.235](https://vuldb.com/?ip.5.61.42.235) | - | - | High
3 | [5.104.230.200](https://vuldb.com/?ip.5.104.230.200) | hosted-by.snel.com | - | High
4 | [5.199.174.223](https://vuldb.com/?ip.5.199.174.223) | - | - | High
5 | [18.133.158.66](https://vuldb.com/?ip.18.133.158.66) | ec2-18-133-158-66.eu-west-2.compute.amazonaws.com | - | Medium
6 | [23.21.42.25](https://vuldb.com/?ip.23.21.42.25) | ec2-23-21-42-25.compute-1.amazonaws.com | - | Medium
7 | ... | ... | ... | ...

There are 23 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Bunitu_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Bunitu. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `..\WWWRoot\CustomPages\aspshell.asp` | High
2 | File | `/09/business/upgrade/upcfgAction.php?download=true` | High
3 | File | `/32` | Low
4 | File | `/admin/categories/manage_category.php` | High
5 | File | `/admin/categories/view_category.php` | High
6 | File | `/admin/maintenance/view_designation.php` | High
7 | File | `/admin/member_save.php` | High
8 | File | `/admin/products/view_product.php` | High
9 | File | `/admin/usermanagement.php` | High
10 | File | `/api/controllers/merchant/shop/PosterController.php` | High
11 | File | `/assets/something/services/AppModule.class` | High
12 | File | `/bcms/admin/?page=reports/daily_court_rental_report` | High
13 | File | `/cgi-bin/kerbynet` | High
14 | File | `/cgi-bin/luci;stok=/locale` | High
15 | File | `/cgi-bin/pass` | High
16 | File | `/classes/Master.php?f=save_item` | High
17 | File | `/classes/SystemSettings.php?f=update_settings` | High
18 | File | `/collection/all` | High
19 | File | `/ctpms/admin/?page=applications/view_application` | High
20 | File | `/dev/tcx0` | Medium
21 | File | `/dev/urandom` | Medium
22 | File | `/etc/environment` | High
23 | File | `/etc/keystone/user-project-map.json` | High
24 | File | `/etc/passwd` | Medium
25 | File | `/home.jsp` | Medium
26 | File | `/inc/campaign/view-campaign-list.php` | High
27 | File | `/include/menu_v.inc.php` | High
28 | File | `/index.php/weblinks-categories` | High
29 | File | `/librarian/bookdetails.php` | High
30 | File | `/servlet/webacc` | High
31 | File | `/student-grading-system/rms.php?page=school_year` | High
32 | File | `/system?action=ServiceAdmin` | High
33 | File | `/usr/` | Low
34 | File | `/usr/bin/pkexec` | High
35 | File | `/wp-admin/admin.php?page=cpabc_appointments.php` | High
36 | File | `ActiveMQConnection.java` | High
37 | File | `addq.php` | Medium
38 | File | `admin-ajax.php` | High
39 | File | `admin.php` | Medium
40 | File | `admin/ad_list.php` | High
41 | File | `admin/panels/uploader/admin.uploader.php` | High
42 | File | `admin/status/realtime/bandwidth_status` | High
43 | ... | ... | ...

There are 375 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/11/threat-roundup-1115-1122.html
* https://blog.talosintelligence.com/2021/01/threat-roundup-0108-0115.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
