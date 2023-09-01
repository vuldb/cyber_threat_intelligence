# Tokelau Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Tokelau Unknown](https://vuldb.com/?actor.tokelau_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tokelau_unknown](https://vuldb.com/?actor.tokelau_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tokelau Unknown:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Tokelau Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.56.224](https://vuldb.com/?ip.5.62.56.224) | r-224-56-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.58.204](https://vuldb.com/?ip.5.62.58.204) | r-204-58-62-5.consumer-pool.prcdn.net | - | High
3 | [27.96.24.0](https://vuldb.com/?ip.27.96.24.0) | - | - | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Tokelau Unknown_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Tokelau Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//WEB-INF` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/update/getFile.html` | High
4 | File | `/admin/cashadvance_row.php` | High
5 | File | `/admin/maintenance/view_designation.php` | High
6 | File | `/admin/sys_sql_query.php` | High
7 | File | `/admin/upload.php` | High
8 | File | `/admin/userprofile.php` | High
9 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
10 | File | `/adms/admin/?page=vehicles/view_transaction` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/APR/login.php` | High
13 | File | `/bin/httpd` | Medium
14 | File | `/blog` | Low
15 | File | `/cgi-bin/wapopen` | High
16 | File | `/company/store` | High
17 | File | `/Controller/Ajaxfileupload.ashx` | High
18 | File | `/dev/block/mmcblk0rpmb` | High
19 | File | `/download` | Medium
20 | File | `/etc/passwd` | Medium
21 | File | `/feeds/post/publish` | High
22 | File | `/forum/away.php` | High
23 | File | `/fos/admin/ajax.php?action=login` | High
24 | File | `/fos/admin/index.php?page=menu` | High
25 | File | `/h/` | Low
26 | File | `/home/masterConsole` | High
27 | File | `/home/sendBroadcast` | High
28 | File | `/inc/jquery/uploadify/uploadify.php` | High
29 | File | `/index.php?app=main&func=passport&action=login` | High
30 | File | `/index.php?page=category_list` | High
31 | File | `/jobinfo/` | Medium
32 | File | `/Moosikay/order.php` | High
33 | File | `/mygym/admin/index.php?view_exercises` | High
34 | File | `/opac/Actions.php?a=login` | High
35 | File | `/php-opos/index.php` | High
36 | File | `/PreviewHandler.ashx` | High
37 | File | `/public/launchNewWindow.jsp` | High
38 | File | `/recipe-result` | High
39 | File | `/reports/rwservlet` | High
40 | File | `/reservation/add_message.php` | High
41 | File | `/Service/ImageStationDataService.asmx` | High
42 | File | `/student/bookdetails.php` | High
43 | File | `/uncpath/` | Medium
44 | File | `/uploads/exam_question/` | High
45 | File | `/user/ticket/create` | High
46 | File | `/user/updatePwd` | High
47 | File | `/var/lib/docker/<remapping>` | High
48 | File | `/wireless/security.asp` | High
49 | File | `/wp-admin/admin-ajax.php` | High
50 | File | `01article.php` | High
51 | File | `a-forms.php` | Medium
52 | File | `activenews_view.asp` | High
53 | File | `adclick.php` | Medium
54 | File | `admin.a6mambocredits.php` | High
55 | File | `admin.cropcanvas.php` | High
56 | File | `admin.php` | Medium
57 | File | `admin/abc.php` | High
58 | File | `admin/admin.php?action=users&mode=info&user=2` | High
59 | File | `admin/admin/adminsave.html` | High
60 | File | `admin/asset/grid-proxy` | High
61 | ... | ... | ...

There are 530 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_tk.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_tk.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_tk.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
