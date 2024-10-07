# APT34 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT34](https://vuldb.com/?actor.apt34). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt34](https://vuldb.com/?actor.apt34)

## Campaigns

The following _campaigns_ are known and can be associated with APT34:

* SideTwist
* Veaty and Spearal

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT34:

* [NL](https://vuldb.com/?country.nl)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT34.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [11.0.188.38](https://vuldb.com/?ip.11.0.188.38) | - | SideTwist | High
2 | [23.19.226.69](https://vuldb.com/?ip.23.19.226.69) | - | - | High
3 | [23.106.215.76](https://vuldb.com/?ip.23.106.215.76) | - | - | High
4 | [23.227.201.6](https://vuldb.com/?ip.23.227.201.6) | 23-227-201-6.static.hvvc.us | - | High
5 | [37.1.213.152](https://vuldb.com/?ip.37.1.213.152) | - | Veaty and Spearal | High
6 | [38.132.124.153](https://vuldb.com/?ip.38.132.124.153) | - | - | High
7 | [45.11.19.47](https://vuldb.com/?ip.45.11.19.47) | - | - | High
8 | [46.4.69.52](https://vuldb.com/?ip.46.4.69.52) | static.52.69.4.46.clients.your-server.de | - | High
9 | [46.105.221.247](https://vuldb.com/?ip.46.105.221.247) | - | - | High
10 | [46.105.251.42](https://vuldb.com/?ip.46.105.251.42) | ip42.ip-46-105-251.eu | - | High
11 | [46.165.246.196](https://vuldb.com/?ip.46.165.246.196) | - | - | High
12 | [70.36.107.34](https://vuldb.com/?ip.70.36.107.34) | - | - | High
13 | [74.91.19.108](https://vuldb.com/?ip.74.91.19.108) | - | - | High
14 | [74.91.19.122](https://vuldb.com/?ip.74.91.19.122) | - | - | High
15 | [78.47.218.106](https://vuldb.com/?ip.78.47.218.106) | static.106.218.47.78.clients.your-server.de | - | High
16 | [80.82.79.221](https://vuldb.com/?ip.80.82.79.221) | - | - | High
17 | [80.82.79.240](https://vuldb.com/?ip.80.82.79.240) | - | - | High
18 | ... | ... | ... | ...

There are 69 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT34_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT34. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=recruit/resume/edit&op=status` | High
2 | File | `/admin/` | Low
3 | File | `/admin/about-us.php` | High
4 | File | `/admin/addemployee.php` | High
5 | File | `/admin/add_trainers.php` | High
6 | File | `/admin/api/theme-edit/` | High
7 | File | `/admin/app/login_crud.php` | High
8 | File | `/admin/app/profile_crud.php` | High
9 | File | `/admin/countrymanagement.php` | High
10 | File | `/admin/del_category.php` | High
11 | File | `/admin/del_service.php` | High
12 | File | `/admin/edit-accepted-appointment.php` | High
13 | File | `/admin/edit-services.php` | High
14 | File | `/admin/edit_category.php` | High
15 | File | `/admin/edit_supplier.php` | High
16 | File | `/admin/emp-profile-avatar.php` | High
17 | File | `/admin/forgot-password.php` | High
18 | File | `/admin/generalsettings.php` | High
19 | File | `/admin/index.php` | High
20 | File | `/admin/list_ipAddressPolicy.php` | High
21 | File | `/admin/login.php` | High
22 | File | `/Admin/login.php` | High
23 | File | `/admin/maintenance/view_designation.php` | High
24 | File | `/admin/makehtml_freelist_action.php` | High
25 | File | `/admin/manage-ambulance.php` | High
26 | File | `/admin/newsletter1.php` | High
27 | File | `/admin/payment.php` | High
28 | File | `/admin/reg.php` | High
29 | File | `/admin/search-appointment.php` | High
30 | File | `/admin/students/update_status.php` | High
31 | File | `/admin/subnets/ripe-query.php` | High
32 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
33 | File | `/ajax-api.php` | High
34 | File | `/api/sys/login` | High
35 | File | `/api/sys/set_passwd` | High
36 | File | `/app/ajax/search_sales_report.php` | High
37 | File | `/app/controller/Setup.php` | High
38 | File | `/apply.cgi` | Medium
39 | File | `/App_Resource/UEditor/server/upload.aspx` | High
40 | File | `/bin/boa` | Medium
41 | File | `/boafrm/formMapDelDevice` | High
42 | File | `/booking/show_bookings/` | High
43 | File | `/cancel.php` | Medium
44 | File | `/cgi-bin/adm.cgi` | High
45 | File | `/cgi-bin/cstecgi.cgi` | High
46 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
47 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
48 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
49 | File | `/cgi-bin/myMusic.cgi` | High
50 | File | `/cgi-bin/nas_sharing.cgi` | High
51 | File | `/chaincity/user/ticket/create` | High
52 | File | `/check_availability.php` | High
53 | File | `/classes/Master.php` | High
54 | File | `/collection/all` | High
55 | File | `/common/info.cgi` | High
56 | File | `/core/conditions/AbstractWrapper.java` | High
57 | File | `/core/config-revisions` | High
58 | File | `/dcim/power-feeds/add` | High
59 | File | `/debug/pprof` | Medium
60 | File | `/deletefile.php` | High
61 | ... | ... | ...

There are 531 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/204/apt34-apt-iocs/
* https://github.com/blackorbird/APT_REPORT/tree/master/APT34
* https://nsfocusglobal.com/apt34-unleashes-new-wave-of-phishing-attack-with-variant-of-sidetwist-trojan/
* https://research.checkpoint.com/2024/iranian-malware-attacks-iraqi-government/
* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/crambus-middle-east-government
* https://unit42.paloaltonetworks.com/unit42-oilrig-group-steps-attacks-new-delivery-documents-new-injector-trojan/
* https://unit42.paloaltonetworks.com/unit42-oilrig-uses-ismdoor-variant-possibly-linked-greenbug-threat-group/
* https://unit42.paloaltonetworks.com/unit42-oilrig-uses-updated-bondupdater-target-middle-eastern-government/
* https://unit42.paloaltonetworks.com/unit42-oopsie-oilrig-uses-threedollars-deliver-new-trojan/
* https://www.clearskysec.com/oilrig/
* https://www.cyber45.com
* https://www.fireeye.com/blog/threat-research/2017/12/targeted-attack-in-middle-east-by-apt34.html
* https://www.fireeye.com/blog/threat-research/2019/07/hard-pass-declining-apt34-invite-to-join-their-professional-network.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
