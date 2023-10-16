# Nemty - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Nemty](https://vuldb.com/?actor.nemty). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.nemty](https://vuldb.com/?actor.nemty)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Nemty:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Nemty.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.234.181.234](https://vuldb.com/?ip.3.234.181.234) | ec2-3-234-181-234.compute-1.amazonaws.com | - | Medium
2 | [6.43.51.17](https://vuldb.com/?ip.6.43.51.17) | - | - | High
3 | [13.107.42.12](https://vuldb.com/?ip.13.107.42.12) | 1drv.ms | - | High
4 | [23.20.239.12](https://vuldb.com/?ip.23.20.239.12) | ec2-23-20-239-12.compute-1.amazonaws.com | - | Medium
5 | [23.21.50.37](https://vuldb.com/?ip.23.21.50.37) | ec2-23-21-50-37.compute-1.amazonaws.com | - | Medium
6 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Nemty_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Nemty. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/upload/upload` | High
3 | File | `/api/baskets/{name}` | High
4 | File | `/api/gen/clients/{language}` | High
5 | File | `/bin/login` | Medium
6 | File | `/bin/mini_upnpd` | High
7 | File | `/cgi-bin/wlogin.cgi` | High
8 | File | `/config/myfield/test.php` | High
9 | File | `/debug/pprof` | Medium
10 | File | `/ecshop/admin/template.php` | High
11 | File | `/file/upload/1` | High
12 | File | `/forum/away.php` | High
13 | File | `/forum/PostPrivateMessage` | High
14 | File | `/goform/set_LimitClient_cfg` | High
15 | File | `/h/autoSaveDraft` | High
16 | File | `/h/search?action` | High
17 | File | `/home/www/cgi-bin/login.cgi` | High
18 | File | `/hss/admin/?page=products/view_product` | High
19 | File | `/importexport.php` | High
20 | File | `/index.php?app=main&func=passport&action=login` | High
21 | File | `/multi-vendor-shopping-script/product-list.php` | High
22 | File | `/net-banking/customer_transactions.php` | High
23 | File | `/obs/book.php` | High
24 | File | `/ossn/administrator/com_installer` | High
25 | File | `/owa/auth/logon.aspx` | High
26 | File | `/pms/update_user.php?user_id=1` | High
27 | File | `/preview.php` | Medium
28 | File | `/requests.php` | High
29 | File | `/secure/ViewCollectors` | High
30 | File | `/spip.php` | Medium
31 | File | `/sqlite3_aflpp/shell.c` | High
32 | File | `/squashfs-root/etc_ro/custom.conf` | High
33 | File | `/SVFE2/pages/feegroups/service_group.jsf` | High
34 | File | `/sys/user/querySysUser?username=admin` | High
35 | File | `/uncpath/` | Medium
36 | File | `/user/upload/upload` | High
37 | File | `/Users` | Low
38 | File | `/usr/local/www/csrf/csrf-magic.php` | High
39 | File | `/vendor` | Low
40 | File | `AccessibilityManagerService.java` | High
41 | File | `accountrecoveryendpoint/recoverpassword.do` | High
42 | File | `adclick.php` | Medium
43 | File | `add_contestant.php` | High
44 | File | `admin.php` | Medium
45 | File | `admin/edit_category.php` | High
46 | File | `admin/index.php` | High
47 | ... | ... | ...

There are 408 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/03/threat-roundup-0228-0306.html
* https://www.fortinet.com/blog/threat-research/nemty-ransomware-early-stage-threat.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
