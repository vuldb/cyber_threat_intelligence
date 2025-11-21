# UAC-215 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-215](https://vuldb.com/?actor.uac-215). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-215](https://vuldb.com/?actor.uac-215)

## Campaigns

The following _campaigns_ are known and can be associated with UAC-215:

* Rogue RDP

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-215:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-215.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.201.112](https://vuldb.com/?ip.2.58.201.112) | 112.201.58.2.us.kuroit.com | Rogue RDP | High
2 | [13.49.21.253](https://vuldb.com/?ip.13.49.21.253) | ec2-13-49-21-253.eu-north-1.compute.amazonaws.com | Rogue RDP | Medium
3 | [23.160.56.100](https://vuldb.com/?ip.23.160.56.100) | - | Rogue RDP | High
4 | [23.160.56.122](https://vuldb.com/?ip.23.160.56.122) | - | Rogue RDP | High
5 | [37.153.155.143](https://vuldb.com/?ip.37.153.155.143) | - | Rogue RDP | High
6 | [38.180.110.238](https://vuldb.com/?ip.38.180.110.238) | - | Rogue RDP | High
7 | [38.180.146.210](https://vuldb.com/?ip.38.180.146.210) | - | Rogue RDP | High
8 | [38.180.146.230](https://vuldb.com/?ip.38.180.146.230) | - | Rogue RDP | High
9 | [45.11.230.105](https://vuldb.com/?ip.45.11.230.105) | 105.230.11.45.us.kuroit.com | Rogue RDP | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-215_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-35, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-215. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/add-subadmin.php` | High
3 | File | `/add_new_invoice.php` | High
4 | File | `/add_user.php` | High
5 | File | `/admin/about-us.php` | High
6 | File | `/admin/action/delete-vaccine.php` | High
7 | File | `/admin/add-table.php` | High
8 | File | `/admin/admin_running.php` | High
9 | File | `/Admin/akun_edit.php` | High
10 | File | `/admin/apply.php` | High
11 | File | `/admin/category/view_category.php` | High
12 | File | `/admin/changeimage.php` | High
13 | File | `/admin/class.php` | High
14 | File | `/admin/config_time_sync.php` | High
15 | File | `/admin/content/editor` | High
16 | File | `/admin/create-package.php` | High
17 | File | `/admin/delete_s6.php` | High
18 | File | `/admin/doAdminAction.php?act=addCate` | High
19 | File | `/admin/edit-brand.php` | High
20 | File | `/admin/edit-post.php` | High
21 | File | `/admin/edit_product.php` | High
22 | File | `/admin/index2.html` | High
23 | File | `/Admin/login.php` | High
24 | File | `/admin/mechanics/manage_mechanic.php` | High
25 | File | `/admin/modules/room/index.php` | High
26 | File | `/admin/profile.php` | High
27 | File | `/Admin/Proses_Edit_Akun.php` | High
28 | File | `/admin/robot.php` | High
29 | File | `/admin/search-appointment.php` | High
30 | File | `/admin/search-invoices.php` | High
31 | File | `/admin/tags/save` | High
32 | File | `/admin/twitter.php` | High
33 | File | `/admin/yesterday-reg-users.php` | High
34 | File | `/api/baskets/{name}` | High
35 | File | `/api/settings` | High
36 | File | `/api/wizard/getCapability` | High
37 | File | `/app/api/v1/openvpn.py` | High
38 | File | `/app/controller/Api.php` | High
39 | File | `/app/index/controller/Common.php` | High
40 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
41 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
42 | File | `/applications/nexus/modules/front/store/store.php` | High
43 | File | `/auth.asp` | Medium
44 | File | `/backend/doc/his_doc_update-account.php` | High
45 | File | `/bitrix/admin/ldap_server_edit.php` | High
46 | File | `/biurl_grou` | Medium
47 | File | `/cgi-bin/apkg_mgr.cgi` | High
48 | File | `/cgi-bin/cstecgi.cgi` | High
49 | File | `/cgi-bin/nas_sharing.cgi` | High
50 | File | `/cgi-bin/photocenter_mgr.cgi` | High
51 | File | `/cgi-bin/supervisor/CloudSetup.cgi` | High
52 | File | `/classes/Master.php` | High
53 | File | `/classes/Master.php?f=delete_record` | High
54 | File | `/classes/Master.php?f=save_category` | High
55 | File | `/classes/SystemSettings.php?f=update_settings` | High
56 | File | `/classes/Users.php?f=save` | High
57 | File | `/cms/users/complaint-details.php` | High
58 | File | `/customnode/install` | High
59 | File | `/dcim/rack-roles/` | High
60 | File | `/deal/{note_id}/note` | High
61 | File | `/del_promote.php` | High
62 | File | `/detailed.php` | High
63 | ... | ... | ...

There are 547 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/6281076

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
