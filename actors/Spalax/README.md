# Spalax - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Spalax](https://vuldb.com/?actor.spalax). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.spalax](https://vuldb.com/?actor.spalax)

## Campaigns

The following _campaigns_ are known and can be associated with Spalax:

* Spalax

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Spalax:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Spalax.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [128.90.108.132](https://vuldb.com/?ip.128.90.108.132) | undefined.hostname.localhost | Spalax | High
2 | [128.90.108.177](https://vuldb.com/?ip.128.90.108.177) | undefined.hostname.localhost | Spalax | High
3 | [128.90.112.34](https://vuldb.com/?ip.128.90.112.34) | undefined.hostname.localhost | Spalax | High
4 | [128.90.112.142](https://vuldb.com/?ip.128.90.112.142) | undefined.hostname.localhost | Spalax | High
5 | [128.90.115.100](https://vuldb.com/?ip.128.90.115.100) | undefined.hostname.localhost | Spalax | High
6 | [128.90.115.244](https://vuldb.com/?ip.128.90.115.244) | undefined.hostname.localhost | Spalax | High
7 | [179.14.171.7](https://vuldb.com/?ip.179.14.171.7) | Dinamic-Tigo-179-14-171-7.tigo.com.co | Spalax | High
8 | [179.14.173.93](https://vuldb.com/?ip.179.14.173.93) | Dinamic-Tigo-179-14-173-93.tigo.com.co | Spalax | High
9 | [181.49.90.193](https://vuldb.com/?ip.181.49.90.193) | dynamic-ip-1814990193.cable.net.co | Spalax | High
10 | [181.52.100.157](https://vuldb.com/?ip.181.52.100.157) | static-ip-cr181520100157.cable.net.co | Spalax | High
11 | [181.52.102.87](https://vuldb.com/?ip.181.52.102.87) | static-ip-cr18152010287.cable.net.co | Spalax | High
12 | [181.52.103.140](https://vuldb.com/?ip.181.52.103.140) | static-ip-cr181520103140.cable.net.co | Spalax | High
13 | [181.52.104.2](https://vuldb.com/?ip.181.52.104.2) | static-ip-cr1815201042.cable.net.co | Spalax | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Spalax_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Spalax. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//WEB-INF` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/update/getFile.html` | High
4 | File | `/admin/cashadvance_row.php` | High
5 | File | `/admin/maintenance/view_designation.php` | High
6 | File | `/admin/sys_sql_query.php` | High
7 | File | `/admin/userprofile.php` | High
8 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
9 | File | `/adms/admin/?page=vehicles/view_transaction` | High
10 | File | `/api/baskets/{name}` | High
11 | File | `/APR/login.php` | High
12 | File | `/bin/httpd` | Medium
13 | File | `/bitrix/admin/ldap_server_edit.php` | High
14 | File | `/cgi-bin/luci/api/wireless` | High
15 | File | `/cgi-bin/wapopen` | High
16 | File | `/company/store` | High
17 | File | `/Content/Template/root/reverse-shell.aspx` | High
18 | File | `/Controller/Ajaxfileupload.ashx` | High
19 | File | `/core/conditions/AbstractWrapper.java` | High
20 | File | `/dev/block/mmcblk0rpmb` | High
21 | File | `/etc/passwd` | Medium
22 | File | `/feeds/post/publish` | High
23 | File | `/forum/away.php` | High
24 | File | `/fos/admin/ajax.php?action=login` | High
25 | File | `/fos/admin/index.php?page=menu` | High
26 | File | `/h/` | Low
27 | File | `/home/masterConsole` | High
28 | File | `/home/sendBroadcast` | High
29 | File | `/inc/jquery/uploadify/uploadify.php` | High
30 | File | `/index.php?app=main&func=passport&action=login` | High
31 | File | `/index.php?page=category_list` | High
32 | File | `/jobinfo/` | Medium
33 | File | `/Moosikay/order.php` | High
34 | File | `/mygym/admin/index.php?view_exercises` | High
35 | File | `/opac/Actions.php?a=login` | High
36 | File | `/php-opos/index.php` | High
37 | File | `/PreviewHandler.ashx` | High
38 | File | `/public/launchNewWindow.jsp` | High
39 | File | `/recipe-result` | High
40 | File | `/register.do` | Medium
41 | File | `/reports/rwservlet` | High
42 | File | `/reservation/add_message.php` | High
43 | File | `/Service/ImageStationDataService.asmx` | High
44 | File | `/spip.php` | Medium
45 | File | `/student/bookdetails.php` | High
46 | File | `/uncpath/` | Medium
47 | File | `/uploads/exam_question/` | High
48 | File | `/user/ticket/create` | High
49 | File | `/user/updatePwd` | High
50 | File | `/var/lib/docker/<remapping>` | High
51 | File | `/wireless/security.asp` | High
52 | File | `/wp-admin/admin-ajax.php` | High
53 | File | `01article.php` | High
54 | File | `a-forms.php` | Medium
55 | File | `activenews_view.asp` | High
56 | ... | ... | ...

There are 492 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/spalax

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
