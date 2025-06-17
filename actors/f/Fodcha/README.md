# Fodcha - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Fodcha](https://vuldb.com/?actor.fodcha). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fodcha](https://vuldb.com/?actor.fodcha)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fodcha:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 4 more country items available. Please use our online service to access the data.

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
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Fodcha. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/addproduct.php` | High
3 | File | `/addQuestion.php` | High
4 | File | `/add_new_invoice.php` | High
5 | File | `/admin/?page=system_info/contact_info` | High
6 | File | `/admin/about-us.php` | High
7 | File | `/admin/action/new-feed.php` | High
8 | File | `/admin/add_trainers.php` | High
9 | File | `/admin/admin.php` | High
10 | File | `/admin/admin_cl.php?mudi=revPwd` | High
11 | File | `/admin/admin_login.php` | High
12 | File | `/admin/api/admin/v2_products` | High
13 | File | `/admin/check_admin.php` | High
14 | File | `/admin/check_availability.php` | High
15 | File | `/admin/client_user` | High
16 | File | `/Admin/createClass.php` | High
17 | File | `/admin/DeviceS3` | High
18 | File | `/admin/edit_admin_details.php?id=admin` | High
19 | File | `/admin/edit_role.php` | High
20 | File | `/admin/index.php` | High
21 | File | `/admin/inquiries/view_details.php` | High
22 | File | `/admin/login.php` | High
23 | File | `/admin/makehtml_freelist_action.php` | High
24 | File | `/admin/network/ajax_getChannelList` | High
25 | File | `/admin/new-content` | High
26 | File | `/admin/students/view_student.php` | High
27 | File | `/adminPage/main/upload` | High
28 | File | `/admin_route/inc_service_credits.php` | High
29 | File | `/ajax` | Low
30 | File | `/api/public/signup` | High
31 | File | `/api/v1/attack` | High
32 | File | `/api/v1/attack/falco` | High
33 | File | `/app/api/controller/Site.php` | High
34 | File | `/backend/admin/his_admin_add_vendor.php` | High
35 | File | `/backend/doc/his_doc_update-account.php` | High
36 | File | `/bsms_ci/index.php` | High
37 | File | `/cgi-bin/cstecgi.cgi` | High
38 | File | `/cgi-bin/hd_config.cgi` | High
39 | File | `/claire_blake` | High
40 | File | `/conf/app.conf` | High
41 | File | `/control/register_case.php` | High
42 | File | `/csms/admin/?page=system_info` | High
43 | File | `/csms/admin/?page=user/list` | High
44 | File | `/device.rsp?opt=sys&cmd=___S_O_S_T_R_E_A_MAX___` | High
45 | File | `/DocSystem/Repos/getReposAllUsers.do` | High
46 | File | `/downloadReport.php` | High
47 | File | `/editar-produto.php` | High
48 | File | `/edit_user.php` | High
49 | File | `/employeeview.php` | High
50 | File | `/endpoint/delete-bookmark.php?bookmark=1` | High
51 | File | `/endpoint/delete-mark.php` | High
52 | File | `/face-recognition-php/facepay-master/camera.php` | High
53 | File | `/foms/routers/cancel-order.php` | High
54 | File | `/forum/away.php` | High
55 | File | `/goform/execCommand` | High
56 | File | `/goform/fromRouteStatic` | High
57 | File | `/goform/qossetting` | High
58 | File | `/goform/SetOnlineDevName` | High
59 | File | `/goform/SetSysAutoRebbotCfg` | High
60 | File | `/goform/webExcptypemanFilter` | High
61 | File | `/goform/wifiSSIDget` | High
62 | File | `/index.php` | Medium
63 | File | `/labvantage/rc?command=page&page=SampleList&_iframename=list` | High
64 | File | `/login` | Low
65 | File | `/login.php` | Medium
66 | File | `/manage_laundry.php` | High
67 | File | `/manage_person.php` | High
68 | File | `/manage_supplier.php` | High
69 | File | `/mims/app/addcustomerHandler.php` | High
70 | File | `/mkshop/Men/profile.php` | High
71 | File | `/model/approve_petty_cash.php` | High
72 | File | `/modules/ajaxBloqueaCita.php` | High
73 | ... | ... | ...

There are 644 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/ddosmonster_the_return_of__fodcha_cn/
* https://blog.netlab.360.com/men-sheng-fa-da-cai-fodchajiang-shi-wang-luo/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
