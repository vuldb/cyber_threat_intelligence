# Rhysida - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Rhysida](https://vuldb.com/?actor.rhysida). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.rhysida](https://vuldb.com/?actor.rhysida)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Rhysida:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Rhysida.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.39.222.67](https://vuldb.com/?ip.5.39.222.67) | - | - | High
2 | [5.161.150.40](https://vuldb.com/?ip.5.161.150.40) | static.40.150.161.5.clients.your-server.de | - | High
3 | [5.161.252.127](https://vuldb.com/?ip.5.161.252.127) | static.127.252.161.5.clients.your-server.de | - | High
4 | [5.226.141.196](https://vuldb.com/?ip.5.226.141.196) | 196.141.226.5.baremetal.zare.com | - | High
5 | [5.226.141.198](https://vuldb.com/?ip.5.226.141.198) | 198.141.226.5.baremetal.zare.com | - | High
6 | [5.255.99.59](https://vuldb.com/?ip.5.255.99.59) | - | - | High
7 | [5.255.100.101](https://vuldb.com/?ip.5.255.100.101) | - | - | High
8 | [5.255.101.30](https://vuldb.com/?ip.5.255.101.30) | - | - | High
9 | [5.255.103.7](https://vuldb.com/?ip.5.255.103.7) | - | - | High
10 | [5.255.103.142](https://vuldb.com/?ip.5.255.103.142) | - | - | High
11 | [5.255.104.237](https://vuldb.com/?ip.5.255.104.237) | - | - | High
12 | [15.222.251.55](https://vuldb.com/?ip.15.222.251.55) | ec2-15-222-251-55.ca-central-1.compute.amazonaws.com | - | Medium
13 | [23.19.58.57](https://vuldb.com/?ip.23.19.58.57) | - | - | High
14 | [23.108.57.83](https://vuldb.com/?ip.23.108.57.83) | - | - | High
15 | [23.227.198.234](https://vuldb.com/?ip.23.227.198.234) | 23-227-198-234.static.hvvc.us | - | High
16 | [31.57.243.18](https://vuldb.com/?ip.31.57.243.18) | - | - | High
17 | [35.182.112.88](https://vuldb.com/?ip.35.182.112.88) | ec2-35-182-112-88.ca-central-1.compute.amazonaws.com | - | Medium
18 | [37.59.132.163](https://vuldb.com/?ip.37.59.132.163) | ip163.ip-37-59-132.eu | - | High
19 | [37.59.205.5](https://vuldb.com/?ip.37.59.205.5) | ip5.ip-37-59-205.eu | - | High
20 | [38.132.122.156](https://vuldb.com/?ip.38.132.122.156) | - | - | High
21 | [38.146.25.131](https://vuldb.com/?ip.38.146.25.131) | - | - | High
22 | [41.255.166.66](https://vuldb.com/?ip.41.255.166.66) | - | - | High
23 | [45.61.136.48](https://vuldb.com/?ip.45.61.136.48) | - | - | High
24 | [45.61.136.85](https://vuldb.com/?ip.45.61.136.85) | - | - | High
25 | [45.61.136.244](https://vuldb.com/?ip.45.61.136.244) | - | - | High
26 | ... | ... | ... | ...

There are 99 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Rhysida_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Rhysida. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//proc/kcore` | Medium
2 | File | `/?explorer/index/zip` | High
3 | File | `/add-subadmin.php` | High
4 | File | `/add_new_invoice.php` | High
5 | File | `/add_user.php` | High
6 | File | `/admin/?page=zone` | High
7 | File | `/admin/about-us.php` | High
8 | File | `/admin/aboutus.php` | High
9 | File | `/admin/action/delete-vaccine.php` | High
10 | File | `/admin/actions/check-attendance.php` | High
11 | File | `/admin/add-table.php` | High
12 | File | `/admin/admin_running.php` | High
13 | File | `/Admin/akun_edit.php` | High
14 | File | `/admin/apply.php` | High
15 | File | `/admin/changeimage.php` | High
16 | File | `/Admin/changepassword.php` | High
17 | File | `/admin/completed-requests.php` | High
18 | File | `/admin/content/editor` | High
19 | File | `/admin/create-package.php` | High
20 | File | `/admin/delete_s6.php` | High
21 | File | `/admin/delete_user.php` | High
22 | File | `/admin/doAdminAction.php?act=addCate` | High
23 | File | `/admin/edit-art-product-detail.php?editid=2` | High
24 | File | `/admin/edit-brand.php` | High
25 | File | `/admin/edit-post.php` | High
26 | File | `/admin/edit-user.php` | High
27 | File | `/admin/edit_room.php` | High
28 | File | `/admin/includes/edit_post.php` | High
29 | File | `/admin/index.php?page=user-profile` | High
30 | File | `/admin/index2.html` | High
31 | File | `/Admin/login.php` | High
32 | File | `/admin/login.php` | High
33 | File | `/admin/mechanics/manage_mechanic.php` | High
34 | File | `/admin/modules/room/index.php` | High
35 | File | `/admin/profile.php` | High
36 | File | `/Admin/Proses_Edit_Akun.php` | High
37 | File | `/admin/robot.php` | High
38 | File | `/admin/search-invoices.php` | High
39 | File | `/admin/tags/save` | High
40 | File | `/admin/twitter.php` | High
41 | File | `/admin/user-bookings.php` | High
42 | File | `/admin/user/index.php?view=edit` | High
43 | File | `/admin/yesterday-reg-users.php` | High
44 | File | `/adminapi/system/file/openfile` | High
45 | File | `/administrator/addcategory.php` | High
46 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
47 | File | `/ajax.php?action=save_payroll` | High
48 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
49 | File | `/alphaware/summary.php` | High
50 | File | `/api/File/downloadFile` | High
51 | File | `/api/settings` | High
52 | File | `/api/sys/login` | High
53 | File | `/api/wizard/getCapability` | High
54 | File | `/app/api/controller/collect.php` | High
55 | File | `/app/api/v1/openvpn.py` | High
56 | File | `/app/controller/Api.php` | High
57 | File | `/app/index/controller/Common.php` | High
58 | File | `/app/register.php?action=reg` | High
59 | File | `/app/sys1.php` | High
60 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
61 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
62 | File | `/applications/nexus/modules/front/store/store.php` | High
63 | File | `/assetsGroupReport/assetsService.j%73p` | High
64 | File | `/auth.asp` | Medium
65 | File | `/backend/doc/his_doc_update-account.php` | High
66 | File | `/bin/httpd` | Medium
67 | File | `/bitrix/admin/ldap_server_edit.php` | High
68 | File | `/biurl_grou` | Medium
69 | File | `/boaform/formSysCmd` | High
70 | File | `/boafrm/formDMZ` | High
71 | File | `/boafrm/formTmultiAP` | High
72 | File | `/borrow.php` | Medium
73 | File | `/browse.php` | Medium
74 | File | `/cgi-bin/apkg_mgr.cgi` | High
75 | File | `/cgi-bin/cstecgi.cgi` | High
76 | ... | ... | ...

There are 664 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/blackorbird/APT_REPORT/blob/master/cybercrime/2024/Rhysida202410-c2.pdf
* https://github.com/prodaft/malware-ioc/tree/master/ViceSociety
* https://research.checkpoint.com/2023/the-rhysida-ransomware-activity-analysis-and-ties-to-vice-society/
* https://search.censys.io/hosts/5.161.252.127
* https://search.censys.io/hosts/37.59.205.5
* https://search.censys.io/hosts/51.68.216.13
* https://search.censys.io/hosts/51.89.137.8
* https://search.censys.io/hosts/57.128.166.214
* https://search.censys.io/hosts/65.108.49.36
* https://search.censys.io/hosts/78.47.60.67
* https://search.censys.io/hosts/85.239.53.94
* https://search.censys.io/hosts/109.176.207.22
* https://search.censys.io/hosts/139.64.133.194
* https://search.censys.io/hosts/159.100.6.103
* https://search.censys.io/hosts/173.46.80.206
* https://search.censys.io/hosts/185.216.144.51
* https://search.censys.io/hosts/216.74.123.41
* https://threatfox.abuse.ch
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-319a
* https://www.guidepointsecurity.com/blog/update-from-the-ransomware-trenches/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
