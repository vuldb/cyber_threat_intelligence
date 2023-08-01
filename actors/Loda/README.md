# Loda - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Loda](https://vuldb.com/?actor.loda). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.loda](https://vuldb.com/?actor.loda)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Loda:

* [SH](https://vuldb.com/?country.sh)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 5 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Loda.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.58.56.188](https://vuldb.com/?ip.2.58.56.188) | powered.by.rdp.sh | - | High
2 | [3.141.204.47](https://vuldb.com/?ip.3.141.204.47) | ec2-3-141-204-47.us-east-2.compute.amazonaws.com | - | Medium
3 | [13.40.105.36](https://vuldb.com/?ip.13.40.105.36) | ec2-13-40-105-36.eu-west-2.compute.amazonaws.com | - | Medium
4 | [34.174.95.150](https://vuldb.com/?ip.34.174.95.150) | 150.95.174.34.bc.googleusercontent.com | - | Medium
5 | [46.105.113.84](https://vuldb.com/?ip.46.105.113.84) | ns320209.ip-46-105-113.eu | - | High
6 | ... | ... | ... | ...

There are 20 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Loda_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Loda. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/admin/?page=product/manage_product&id=2` | High
3 | File | `/admin/admin.php` | High
4 | File | `/admin/casedetails.php` | High
5 | File | `/admin/fields/manage_field.php` | High
6 | File | `/admin/maintenance/brand.php` | High
7 | File | `/admin/mechanics/manage_mechanic.php` | High
8 | File | `/admin/modal_add_product.php` | High
9 | File | `/admin/offenses/view_details.php` | High
10 | File | `/admin/positions_add.php` | High
11 | File | `/admin/sales/index.php` | High
12 | File | `/admin/user/manage_user.php` | High
13 | File | `/admin/voters_row.php` | High
14 | File | `/ad_js.php` | Medium
15 | File | `/agc/vicidial.php` | High
16 | File | `/ajax.php?action=save_company` | High
17 | File | `/ajax.php?action=save_user` | High
18 | File | `/ajax/myshop` | Medium
19 | File | `/alumni/admin/ajax.php?action=save_settings` | High
20 | File | `/api/gen/clients/{language}` | High
21 | File | `/App_Resource/UEditor/server/upload.aspx` | High
22 | File | `/APR/signup.php` | High
23 | File | `/authenticationendpoint/login.do` | High
24 | File | `/aux` | Low
25 | File | `/backup.pl` | Medium
26 | File | `/blog` | Low
27 | File | `/BRS_netgear_success.html` | High
28 | File | `/cas/logout` | Medium
29 | File | `/category.php` | High
30 | File | `/categorypage.php` | High
31 | File | `/cgi-bin/adm.cgi` | High
32 | File | `/cgi-bin/system_mgr.cgi` | High
33 | File | `/cha.php` | Medium
34 | File | `/chaincity/user/ticket/create` | High
35 | File | `/classes/Master.php?f=delete_sub_category` | High
36 | File | `/College/admin/teacher.php` | High
37 | File | `/contactform/contactform.php` | High
38 | File | `/Controller/Ajaxfileupload.ashx` | High
39 | File | `/dayrui/Fcms/View/system_log.html` | High
40 | File | `/drivers/block/floppy.c` | High
41 | File | `/ecommerce/admin/category/controller.php` | High
42 | File | `/ecommerce/support_ticket` | High
43 | File | `/etc/shadow` | Medium
44 | File | `/files/list-file` | High
45 | File | `/fos/admin/ajax.php` | High
46 | File | `/friends/ajax_invite` | High
47 | File | `/goform/aspForm` | High
48 | File | `/goform/SetOnlineDevName` | High
49 | File | `/goform/WifiGuestSet` | High
50 | File | `/index.php` | Medium
51 | File | `/index.php/client/message/message_read/xxxxxxxx[random-msg-hash]` | High
52 | File | `/index.php?s=/article/ApiAdminArticle/itemAdd` | High
53 | File | `/kelasdosen/data` | High
54 | File | `/libraries` | Medium
55 | File | `/load.php` | Medium
56 | File | `/Log/Query?appid=0B736354-9473-4D66-B9C0-15CAC149EB05&tabid=tab_0B73635494734D66B9C015CAC149EB05` | High
57 | ... | ... | ...

There are 494 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/0370524d-75ee-4ea2-ad99-01e40a8d6b4a
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
