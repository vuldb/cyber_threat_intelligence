# APT-C-36 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT-C-36](https://vuldb.com/?actor.apt-c-36). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt-c-36](https://vuldb.com/?actor.apt-c-36)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT-C-36:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 25 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT-C-36.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [46.246.12.6](https://vuldb.com/?ip.46.246.12.6) | c-46-246-12-6.ip4.frootvpn.com | - | High
2 | [46.246.86.3](https://vuldb.com/?ip.46.246.86.3) | c-46-246-86-3.ip4.frootvpn.com | - | High
3 | [128.90.106.22](https://vuldb.com/?ip.128.90.106.22) | undefined.hostname.localhost | - | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT-C-36_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT-C-36. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `//WEB-INF` | Medium
3 | File | `/about.php` | Medium
4 | File | `/admin.php/update/getFile.html` | High
5 | File | `/admin/api/admin/articles/` | High
6 | File | `/admin/cashadvance_row.php` | High
7 | File | `/admin/maintenance/view_designation.php` | High
8 | File | `/admin/userprofile.php` | High
9 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
10 | File | `/adms/admin/?page=vehicles/view_transaction` | High
11 | File | `/APR/login.php` | High
12 | File | `/bin/httpd` | Medium
13 | File | `/cgi-bin/wapopen` | High
14 | File | `/dev/block/mmcblk0rpmb` | High
15 | File | `/DocSystem/Repos/getReposAllUsers.do` | High
16 | File | `/face-recognition-php/facepay-master/camera.php` | High
17 | File | `/feeds/post/publish` | High
18 | File | `/forum/away.php` | High
19 | File | `/fos/admin/ajax.php?action=login` | High
20 | File | `/fos/admin/index.php?page=menu` | High
21 | File | `/h/` | Low
22 | File | `/home/masterConsole` | High
23 | File | `/home/sendBroadcast` | High
24 | File | `/hrm/employeeadd.php` | High
25 | File | `/hrm/employeeview.php` | High
26 | File | `/inc/jquery/uploadify/uploadify.php` | High
27 | File | `/index.php?app=main&func=passport&action=login` | High
28 | File | `/index.php?page=category_list` | High
29 | File | `/jobinfo/` | Medium
30 | File | `/jsoa/hntdCustomDesktopActionContent` | High
31 | File | `/lookin/info` | Medium
32 | File | `/Moosikay/order.php` | High
33 | File | `/mygym/admin/index.php?view_exercises` | High
34 | File | `/opac/Actions.php?a=login` | High
35 | File | `/out.php` | Medium
36 | File | `/php-opos/index.php` | High
37 | File | `/PreviewHandler.ashx` | High
38 | File | `/proxy` | Low
39 | File | `/public/launchNewWindow.jsp` | High
40 | File | `/Redcock-Farm/farm/category.php` | High
41 | File | `/reports/rwservlet` | High
42 | File | `/reservation/add_message.php` | High
43 | File | `/spip.php` | Medium
44 | File | `/student/bookdetails.php` | High
45 | File | `/uncpath/` | Medium
46 | File | `/uploads/exam_question/` | High
47 | File | `/user/updatePwd` | High
48 | File | `/var/lib/docker/<remapping>` | High
49 | File | `/wireless/security.asp` | High
50 | File | `/wp-admin/admin-ajax.php` | High
51 | File | `01article.php` | High
52 | File | `a-forms.php` | Medium
53 | File | `AbstractScheduleJob.java` | High
54 | File | `actionphp/download.File.php` | High
55 | File | `activenews_view.asp` | High
56 | File | `adclick.php` | Medium
57 | File | `admin.a6mambocredits.php` | High
58 | File | `admin.cropcanvas.php` | High
59 | File | `admin.php` | Medium
60 | File | `admin/abc.php` | High
61 | ... | ... | ...

There are 530 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blogs.blackberry.com/en/2023/02/blind-eagle-apt-c-36-targets-colombia
* https://web.archive.org/web/20190625182633if_/https://ti.360.net/blog/articles/apt-c-36-continuous-attacks-targeting-colombian-government-institutions-and-corporations-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
