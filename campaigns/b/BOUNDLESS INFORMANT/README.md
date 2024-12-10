# BOUNDLESS INFORMANT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _BOUNDLESS INFORMANT_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BOUNDLESS INFORMANT:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 29 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with BOUNDLESS INFORMANT or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [NSA](https://vuldb.com/?actor.nsa) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BOUNDLESS INFORMANT.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [31.6.17.94](https://vuldb.com/?ip.31.6.17.94) | - | [NSA](https://vuldb.com/?actor.nsa) | High
2 | [37.72.168.84](https://vuldb.com/?ip.37.72.168.84) | 84.168.72.37.static.swiftway.net | [NSA](https://vuldb.com/?actor.nsa) | High
3 | [37.130.229.100](https://vuldb.com/?ip.37.130.229.100) | uk.server | [NSA](https://vuldb.com/?actor.nsa) | High
4 | [37.130.229.101](https://vuldb.com/?ip.37.130.229.101) | uk.server | [NSA](https://vuldb.com/?actor.nsa) | High
5 | [37.220.10.28](https://vuldb.com/?ip.37.220.10.28) | h37-220-10-28.host.redstation.co.uk | [NSA](https://vuldb.com/?actor.nsa) | High
6 | [50.115.118.140](https://vuldb.com/?ip.50.115.118.140) | sfaaa.net | [NSA](https://vuldb.com/?actor.nsa) | High
7 | ... | ... | ... | ...

There are 25 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within BOUNDLESS INFORMANT. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during BOUNDLESS INFORMANT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.procmailrc` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin-ajax.php?action=eps_redirect_save` | High
4 | File | `/admin.php` | Medium
5 | File | `/admin.php/accessory/filesdel.html` | High
6 | File | `/admin/` | Low
7 | File | `/Admin/add-student.php` | High
8 | File | `/admin/api/theme-edit/` | High
9 | File | `/admin/index3.php` | High
10 | File | `/admin/login.php` | High
11 | File | `/admin/manage-users.php` | High
12 | File | `/admin/photo.php` | High
13 | File | `/adms/admin/?page=vehicles/view_transaction` | High
14 | File | `/anony/mjpg.cgi` | High
15 | File | `/application/plugins/controller/Upload.php` | High
16 | File | `/apply.cgi` | Medium
17 | File | `/auth` | Low
18 | File | `/catcompany.php` | High
19 | File | `/cms/category/list` | High
20 | File | `/dashboard/view-chair-list.php` | High
21 | File | `/Default/Bd` | Medium
22 | File | `/ebics-server/ebics.aspx` | High
23 | File | `/egroupware/index.php` | High
24 | File | `/etc/hosts` | Medium
25 | File | `/etc/shadow.sample` | High
26 | File | `/filemanager/upload.php` | High
27 | File | `/forms/doLogin` | High
28 | File | `/forum/away.php` | High
29 | File | `/general/address/private/address/query/delete.php` | High
30 | File | `/GponForm/device_Form?script/` | High
31 | File | `/GponForm/fsetup_Form` | High
32 | File | `/GponForm/usb_restore_Form?script/` | High
33 | File | `/hrm/employeeview.php` | High
34 | File | `/html/device-id` | High
35 | File | `/importexport.php` | High
36 | File | `/includes/decorators/global-translations.jsp` | High
37 | File | `/index.php` | Medium
38 | File | `/index/ajax/lang` | High
39 | File | `/loginsave.php` | High
40 | File | `/param.file.tgz` | High
41 | File | `/product_list.php` | High
42 | File | `/public_html/users.php` | High
43 | File | `/secure/QueryComponent!Default.jspa` | High
44 | File | `/see_more_details.php` | High
45 | File | `/server-status` | High
46 | File | `/setSystemAdmin` | High
47 | File | `/uncpath/` | Medium
48 | File | `/user/s.php` | Medium
49 | File | `/usr/local/WowzaStreamingEngine/bin/` | High
50 | File | `/WEB-INF/web.xml` | High
51 | File | `/wireless/guestnetwork.asp` | High
52 | File | `?r=recruit/interview/export&interviews=x` | High
53 | File | `a2dp_aac_decoder.cc` | High
54 | File | `actbar3.ocx` | Medium
55 | File | `adclick.php` | Medium
56 | File | `add-locker-form.php` | High
57 | ... | ... | ...

There are 493 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://medium.com/@danchodanchev/how-the-nsa-utilized-iranian-cyber-proxies-to-participate-in-the-boundless-informant-program-e82045d44848

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
