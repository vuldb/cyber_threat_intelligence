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

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Houdini_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
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
10 | File | `/admin/emp-profile-avatar.php` | High
11 | File | `/admin/forgot-password.php` | High
12 | File | `/admin/general/change-lang` | High
13 | File | `/admin/index.php` | High
14 | File | `/admin/inquiries/view_details.php` | High
15 | File | `/Admin/login.php` | High
16 | File | `/admin/login.php` | High
17 | File | `/admin/maintenance/view_designation.php` | High
18 | File | `/Admin/News.php` | High
19 | File | `/admin/save.php` | High
20 | File | `/admin/transactions/update_status.php` | High
21 | File | `/admin/uesrs.php&action=type&userrole=Admin&userid=3` | High
22 | File | `/admin/users.php` | High
23 | File | `/AdminDir` | Medium
24 | File | `/analysisProject/pagingQueryData` | High
25 | File | `/api/authentication/login` | High
26 | File | `/api/user/password/sent-reset-email` | High
27 | File | `/app/api/controller/caiji.php` | High
28 | File | `/application/controller/Transaki.php` | High
29 | File | `/application/index/common.php` | High
30 | File | `/blog` | Low
31 | File | `/carbon/ndatasource/validateconnection/ajaxprocessor.jsp` | High
32 | File | `/category.php` | High
33 | File | `/cgi-bin/cstecgi.cgi` | High
34 | File | `/cgi-bin/nas_sharing.cgi` | High
35 | File | `/cgi-bin/photocenter_mgr.cgi` | High
36 | File | `/cgi-bin/system_mgr.cgi` | High
37 | File | `/cgi-bin/vitogate.cgi` | High
38 | File | `/classes/Master.php` | High
39 | File | `/control/register_case.php` | High
40 | File | `/coreframe/app/order/admin/index.php` | High
41 | File | `/course/filterRecords/` | High
42 | File | `/debug/pprof` | Medium
43 | File | `/dev/snd/seq` | Medium
44 | File | `/en/blog-comment-4` | High
45 | File | `/etc/sudoers` | Medium
46 | File | `/film-rating.php` | High
47 | File | `/forgot-password` | High
48 | File | `/forum/away.php` | High
49 | File | `/fos/admin/ajax.php?action=login` | High
50 | File | `/goForm/aspForm` | High
51 | File | `/guestbook` | Medium
52 | File | `/home/kickPlayer` | High
53 | File | `/index.jsp#settings` | High
54 | File | `/index.php/signin` | High
55 | File | `/index.php?action=editManager` | High
56 | File | `/Log/Query?appid=0B736354-9473-4D66-B9C0-15CAC149EB05&tabid=tab_0B73635494734D66B9C015CAC149EB05` | High
57 | File | `/login` | Low
58 | File | `/login.php` | Medium
59 | File | `/net-banking/beneficiary.php` | High
60 | File | `/net-banking/delete_customer.php` | High
61 | File | `/net-banking/edit_customer_action.php` | High
62 | File | `/net-banking/transactions.php` | High
63 | File | `/philosophy/admin/login.php` | High
64 | File | `/pms/update_user.php?user_id=1` | High
65 | ... | ... | ...

There are 573 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
