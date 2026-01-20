# BlackCat - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [BlackCat](https://vuldb.com/?actor.blackcat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.blackcat](https://vuldb.com/?actor.blackcat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with BlackCat:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of BlackCat.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.199.168.24](https://vuldb.com/?ip.5.199.168.24) | - | - | High
2 | [5.199.168.233](https://vuldb.com/?ip.5.199.168.233) | - | - | High
3 | [20.46.245.56](https://vuldb.com/?ip.20.46.245.56) | - | - | High
4 | [23.106.223.97](https://vuldb.com/?ip.23.106.223.97) | - | - | High
5 | [37.120.238.58](https://vuldb.com/?ip.37.120.238.58) | - | - | High
6 | [45.32.141.168](https://vuldb.com/?ip.45.32.141.168) | 45.32.141.168.vultrusercontent.com | - | Medium
7 | [45.77.0.92](https://vuldb.com/?ip.45.77.0.92) | 45.77.0.92.vultrusercontent.com | - | Medium
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _BlackCat_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-29, CWE-37 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by BlackCat. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/acms/admin/cargo_types/manage_cargo_type.php` | High
3 | File | `/admin/ajax.php` | High
4 | File | `/admin/ajax.php?action=confirm_order` | High
5 | File | `/admin/ajax.php?action=delete_user` | High
6 | File | `/admin/ajax.php?action=delete_window` | High
7 | File | `/admin/ajax.php?action=save_window` | High
8 | File | `/admin/ajax/avatar.php` | High
9 | File | `/admin/article/article-add.php` | High
10 | File | `/admin/edit_subject.php` | High
11 | File | `/admin/index.php` | High
12 | File | `/admin/index/index.html#/admin/mall.goods/index.html` | High
13 | File | `/admin/list_onlineuser.php` | High
14 | File | `/admin/login.php` | High
15 | File | `/admin/maintenance/view_designation.php` | High
16 | File | `/admin/media_folders` | High
17 | File | `/admin/options` | High
18 | File | `/admin/pages/update_go.php` | High
19 | File | `/admin/report/index.php` | High
20 | File | `/admin/services/manage_service.php` | High
21 | File | `/admin/settings/` | High
22 | File | `/admin/show.php` | High
23 | File | `/admin/students/update_status.php` | High
24 | File | `/admin/subject.php` | High
25 | File | `/admin/user/manage_user.php` | High
26 | File | `/ample/app/ajax/member_data.php` | High
27 | File | `/app/index/controller/Common.php` | High
28 | File | `/apply.cgi` | Medium
29 | File | `/article/DelectArticleById/` | High
30 | File | `/auth/auth.php?user=1` | High
31 | File | `/b2b-supermarket/shopping-cart` | High
32 | File | `/blog` | Low
33 | File | `/category.php` | High
34 | File | `/cgi-bin/cstecgi.cgi` | High
35 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
36 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=ie8` | High
37 | File | `/cgi-bin/nas_sharing.cgi` | High
38 | File | `/cgi-bin/supervisor/PwdGrp.cgi` | High
39 | File | `/classes/Master.php?f=delete_category` | High
40 | File | `/classes/Master.php?f=delete_inquiry` | High
41 | File | `/classes/Master.php?f=save_reminder` | High
42 | File | `/collection/all` | High
43 | File | `/company/store` | High
44 | File | `/config/list` | Medium
45 | File | `/designation_viewmore.php` | High
46 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
47 | File | `/ext/phar/phar_object.c` | High
48 | File | `/file-manager/upload.php` | High
49 | File | `/foms/place-order.php` | High
50 | File | `/forum/away.php` | High
51 | File | `/forum/PostPrivateMessage` | High
52 | File | `/fos/admin/index.php?page=menu` | High
53 | File | `/friends` | Medium
54 | File | `/goform/WifiBasicSet` | High
55 | File | `/graphql` | Medium
56 | File | `/home/get_tasks_list` | High
57 | File | `/importexport.php` | High
58 | File | `/index.php` | Medium
59 | File | `/items/search` | High
60 | File | `/jurusan/data` | High
61 | File | `/listplace/user/coverPhotoUpdate` | High
62 | File | `/login.php` | Medium
63 | File | `/login/index.php` | High
64 | File | `/menu.html` | Medium
65 | File | `/multiarch/memmove-vec-unaligned-erms.S` | High
66 | File | `/my_photo_gallery/image.php` | High
67 | File | `/news-portal-script/information.php` | High
68 | File | `/patient/doctors.php` | High
69 | ... | ... | ...

There are 603 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2022/03/from-blackmatter-to-blackcat-analyzing.html
* https://de.darktrace.com/blog/no-bad-luck-for-darktrace-combatting-alphv-blackcat-ransomware
* https://threatfox.abuse.ch
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-353a
* https://www.huntress.com/blog/blackcat-ransomware-affiliate-ttps
* https://www.ic3.gov/Media/News/2022/220420.pdf
* https://www.malwarebytes.com/blog/threat-intelligence/2024/04/active-nitrogen-campaign-delivered-via-malicious-ads-for-putty-filezilla

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
