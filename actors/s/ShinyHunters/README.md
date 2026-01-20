# ShinyHunters - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ShinyHunters](https://vuldb.com/?actor.shinyhunters). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.shinyhunters](https://vuldb.com/?actor.shinyhunters)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ShinyHunters:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ShinyHunters.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.47.87.202](https://vuldb.com/?ip.5.47.87.202) | - | - | High
2 | [37.19.210.21](https://vuldb.com/?ip.37.19.210.21) | unn-37-19-210-21.datapacket.com | - | High
3 | [37.19.210.34](https://vuldb.com/?ip.37.19.210.34) | unn-37-19-210-34.datapacket.com | - | High
4 | [45.86.221.146](https://vuldb.com/?ip.45.86.221.146) | - | - | High
5 | [45.134.140.144](https://vuldb.com/?ip.45.134.140.144) | unn-45-134-140-144.datapacket.com | - | High
6 | [45.134.142.200](https://vuldb.com/?ip.45.134.142.200) | unn-45-134-142-200.datapacket.com | - | High
7 | [45.155.91.99](https://vuldb.com/?ip.45.155.91.99) | - | - | High
8 | [66.63.167.147](https://vuldb.com/?ip.66.63.167.147) | 66.63.167.147.static.quadranet.com | - | High
9 | [66.115.189.247](https://vuldb.com/?ip.66.115.189.247) | - | - | High
10 | [79.127.217.44](https://vuldb.com/?ip.79.127.217.44) | unn-79-127-217-44.datapacket.com | - | High
11 | [87.249.134.11](https://vuldb.com/?ip.87.249.134.11) | unn-87-249-134-11.datapacket.com | - | High
12 | [93.115.0.49](https://vuldb.com/?ip.93.115.0.49) | - | - | High
13 | [96.44.191.140](https://vuldb.com/?ip.96.44.191.140) | 96.44.191.140.static.quadranet.com | - | High
14 | ... | ... | ... | ...

There are 53 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ShinyHunters_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-267, CWE-268, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ShinyHunters. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/addProduct.php` | High
3 | File | `/admin/?page=zone` | High
4 | File | `/admin/aboutus.php` | High
5 | File | `/admin/add-module.php` | High
6 | File | `/admin/add_teacher.php` | High
7 | File | `/admin/ajax.php?action=delete_recruitment_status` | High
8 | File | `/admin/archives_add.php` | High
9 | File | `/admin/bwdates-report-details.php` | High
10 | File | `/admin/candidates.php` | High
11 | File | `/admin/categories/save` | High
12 | File | `/admin/checklogin.php` | High
13 | File | `/admin/contact-us.php` | High
14 | File | `/Admin/Controller/CustomController.class.php` | High
15 | File | `/admin/delete_user.php` | High
16 | File | `/admin/index2.html` | High
17 | File | `/admin/login.php` | High
18 | File | `/admin/manage-admins.php` | High
19 | File | `/admin/manage-pages.php` | High
20 | File | `/admin/newsletterdel.php` | High
21 | File | `/admin/positions.php` | High
22 | File | `/admin/print_inv.php` | High
23 | File | `/admin/receipt.php` | High
24 | File | `/admin/return_add.php` | High
25 | File | `/admin/search-vehicle.php` | High
26 | File | `/admin/update_s3.php` | High
27 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=0` | High
28 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=1` | High
29 | File | `/ajax.php?action=login` | High
30 | File | `/ajax.php?action=save_loan_type` | High
31 | File | `/api/blade-user/submit` | High
32 | File | `/api/files/recipepictures/` | High
33 | File | `/api/mjkj-chat/cgform-api/addData/` | High
34 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
35 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
36 | File | `/api/upload.php` | High
37 | File | `/app/admin/controller/api/Plugs.php` | High
38 | File | `/app/register.php?action=reg` | High
39 | File | `/ari/asterisk/variable` | High
40 | File | `/authentication.cgi` | High
41 | File | `/basico/webservice/imprimir-danfe/id/` | High
42 | File | `/bin/httpd` | Medium
43 | File | `/biurl_grou` | Medium
44 | File | `/boafrm/formDdns` | High
45 | File | `/boafrm/formFirewallAdv` | High
46 | File | `/boafrm/formNtp` | High
47 | File | `/boafrm/formPinManageSetup` | High
48 | File | `/boafrm/formTracerouteDiagnosticRun` | High
49 | File | `/boafrm/formVpnConfigSetup` | High
50 | File | `/boafrm/formWlanMultipleAP` | High
51 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
52 | File | `/cgi-bin/cstecgi.cgi` | High
53 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
54 | File | `/cgi-bin/nightled.cgi` | High
55 | File | `/cgi-bin/s3.cgi` | High
56 | File | `/change_password_process` | High
57 | File | `/chatgpt-boot/src/main/java/org/springblade/modules/mjkj/controller/OpenController.java` | High
58 | File | `/checklogin.php` | High
59 | File | `/class/edit/edit` | High
60 | File | `/clientdetails/admin/index.php` | High
61 | File | `/CMSInstall/install.aspx` | High
62 | File | `/command_port.ini` | High
63 | File | `/cussignup.php` | High
64 | File | `/data/pbootcms.db` | High
65 | File | `/dell.php` | Medium
66 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
67 | ... | ... | ...

There are 585 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/threat-advisory-snowflake-data-breach-impacts-its-clients/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
