# RMS - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RMS](https://vuldb.com/?actor.rms). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rms](https://vuldb.com/?actor.rms)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RMS:

* [DE](https://vuldb.com/?country.de)
* [RU](https://vuldb.com/?country.ru)
* [US](https://vuldb.com/?country.us)
* ...

There are 13 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RMS.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.133.65.53](https://vuldb.com/?ip.5.133.65.53) | - | - | High
2 | [37.18.37.70](https://vuldb.com/?ip.37.18.37.70) | - | - | High
3 | [37.58.60.5](https://vuldb.com/?ip.37.58.60.5) | hosted-by.zenex5.com | - | High
4 | [43.255.175.215](https://vuldb.com/?ip.43.255.175.215) | - | - | High
5 | [45.82.71.172](https://vuldb.com/?ip.45.82.71.172) | cathost.io | - | High
6 | [45.144.30.30](https://vuldb.com/?ip.45.144.30.30) | polzovatel.com | - | High
7 | [45.144.52.44](https://vuldb.com/?ip.45.144.52.44) | 107343.h2.nexus | - | High
8 | [45.150.32.137](https://vuldb.com/?ip.45.150.32.137) | - | - | High
9 | [50.240.232.117](https://vuldb.com/?ip.50.240.232.117) | 50-240-232-117-static.hfc.comcastbusiness.net | - | High
10 | [51.83.171.208](https://vuldb.com/?ip.51.83.171.208) | hosted.by.majorcore.com | - | High
11 | [51.83.171.223](https://vuldb.com/?ip.51.83.171.223) | hosted.by.majorcore.com | - | High
12 | [52.208.217.243](https://vuldb.com/?ip.52.208.217.243) | ec2-52-208-217-243.eu-west-1.compute.amazonaws.com | - | Medium
13 | [54.188.107.146](https://vuldb.com/?ip.54.188.107.146) | ec2-54-188-107-146.us-west-2.compute.amazonaws.com | - | Medium
14 | [65.0.5.240](https://vuldb.com/?ip.65.0.5.240) | ec2-65-0-5-240.ap-south-1.compute.amazonaws.com | - | Medium
15 | [66.23.226.254](https://vuldb.com/?ip.66.23.226.254) | - | - | High
16 | [66.208.244.253](https://vuldb.com/?ip.66.208.244.253) | sbs.heraldtech.net | - | High
17 | [77.161.25.182](https://vuldb.com/?ip.77.161.25.182) | 77-161-25-182.fixed.kpn.net | - | High
18 | [77.223.119.187](https://vuldb.com/?ip.77.223.119.187) | - | - | High
19 | ... | ... | ... | ...

There are 73 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RMS_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RMS. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.git/` | Low
2 | File | `/../../conf/template/uhttpd.json` | High
3 | File | `/addclient1.php` | High
4 | File | `/addproduct.php` | High
5 | File | `/admin-manage-user.php` | High
6 | File | `/admin/?page=inventory/view_inventory&id=2` | High
7 | File | `/admin/?page=musics/manage_music` | High
8 | File | `/admin/add-doctor.php` | High
9 | File | `/admin/add_sundaysch.php` | High
10 | File | `/admin/admin-profile.php` | High
11 | File | `/admin/AdminLogin.php` | High
12 | File | `/admin/admin_action.php` | High
13 | File | `/admin/admin_invt2.php` | High
14 | File | `/admin/admin_user.php` | High
15 | File | `/admin/bookdate.php` | High
16 | File | `/admin/change-image.php` | High
17 | File | `/admin/core/new_staff` | High
18 | File | `/admin/delete.php` | High
19 | File | `/admin/delete_subject.php` | High
20 | File | `/admin/delete_teacher.php` | High
21 | File | `/admin/del_feedback.php` | High
22 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
23 | File | `/admin/ind_backstage.php` | High
24 | File | `/admin/maintenance/manage_department.php` | High
25 | File | `/admin/modal_add_product.php` | High
26 | File | `/admin/network/ajax_getChannelList` | High
27 | File | `/admin/options` | High
28 | File | `/admin/pages/list` | High
29 | File | `/admin/pages/update_go.php` | High
30 | File | `/admin/positions_add.php` | High
31 | File | `/admin/rooms.php` | High
32 | File | `/admin/services/view_service.php` | High
33 | File | `/admin/sys/log/list` | High
34 | File | `/admin/sys/menu/list` | High
35 | File | `/admin/twitter.php` | High
36 | File | `/admin/update-rooms.php` | High
37 | File | `/admin/vacancy/index.php` | High
38 | File | `/admin/vendor` | High
39 | File | `/admin/view-enquiry.php` | High
40 | File | `/admin?do=admin:user:editPost` | High
41 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
42 | File | `/animalsupdate.php` | High
43 | File | `/api/baskets/{name}` | High
44 | File | `/api/controllers/merchant/app/ComboController.php` | High
45 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
46 | File | `/api/wizard/getBasicInfo` | High
47 | File | `/application/index/common.php` | High
48 | File | `/application/index/controller/Screen.php` | High
49 | File | `/assoc_table.php` | High
50 | File | `/BBfile/Blood/o+.php` | High
51 | File | `/bin/webs` | Medium
52 | File | `/blog-details.php` | High
53 | File | `/cgi-bin/cstecgi.cgi` | High
54 | File | `/cgi-bin/hd_config.cgi` | High
55 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
56 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
57 | File | `/cgi-bin/vitogate.cgi` | High
58 | File | `/change-password.php` | High
59 | File | `/classes/Master.php?f=delete_category` | High
60 | File | `/classes/Master.php?f=save_category` | High
61 | File | `/classes/Master.php?f=save_inquiry` | High
62 | File | `/classes/Master.php?f=save_item` | High
63 | File | `/classes/Master.php?f=update_order_status` | High
64 | File | `/clinic/patients_view.php` | High
65 | ... | ... | ...

There are 571 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/de7fab866e4ec43a9421d6f98ee5d37ab55c0d341261eb93b564d39786b882ae/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
