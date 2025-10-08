# JumpCloud - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _JumpCloud_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with JumpCloud:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 14 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with JumpCloud or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DPRK](https://vuldb.com/?actor.dprk) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of JumpCloud.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.29.115.171](https://vuldb.com/?ip.23.29.115.171) | 23-29-115-171.static.hvvc.us | [DPRK](https://vuldb.com/?actor.dprk) | High
2 | [23.95.182.5](https://vuldb.com/?ip.23.95.182.5) | 23-95-182-5-host.colocrossing.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.82.250.186](https://vuldb.com/?ip.45.82.250.186) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [51.254.24.19](https://vuldb.com/?ip.51.254.24.19) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abcd/opac/php/otros_sitios.php` | High
2 | File | `/add-subadmin.php` | High
3 | File | `/addcategory.php` | High
4 | File | `/addcompany.php` | High
5 | File | `/addcustcom.php` | High
6 | File | `/addcustind.php` | High
7 | File | `/addstock.php` | High
8 | File | `/add_new_invoice.php` | High
9 | File | `/add_user.php` | High
10 | File | `/admin/?page=musics/manage_music` | High
11 | File | `/admin/?page=reports` | High
12 | File | `/admin/aboutus.php` | High
13 | File | `/admin/add-table.php` | High
14 | File | `/Admin/adminlogin.php` | High
15 | File | `/admin/admin_running.php` | High
16 | File | `/admin/ajax.php?action=login` | High
17 | File | `/Admin/akun_edit.php` | High
18 | File | `/admin/apply.php` | High
19 | File | `/admin/blood/update/o-.php` | High
20 | File | `/admin/categories/manage_category.php` | High
21 | File | `/admin/changeimage.php` | High
22 | File | `/admin/config_time_sync.php` | High
23 | File | `/admin/content/editor` | High
24 | File | `/admin/create-package.php` | High
25 | File | `/admin/deleteuser.php` | High
26 | File | `/admin/delete_s6.php` | High
27 | File | `/admin/doAdminAction.php?act=addCate` | High
28 | File | `/admin/edit-brand.php` | High
29 | File | `/admin/edit-card-detail.php` | High
30 | File | `/admin/emp-profile-avatar.php` | High
31 | File | `/admin/forgot-password.php` | High
32 | File | `/admin/index.php` | High
33 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
34 | File | `/admin/index.php?r=friendly-link%2Fupdate` | High
35 | File | `/admin/index.php?r=user%2Fcreate` | High
36 | File | `/admin/login.php` | High
37 | File | `/Admin/login.php` | High
38 | File | `/admin/modules/room/index.php` | High
39 | File | `/admin/password-recovery.php` | High
40 | File | `/admin/process_category_edit.php` | High
41 | File | `/admin/profile.php` | High
42 | File | `/Admin/Proses_Edit_Akun.php` | High
43 | File | `/Admin/registration.php` | High
44 | File | `/Admin/resultdetails.php` | High
45 | File | `/admin/robot.php` | High
46 | File | `/admin/search-invoices.php` | High
47 | File | `/admin/search-medicalcard.php` | High
48 | File | `/admin/system.html` | High
49 | File | `/admin/tags/save` | High
50 | File | `/admin/twitter.php` | High
51 | File | `/admin/view-card-detail.php` | High
52 | File | `/admin/view-enquiry.php` | High
53 | File | `/admin/yesterday-reg-users.php` | High
54 | File | `/admin_class.php` | High
55 | File | `/ajax.php?action=delete_deductions` | High
56 | File | `/ajax.php?action=login` | High
57 | File | `/ajax.php?action=save_deductions` | High
58 | File | `/ajax/checkin.php` | High
59 | File | `/ajax/get_patient_history.php` | High
60 | File | `/animalsupdate.php` | High
61 | File | `/api/settings` | High
62 | File | `/api/wizard/getCapability` | High
63 | File | `/api/wizard/getDualbandSync` | High
64 | File | `/api/workspace/:workspace-slug/update` | High
65 | File | `/app/api/v1/openvpn.py` | High
66 | File | `/app/controller/Api.php` | High
67 | File | `/apply.cgi` | Medium
68 | File | `/authMonitCallcenter` | High
69 | File | `/backend/doc/his_doc_update-account.php` | High
70 | File | `/biurl_grou` | Medium
71 | File | `/boafrm/formReflashClientTbl` | High
72 | File | `/cancelar-enturmacao-em-lote/` | High
73 | File | `/cgi-bin/apkg_mgr.cgi` | High
74 | File | `/cgi-bin/cstecgi.cgi` | High
75 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
76 | File | `/cgi-bin/hd_config.cgi` | High
77 | File | `/cgi-bin/lighttpd.cgi` | High
78 | File | `/cgi-bin/myMusic.cgi` | High
79 | File | `/cgi-bin/nas_sharing.cgi` | High
80 | File | `/cgi-bin/photocenter_mgr.cgi` | High
81 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
82 | File | `/classes/Master.php?f=delete_category` | High
83 | File | `/classes/Master.php?f=delete_record` | High
84 | File | `/classes/SystemSettings.php?f=update_settings` | High
85 | File | `/com/esafenet/servlet/ajax/PublicDocInfoAjax.java` | High
86 | File | `/common/show_image.php` | High
87 | File | `/control/forgot_pass.php` | High
88 | File | `/control/login.php` | High
89 | File | `/controllers/logincontrol.php` | High
90 | File | `/customnode/install` | High
91 | File | `/deal/{note_id}/note` | High
92 | File | `/deletebird.php` | High
93 | File | `/del_promote.php` | High
94 | File | `/detailed.php` | High
95 | File | `/diario-de-observacoes/` | High
96 | ... | ... | ...

There are 849 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://jumpcloud.com/support/july-2023-iocs

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
