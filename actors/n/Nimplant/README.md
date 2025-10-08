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

There are 46 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nimplant_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-271, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nimplant. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?g=route_ispinfo_export_save` | High
2 | File | `/?s=doudou&c=file&a=list` | High
3 | File | `/a/sys/user/save` | High
4 | File | `/addcustind.php` | High
5 | File | `/admin-profile.php` | High
6 | File | `/admin.php` | Medium
7 | File | `/admin/?page=user/manage` | High
8 | File | `/admin/add-animals.php` | High
9 | File | `/admin/add_vehicles.php` | High
10 | File | `/admin/admin-profile.php` | High
11 | File | `/admin/ajax.php?action=delete_recruitment_status` | High
12 | File | `/admin/ajax.php?action=login` | High
13 | File | `/admin/ajax.php?action=save_recruitment_status` | High
14 | File | `/admin/assign_save.php` | High
15 | File | `/admin/campsdetails.php` | High
16 | File | `/admin/category/controller.php` | High
17 | File | `/admin/category_update.php` | High
18 | File | `/admin/changepropic.php` | High
19 | File | `/admin/config_ISCGroupNoCache.php` | High
20 | File | `/admin/deduction_edit.php` | High
21 | File | `/admin/delete_s2.php` | High
22 | File | `/admin/delete_s3.php` | High
23 | File | `/admin/delete_s5.php` | High
24 | File | `/admin/delete_s6.php` | High
25 | File | `/admin/del_feedback.php` | High
26 | File | `/admin/department/add` | High
27 | File | `/admin/doctors.php` | High
28 | File | `/admin/edit-admin.php` | High
29 | File | `/admin/edit-card-detail.php` | High
30 | File | `/admin/edit-class.php` | High
31 | File | `/admin/edit-doc.php` | High
32 | File | `/admin/edit_class.php` | High
33 | File | `/admin/edit_event.php` | High
34 | File | `/admin/edit_query_account.php` | High
35 | File | `/admin/fields/manage_field.php` | High
36 | File | `/admin/file/upload.do` | High
37 | File | `/admin/index.php` | High
38 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
39 | File | `/admin/inquiries/view_details.php` | High
40 | File | `/admin/login.php` | High
41 | File | `/admin/manage-card.php` | High
42 | File | `/Admin/NewsReport.php` | High
43 | File | `/admin/payment_save.php` | High
44 | File | `/admin/product.php` | High
45 | File | `/admin/team_update.php` | High
46 | File | `/admin/updatecomplaint.php` | High
47 | File | `/admin/update_s1.php` | High
48 | File | `/admin/update_s3.php` | High
49 | File | `/admin/update_s4.php` | High
50 | File | `/admin/update_s8.php` | High
51 | File | `/admin/users.php` | High
52 | File | `/admin/user_save.php` | High
53 | File | `/admin/user_update.php` | High
54 | File | `/admin/visitors-form.php` | High
55 | File | `/admin_paylog.php` | High
56 | File | `/ajax.php?action=delete_member` | High
57 | File | `/ajax.php?action=delete_user` | High
58 | File | `/ajax.php?action=save_deductions` | High
59 | File | `/ajax.php?Ajax=GetModal_MQTTEdit` | High
60 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
61 | File | `/Android/data/com.myairtelapp/files/` | High
62 | File | `/api/File/downloadFile` | High
63 | File | `/api/Image/WithPath` | High
64 | File | `/api/proxy` | Medium
65 | File | `/attendancelist.php` | High
66 | File | `/bin/mail` | Medium
67 | File | `/boafrm/formDMZ` | High
68 | File | `/boafrm/formFilter` | High
69 | File | `/boafrm/formMapDel` | High
70 | File | `/boafrm/formNtp` | High
71 | File | `/boafrm/formRoute` | High
72 | File | `/boafrm/formSaveConfig` | High
73 | File | `/boafrm/formWirelessTbl` | High
74 | File | `/BRS_top.html` | High
75 | File | `/business/common/sms/sendsms.jsp` | High
76 | File | `/categoryvalue.php` | High
77 | ... | ... | ...

There are 678 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
* https://search.censys.io/hosts/52.243.66.182
* https://search.censys.io/hosts/54.38.242.131
* https://search.censys.io/hosts/54.202.46.22
* https://search.censys.io/hosts/65.49.204.212
* https://search.censys.io/hosts/88.208.3.157
* https://search.censys.io/hosts/89.73.53.34
* https://search.censys.io/hosts/94.102.49.16
* https://search.censys.io/hosts/94.102.49.106
* https://search.censys.io/hosts/124.156.166.6
* https://search.censys.io/hosts/136.144.243.50
* https://search.censys.io/hosts/139.180.217.224
* https://search.censys.io/hosts/142.93.226.220
* https://search.censys.io/hosts/146.190.109.188
* https://search.censys.io/hosts/146.190.241.166
* https://search.censys.io/hosts/149.248.79.215
* https://search.censys.io/hosts/156.244.1.13
* https://search.censys.io/hosts/156.244.13.120
* https://search.censys.io/hosts/161.97.116.56
* https://search.censys.io/hosts/167.88.160.211
* https://search.censys.io/hosts/167.88.170.172
* https://search.censys.io/hosts/185.196.10.245
* https://search.censys.io/hosts/194.26.192.127
* https://search.censys.io/hosts/207.154.192.30
* https://search.censys.io/hosts/207.180.253.60
* https://search.censys.io/hosts/210.2.169.231
* https://search.censys.io/hosts/213.32.106.89
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
