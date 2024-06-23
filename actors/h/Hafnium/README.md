# Hafnium - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Hafnium](https://vuldb.com/?actor.hafnium). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.hafnium](https://vuldb.com/?actor.hafnium)

## Campaigns

The following _campaigns_ are known and can be associated with Hafnium:

* Hafnium

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Hafnium:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Hafnium.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [172.105.174.117](https://vuldb.com/?ip.172.105.174.117) | 172-105-174-117.ip.linodeusercontent.com | Hafnium | High
2 | [182.239.123.241](https://vuldb.com/?ip.182.239.123.241) | 182.239.123.241.hk.chinamobile.com | Hafnium | High
3 | [182.239.124.180](https://vuldb.com/?ip.182.239.124.180) | 182.239.124.180.hk.chinamobile.com | Hafnium | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Hafnium_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Hafnium. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/.env` | Low
3 | File | `/admin/students/manage.php` | High
4 | File | `/ajax/networking/get_netcfg.php` | High
5 | File | `/auth/session` | High
6 | File | `/backups/` | Medium
7 | File | `/bcms/admin/?page=user/list` | High
8 | File | `/bin/httpd` | Medium
9 | File | `/cardo/api` | Medium
10 | File | `/CMD_ACCOUNT_ADMIN` | High
11 | File | `/ecshop/admin/template.php` | High
12 | File | `/forum/PostPrivateMessage` | High
13 | File | `/fos/admin/ajax.php?action=login` | High
14 | File | `/fos/admin/index.php?page=menu` | High
15 | File | `/home/cavesConsole` | High
16 | File | `/home/kickPlayer` | High
17 | File | `/home/masterConsole` | High
18 | File | `/home/sendBroadcast` | High
19 | File | `/oews/classes/Master.php?f=update_cart` | High
20 | File | `/param.file.tgz` | High
21 | File | `/picturesPreview` | High
22 | File | `/royal_event/companyprofile.php` | High
23 | File | `/royal_event/userregister.php` | High
24 | File | `/user/s.php` | Medium
25 | File | `/user/updatePwd` | High
26 | File | `/wireless/basic.asp` | High
27 | File | `/wireless/guestnetwork.asp` | High
28 | File | `/wireless/security.asp` | High
29 | File | `/zoo/admin/public_html/view_accounts?type=zookeeper` | High
30 | File | `01article.php` | High
31 | File | `action.php` | Medium
32 | File | `add-locker-form.php` | High
33 | File | `add.php` | Low
34 | File | `add_contestant.php` | High
35 | File | `admin.php/index/upload because app/common/service/UploadService.php` | High
36 | File | `admin/?page=orders/view_order` | High
37 | File | `admin/?page=students` | High
38 | File | `admin/abc.php` | High
39 | File | `admin/add_payment.php` | High
40 | File | `admin/approve_user.php` | High
41 | File | `admin/booking_report.php` | High
42 | File | `admin/disapprove_user.php` | High
43 | File | `admin/expense_report.php` | High
44 | File | `admin/forget_password.php` | High
45 | File | `admin/login.php` | High
46 | File | `admin/manage-ticket.php` | High
47 | File | `admin/manage_user.php` | High
48 | File | `admin/page-login.php` | High
49 | File | `admin/panels/entry/admin.entry.list.php` | High
50 | File | `admin/panels/uploader/admin.uploader.php` | High
51 | File | `admin/practice_pdf.php` | High
52 | File | `administrator/components/com_joomgallery/views/config/tmpl/default.php` | High
53 | File | `admin_class.php` | High
54 | File | `agent/listener/templates/tail.html` | High
55 | File | `announce.php` | Medium
56 | File | `Ap4BitStream.cpp` | High
57 | File | `Ap4ByteStream.cpp` | High
58 | File | `Ap4LinearReader.cpp` | High
59 | File | `Ap4Sample.h` | Medium
60 | File | `APDE/src/main/java/com/calsignlabs/apde/build/dag/CopyBuildTask.java` | High
61 | ... | ... | ...

There are 534 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://twitter.com/KyleHanslovan/status/1370077442984001537
* https://twitter.com/TheDFIRReport/status/1370079472033136640

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
