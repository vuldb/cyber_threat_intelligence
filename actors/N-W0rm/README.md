# N-W0rm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [N-W0rm](https://vuldb.com/?actor.n-w0rm). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.n-w0rm](https://vuldb.com/?actor.n-w0rm)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with N-W0rm:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of N-W0rm.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.254.54](https://vuldb.com/?ip.2.56.254.54) | - | - | High
2 | [20.48.21.149](https://vuldb.com/?ip.20.48.21.149) | - | - | High
3 | [23.7.53.229](https://vuldb.com/?ip.23.7.53.229) | a23-7-53-229.deploy.static.akamaitechnologies.com | - | High
4 | [23.8.82.173](https://vuldb.com/?ip.23.8.82.173) | a23-8-82-173.deploy.static.akamaitechnologies.com | - | High
5 | [23.9.169.37](https://vuldb.com/?ip.23.9.169.37) | a23-9-169-37.deploy.static.akamaitechnologies.com | - | High
6 | [23.204.189.35](https://vuldb.com/?ip.23.204.189.35) | a23-204-189-35.deploy.static.akamaitechnologies.com | - | High
7 | [35.83.156.201](https://vuldb.com/?ip.35.83.156.201) | ec2-35-83-156-201.us-west-2.compute.amazonaws.com | - | Medium
8 | [35.168.183.178](https://vuldb.com/?ip.35.168.183.178) | ec2-35-168-183-178.compute-1.amazonaws.com | - | Medium
9 | [37.113.171.12](https://vuldb.com/?ip.37.113.171.12) | dynamicip-37-113-171-12.pppoe.chel.ertelecom.ru | - | High
10 | [37.120.141.147](https://vuldb.com/?ip.37.120.141.147) | - | - | High
11 | [37.120.141.190](https://vuldb.com/?ip.37.120.141.190) | - | - | High
12 | ... | ... | ... | ...

There are 45 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _N-W0rm_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 24 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by N-W0rm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `//WEB-INF` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin/?page=user/manage_user&id=3` | High
4 | File | `/admin/about-us.php` | High
5 | File | `/admin/sys_sql_query.php` | High
6 | File | `/api/baskets/{name}` | High
7 | File | `/api/download` | High
8 | File | `/api/stl/actions/search` | High
9 | File | `/api/v1/terminal/sessions/?limit=1` | High
10 | File | `/bin/ate` | Medium
11 | File | `/bitrix/admin/ldap_server_edit.php` | High
12 | File | `/booking/show_bookings/` | High
13 | File | `/category.php` | High
14 | File | `/cgi-bin` | Medium
15 | File | `/cgi-bin/luci/api/wireless` | High
16 | File | `/company/store` | High
17 | File | `/Content/Template/root/reverse-shell.aspx` | High
18 | File | `/Controller/Ajaxfileupload.ashx` | High
19 | File | `/core/conditions/AbstractWrapper.java` | High
20 | File | `/dashboard/add-blog.php` | High
21 | File | `/dcim/rack-roles/` | High
22 | File | `/debug/pprof` | Medium
23 | File | `/env` | Low
24 | File | `/etc/passwd` | Medium
25 | File | `/forum/away.php` | High
26 | File | `/group1/uploa` | High
27 | File | `/h/` | Low
28 | File | `/horde/util/go.php` | High
29 | File | `/inc/jquery/uploadify/uploadify.php` | High
30 | File | `/index.php` | Medium
31 | File | `/index.php?app=main&func=passport&action=login` | High
32 | File | `/index.php?page=category_list` | High
33 | File | `/jeecg-boot/sys/common/upload` | High
34 | File | `/jobinfo/` | Medium
35 | File | `/kelas/data` | Medium
36 | File | `/Moosikay/order.php` | High
37 | File | `/php-sms/admin/?page=user/manage_user` | High
38 | File | `/PreviewHandler.ashx` | High
39 | File | `/recipe-result` | High
40 | File | `/register.do` | Medium
41 | File | `/resources//../` | High
42 | File | `/Service/ImageStationDataService.asmx` | High
43 | File | `/spip.php` | Medium
44 | File | `/squashfs-root/etc_ro/custom.conf` | High
45 | File | `/staff/edit_book_details.php` | High
46 | ... | ... | ...

There are 397 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
