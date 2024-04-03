# Fodcha - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Fodcha](https://vuldb.com/?actor.fodcha). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fodcha](https://vuldb.com/?actor.fodcha)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fodcha:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fodcha.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.58.143](https://vuldb.com/?ip.3.0.58.143) | ec2-3-0-58-143.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.65.206.229](https://vuldb.com/?ip.3.65.206.229) | ec2-3-65-206-229.eu-central-1.compute.amazonaws.com | - | Medium
3 | [3.70.127.241](https://vuldb.com/?ip.3.70.127.241) | ec2-3-70-127-241.eu-central-1.compute.amazonaws.com | - | Medium
4 | [3.121.234.237](https://vuldb.com/?ip.3.121.234.237) | ec2-3-121-234-237.eu-central-1.compute.amazonaws.com | - | Medium
5 | [3.122.255.225](https://vuldb.com/?ip.3.122.255.225) | ec2-3-122-255-225.eu-central-1.compute.amazonaws.com | - | Medium
6 | [13.229.98.186](https://vuldb.com/?ip.13.229.98.186) | ec2-13-229-98-186.ap-southeast-1.compute.amazonaws.com | - | Medium
7 | [15.204.18.203](https://vuldb.com/?ip.15.204.18.203) | hosted-by.100up.net | - | High
8 | [15.204.18.232](https://vuldb.com/?ip.15.204.18.232) | shezmu.xyz | - | High
9 | [15.204.128.25](https://vuldb.com/?ip.15.204.128.25) | hosted-by.100up.net | - | High
10 | [18.136.209.2](https://vuldb.com/?ip.18.136.209.2) | ec2-18-136-209-2.ap-southeast-1.compute.amazonaws.com | - | Medium
11 | [18.185.188.32](https://vuldb.com/?ip.18.185.188.32) | ec2-18-185-188-32.eu-central-1.compute.amazonaws.com | - | Medium
12 | [23.183.83.171](https://vuldb.com/?ip.23.183.83.171) | - | - | High
13 | [31.214.245.253](https://vuldb.com/?ip.31.214.245.253) | vps-zap883671-1.zap-srv.com | - | High
14 | [45.41.240.145](https://vuldb.com/?ip.45.41.240.145) | hosted-by.100up.net | - | High
15 | [45.61.139.116](https://vuldb.com/?ip.45.61.139.116) | - | - | High
16 | [45.88.221.143](https://vuldb.com/?ip.45.88.221.143) | copouts.tinyblazer.com | - | High
17 | [45.135.135.33](https://vuldb.com/?ip.45.135.135.33) | - | - | High
18 | [45.140.169.122](https://vuldb.com/?ip.45.140.169.122) | wehomebuy.shop | - | High
19 | [45.147.200.168](https://vuldb.com/?ip.45.147.200.168) | - | - | High
20 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Fodcha_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Fodcha. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/?page=inmates/view_inmate` | High
2 | File | `/admin/?page=user/list` | High
3 | File | `/admin/add_trainers.php` | High
4 | File | `/admin/add_user_modal.php` | High
5 | File | `/admin/conferences/get-all-status/` | High
6 | File | `/admin/curriculum/view_curriculum.php` | High
7 | File | `/admin/del_feedback.php` | High
8 | File | `/admin/departments/view_department.php` | High
9 | File | `/admin/report/index.php` | High
10 | File | `/admin/reports/index.php` | High
11 | File | `/admin/students/view_student.php` | High
12 | File | `/admin/user/manage_user.php` | High
13 | File | `/api/` | Low
14 | File | `/api/database` | High
15 | File | `/api/sys/set_passwd` | High
16 | File | `/api/v1/terminal/sessions/?limit=1` | High
17 | File | `/assets/php/upload.php` | High
18 | File | `/author/list?limit=10&offset=0&order=desc` | High
19 | File | `/aya/module/admin/fst_down.inc.php` | High
20 | File | `/browse` | Low
21 | File | `/cardo/api` | Medium
22 | File | `/catcompany.php` | High
23 | File | `/ci_hms/massage_room/edit/1` | High
24 | File | `/claire_blake` | High
25 | File | `/classes/Users.php` | High
26 | File | `/dashboard/updatelogo.php` | High
27 | File | `/fax/fax_send.php` | High
28 | File | `/goform/RgDhcp` | High
29 | File | `/goform/RgTime` | High
30 | File | `/guestmanagement/front.php` | High
31 | File | `/inc/jquery/uploadify/uploadify.php` | High
32 | File | `/index.php/coins/update_marketboxslider` | High
33 | File | `/index.php?/manage/channel/addchannel` | High
34 | File | `/lists/index.php` | High
35 | File | `/mkshop/Men/profile.php` | High
36 | File | `/modules/projects/vw_files.php` | High
37 | File | `/movie.php` | Medium
38 | File | `/mygym/admin/login.php` | High
39 | File | `/obs/book.php` | High
40 | File | `/preview.php` | Medium
41 | File | `/process/eprocess.php` | High
42 | File | `/requests.php` | High
43 | File | `/rest/project-templates/1.0/createshared` | High
44 | File | `/search.php` | Medium
45 | File | `/siteminderagent/pwcgi/smpwservicescgi.exe` | High
46 | File | `/view-pass-detail.php` | High
47 | File | `/whbs/?page=contact_us` | High
48 | File | `/wolfcms/?/admin/user/add` | High
49 | File | `/wp-admin/admin-ajax.php` | High
50 | File | `/www/cgi-bin/popen.cgi` | High
51 | File | `404Like.php` | Medium
52 | File | `a-forms.php` | Medium
53 | File | `aa/../../uploads/blog/201811/attach_#.jpg` | High
54 | File | `ad-blocking-detector.php` | High
55 | File | `adclick.php` | Medium
56 | File | `add.php` | Low
57 | File | `admin.color.php` | High
58 | File | `admin.cropcanvas.php` | High
59 | File | `admin.joomlaradiov5.php` | High
60 | File | `admin.php` | Medium
61 | File | `admin/?page=user/manage_user` | High
62 | File | `admin/addons/archive/archive.php` | High
63 | File | `admin/admincore.php` | High
64 | File | `admin/ajax.php?action=save_user` | High
65 | File | `admin/auth.php` | High
66 | File | `admin/class-woo-popup-admin.php` | High
67 | File | `admin/departments/manage_department.php` | High
68 | File | `admin/expense_report.php` | High
69 | File | `admin/inc/auth.inc.php` | High
70 | File | `admin/systempreferences.pl` | High
71 | File | `admin\posts\manage_post.php` | High
72 | File | `affich.php` | Medium
73 | File | `ajax_blurb.php` | High
74 | File | `akocomments.php` | High
75 | File | `album_portal.php` | High
76 | File | `allopass-error.php` | High
77 | File | `allopass.php` | Medium
78 | File | `al_initialize.php` | High
79 | File | `announce.php` | Medium
80 | ... | ... | ...

There are 704 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/ddosmonster_the_return_of__fodcha_cn/
* https://blog.netlab.360.com/men-sheng-fa-da-cai-fodchajiang-shi-wang-luo/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
