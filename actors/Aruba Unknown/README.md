# Aruba Unknown - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Aruba Unknown](https://vuldb.com/?actor.aruba_unknown). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.aruba_unknown](https://vuldb.com/?actor.aruba_unknown)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Aruba Unknown:

* [US](https://vuldb.com/?country.us)
* [ES](https://vuldb.com/?country.es)
* [DE](https://vuldb.com/?country.de)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Aruba Unknown.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.62.56.20](https://vuldb.com/?ip.5.62.56.20) | r-20-56-62-5.consumer-pool.prcdn.net | - | High
2 | [5.62.58.20](https://vuldb.com/?ip.5.62.58.20) | r-20-58-62-5.consumer-pool.prcdn.net | - | High
3 | [23.247.138.0](https://vuldb.com/?ip.23.247.138.0) | - | - | High
4 | [45.12.70.14](https://vuldb.com/?ip.45.12.70.14) | suasion.get-eye.com | - | High
5 | [45.12.71.14](https://vuldb.com/?ip.45.12.71.14) | - | - | High
6 | [57.74.102.0](https://vuldb.com/?ip.57.74.102.0) | - | - | High
7 | [57.91.224.0](https://vuldb.com/?ip.57.91.224.0) | - | - | High
8 | [66.247.200.0](https://vuldb.com/?ip.66.247.200.0) | - | - | High
9 | ... | ... | ... | ...

There are 31 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Aruba Unknown_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 16 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Aruba Unknown. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/photo.php` | High
2 | File | `/admin/user/add` | High
3 | File | `/APP_Installation.asp` | High
4 | File | `/categorypage.php` | High
5 | File | `/cm/delete` | Medium
6 | File | `/common/logViewer/logViewer.jsf` | High
7 | File | `/crmeb/app/admin/controller/store/CopyTaobao.php` | High
8 | File | `/drivers/media/media-device.c` | High
9 | File | `/etc/master.passwd` | High
10 | File | `/filemanager/upload.php` | High
11 | File | `/forum/away.php` | High
12 | File | `/getcfg.php` | Medium
13 | File | `/home.php` | Medium
14 | File | `/homeaction.php` | High
15 | File | `/modules/profile/index.php` | High
16 | File | `/modules/tasks/summary.inc.php` | High
17 | File | `/multi-vendor-shopping-script/product-list.php` | High
18 | File | `/out.php` | Medium
19 | File | `/p` | Low
20 | File | `/preauth` | Medium
21 | File | `/products/details.asp` | High
22 | File | `/recordings/index.php` | High
23 | File | `/see_more_details.php` | High
24 | File | `/show_news.php` | High
25 | File | `/tmp/before` | Medium
26 | File | `/uncpath/` | Medium
27 | File | `/updownload/t.report` | High
28 | File | `/user.profile.php` | High
29 | File | `/var/WEB-GUI/cgi-bin/telnet.cgi` | High
30 | File | `/wordpress/wp-admin/options-general.php` | High
31 | File | `/wp-admin` | Medium
32 | File | `/wp-admin/admin-ajax.php` | High
33 | File | `account.asp` | Medium
34 | File | `adclick.php` | Medium
35 | File | `adm/systools.asp` | High
36 | File | `admin.php` | Medium
37 | File | `admin/admin.shtml` | High
38 | File | `Admin/ADM_Pagina.php` | High
39 | File | `admin/category.inc.php` | High
40 | File | `admin/main.asp` | High
41 | File | `admin/param/param_func.inc.php` | High
42 | File | `admin/y_admin.asp` | High
43 | File | `adminer.php` | Medium
44 | File | `administrator/components/com_media/helpers/media.php` | High
45 | File | `admin_ok.asp` | Medium
46 | File | `app/Core/Paginator.php` | High
47 | File | `app/index.php/accounts/default/details?id=2&kanbanBoard=1&openToTaskId=1` | High
48 | File | `artlinks.dispnew.php` | High
49 | File | `auth.php` | Medium
50 | File | `bin/named/query.c` | High
51 | File | `blank.php` | Medium
52 | File | `blocklayered-ajax.php` | High
53 | ... | ... | ...

There are 465 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/firehol/blocklist-ipsets/blob/master/geolite2_country/country_aw.netset
* https://github.com/firehol/blocklist-ipsets/blob/master/ip2location_country/ip2location_country_aw.netset

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!