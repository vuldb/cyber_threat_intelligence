# CowTunnel - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [CowTunnel](https://vuldb.com/?actor.cowtunnel). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cowtunnel](https://vuldb.com/?actor.cowtunnel)

## Campaigns

The following _campaigns_ are known and can be associated with CowTunnel:

* CVE-2025-55182

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with CowTunnel:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [ES](https://vuldb.com/?country.es)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of CowTunnel.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.226.71.197](https://vuldb.com/?ip.23.226.71.197) | we.love.servers.at.ioflood.net | CVE-2025-55182 | High
2 | [23.226.71.200](https://vuldb.com/?ip.23.226.71.200) | we.love.servers.at.ioflood.net | CVE-2025-55182 | High
3 | [23.226.71.209](https://vuldb.com/?ip.23.226.71.209) | we.love.servers.at.ioflood.net | CVE-2025-55182 | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _CowTunnel_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by CowTunnel. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/bwdates-reports-details.php` | High
2 | File | `/admin/category/controller.php` | High
3 | File | `/admin/create_product.php` | High
4 | File | `/admin/general.cgi` | High
5 | File | `/admin/reminders/manage_reminder.php` | High
6 | File | `/API/info` | Medium
7 | File | `/att_add.php` | Medium
8 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
9 | File | `/Bloodgroop_process.php` | High
10 | File | `/cancelbookingpatient.php` | High
11 | File | `/CCMAdmin/serverlist.asp` | High
12 | File | `/cgi-bin/cstecgi.cgi` | High
13 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
14 | File | `/cgi-bin/nas_sharing.cgi` | High
15 | File | `/cgi/get_param.cgi` | High
16 | File | `/csms/admin/inquiries/view_details.php` | High
17 | File | `/cstecgi.cgi` | Medium
18 | File | `/Digital-Infrastructure-9.6.7/y9-digitalbase-webapp/y9-module-filemanager/risenet-y9boot-webapp-filemanager/src/main/java/net/risesoft/y9public/controller/Y9FileController.java` | High
19 | File | `/ecommerce/support_ticket` | High
20 | File | `/files.md5` | Medium
21 | File | `/forum/away.php` | High
22 | File | `/goform/verifyFacebookLike` | High
23 | File | `/home/search` | Medium
24 | File | `/hrm/employeeview.php` | High
25 | File | `/include/chart_generator.php` | High
26 | File | `/librarian/bookdetails.php` | High
27 | File | `/messageboard/view.php` | High
28 | File | `/out.php` | Medium
29 | File | `/owa/auth/logon.aspx` | High
30 | File | `/SAP_Information_System/controllers/add_admin.php` | High
31 | File | `/spgpm/updateListing` | High
32 | File | `/spip.php` | Medium
33 | File | `/SVFE2/pages/feegroups/country_group.jsf` | High
34 | File | `/textpattern/index.php` | High
35 | File | `/upfile.cgi` | Medium
36 | File | `/v2/quantum/save-data-upload-big-file` | High
37 | File | `/WEAS_AlarmResult/GetAlarmResultProcessList` | High
38 | File | `/webui/modules/log/operate.mds` | High
39 | File | `/wordpress/wp-admin/admin.php` | High
40 | ... | ... | ...

There are 347 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.huntress.com/blog/peerblight-linux-backdoor-exploits-react2shell

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
