# LookBack - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _LookBack_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LookBack:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 11 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with LookBack or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Witchetty](https://vuldb.com/?actor.witchetty) | High
2 | [Lookback](https://vuldb.com/?actor.lookback) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LookBack.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.176.3](https://vuldb.com/?ip.5.252.176.3) | no-rdns.mivocloud.com | [Witchetty](https://vuldb.com/?actor.witchetty) | High
2 | [79.141.168.137](https://vuldb.com/?ip.79.141.168.137) | nceess.com | [Lookback](https://vuldb.com/?actor.lookback) | High
3 | [103.253.41.45](https://vuldb.com/?ip.103.253.41.45) | mail.e-cigs-mart.com | [Lookback](https://vuldb.com/?actor.lookback) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within LookBack. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LookBack. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/upload/upload` | High
3 | File | `/api/baskets/{name}` | High
4 | File | `/api/gen/clients/{language}` | High
5 | File | `/apply.cgi` | Medium
6 | File | `/bin/login` | Medium
7 | File | `/bin/mini_upnpd` | High
8 | File | `/cgi-bin/wlogin.cgi` | High
9 | File | `/config/myfield/test.php` | High
10 | File | `/debug/pprof` | Medium
11 | File | `/ecshop/admin/template.php` | High
12 | File | `/file/upload/1` | High
13 | File | `/forum/away.php` | High
14 | File | `/forum/PostPrivateMessage` | High
15 | File | `/goform/set_LimitClient_cfg` | High
16 | File | `/h/autoSaveDraft` | High
17 | File | `/h/search?action` | High
18 | File | `/home/www/cgi-bin/login.cgi` | High
19 | File | `/hss/admin/?page=products/view_product` | High
20 | File | `/importexport.php` | High
21 | File | `/index.php?app=main&func=passport&action=login` | High
22 | File | `/multi-vendor-shopping-script/product-list.php` | High
23 | File | `/net-banking/customer_transactions.php` | High
24 | File | `/obs/book.php` | High
25 | File | `/ossn/administrator/com_installer` | High
26 | File | `/owa/auth/logon.aspx` | High
27 | File | `/pms/update_user.php?user_id=1` | High
28 | File | `/preview.php` | Medium
29 | File | `/requests.php` | High
30 | File | `/scripts/unlock_tasks.php` | High
31 | File | `/secure/ViewCollectors` | High
32 | File | `/spip.php` | Medium
33 | File | `/sqlite3_aflpp/shell.c` | High
34 | File | `/squashfs-root/etc_ro/custom.conf` | High
35 | File | `/SVFE2/pages/feegroups/service_group.jsf` | High
36 | File | `/sys/user/querySysUser?username=admin` | High
37 | File | `/system/user/modules/mod_users/controller.php` | High
38 | File | `/uncpath/` | Medium
39 | File | `/user/upload/upload` | High
40 | File | `/usr/local/www/csrf/csrf-magic.php` | High
41 | File | `/vendor` | Low
42 | File | `AccessibilityManagerService.java` | High
43 | File | `accountrecoveryendpoint/recoverpassword.do` | High
44 | File | `adclick.php` | Medium
45 | File | `add_contestant.php` | High
46 | File | `admin.php` | Medium
47 | ... | ... | ...

There are 404 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/witchetty-steganography-espionage
* https://www.proofpoint.com/us/threat-insight/post/lookback-malware-targets-united-states-utilities-sector-phishing-attacks

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
