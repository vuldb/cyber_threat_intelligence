# Lapsus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Lapsus](https://vuldb.com/?actor.lapsus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.lapsus](https://vuldb.com/?actor.lapsus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Lapsus:

* [US](https://vuldb.com/?country.us)
* [GB](https://vuldb.com/?country.gb)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Lapsus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.132.227.213](https://vuldb.com/?ip.45.132.227.213) | - | - | High
2 | [62.182.98.170](https://vuldb.com/?ip.62.182.98.170) | - | - | High
3 | [67.43.235.122](https://vuldb.com/?ip.67.43.235.122) | mail.pnoc.com.ph | - | High
4 | ... | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Lapsus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-36, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Lapsus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `.travis.yml` | Medium
3 | File | `/+CSCOE+/logon.html` | High
4 | File | `/../conf/config.properties` | High
5 | File | `/.env` | Low
6 | File | `//proc/kcore` | Medium
7 | File | `/admin/?page=user` | High
8 | File | `/admin/cms.php` | High
9 | File | `/admin/communitymanagement.php` | High
10 | File | `/admin/contacts/organizations/edit/2` | High
11 | File | `/admin/edit_admin_details.php?id=admin` | High
12 | File | `/admin/employee_row.php` | High
13 | File | `/admin/featured.php` | High
14 | File | `/admin/generalsettings.php` | High
15 | File | `/Admin/login.php` | High
16 | File | `/admin/login.php` | High
17 | File | `/admin/maintenance/brand.php` | High
18 | File | `/admin/newsletter1.php` | High
19 | File | `/admin/offenses/view_details.php` | High
20 | File | `/admin/patient.php` | High
21 | File | `/admin/payment.php` | High
22 | File | `/admin/photo.php` | High
23 | File | `/admin/products/index.php` | High
24 | File | `/admin/read.php?mudi=getSignal` | High
25 | File | `/admin/renewaldue.php` | High
26 | File | `/admin/robot/approval/list` | High
27 | File | `/admin/searchview.php` | High
28 | File | `/admin/success_story.php` | High
29 | File | `/admin/sys_sql_query.php` | High
30 | File | `/admin/test_status.php` | High
31 | File | `/admin/user/manage_user.php` | High
32 | File | `/admin/voters_row.php` | High
33 | File | `/ajax.php?action=save_company` | High
34 | File | `/api/wechat/app_auth` | High
35 | File | `/appliance/users?action=edit` | High
36 | File | `/APR/login.php` | High
37 | File | `/author_posts.php` | High
38 | File | `/bilal final/login.php` | High
39 | File | `/blog` | Low
40 | File | `/blog-single.php` | High
41 | File | `/browse` | Low
42 | File | `/bsms_ci/index.php` | High
43 | File | `/bsms_ci/index.php/user/edit_user/` | High
44 | File | `/catalog/admin/categories.php?cPath=&action=new_product` | High
45 | File | `/category.php` | High
46 | File | `/cbpos/` | Low
47 | File | `/classes/Master.php` | High
48 | File | `/classes/Master.php?f=delete_img` | High
49 | File | `/classes/Master.php?f=delete_service` | High
50 | File | `/classes/Master.php?f=save_item` | High
51 | File | `/classes/Master.php?f=update_order_status` | High
52 | File | `/classes/Users.php` | High
53 | File | `/common/download?filename=1.jsp&delete=false` | High
54 | File | `/config/getuser` | High
55 | File | `/contact.php` | Medium
56 | File | `/contact/store` | High
57 | File | `/context/%2e/WEB-INF/web.xml` | High
58 | File | `/Controller/Ajaxfileupload.ashx` | High
59 | File | `/Default/Bd` | Medium
60 | File | `/E-mobile/App/System/File/downfile.php` | High
61 | File | `/ecommerce/admin/category/controller.php` | High
62 | File | `/ecshop/admin/template.php` | High
63 | File | `/event/admin/?page=user/list` | High
64 | File | `/ffos/admin/menus/view_menu.php` | High
65 | File | `/forum/away.php` | High
66 | File | `/fos/admin/ajax.php?action=login` | High
67 | File | `/getImage` | Medium
68 | File | `/goform/formTcpipSetup` | High
69 | File | `/group1/uploa` | High
70 | File | `/horde/util/go.php` | High
71 | File | `/hrm/controller/employee.php` | High
72 | File | `/hrm/employeeadd.php` | High
73 | ... | ... | ...

There are 645 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://krypt3ia.wordpress.com/2023/12/22/lapsus-threat-card-and-dossiers/
* https://research.nccgroup.com/2022/04/28/lapsus-recent-techniques-tactics-and-procedures/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
