# OpBlueRaven - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _OpBlueRaven_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with OpBlueRaven:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 19 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with OpBlueRaven or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [FIN7](https://vuldb.com/?actor.fin7) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of OpBlueRaven.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.177.23](https://vuldb.com/?ip.5.252.177.23) | 5-252-177-23.mivocloud.com | [FIN7](https://vuldb.com/?actor.fin7) | High
2 | [5.252.177.37](https://vuldb.com/?ip.5.252.177.37) | no-rdns.mivocloud.com | [FIN7](https://vuldb.com/?actor.fin7) | High
3 | [23.83.133.119](https://vuldb.com/?ip.23.83.133.119) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
4 | [37.1.211.239](https://vuldb.com/?ip.37.1.211.239) | ourdrops.org | [FIN7](https://vuldb.com/?actor.fin7) | High
5 | [37.1.215.4](https://vuldb.com/?ip.37.1.215.4) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
6 | [37.1.215.72](https://vuldb.com/?ip.37.1.215.72) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
7 | [37.252.4.131](https://vuldb.com/?ip.37.252.4.131) | - | [FIN7](https://vuldb.com/?actor.fin7) | High
8 | [45.77.60.230](https://vuldb.com/?ip.45.77.60.230) | 45.77.60.230.vultr.com | [FIN7](https://vuldb.com/?actor.fin7) | Medium
9 | [45.77.204.130](https://vuldb.com/?ip.45.77.204.130) | 45.77.204.130.vultr.com | [FIN7](https://vuldb.com/?actor.fin7) | Medium
10 | [45.87.152.64](https://vuldb.com/?ip.45.87.152.64) | free.pq.hosting | [FIN7](https://vuldb.com/?actor.fin7) | High
11 | [45.133.216.25](https://vuldb.com/?ip.45.133.216.25) | lisulisimp.example.com | [FIN7](https://vuldb.com/?actor.fin7) | High
12 | ... | ... | ... | ...

There are 44 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/about.php` | Medium
2 | File | `/addQuestion.php` | High
3 | File | `/admin.php/accessory/filesdel.html` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/addemployee.php` | High
7 | File | `/admin/api/theme-edit/` | High
8 | File | `/admin/doctors.php` | High
9 | File | `/admin/photo.php` | High
10 | File | `/admin/students/manage.php` | High
11 | File | `/admin/submit-articles` | High
12 | File | `/ad_js.php` | Medium
13 | File | `/alphaware/summary.php` | High
14 | File | `/api/` | Low
15 | File | `/api/admin/store/product/list` | High
16 | File | `/api/RecordingList/DownloadRecord?file=` | High
17 | File | `/apply.cgi` | Medium
18 | File | `/artist-display.php` | High
19 | File | `/attachments` | Medium
20 | File | `/boat/login.php` | High
21 | File | `/bsms_ci/index.php` | High
22 | File | `/bsms_ci/index.php/book` | High
23 | File | `/cgi-bin/luci/api/wireless` | High
24 | File | `/cgi-bin/nightled.cgi` | High
25 | File | `/cgi-bin/wlogin.cgi` | High
26 | File | `/common/info.cgi` | High
27 | File | `/context/%2e/WEB-INF/web.xml` | High
28 | File | `/dashboard/reports/logs/view` | High
29 | File | `/debian/patches/load_ppp_generic_if_needed` | High
30 | File | `/debug/pprof` | Medium
31 | File | `/etc/hosts` | Medium
32 | File | `/foms/place-order.php` | High
33 | File | `/forum/away.php` | High
34 | File | `/goform/setmac` | High
35 | File | `/goform/wizard_end` | High
36 | File | `/index.php` | Medium
37 | File | `/jsoa/hntdCustomDesktopActionContent` | High
38 | File | `/librarian/bookdetails.php` | High
39 | File | `/manage-apartment.php` | High
40 | File | `/management/api/rcx_management/global_config_query` | High
41 | File | `/mcategory.php` | High
42 | File | `/medicines/profile.php` | High
43 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
44 | File | `/multi-vendor-shopping-script/product-list.php` | High
45 | File | `/pages/apply_vacancy.php` | High
46 | File | `/php-sms/admin/` | High
47 | File | `/product/savenewproduct.php?flag=1` | High
48 | File | `/proxy` | Low
49 | File | `/ptipupgrade.cgi` | High
50 | File | `/real-estate-script/search_property.php` | High
51 | File | `/reservation/add_message.php` | High
52 | File | `/services/Card/findUser` | High
53 | File | `/spip.php` | Medium
54 | File | `/staff/bookdetails.php` | High
55 | File | `/subpage.php` | Medium
56 | File | `/template/edit` | High
57 | ... | ... | ...

There are 498 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/OpBlueRaven

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
