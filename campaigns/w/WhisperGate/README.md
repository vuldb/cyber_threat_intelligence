# WhisperGate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _WhisperGate_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with WhisperGate:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 21 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with WhisperGate or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [GRU Unit 29155](https://vuldb.com/?actor.gru_unit_29155) | High
2 | [WhisperGate](https://vuldb.com/?actor.whispergate) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of WhisperGate.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.226.139.66](https://vuldb.com/?ip.5.226.139.66) | 66.139.226.5.baremetal.zare.com | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
2 | [45.141.87.11](https://vuldb.com/?ip.45.141.87.11) | - | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
3 | [46.101.242.222](https://vuldb.com/?ip.46.101.242.222) | kukij.com | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
4 | [62.173.140.223](https://vuldb.com/?ip.62.173.140.223) | vserver.tbits.ru | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
5 | [79.124.8.66](https://vuldb.com/?ip.79.124.8.66) | - | [WhisperGate](https://vuldb.com/?actor.whispergate) | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within WhisperGate. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during WhisperGate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//index.php` | Medium
2 | File | `/action.php` | Medium
3 | File | `/add-students.php` | High
4 | File | `/add-subadmin.php` | High
5 | File | `/addstock.php` | High
6 | File | `/add_new_invoice.php` | High
7 | File | `/add_new_supplier.php` | High
8 | File | `/add_user.php` | High
9 | File | `/admin/?page=reports` | High
10 | File | `/admin/?page=system_info/contact_info` | High
11 | File | `/admin/adddoctorclinic.php` | High
12 | File | `/Admin/akun_edit.php` | High
13 | File | `/admin/app/service_crud.php` | High
14 | File | `/admin/apply.php` | High
15 | File | `/admin/betweendates-detailsreports.php` | High
16 | File | `/admin/book-details.php` | High
17 | File | `/admin/content/editor` | High
18 | File | `/admin/create-package.php` | High
19 | File | `/admin/create_product.php` | High
20 | File | `/admin/doAdminAction.php?act=addCate` | High
21 | File | `/admin/edit-admin.php` | High
22 | File | `/admin/edit-brand.php` | High
23 | File | `/admin/edit-post.php` | High
24 | File | `/admin/list_crl_conf` | High
25 | File | `/Admin/login.php` | High
26 | File | `/admin/manage_user.php` | High
27 | File | `/admin/massage.php` | High
28 | File | `/admin/network/ajax_getChannelList` | High
29 | File | `/admin/pages/list` | High
30 | File | `/admin/password-recovery.php` | High
31 | File | `/admin/profile.php` | High
32 | File | `/Admin/Proses_Edit_Akun.php` | High
33 | File | `/admin/robot.php` | High
34 | File | `/admin/search-invoices.php` | High
35 | File | `/admin/search.php` | High
36 | File | `/admin/system.html` | High
37 | File | `/admin/twitter.php` | High
38 | File | `/admin/voters_row.php` | High
39 | File | `/animalsupdate.php` | High
40 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
41 | File | `/api/wizard/networkSetup` | High
42 | File | `/app/admin/controller/api/Plugs.php` | High
43 | File | `/app/admin/controller/Upload.php` | High
44 | File | `/app/ajax/search_sales_report.php` | High
45 | File | `/app/controller/Api.php` | High
46 | File | `/app/controller/Setup.php` | High
47 | File | `/app/middleware/TokenVerify.php` | High
48 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
49 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
50 | File | `/applications/nexus/modules/front/store/store.php` | High
51 | File | `/apply/index.php` | High
52 | File | `/b2b-supermarket/catalog/all-products` | High
53 | File | `/backend/doc/his_doc_update-account.php` | High
54 | File | `/boafrm/formMultiAP` | High
55 | File | `/cgi-bin/apkg_mgr.cgi` | High
56 | File | `/cgi-bin/cstecgi.cgi` | High
57 | File | `/cgi-bin/myMusic.cgi` | High
58 | File | `/cgi-bin/nas_sharing.cgi` | High
59 | File | `/cgi-bin/photocenter_mgr.cgi` | High
60 | File | `/cgi-bin/system_mgr.cgi` | High
61 | File | `/classes/Master.php` | High
62 | File | `/classes/Master.php?f=delete_record` | High
63 | File | `/classes/Master.php?f=save_category` | High
64 | File | `/classes/Master.php?f=save_medicine` | High
65 | File | `/classes/SystemSettings.php?f=update_settings` | High
66 | File | `/classes/Users.php?f=save` | High
67 | File | `/com/esafenet/servlet/ajax/MultiServerAjax.java` | High
68 | ... | ... | ...

There are 601 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.cyble.com/2022/02/01/whispergate-malware-deep-dive-analysis/
* https://blogs.blackberry.com/en/2022/01/threat-thursday-whispergate-wiper
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-249a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
