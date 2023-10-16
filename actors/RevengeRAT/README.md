# RevengeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RevengeRAT](https://vuldb.com/?actor.revengerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.revengerat](https://vuldb.com/?actor.revengerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RevengeRAT:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RevengeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | - | High
2 | [10.0.2.15](https://vuldb.com/?ip.10.0.2.15) | - | - | High
3 | [45.147.230.231](https://vuldb.com/?ip.45.147.230.231) | - | - | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RevengeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-29, CWE-36 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RevengeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/upload/upload` | High
3 | File | `/api/baskets/{name}` | High
4 | File | `/api/gen/clients/{language}` | High
5 | File | `/bin/login` | Medium
6 | File | `/cgi-bin/wlogin.cgi` | High
7 | File | `/config/myfield/test.php` | High
8 | File | `/debug/pprof` | Medium
9 | File | `/ecshop/admin/template.php` | High
10 | File | `/file/upload/1` | High
11 | File | `/forum/away.php` | High
12 | File | `/forum/PostPrivateMessage` | High
13 | File | `/goform/set_LimitClient_cfg` | High
14 | File | `/home/www/cgi-bin/login.cgi` | High
15 | File | `/hss/admin/?page=products/view_product` | High
16 | File | `/importexport.php` | High
17 | File | `/index.php?app=main&func=passport&action=login` | High
18 | File | `/multi-vendor-shopping-script/product-list.php` | High
19 | File | `/net-banking/customer_transactions.php` | High
20 | File | `/obs/book.php` | High
21 | File | `/ossn/administrator/com_installer` | High
22 | File | `/owa/auth/logon.aspx` | High
23 | File | `/pms/update_user.php?user_id=1` | High
24 | File | `/preview.php` | Medium
25 | File | `/requests.php` | High
26 | File | `/secure/ViewCollectors` | High
27 | File | `/spip.php` | Medium
28 | File | `/sqlite3_aflpp/shell.c` | High
29 | File | `/squashfs-root/etc_ro/custom.conf` | High
30 | File | `/SVFE2/pages/feegroups/service_group.jsf` | High
31 | File | `/sys/user/querySysUser?username=admin` | High
32 | File | `/uncpath/` | Medium
33 | File | `/user/upload/upload` | High
34 | File | `/Users` | Low
35 | File | `/usr/local/www/csrf/csrf-magic.php` | High
36 | File | `/vendor` | Low
37 | File | `AccessibilityManagerService.java` | High
38 | File | `accountrecoveryendpoint/recoverpassword.do` | High
39 | File | `adclick.php` | Medium
40 | File | `add_contestant.php` | High
41 | File | `admin.php` | Medium
42 | File | `admin/edit_category.php` | High
43 | File | `admin/index.php` | High
44 | File | `admin/make_payments.php` | High
45 | File | `admin/_cmdstat.jsp` | High
46 | File | `af_netlink.c` | Medium
47 | ... | ... | ...

There are 407 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://1275.ru/ioc/149/revengerat-iocs/
* https://blog.talosintelligence.com/2019/07/threat-roundup-0628-0705.html
* https://blog.talosintelligence.com/2019/08/rat-ratatouille-revrat-orcus.html
* https://blog.talosintelligence.com/threat-roundup-0616-0623-2/
* https://www.fortinet.com/blog/threat-research/malware-analysis-revenge-rat-sample.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
