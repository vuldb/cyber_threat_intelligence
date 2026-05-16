# Molerats - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Molerats](https://vuldb.com/?actor.molerats). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.molerats](https://vuldb.com/?actor.molerats)

## Campaigns

The following _campaigns_ are known and can be associated with Molerats:

* DustySky
* Middle East
* SneakyPastes
* ...

There are 1 more campaign items available. Please use our online service to access the data.

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Molerats:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Molerats.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.94.218.221](https://vuldb.com/?ip.23.94.218.221) | 23-94-218-221-host.colocrossing.com | Middle East | High
2 | [23.229.3.70](https://vuldb.com/?ip.23.229.3.70) | ebonyha.club | DustySky | High
3 | [45.63.49.202](https://vuldb.com/?ip.45.63.49.202) | 45.63.49.202.vultr.com | Middle East | Medium
4 | [45.63.97.44](https://vuldb.com/?ip.45.63.97.44) | 45.63.97.44.vultr.com | SneakyPastes | Medium
5 | [72.11.148.147](https://vuldb.com/?ip.72.11.148.147) | mta8.wintogethere.com | - | High
6 | ... | ... | ... | ...

There are 21 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Molerats_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-25, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80, CWE-85 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-266, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Molerats. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/addbill.php` | Medium
4 | File | `/addProduct.php` | High
5 | File | `/admin/action/delete-vaccine.php` | High
6 | File | `/Admin/add-admin.php` | High
7 | File | `/admin/add-module.php` | High
8 | File | `/admin/add_expenses.php` | High
9 | File | `/admin/admin_manage/delete` | High
10 | File | `/admin/archives_add.php` | High
11 | File | `/admin/categories/save` | High
12 | File | `/admin/clientview.php` | High
13 | File | `/admin/contact-us.php` | High
14 | File | `/admin/delete_user.php` | High
15 | File | `/admin/edit-ambulance.php` | High
16 | File | `/admin/index.php` | High
17 | File | `/admin/login.php` | High
18 | File | `/admin/manage-tickets.php` | High
19 | File | `/admin/newsletterdel.php` | High
20 | File | `/admin/pages/` | High
21 | File | `/admin/positions.php` | High
22 | File | `/admin/receipt.php` | High
23 | File | `/admin/video/list` | High
24 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=0` | High
25 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=1` | High
26 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
27 | File | `/Administrator/PHP/AdminEditUser.php` | High
28 | File | `/Administrator/PHP/AdminReply.php` | High
29 | File | `/admins` | Low
30 | File | `/adv_mac_filter.php` | High
31 | File | `/ajax.php?action=login` | High
32 | File | `/ajax.php?action=update_account` | High
33 | File | `/ajax/getBasicInfo.php` | High
34 | File | `/api/admin/system/store/order/list` | High
35 | File | `/api/files/recipepictures/` | High
36 | File | `/app/register.php?action=reg` | High
37 | File | `/application/index/controller/Icon.php` | High
38 | File | `/apply/index.php` | High
39 | File | `/auth/user/all.api` | High
40 | File | `/authentication.cgi` | High
41 | File | `/boaform/device_reset.cgi` | High
42 | File | `/boaform/formSamba` | High
43 | File | `/boafrm/formDdns` | High
44 | File | `/boafrm/formTracerouteDiagnosticRun` | High
45 | File | `/boafrm/formVpnConfigSetup` | High
46 | File | `/cgformTemplateController.do?doAdd` | High
47 | File | `/cgi-bin/cstecgi.cgi` | High
48 | File | `/cgi-bin/wlogin.cgi` | High
49 | File | `/classes/Master.php?f=save_category` | High
50 | File | `/clientdetails/admin/regester.php` | High
51 | File | `/collection/all` | High
52 | File | `/config/php.ini` | High
53 | File | `/course.php` | Medium
54 | File | `/csms/?page=contact_us` | High
55 | File | `/detailtransac.php` | High
56 | File | `/dev/ptpX` | Medium
57 | File | `/dl/dl_sendmail.php` | High
58 | File | `/ecommerce/admin/products/controller.php` | High
59 | File | `/editeddonor.php` | High
60 | File | `/editprofile.php` | High
61 | File | `/etc/passwd` | Medium
62 | File | `/farm/product.php` | High
63 | File | `/file-manager/rename.php` | High
64 | File | `/foreigner-search.php` | High
65 | ... | ... | ...

There are 574 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://ddanchev.blogspot.com/2024/06/exposing-molerats-cyber-threat-actor.html
* https://securelist.com/gaza-cybergang-group1-operation-sneakypastes/90068/
* https://unit42.paloaltonetworks.com/molerats-delivers-spark-backdoor/
* https://www.clearskysec.com/wp-content/uploads/2016/06/Operation-DustySky2_-6.2016_TLP_White.pdf
* https://www.fireeye.com/blog/threat-research/2013/08/operation-molerats-middle-east-cyber-attacks-using-poison-ivy.html
* https://www.proofpoint.com/us/blog/threat-insight/new-ta402-molerats-malware-targets-governments-middle-east
* https://www.zscaler.com/blogs/security-research/new-espionage-attack-molerats-apt-targeting-users-middle-east

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
