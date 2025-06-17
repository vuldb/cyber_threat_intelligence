# Houdini - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Houdini](https://vuldb.com/?actor.houdini). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.houdini](https://vuldb.com/?actor.houdini)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Houdini:

* [US](https://vuldb.com/?country.us)
* [DE](https://vuldb.com/?country.de)
* [ES](https://vuldb.com/?country.es)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Houdini.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.59.254.111](https://vuldb.com/?ip.2.59.254.111) | - | - | High
2 | [5.181.80.127](https://vuldb.com/?ip.5.181.80.127) | ip-80-127-bullethost.net | - | High
3 | [37.48.102.22](https://vuldb.com/?ip.37.48.102.22) | - | - | High
4 | [41.216.188.103](https://vuldb.com/?ip.41.216.188.103) | - | - | High
5 | [45.90.222.125](https://vuldb.com/?ip.45.90.222.125) | 45-90-222-125-hostedby.bcr.host | - | High
6 | [45.90.222.131](https://vuldb.com/?ip.45.90.222.131) | 45-90-222-131-hostedby.bcr.host | - | High
7 | ... | ... | ... | ...

There are 23 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Houdini_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Houdini. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Account/login.php` | High
2 | File | `/admin` | Low
3 | File | `/admin.php?p=/Area/index#tab=t2` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=user/manage` | High
6 | File | `/Admin/add-student.php` | High
7 | File | `/admin/admin.php` | High
8 | File | `/admin/admin_user.php` | High
9 | File | `/admin/article.php` | High
10 | File | `/admin/create_product.php` | High
11 | File | `/admin/emp-profile-avatar.php` | High
12 | File | `/admin/forgot-password.php` | High
13 | File | `/admin/general/change-lang` | High
14 | File | `/admin/index.php` | High
15 | File | `/admin/inquiries/view_details.php` | High
16 | File | `/admin/lab.php` | High
17 | File | `/Admin/login.php` | High
18 | File | `/admin/login.php` | High
19 | File | `/admin/maintenance/view_designation.php` | High
20 | File | `/Admin/News.php` | High
21 | File | `/admin/save.php` | High
22 | File | `/admin/transactions/update_status.php` | High
23 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
24 | File | `/admin/users.php` | High
25 | File | `/AdminDir` | Medium
26 | File | `/analysisProject/pagingQueryData` | High
27 | File | `/api/authentication/login` | High
28 | File | `/api/user/password/sent-reset-email` | High
29 | File | `/app/api/controller/caiji.php` | High
30 | File | `/application/controller/Transaki.php` | High
31 | File | `/application/index/common.php` | High
32 | File | `/blog` | Low
33 | File | `/carbon/ndatasource/validateconnection/ajaxprocessor.jsp` | High
34 | File | `/category.php` | High
35 | File | `/cgi-bin/cstecgi.cgi` | High
36 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
37 | File | `/cgi-bin/nas_sharing.cgi` | High
38 | File | `/cgi-bin/photocenter_mgr.cgi` | High
39 | File | `/cgi-bin/system_mgr.cgi` | High
40 | File | `/cgi-bin/vitogate.cgi` | High
41 | File | `/classes/Master.php` | High
42 | File | `/control/register_case.php` | High
43 | File | `/coreframe/app/order/admin/index.php` | High
44 | File | `/course/filterRecords/` | High
45 | File | `/debug/pprof` | Medium
46 | File | `/dev/snd/seq` | Medium
47 | File | `/en/blog-comment-4` | High
48 | File | `/etc/config/rpcd` | High
49 | File | `/etc/sudoers` | Medium
50 | File | `/film-rating.php` | High
51 | File | `/forgot-password` | High
52 | File | `/forum/away.php` | High
53 | File | `/fos/admin/ajax.php?action=login` | High
54 | File | `/goForm/aspForm` | High
55 | File | `/guestbook` | Medium
56 | File | `/home/kickPlayer` | High
57 | File | `/index.jsp#settings` | High
58 | File | `/index.php/signin` | High
59 | File | `/index.php?action=editManager` | High
60 | File | `/Log/Query?appid=0B736354-9473-4D66-B9C0-15CAC149EB05&tabid=tab_0B73635494734D66B9C015CAC149EB05` | High
61 | File | `/login` | Low
62 | File | `/login.php` | Medium
63 | File | `/modules/profile/index.php` | High
64 | File | `/net-banking/beneficiary.php` | High
65 | File | `/net-banking/delete_customer.php` | High
66 | File | `/net-banking/edit_customer_action.php` | High
67 | File | `/net-banking/transactions.php` | High
68 | ... | ... | ...

There are 599 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/568aac24-7631-4f8f-a89b-ff10adf6b875
* https://app.any.run/tasks/8070f7cb-b7e2-4394-8898-cfcf9b52c332/
* https://bazaar.abuse.ch/sample/aed8a6b3191c2097fcbadb520f5d0f7e30b578c23f9abc0ab52b63bbb7abc141/
* https://bazaar.abuse.ch/sample/f0962774a22adb03e29c34fda016085f1fc99598f23562e5165474469f653bd0/
* https://github.com/executemalware/Malware-IOCs/blob/main/2022-06-20%20Vjw0rm%20and%20Houdini%20IOCs
* https://isc.sans.edu/forums/diary/Houdini+is+Back+Delivered+Through+a+JavaScript+Dropper/28746/
* https://threatfox.abuse.ch
* https://tria.ge/211009-xz62wafch8
* https://tria.ge/220613-smnybadca4
* https://twitter.com/suyog41/status/1692068700155965877
* https://www.joesandbox.com/analysis/839457/0/html#TCP_Packets
* https://www.virustotal.com/gui/file/00163dbf765b7011710330c18bad0a195208846e4aa471f4377eeb9d71b9fd34/detection
* https://www.virustotal.com/gui/file/be8a02ffd80f9367a1a23aac1a4f6b51ad25482783ac42147b18e5b2b36c98d0/detection

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
