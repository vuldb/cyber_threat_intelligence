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
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during LookBack. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.terminfo` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin/upload/upload` | High
4 | File | `/api/baskets/{name}` | High
5 | File | `/api/gen/clients/{language}` | High
6 | File | `/apply.cgi` | Medium
7 | File | `/bin/login` | Medium
8 | File | `/bin/mini_upnpd` | High
9 | File | `/cgi-bin/wlogin.cgi` | High
10 | File | `/config/myfield/test.php` | High
11 | File | `/debug/pprof` | Medium
12 | File | `/ecshop/admin/template.php` | High
13 | File | `/file/upload/1` | High
14 | File | `/forum/away.php` | High
15 | File | `/forum/PostPrivateMessage` | High
16 | File | `/goform/set_LimitClient_cfg` | High
17 | File | `/h/autoSaveDraft` | High
18 | File | `/h/search?action` | High
19 | File | `/home/www/cgi-bin/login.cgi` | High
20 | File | `/hss/admin/?page=products/view_product` | High
21 | File | `/importexport.php` | High
22 | File | `/index.php?app=main&func=passport&action=login` | High
23 | File | `/mgmt/` | Low
24 | File | `/multi-vendor-shopping-script/product-list.php` | High
25 | File | `/net-banking/customer_transactions.php` | High
26 | File | `/obs/book.php` | High
27 | File | `/ossn/administrator/com_installer` | High
28 | File | `/owa/auth/logon.aspx` | High
29 | File | `/pms/update_user.php?user_id=1` | High
30 | File | `/preview.php` | Medium
31 | File | `/requests.php` | High
32 | File | `/scripts/unlock_tasks.php` | High
33 | File | `/secure/ViewCollectors` | High
34 | File | `/spip.php` | Medium
35 | File | `/sqlite3_aflpp/shell.c` | High
36 | File | `/squashfs-root/etc_ro/custom.conf` | High
37 | File | `/SVFE2/pages/feegroups/service_group.jsf` | High
38 | File | `/sys/user/querySysUser?username=admin` | High
39 | File | `/system/user/modules/mod_users/controller.php` | High
40 | File | `/uncpath/` | Medium
41 | ... | ... | ...

There are 352 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
