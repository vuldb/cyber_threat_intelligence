# TA866 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [TA866](https://vuldb.com/?actor.ta866). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.ta866](https://vuldb.com/?actor.ta866)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TA866:

* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TA866.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.192.63.13](https://vuldb.com/?ip.5.192.63.13) | - | - | High
2 | [5.192.63.126](https://vuldb.com/?ip.5.192.63.126) | - | - | High
3 | [6.151.25.15](https://vuldb.com/?ip.6.151.25.15) | - | - | High
4 | [8.210.10.62](https://vuldb.com/?ip.8.210.10.62) | - | - | High
5 | [12.113.6.27](https://vuldb.com/?ip.12.113.6.27) | - | - | High
6 | [15.225.200.157](https://vuldb.com/?ip.15.225.200.157) | - | - | High
7 | [18.225.200.157](https://vuldb.com/?ip.18.225.200.157) | ec2-18-225-200-157.us-east-2.compute.amazonaws.com | - | Medium
8 | [21.113.106.27](https://vuldb.com/?ip.21.113.106.27) | - | - | High
9 | ... | ... | ... | ...

There are 33 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TA866_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-35, CWE-37 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TA866. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/Admin/akun_edit.php` | High
2 | File | `/admin/api/theme-edit/` | High
3 | File | `/Admin/changepassword.php` | High
4 | File | `/admin/edit_area.php` | High
5 | File | `/admin/edit_page.php?link_id=1` | High
6 | File | `/admin/fetch_product_details.php` | High
7 | File | `/admin/filemanager/connector/` | High
8 | File | `/admin/index2.html` | High
9 | File | `/admin/list_onlineuser.php` | High
10 | File | `/admin/maintenance/view_designation.php` | High
11 | File | `/admin/products/manage_product.php` | High
12 | File | `/admin/sys/user/list` | High
13 | File | `/ajax/getBasicInfo.php` | High
14 | File | `/api/dept` | Medium
15 | File | `/api/RecordingList/DownloadRecord?file=` | High
16 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
17 | File | `/api/upload` | Medium
18 | File | `/apply.cgi` | Medium
19 | File | `/author/list?limit=10&offset=0&order=desc` | High
20 | File | `/catalog/all-products` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
23 | File | `/cgi-bin/login_action.cgi` | High
24 | File | `/classes/Master.php` | High
25 | File | `/classes/Master.php?f=delete_category` | High
26 | File | `/control/player?center&eventlist&pda&dummy_for_reload=1736177631&p_evt` | High
27 | File | `/cwc/login` | Medium
28 | File | `/edit_user.php` | High
29 | File | `/endpoint/delete.php` | High
30 | File | `/etc/gsissh/sshd_config` | High
31 | File | `/face-recognition-php/facepay-master/camera.php` | High
32 | File | `/forgot.php` | Medium
33 | File | `/forum/away.php` | High
34 | File | `/forum/PostPrivateMessage` | High
35 | File | `/goform/execCommand` | High
36 | File | `/goform/formDeviceReboot` | High
37 | File | `/goform/saveParentControlInfo` | High
38 | File | `/goform/SetNetControlList` | High
39 | File | `/home/masterConsole` | High
40 | File | `/hrm/employeeadd.php` | High
41 | File | `/hrm/employeeview.php` | High
42 | File | `/index.php/dashboard/save` | High
43 | File | `/intern/controller.php` | High
44 | File | `/jeecg-boot/jmreport/show` | High
45 | File | `/labvantage/rc?command=page` | High
46 | File | `/log/download.php` | High
47 | File | `/main/java/com/ujcms/cms/ext/web/backendapi/WebFileUploadController.java` | High
48 | File | `/main/webservices/additional_webservices.php` | High
49 | File | `/manage_invoice.php` | High
50 | File | `/members/poster.php` | High
51 | ... | ... | ...

There are 444 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/highlighting-ta866-asylum-ambuscade/
* https://github.com/Cisco-Talos/IOCs/blob/main/2024/10/highlighting-ta866-asylum-ambuscade.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
