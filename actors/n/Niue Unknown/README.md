# Niue Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Niue Unknown](https://vuldb.com/?actor.niue_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.niue_unknown](https://vuldb.com/?actor.niue_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Niue Unknown:

* [US](https://vuldb.com/?country.us)
* [AU](https://vuldb.com/?country.au)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 26 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Niue Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.56.152](https://vuldb.com/?ip.5.62.56.152) | r-152-56-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.58.144](https://vuldb.com/?ip.5.62.58.144) | r-144-58-62-5.consumer-pool.prcdn.net | - | High
3 | [45.12.70.171](https://vuldb.com/?ip.45.12.70.171) | bingo.alltieinc.com | - | High
4 | [45.12.71.171](https://vuldb.com/?ip.45.12.71.171) | - | - | High
5 | [46.36.200.71](https://vuldb.com/?ip.46.36.200.71) | - | - | High
6 | [46.36.200.72](https://vuldb.com/?ip.46.36.200.72) | - | - | High
7 | [46.36.200.80](https://vuldb.com/?ip.46.36.200.80) | - | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Niue Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Niue Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMFILES(X86)%\Steam` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/Admin/changepassword.php` | High
4 | File | `/admin/index.php` | High
5 | File | `/admin/manage_academic.php` | High
6 | File | `/admin/photo.php` | High
7 | File | `/admin/upload.php` | High
8 | File | `/admin/user/add` | High
9 | File | `/admin/user/user-move-run.php` | High
10 | File | `/ajax_city.php` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/api/role` | Medium
13 | File | `/api/upload.php` | High
14 | File | `/bin/sh` | Low
15 | File | `/blog` | Low
16 | File | `/car-rental-management-system/admin/view_car.php=` | High
17 | File | `/cgi-bin/cstecgi.cgi` | High
18 | File | `/cgi-bin/koha/catalogue/search.pl` | High
19 | File | `/classes/SystemSettings.php?f=update_settings` | High
20 | File | `/cm/delete` | Medium
21 | File | `/common/logViewer/logViewer.jsf` | High
22 | File | `/config/config.json` | High
23 | File | `/crmeb/app/admin/controller/store/CopyTaobao.php` | High
24 | File | `/debug/pprof` | Medium
25 | File | `/download` | Medium
26 | File | `/etc/hosts.deny` | High
27 | File | `/forum/away.php` | High
28 | File | `/GponForm/device_Form?script/` | High
29 | File | `/GponForm/usb_restore_Form?script/` | High
30 | File | `/homeaction.php` | High
31 | File | `/index.php?menu=asterisk_cli` | High
32 | File | `/mee/login` | Medium
33 | File | `/modules/profile/index.php` | High
34 | File | `/multi-vendor-shopping-script/product-list.php` | High
35 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
36 | File | `/out.php` | Medium
37 | File | `/p` | Low
38 | File | `/pg_meta/default/query` | High
39 | File | `/portal/search.htm` | High
40 | File | `/preauth` | Medium
41 | File | `/see_more_details.php` | High
42 | File | `/show_news.php` | High
43 | File | `/spip.php` | Medium
44 | File | `/sqleditor/query_tool/download` | High
45 | File | `/static/ueditor/php/controller.php` | High
46 | File | `/student.php` | Medium
47 | File | `/student/bookdetails.php` | High
48 | File | `/uncpath/` | Medium
49 | File | `/update-article.php` | High
50 | File | `/upload/ueditorConfig?action=config` | High
51 | File | `/user.profile.php` | High
52 | File | `/user/chat/mynewuser` | High
53 | File | `/user/loader.php?api=1` | High
54 | File | `/usr/bin/at` | Medium
55 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
56 | File | `/view/vpn/autovpn/online_check.php` | High
57 | File | `/wordpress/wp-admin/options-general.php` | High
58 | ... | ... | ...

There are 506 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_nu.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ipip_country/ipip_country_nu.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
