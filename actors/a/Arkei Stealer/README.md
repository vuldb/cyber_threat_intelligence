# Arkei Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Arkei Stealer](https://vuldb.com/?actor.arkei_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.arkei_stealer](https://vuldb.com/?actor.arkei_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Arkei Stealer:

* [US](https://vuldb.com/?country.us)
* [PL](https://vuldb.com/?country.pl)
* [LU](https://vuldb.com/?country.lu)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Arkei Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [45.11.229.188](https://vuldb.com/?ip.45.11.229.188) | 188.229.11.45.in-addr.arpa | - | High
2 | [91.92.250.149](https://vuldb.com/?ip.91.92.250.149) | - | - | High
3 | [93.174.93.178](https://vuldb.com/?ip.93.174.93.178) | - | - | High
4 | ... | ... | ... | ...

There are 4 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Arkei Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Arkei Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/$({curl` | Medium
2 | File | `/?g=log_import_save` | High
3 | File | `/action/ipcamRecordPost` | High
4 | File | `/ad-list` | Medium
5 | File | `/admin/ajax.php` | High
6 | File | `/admin/ajax.php?action=delete_window` | High
7 | File | `/admin/client_user` | High
8 | File | `/admin/communitymanagement.php` | High
9 | File | `/admin/generalsettings.php` | High
10 | File | `/admin/index.php?page=categories` | High
11 | File | `/admin/inquiries/view_details.php` | High
12 | File | `/admin/maintenance/manage_category.php` | High
13 | File | `/admin/maintenance/view_designation.php` | High
14 | File | `/admin/mechanics/manage_mechanic.php` | High
15 | File | `/admin/payment.php` | High
16 | File | `/admin/service_requests/manage_inventory.php` | High
17 | File | `/admin/syslog` | High
18 | File | `/administrator/components/table_manager/` | High
19 | File | `/Api/ASF` | Medium
20 | File | `/api/public/signup` | High
21 | File | `/appConfig/userDB.json` | High
22 | File | `/aqpg/users/login.php` | High
23 | File | `/bsms_ci/index.php/user/edit_user/` | High
24 | File | `/cancel.php` | Medium
25 | File | `/catcompany.php` | High
26 | File | `/cgi-bin/` | Medium
27 | File | `/cgi-bin/luci;stok=/locale` | High
28 | File | `/classes/Login.php` | High
29 | File | `/classes/Master.php` | High
30 | File | `/classes/Master.php?f=delete_category` | High
31 | File | `/classes/Users.php` | High
32 | File | `/common/run_cross_report.php` | High
33 | File | `/dashboard/contact` | High
34 | File | `/dbhcms/ext/news/ext.news.be.php` | High
35 | File | `/dcim/sites/add/` | High
36 | File | `/Default/Bd` | Medium
37 | File | `/etc/passwd` | Medium
38 | File | `/event/admin/?page=user/list` | High
39 | File | `/file-manager/upload.php` | High
40 | File | `/filemanager/upload/drop` | High
41 | File | `/getcfg.php` | Medium
42 | File | `/goform/WifiBasicSet` | High
43 | File | `/hrm/employeeview.php` | High
44 | File | `/inc/topBarNav.php` | High
45 | File | `/index.php` | Medium
46 | File | `/index.php?case=table&act=add&table=archive&admin_dir=admin` | High
47 | File | `/labvantage/rc?command=page&page=SampleHistoricalList&_iframename=list&__crc=crc_1701669816260` | High
48 | File | `/login.php` | Medium
49 | File | `/manage_laundry.php` | High
50 | File | `/members/view_member.php` | High
51 | ... | ... | ...

There are 443 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/a536276d-8b87-4b02-bed5-ca8135a0dbce/
* https://threatfox.abuse.ch
* https://tria.ge/220316-w6lh3sffe3
* https://www.filescan.io/uploads/652746408d16e62970c20643/reports/933c92b2-db25-4cd7-8e05-1595ed51992b/ioc

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
