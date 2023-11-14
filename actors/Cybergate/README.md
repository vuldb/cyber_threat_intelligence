# Cybergate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cybergate](https://vuldb.com/?actor.cybergate). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cybergate](https://vuldb.com/?actor.cybergate)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cybergate:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cybergate.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
2 | [20.36.253.92](https://vuldb.com/?ip.20.36.253.92) | - | - | High
3 | [23.5.234.11](https://vuldb.com/?ip.23.5.234.11) | a23-5-234-11.deploy.static.akamaitechnologies.com | - | High
4 | [23.105.131.235](https://vuldb.com/?ip.23.105.131.235) | mail235.nessfist.com | - | High
5 | [23.203.29.190](https://vuldb.com/?ip.23.203.29.190) | a23-203-29-190.deploy.static.akamaitechnologies.com | - | High
6 | [37.35.233.20](https://vuldb.com/?ip.37.35.233.20) | 20.233.35.37.dynamic.jazztel.es | - | High
7 | [37.252.5.213](https://vuldb.com/?ip.37.252.5.213) | - | - | High
8 | [41.217.176.33](https://vuldb.com/?ip.41.217.176.33) | - | - | High
9 | [52.8.126.80](https://vuldb.com/?ip.52.8.126.80) | ec2-52-8-126-80.us-west-1.compute.amazonaws.com | - | Medium
10 | [52.201.110.209](https://vuldb.com/?ip.52.201.110.209) | ec2-52-201-110-209.compute-1.amazonaws.com | - | Medium
11 | [65.55.44.109](https://vuldb.com/?ip.65.55.44.109) | - | - | High
12 | [69.65.19.115](https://vuldb.com/?ip.69.65.19.115) | ns3.no-ip.com | - | High
13 | [78.159.135.230](https://vuldb.com/?ip.78.159.135.230) | - | - | High
14 | [78.171.201.199](https://vuldb.com/?ip.78.171.201.199) | 78.171.201.199.dynamic.ttnet.com.tr | - | High
15 | [86.18.99.199](https://vuldb.com/?ip.86.18.99.199) | cpc86441-seve24-2-0-cust198.13-3.cable.virginm.net | - | High
16 | ... | ... | ... | ...

There are 59 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cybergate_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cybergate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$HOME/.terminfo` | High
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin/upload/upload` | High
4 | File | `/api/baskets/{name}` | High
5 | File | `/api/gen/clients/{language}` | High
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
22 | File | `/mgmt/` | Low
23 | File | `/multi-vendor-shopping-script/product-list.php` | High
24 | File | `/net-banking/customer_transactions.php` | High
25 | File | `/obs/book.php` | High
26 | File | `/ossn/administrator/com_installer` | High
27 | File | `/owa/auth/logon.aspx` | High
28 | File | `/pms/update_user.php?user_id=1` | High
29 | File | `/preview.php` | Medium
30 | File | `/requests.php` | High
31 | File | `/secure/ViewCollectors` | High
32 | File | `/server-status` | High
33 | File | `/spip.php` | Medium
34 | File | `/sqlite3_aflpp/shell.c` | High
35 | File | `/squashfs-root/etc_ro/custom.conf` | High
36 | File | `/SVFE2/pages/feegroups/service_group.jsf` | High
37 | File | `/sys/user/querySysUser?username=admin` | High
38 | ... | ... | ...

There are 327 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/08/threat-roundup-0809-0816.html
* https://blog.talosintelligence.com/2020/08/threat-roundup-0814-0821.html
* https://blog.talosintelligence.com/2020/08/threat-roundup-0821-0827.html
* https://threatfox.abuse.ch
* https://www.zscaler.com/blogs/research/cybergate-rat-and-redline-stealer-delivered-ongoing-autoit-malware-campaigns

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
