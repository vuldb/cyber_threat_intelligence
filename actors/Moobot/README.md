# MooBot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MooBot](https://vuldb.com/?actor.moobot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.moobot](https://vuldb.com/?actor.moobot)

## Campaigns

The following _campaigns_ are known and can be associated with MooBot:

* DDoS Ukraine
* UNIX CCTV DVR

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MooBot:

* [US](https://vuldb.com/?country.us)
* [LU](https://vuldb.com/?country.lu)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MooBot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [31.13.195.56](https://vuldb.com/?ip.31.13.195.56) | - | - | High
2 | [37.49.226.216](https://vuldb.com/?ip.37.49.226.216) | - | - | High
3 | [45.95.168.90](https://vuldb.com/?ip.45.95.168.90) | - | - | High
4 | [45.95.169.14](https://vuldb.com/?ip.45.95.169.14) | - | - | High
5 | [89.248.174.165](https://vuldb.com/?ip.89.248.174.165) | - | UNIX CCTV DVR | High
6 | [89.248.174.166](https://vuldb.com/?ip.89.248.174.166) | - | UNIX CCTV DVR | High
7 | [89.248.174.198](https://vuldb.com/?ip.89.248.174.198) | - | - | High
8 | [89.248.174.203](https://vuldb.com/?ip.89.248.174.203) | no-reverse-dns-configured.com | UNIX CCTV DVR | High
9 | [89.248.174.219](https://vuldb.com/?ip.89.248.174.219) | - | - | High
10 | ... | ... | ... | ...

There are 36 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MooBot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MooBot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\TSplus\UserDesktop\themes.` | High
2 | File | `/activate_hook.php` | High
3 | File | `/addbill.php` | Medium
4 | File | `/add_post_sql.php` | High
5 | File | `/admin/book_row.php` | High
6 | File | `/admin/communitymanagement.php` | High
7 | File | `/admin/del_service.php` | High
8 | File | `/admin/generalsettings.php` | High
9 | File | `/admin/maintenance/view_designation.php` | High
10 | File | `/admin/payment.php` | High
11 | File | `/admin/search-appointment.php` | High
12 | File | `/admin/tag/delete` | High
13 | File | `/admin/user/manage_user.php` | High
14 | File | `/ajax.php?action=read_msg` | High
15 | File | `/ample/app/action/edit_product.php` | High
16 | File | `/api/baskets/{name}` | High
17 | File | `/application/pay/controller/Api.php` | High
18 | File | `/bitrix/admin/ldap_server_edit.php` | High
19 | File | `/blog/edit` | Medium
20 | File | `/bsms_ci/index.php/user/edit_user/` | High
21 | File | `/cgi-bin/wlogin.cgi` | High
22 | File | `/classes/Master.php?f=delete_category` | High
23 | File | `/classes/Master.php?f=save_item` | High
24 | File | `/conf/` | Low
25 | File | `/config/php.ini` | High
26 | File | `/controller/AdminController.php` | High
27 | File | `/debug/pprof` | Medium
28 | File | `/Default/Bd` | Medium
29 | File | `/editprofile.php` | High
30 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
31 | File | `/etc/shadow.sample` | High
32 | File | `/event/admin/?page=user/list` | High
33 | File | `/filemanager/upload/drop` | High
34 | File | `/forum/away.php` | High
35 | File | `/friends/ajax_invite` | High
36 | File | `/getcfg.php` | Medium
37 | File | `/goform/PowerSaveSet` | High
38 | File | `/goform/wizard_end` | High
39 | File | `/HNAP1/` | Low
40 | File | `/home/get_tasks_list` | High
41 | File | `/hrm/employeeview.php` | High
42 | File | `/index.php` | Medium
43 | File | `/isms/classes/Users.php` | High
44 | File | `/lists/index.php` | High
45 | File | `/log/mailsendview.php` | High
46 | File | `/MailAdmin_dll.htm` | High
47 | File | `/members/profiles.php` | High
48 | File | `/members/view_member.php` | High
49 | File | `/messageboard/view.php` | High
50 | File | `/mhds/clinic/view_details.php` | High
51 | File | `/modules/projects/vw_files.php` | High
52 | File | `/net/tls/tls_sw.c` | High
53 | File | `/ordering/index.php?q=category` | High
54 | File | `/owa/auth/logon.aspx` | High
55 | File | `/picturesPreview` | High
56 | ... | ... | ...

There are 489 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/e09dfc1ba1052e4b5c2c3ff2d9985f6f5024b526aeb8ae4a1d28d8cd81bb0c1e/
* https://blog.netlab.360.com/ddos-botnet-moobot-en/
* https://blog.netlab.360.com/moobot-0day-unixcctv-dvr-en/
* https://blog.netlab.360.com/some_details_of_the_ddos_attacks_targeting_ukraine_and_russia_in_recent_days/
* https://blog.netlab.360.com/the-botnet-cluster-on-185-244-25-0-24-en/
* https://search.censys.io/hosts/45.95.169.14
* https://search.censys.io/hosts/91.92.252.23
* https://search.censys.io/hosts/93.123.85.43
* https://search.censys.io/hosts/93.123.85.116
* https://search.censys.io/hosts/93.123.85.122
* https://search.censys.io/hosts/103.74.100.192
* https://search.censys.io/hosts/103.78.0.159
* https://search.censys.io/hosts/103.189.203.36
* https://search.censys.io/hosts/137.175.17.80
* https://search.censys.io/hosts/210.211.117.205
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
