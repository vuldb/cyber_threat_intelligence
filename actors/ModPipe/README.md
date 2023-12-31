# ModPipe - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [ModPipe](https://vuldb.com/?actor.modpipe). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.modpipe](https://vuldb.com/?actor.modpipe)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ModPipe:

* [FR](https://vuldb.com/?country.fr)
* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ModPipe.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.135.230.136](https://vuldb.com/?ip.5.135.230.136) | - | - | High
2 | [23.19.58.114](https://vuldb.com/?ip.23.19.58.114) | - | - | High
3 | [88.99.177.103](https://vuldb.com/?ip.88.99.177.103) | static.103.177.99.88.clients.your-server.de | - | High
4 | ... | ... | ... | ...

There are 3 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ModPipe_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ModPipe. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `//proc/kcore` | Medium
3 | File | `/admin/access` | High
4 | File | `/admin/addemployee.php` | High
5 | File | `/admin/budget/manage_budget.php` | High
6 | File | `/admin/del_category.php` | High
7 | File | `/admin/index.html` | High
8 | File | `/admin/index.php?id=themes&action=edit_template&filename=blog` | High
9 | File | `/admin/manage_academic.php` | High
10 | File | `/admin/posts.php` | High
11 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
12 | File | `/ajax.php?action=read_msg` | High
13 | File | `/book-services.php` | High
14 | File | `/ci_ssms/index.php/orders/create` | High
15 | File | `/CPE` | Low
16 | File | `/edoc/doctor/patient.php` | High
17 | File | `/enterprise/www/student.php` | High
18 | File | `/eval/admin/manage_subject.php` | High
19 | File | `/forum/away.php` | High
20 | File | `/front/actions.php` | High
21 | File | `/fw.login.php` | High
22 | File | `/h/autoSaveDraft` | High
23 | File | `/home/masterConsole` | High
24 | File | `/index.php` | Medium
25 | File | `/membres/modif_profil.php` | High
26 | File | `/NotrinosERP/sales/customer_delivery.php` | High
27 | File | `/oauth/idp/.well-known/openid-configuration` | High
28 | File | `/ordering/admin/category/index.php?view=edit` | High
29 | File | `/pet_shop/admin/orders/update_status.php` | High
30 | File | `/pms/index.php` | High
31 | File | `/pms/update_user.php?user_id=1` | High
32 | File | `/SimpleBusTicket/index.php` | High
33 | File | `/tmp` | Low
34 | File | `/transcation.php` | High
35 | File | `/uncpath/` | Medium
36 | File | `/updown/upload.cgi` | High
37 | File | `/usr/bin/pkexec` | High
38 | File | `/var/run/docker.sock` | High
39 | File | `/wp-admin/admin-ajax.php` | High
40 | File | `/xpdf/Stream.cc` | High
41 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
42 | File | `adclick.php` | Medium
43 | File | `addons/mediapool/pages/index.php` | High
44 | File | `addpost_newpoll.php` | High
45 | File | `adm-index.php` | High
46 | File | `Admin.PHP` | Medium
47 | File | `admin.php` | Medium
48 | File | `admin.php&r=article/AdminContent/edit` | High
49 | File | `admin/expense_report.php` | High
50 | File | `admin/index.php` | High
51 | File | `admin/ops/reports/ops/forum.php` | High
52 | File | `admin/versions.html` | High
53 | File | `admincp/attachment.php` | High
54 | File | `adminedit.pl` | Medium
55 | File | `ajax.php` | Medium
56 | File | `ajax/api/hook/getHookList` | High
57 | File | `application/controllers/Leaves.php` | High
58 | File | `App\Manage\Controller\ArticleController.class.php` | High
59 | ... | ... | ...

There are 513 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://community.blueliv.com/#!/s/5fad26c782df413eb535189f

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
