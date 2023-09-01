# Truebot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Truebot](https://vuldb.com/?actor.truebot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.truebot](https://vuldb.com/?actor.truebot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Truebot:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 24 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Truebot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.188.86.18](https://vuldb.com/?ip.5.188.86.18) | - | - | High
2 | [5.188.206.78](https://vuldb.com/?ip.5.188.206.78) | - | - | High
3 | [45.182.189.71](https://vuldb.com/?ip.45.182.189.71) | - | - | High
4 | [45.182.189.91](https://vuldb.com/?ip.45.182.189.91) | - | - | High
5 | [45.182.189.103](https://vuldb.com/?ip.45.182.189.103) | - | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Truebot_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Truebot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `//WEB-INF` | Medium
3 | File | `/about.php` | Medium
4 | File | `/admin.php/update/getFile.html` | High
5 | File | `/admin/api/admin/articles/` | High
6 | File | `/admin/cashadvance_row.php` | High
7 | File | `/admin/maintenance/view_designation.php` | High
8 | File | `/admin/sys_sql_query.php` | High
9 | File | `/admin/userprofile.php` | High
10 | File | `/adms/admin/?page=vehicles/sell_vehicle` | High
11 | File | `/adms/admin/?page=vehicles/view_transaction` | High
12 | File | `/APR/login.php` | High
13 | File | `/bin/httpd` | Medium
14 | File | `/cgi-bin/wapopen` | High
15 | File | `/company/store` | High
16 | File | `/Controller/Ajaxfileupload.ashx` | High
17 | File | `/dev/block/mmcblk0rpmb` | High
18 | File | `/etc/passwd` | Medium
19 | File | `/feeds/post/publish` | High
20 | File | `/forum/away.php` | High
21 | File | `/fos/admin/ajax.php?action=login` | High
22 | File | `/fos/admin/index.php?page=menu` | High
23 | File | `/h/` | Low
24 | File | `/home/masterConsole` | High
25 | File | `/home/sendBroadcast` | High
26 | File | `/inc/jquery/uploadify/uploadify.php` | High
27 | File | `/index.php?app=main&func=passport&action=login` | High
28 | File | `/index.php?page=category_list` | High
29 | File | `/jobinfo/` | Medium
30 | File | `/jsoa/hntdCustomDesktopActionContent` | High
31 | File | `/Moosikay/order.php` | High
32 | File | `/mygym/admin/index.php?view_exercises` | High
33 | File | `/opac/Actions.php?a=login` | High
34 | File | `/php-opos/index.php` | High
35 | File | `/PreviewHandler.ashx` | High
36 | File | `/proxy` | Low
37 | File | `/public/launchNewWindow.jsp` | High
38 | File | `/recipe-result` | High
39 | File | `/reports/rwservlet` | High
40 | File | `/reservation/add_message.php` | High
41 | File | `/Service/ImageStationDataService.asmx` | High
42 | File | `/student/bookdetails.php` | High
43 | File | `/uncpath/` | Medium
44 | File | `/uploads/exam_question/` | High
45 | File | `/user/ticket/create` | High
46 | File | `/user/updatePwd` | High
47 | File | `/var/lib/docker/<remapping>` | High
48 | File | `/wireless/security.asp` | High
49 | File | `/wp-admin/admin-ajax.php` | High
50 | File | `01article.php` | High
51 | File | `a-forms.php` | Medium
52 | File | `actionphp/download.File.php` | High
53 | File | `activenews_view.asp` | High
54 | File | `adclick.php` | Medium
55 | File | `admin.a6mambocredits.php` | High
56 | File | `admin.cropcanvas.php` | High
57 | File | `admin/abc.php` | High
58 | File | `admin/admin.php?action=users&mode=info&user=2` | High
59 | ... | ... | ...

There are 514 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/breaking-the-silence-recent-truebot-activity/
* https://github.com/Cisco-Talos/IOCs/blob/main/2022/12/breaking_the_silence_truebot_activity.txt
* https://thedfirreport.com/2023/06/12/a-truly-graceful-wipe-out/
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-187a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
