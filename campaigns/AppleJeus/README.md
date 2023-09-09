# AppleJeus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _AppleJeus_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with AppleJeus:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with AppleJeus or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Lazarus](https://vuldb.com/?actor.lazarus) | High
2 | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
4 | ... | ...

There are 1 more actor items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of AppleJeus.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.217.53](https://vuldb.com/?ip.23.254.217.53) | client-23-254-217-53.hostwindsdns.com | [Applejeus](https://vuldb.com/?actor.applejeus) | High
2 | [45.33.2.79](https://vuldb.com/?ip.45.33.2.79) | li956-79.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
3 | [45.33.23.183](https://vuldb.com/?ip.45.33.23.183) | li977-183.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
4 | [45.56.79.23](https://vuldb.com/?ip.45.56.79.23) | li929-23.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
5 | [45.79.19.196](https://vuldb.com/?ip.45.79.19.196) | li1118-196.members.linode.com | [DPRK](https://vuldb.com/?actor.dprk) | High
6 | [45.199.63.220](https://vuldb.com/?ip.45.199.63.220) | - | [DPRK](https://vuldb.com/?actor.dprk) | High
7 | [80.82.64.91](https://vuldb.com/?ip.80.82.64.91) | - | [AppleJeus](https://vuldb.com/?actor.applejeus) | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-29, CWE-36 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during AppleJeus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/?ajax-request=jnews` | High
3 | File | `/admin/upload/upload` | High
4 | File | `/api/baskets/{name}` | High
5 | File | `/api/gen/clients/{language}` | High
6 | File | `/bin/login` | Medium
7 | File | `/cgi-bin/wlogin.cgi` | High
8 | File | `/classes/Users.php` | High
9 | File | `/config/getuser` | High
10 | File | `/config/myfield/test.php` | High
11 | File | `/debug/pprof` | Medium
12 | File | `/ecshop/admin/template.php` | High
13 | File | `/file/upload/1` | High
14 | File | `/forum/away.php` | High
15 | File | `/forum/PostPrivateMessage` | High
16 | File | `/goform/set_LimitClient_cfg` | High
17 | File | `/home/www/cgi-bin/login.cgi` | High
18 | File | `/hss/admin/?page=products/view_product` | High
19 | File | `/index.php?app=main&func=passport&action=login` | High
20 | File | `/multi-vendor-shopping-script/product-list.php` | High
21 | File | `/net-banking/customer_transactions.php` | High
22 | File | `/obs/book.php` | High
23 | File | `/ossn/administrator/com_installer` | High
24 | File | `/owa/auth/logon.aspx` | High
25 | File | `/pms/update_user.php?user_id=1` | High
26 | File | `/preview.php` | Medium
27 | File | `/requests.php` | High
28 | File | `/secure/ViewCollectors` | High
29 | File | `/spip.php` | Medium
30 | File | `/sqlite3_aflpp/shell.c` | High
31 | File | `/squashfs-root/etc_ro/custom.conf` | High
32 | File | `/sre/params.php` | High
33 | File | `/SVFE2/pages/feegroups/service_group.jsf` | High
34 | File | `/sys/user/querySysUser?username=admin` | High
35 | File | `/uncpath/` | Medium
36 | File | `/user/upload/upload` | High
37 | File | `/Users` | Low
38 | File | `/vendor` | Low
39 | File | `AccessibilityManagerService.java` | High
40 | File | `accountrecoveryendpoint/recoverpassword.do` | High
41 | File | `adclick.php` | Medium
42 | File | `add_contestant.php` | High
43 | File | `admin.php` | Medium
44 | File | `admin/edit_category.php` | High
45 | File | `admin/index.php` | High
46 | File | `admin/make_payments.php` | High
47 | File | `admin/_cmdstat.jsp` | High
48 | ... | ... | ...

There are 413 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://securelist.com/operation-applejeus-sequel/95596/
* https://us-cert.cisa.gov/ncas/alerts/aa21-048a
* https://us-cert.cisa.gov/ncas/analysis-reports/ar21-048c
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
