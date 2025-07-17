# Nimplant - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nimplant](https://vuldb.com/?actor.nimplant). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nimplant](https://vuldb.com/?actor.nimplant)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nimplant:

* [VN](https://vuldb.com/?country.vn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nimplant.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.147.54](https://vuldb.com/?ip.3.0.147.54) | ec2-3-0-147-54.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.17.181.161](https://vuldb.com/?ip.3.17.181.161) | ec2-3-17-181-161.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.226.6.113](https://vuldb.com/?ip.3.226.6.113) | ec2-3-226-6-113.compute-1.amazonaws.com | - | Medium
4 | [3.239.44.147](https://vuldb.com/?ip.3.239.44.147) | ec2-3-239-44-147.compute-1.amazonaws.com | - | Medium
5 | [13.70.157.121](https://vuldb.com/?ip.13.70.157.121) | - | - | High
6 | [14.225.206.107](https://vuldb.com/?ip.14.225.206.107) | static.vnpt.vn | - | High
7 | [20.93.3.210](https://vuldb.com/?ip.20.93.3.210) | - | - | High
8 | [23.106.215.199](https://vuldb.com/?ip.23.106.215.199) | - | - | High
9 | [34.134.73.140](https://vuldb.com/?ip.34.134.73.140) | 140.73.134.34.bc.googleusercontent.com | - | Medium
10 | [34.251.151.38](https://vuldb.com/?ip.34.251.151.38) | ec2-34-251-151-38.eu-west-1.compute.amazonaws.com | - | Medium
11 | [35.87.2.201](https://vuldb.com/?ip.35.87.2.201) | ec2-35-87-2-201.us-west-2.compute.amazonaws.com | - | Medium
12 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/(?J)(?'d'(?'d'\g{d}))/` | High
2 | File | `/Account/login.php` | High
3 | File | `/action/wirelessConnect` | High
4 | File | `/addcompany.php` | High
5 | File | `/admin.php/appcenter/local.html?type=addon` | High
6 | File | `/admin/?page=reminders/view_reminder` | High
7 | File | `/admin/article/article-add.php` | High
8 | File | `/admin/bwdates-report-details.php` | High
9 | File | `/admin/category/cate-edit-run.php` | High
10 | File | `/admin/edit_area.php` | High
11 | File | `/admin/file/delete.do` | High
12 | File | `/admin/file_manager/files` | High
13 | File | `/admin/general/change-lang` | High
14 | File | `/admin/get_balance.php` | High
15 | File | `/admin/group/list/` | High
16 | File | `/admin/maintenance/manage_department.php` | High
17 | File | `/admin/massage.php` | High
18 | File | `/admin/modal_add_product.php` | High
19 | File | `/admin/products/manage_product.php` | High
20 | File | `/admin/service/stop/` | High
21 | File | `/admin/update_s6.php` | High
22 | File | `/admin/uploads/` | High
23 | File | `/adminapi/system/file/openfile` | High
24 | File | `/api/DataDictionary/GetItemList` | High
25 | File | `/api/stl/actions/search` | High
26 | File | `/api/v2/labels/` | High
27 | File | `/app/ajax/sell_return_data.php` | High
28 | File | `/base/ecma-helpers.c` | High
29 | File | `/carbon/mediation_secure_vault/properties/ajaxprocessor.jsp` | High
30 | File | `/catalog/compare` | High
31 | File | `/category/order/hits/copyright/46/finish/1/list/1` | High
32 | File | `/cgi-bin/cstecgi.cgi` | High
33 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
34 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
35 | File | `/cgi-bin/mainfunction.cgi` | High
36 | File | `/cms/classes/Master.php?f=delete_service` | High
37 | File | `/common/show_image.php` | High
38 | File | `/core/tools/update_menu.php` | High
39 | File | `/cwc/login` | Medium
40 | File | `/dashboard/createblog` | High
41 | File | `/dict/list.do` | High
42 | File | `/doorgets/app/views/ajax/contactView.php` | High
43 | File | `/dotclear/admin/media.php` | High
44 | File | `/edituser.php` | High
45 | File | `/endpoint/add-folder.php` | High
46 | File | `/example/editor` | High
47 | File | `/film-rating.php` | High
48 | File | `/goform/addIpMacBind` | High
49 | File | `/goform/apPortalPhoneAuth` | High
50 | File | `/goform/aspForm` | High
51 | File | `/goform/delIpMacBind` | High
52 | File | `/goform/execCommand` | High
53 | File | `/goform/formSetMACFilter` | High
54 | File | `/goform/formSetPassword` | High
55 | File | `/goform/formSetWanPPPoE` | High
56 | File | `/goform/FUN_0007343c` | High
57 | File | `/goform/Natlimit` | High
58 | File | `/goform/RgDhcp` | High
59 | ... | ... | ...

There are 512 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://search.censys.io/hosts/3.226.6.113
* https://search.censys.io/hosts/3.239.44.147
* https://search.censys.io/hosts/13.70.157.121
* https://search.censys.io/hosts/14.225.206.107
* https://search.censys.io/hosts/20.93.3.210
* https://search.censys.io/hosts/23.106.215.199
* https://search.censys.io/hosts/34.134.73.140
* https://search.censys.io/hosts/34.134.73.140+140.73.134.34.bc.googleusercontent.com
* https://search.censys.io/hosts/43.143.128.128
* https://search.censys.io/hosts/44.201.19.178
* https://search.censys.io/hosts/46.247.108.127
* https://search.censys.io/hosts/47.243.184.85
* https://search.censys.io/hosts/51.68.222.10
* https://search.censys.io/hosts/54.38.242.131
* https://search.censys.io/hosts/54.202.46.22
* https://search.censys.io/hosts/65.49.204.212
* https://search.censys.io/hosts/88.208.3.157
* https://search.censys.io/hosts/89.73.53.34
* https://search.censys.io/hosts/94.102.49.16
* https://search.censys.io/hosts/94.102.49.106
* https://search.censys.io/hosts/136.144.243.50
* https://search.censys.io/hosts/139.180.217.224
* https://search.censys.io/hosts/142.93.226.220
* https://search.censys.io/hosts/146.190.109.188
* https://search.censys.io/hosts/146.190.241.166
* https://search.censys.io/hosts/149.248.79.215
* https://search.censys.io/hosts/156.244.13.120
* https://search.censys.io/hosts/161.97.116.56
* https://search.censys.io/hosts/167.88.160.211
* https://search.censys.io/hosts/167.88.170.172
* https://search.censys.io/hosts/185.196.10.245
* https://search.censys.io/hosts/194.26.192.127
* https://search.censys.io/hosts/207.154.192.30
* https://search.censys.io/hosts/207.180.253.60
* https://search.censys.io/hosts/210.2.169.231
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
