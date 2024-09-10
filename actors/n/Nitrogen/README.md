# Nitrogen - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nitrogen](https://vuldb.com/?actor.nitrogen). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nitrogen](https://vuldb.com/?actor.nitrogen)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nitrogen:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [PL](https://vuldb.com/?country.pl)
* ...

There are 3 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nitrogen.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.227.196.140](https://vuldb.com/?ip.23.227.196.140) | 23-227-196-140.static.hvvc.us | - | High
2 | [23.227.203.241](https://vuldb.com/?ip.23.227.203.241) | 23-227-203-241.static.hvvc.us | - | High
3 | [45.12.253.137](https://vuldb.com/?ip.45.12.253.137) | - | - | High
4 | [45.61.128.133](https://vuldb.com/?ip.45.61.128.133) | - | - | High
5 | [45.66.230.215](https://vuldb.com/?ip.45.66.230.215) | - | - | High
6 | [45.66.230.216](https://vuldb.com/?ip.45.66.230.216) | - | - | High
7 | [45.66.230.237](https://vuldb.com/?ip.45.66.230.237) | - | - | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nitrogen_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nitrogen. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/admin.php` | High
2 | File | `/admin/ajax.php` | High
3 | File | `/admin/ajax.php?action=save_window` | High
4 | File | `/admin/delete.php` | High
5 | File | `/admin/read.php?mudi=announContent` | High
6 | File | `/admin/sales/view_details.php` | High
7 | File | `/admin/view_order.php` | High
8 | File | `/bl-plugins/backup/plugin.php` | High
9 | File | `/cgi-bin/nightled.cgi` | High
10 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
11 | File | `/config/list` | Medium
12 | File | `/controller/Index.php` | High
13 | File | `/etc/master.passwd` | High
14 | File | `/etc/passwd` | Medium
15 | File | `/gasmark/editbrand.php` | High
16 | File | `/goform/WifiBasicSet` | High
17 | File | `/inxedu/demo_inxedu_open/src/main/resources/mybatis/inxedu/website/WebsiteImagesMapper.xml` | High
18 | File | `/iwgallery/pictures/details.asp` | High
19 | File | `/login.php` | Medium
20 | File | `/medianet/mail.aspx` | High
21 | File | `/news-portal-script/information.php` | High
22 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
23 | File | `/pages/faculty_sched.php` | High
24 | File | `/php_action/createProduct.php` | High
25 | File | `/reviewer/system/system/admins/manage/users/user-update.php` | High
26 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
27 | File | `/secure/admin/RestoreDefaults.jspa` | High
28 | File | `/showfile.php` | High
29 | File | `/textpattern/index.php` | High
30 | File | `/wmiwizard.jsp` | High
31 | File | `/wp-admin/options-general.php` | High
32 | File | `account.asp` | Medium
33 | File | `accounts/inc/include.php` | High
34 | File | `acrotxt.php` | Medium
35 | File | `addpost_newpoll.php` | High
36 | File | `admin.color.php` | High
37 | File | `admin.cropcanvas.php` | High
38 | File | `admin.joomlaradiov5.php` | High
39 | File | `admin.php` | Medium
40 | File | `admin.php/index/upload because app/common/service/UploadService.php` | High
41 | File | `admin/?page=user/manage_user` | High
42 | File | `admin/addons/archive/archive.php` | High
43 | File | `admin/handlers.php` | High
44 | File | `admin/page.php` | High
45 | File | `admin/versions.html` | High
46 | File | `adminAttachments.php` | High
47 | File | `adminBoards.php` | High
48 | File | `admincp/auth/secure.php` | High
49 | File | `admindocumentworker.jsp` | High
50 | File | `administrator/components/com_media/helpers/media.php` | High
51 | File | `adminSmileys.php` | High
52 | File | `akocomments.php` | High
53 | File | `album_portal.php` | High
54 | ... | ... | ...

There are 468 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Nitrogen%202023-07.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
