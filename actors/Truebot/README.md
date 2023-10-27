# Truebot - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Truebot](https://vuldb.com/?actor.truebot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.truebot](https://vuldb.com/?actor.truebot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Truebot:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 19 more country items available. Please use our online service to access the data.

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
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Truebot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//WEB-INF` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/update/getFile.html` | High
4 | File | `/admin/cashadvance_row.php` | High
5 | File | `/admin/maintenance/view_designation.php` | High
6 | File | `/admin/save.php` | High
7 | File | `/admin/sys_sql_query.php` | High
8 | File | `/admin/userprofile.php` | High
9 | File | `/api/baskets/{name}` | High
10 | File | `/api/download` | High
11 | File | `/api/v1/terminal/sessions/?limit=1` | High
12 | File | `/APR/login.php` | High
13 | File | `/bitrix/admin/ldap_server_edit.php` | High
14 | File | `/category.php` | High
15 | File | `/categorypage.php` | High
16 | File | `/cgi-bin/luci/api/wireless` | High
17 | File | `/cgi-bin/vitogate.cgi` | High
18 | File | `/cgi-bin/wapopen` | High
19 | File | `/company/store` | High
20 | File | `/Content/Template/root/reverse-shell.aspx` | High
21 | File | `/Controller/Ajaxfileupload.ashx` | High
22 | File | `/core/conditions/AbstractWrapper.java` | High
23 | File | `/etc/passwd` | Medium
24 | File | `/fcgi/scrut_fcgi.fcgi` | High
25 | File | `/feeds/post/publish` | High
26 | File | `/forum/away.php` | High
27 | File | `/h/` | Low
28 | File | `/HNAP1` | Low
29 | File | `/inc/jquery/uploadify/uploadify.php` | High
30 | File | `/index.php?app=main&func=passport&action=login` | High
31 | File | `/index.php?page=category_list` | High
32 | File | `/jeecg-boot/sys/common/upload` | High
33 | File | `/jobinfo/` | Medium
34 | File | `/Moosikay/order.php` | High
35 | File | `/opac/Actions.php?a=login` | High
36 | File | `/PreviewHandler.ashx` | High
37 | File | `/public/launchNewWindow.jsp` | High
38 | File | `/recipe-result` | High
39 | File | `/register.do` | Medium
40 | File | `/reservation/add_message.php` | High
41 | File | `/RPS2019Service/status.html` | High
42 | File | `/Service/ImageStationDataService.asmx` | High
43 | File | `/sicweb-ajax/tmproot/` | High
44 | File | `/spip.php` | Medium
45 | File | `/student/bookdetails.php` | High
46 | File | `/SystemManage/User/GetGridJson?_search=false&nd=1680855479750&rows=50&page=1&sidx=F_CreatorTime+desc&sord=asc` | High
47 | File | `/uploads/exam_question/` | High
48 | File | `/user/ticket/create` | High
49 | File | `/user/updatePwd` | High
50 | File | `/UserSelfServiceSettings.jsp` | High
51 | File | `/var/lib/docker/<remapping>` | High
52 | File | `/wp-admin/admin-ajax.php` | High
53 | File | `/xxl-job-admin/user/add` | High
54 | File | `a-forms.php` | Medium
55 | ... | ... | ...

There are 478 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
