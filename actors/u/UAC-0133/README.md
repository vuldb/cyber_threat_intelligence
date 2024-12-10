# UAC-0133 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [UAC-0133](https://vuldb.com/?actor.uac-0133). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.uac-0133](https://vuldb.com/?actor.uac-0133)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0133:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0133.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.74.11](https://vuldb.com/?ip.5.45.74.11) | free.ispiria.net | - | High
2 | [5.45.75.45](https://vuldb.com/?ip.5.45.75.45) | mail.virtual-businessman.com | - | High
3 | [88.80.145.239](https://vuldb.com/?ip.88.80.145.239) | - | - | High
4 | ... | ... | ... | ...

There are 13 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0133_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-26, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0133. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/addbill.php` | Medium
2 | File | `/add_new_supplier.php` | High
3 | File | `/admin-cp/theme/editor/default` | High
4 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
5 | File | `/admin.php?page=plugins&tab=new&installstatus=ok&plugin_id=[here` | High
6 | File | `/admin/ajax.php?action=delete_transaction` | High
7 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
8 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
9 | File | `/admin/edit-brand.php` | High
10 | File | `/admin/edit_area.php` | High
11 | File | `/admin/gnssAutoAlign.php` | High
12 | File | `/admin/idcProData_deal.php?mudi=del` | High
13 | File | `/admin/index.php` | High
14 | File | `/admin/inquiries/view_inquiry.php` | High
15 | File | `/admin/pages/list` | High
16 | File | `/admin/subnets/ripe-query.php` | High
17 | File | `/admin/update-clients.php` | High
18 | File | `/admin/upgrade` | High
19 | File | `/Admin/user-record.php` | High
20 | File | `/adminPage/www/addOver` | High
21 | File | `/ajax.php` | Medium
22 | File | `/ajax.php?action=signup` | High
23 | File | `/ajax.php?action=update_account` | High
24 | File | `/ample/app/action/edit_product.php` | High
25 | File | `/api/authentication/login` | High
26 | File | `/api/mob/instrucao/conta/destinatarios` | High
27 | File | `/api/v1/get-upload-file` | High
28 | File | `/appinfo/save` | High
29 | File | `/application/controller/Transaki.php` | High
30 | File | `/apply.cgi` | Medium
31 | File | `/assets` | Low
32 | File | `/attachments` | Medium
33 | File | `/author_posts.php` | High
34 | File | `/bin/boa` | Medium
35 | File | `/blog` | Low
36 | File | `/category.php` | High
37 | File | `/cgi-bin/cstecgi.cgi` | High
38 | File | `/cgi-bin/discovery.cgi` | High
39 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
40 | File | `/classes/Master.php?f=save_inquiry` | High
41 | File | `/classes/Users.php?f=save_client` | High
42 | File | `/collection/all` | High
43 | File | `/com/esafenet/servlet/policy/PrintPolicyService.java` | High
44 | File | `/ConfigFile.ini` | High
45 | File | `/core/tools/update_contact_form_settings.php` | High
46 | File | `/dataSet/testTransform;swagger-ui` | High
47 | File | `/Doctor/user_appointment.php` | High
48 | File | `/ecommerce/support_ticket` | High
49 | File | `/etc/luminex/pkgmgr` | High
50 | File | `/export` | Low
51 | File | `/file/accept.php` | High
52 | ... | ... | ...

There are 456 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/6278706

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
