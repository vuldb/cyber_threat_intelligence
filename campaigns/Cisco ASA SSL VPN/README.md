# Cisco ASA SSL VPN - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cisco ASA SSL VPN_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cisco ASA SSL VPN:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 22 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cisco ASA SSL VPN or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Unknown](https://vuldb.com/?actor.unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cisco ASA SSL VPN.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.61.43.231](https://vuldb.com/?ip.5.61.43.231) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
2 | [5.183.253.129](https://vuldb.com/?ip.5.183.253.129) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
3 | [31.184.236.63](https://vuldb.com/?ip.31.184.236.63) | zemal.kiprises.net | [Unknown](https://vuldb.com/?actor.unknown) | High
4 | [31.184.236.71](https://vuldb.com/?ip.31.184.236.71) | miseria.independentbookstores.net | [Unknown](https://vuldb.com/?actor.unknown) | High
5 | [31.184.236.79](https://vuldb.com/?ip.31.184.236.79) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
6 | [45.66.209.122](https://vuldb.com/?ip.45.66.209.122) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
7 | [45.80.107.220](https://vuldb.com/?ip.45.80.107.220) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
8 | [45.227.252.237](https://vuldb.com/?ip.45.227.252.237) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
9 | [45.227.255.51](https://vuldb.com/?ip.45.227.255.51) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
10 | [46.161.27.123](https://vuldb.com/?ip.46.161.27.123) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
11 | [62.233.50.11](https://vuldb.com/?ip.62.233.50.11) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
12 | [62.233.50.13](https://vuldb.com/?ip.62.233.50.13) | - | [Unknown](https://vuldb.com/?actor.unknown) | High
13 | ... | ... | ... | ...

There are 50 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cisco ASA SSL VPN. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cisco ASA SSL VPN. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//WEB-INF` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/update/getFile.html` | High
4 | File | `/admin/cashadvance_row.php` | High
5 | File | `/admin/getallarticleinfo` | High
6 | File | `/admin/maintenance/view_designation.php` | High
7 | File | `/admin/sys_sql_query.php` | High
8 | File | `/admin/userprofile.php` | High
9 | File | `/api/baskets/{name}` | High
10 | File | `/api/upload` | Medium
11 | File | `/APR/login.php` | High
12 | File | `/bitrix/admin/ldap_server_edit.php` | High
13 | File | `/cgi-bin/luci/api/wireless` | High
14 | File | `/cgi-bin/wapopen` | High
15 | File | `/company/store` | High
16 | File | `/Content/Template/root/reverse-shell.aspx` | High
17 | File | `/Controller/Ajaxfileupload.ashx` | High
18 | File | `/core/conditions/AbstractWrapper.java` | High
19 | File | `/etc/passwd` | Medium
20 | File | `/feeds/post/publish` | High
21 | File | `/forum/away.php` | High
22 | File | `/h/` | Low
23 | File | `/inc/jquery/uploadify/uploadify.php` | High
24 | File | `/inc/lists/edit-list.php` | High
25 | File | `/inc/lists/view-list.php` | High
26 | File | `/index.php?app=main&func=passport&action=login` | High
27 | File | `/index.php?page=category_list` | High
28 | File | `/jeecg-boot/sys/common/upload` | High
29 | File | `/jobinfo/` | Medium
30 | File | `/load.php` | Medium
31 | File | `/Moosikay/order.php` | High
32 | File | `/mygym/admin/index.php?view_exercises` | High
33 | File | `/opac/Actions.php?a=login` | High
34 | File | `/php-opos/index.php` | High
35 | File | `/PreviewHandler.ashx` | High
36 | File | `/public/launchNewWindow.jsp` | High
37 | File | `/recipe-result` | High
38 | File | `/register.do` | Medium
39 | File | `/reservation/add_message.php` | High
40 | File | `/Service/ImageStationDataService.asmx` | High
41 | File | `/spip.php` | Medium
42 | File | `/src/chatbotapp/chatWindow.java` | High
43 | File | `/student/bookdetails.php` | High
44 | File | `/tmp/phpglibccheck` | High
45 | File | `/uploads/exam_question/` | High
46 | File | `/user/ticket/create` | High
47 | File | `/user/updatePwd` | High
48 | File | `/var/lib/docker/<remapping>` | High
49 | File | `/wp-admin/admin-ajax.php` | High
50 | File | `/xxl-job-admin/user/add` | High
51 | File | `a-forms.php` | Medium
52 | File | `actions.php` | Medium
53 | ... | ... | ...

There are 459 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.rapid7.com/blog/post/2023/08/29/under-siege-rapid7-observed-exploitation-of-cisco-asa-ssl-vpns/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
