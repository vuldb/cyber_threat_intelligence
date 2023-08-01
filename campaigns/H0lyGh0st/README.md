# H0lyGh0st - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _H0lyGh0st_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with H0lyGh0st:

* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with H0lyGh0st or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DEV-0530](https://vuldb.com/?actor.dev-0530) | High
2 | [H0lyGh0st](https://vuldb.com/?actor.h0lygh0st) | High
3 | [North Korea Unknown](https://vuldb.com/?actor.north_korea_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of H0lyGh0st.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | [H0lyGh0st](https://vuldb.com/?actor.h0lygh0st) | High
2 | [193.56.29.123](https://vuldb.com/?ip.193.56.29.123) | - | [North Korea Unknown](https://vuldb.com/?actor.north_korea_unknown) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within H0lyGh0st. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-29 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during H0lyGh0st. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/upload/upload` | High
3 | File | `/api/gen/clients/{language}` | High
4 | File | `/cgi-bin/wlogin.cgi` | High
5 | File | `/config/getuser` | High
6 | File | `/config/myfield/test.php` | High
7 | File | `/debug/pprof` | Medium
8 | File | `/ecshop/admin/template.php` | High
9 | File | `/file/upload/1` | High
10 | File | `/forum/away.php` | High
11 | File | `/forum/PostPrivateMessage` | High
12 | File | `/goform/set_LimitClient_cfg` | High
13 | File | `/home/www/cgi-bin/login.cgi` | High
14 | File | `/multi-vendor-shopping-script/product-list.php` | High
15 | File | `/net-banking/customer_transactions.php` | High
16 | File | `/obs/book.php` | High
17 | File | `/ossn/administrator/com_installer` | High
18 | File | `/owa/auth/logon.aspx` | High
19 | File | `/pms/update_user.php?user_id=1` | High
20 | File | `/preview.php` | Medium
21 | File | `/requests.php` | High
22 | File | `/spip.php` | Medium
23 | File | `/sqlite3_aflpp/shell.c` | High
24 | File | `/sre/params.php` | High
25 | File | `/SVFE2/pages/feegroups/service_group.jsf` | High
26 | File | `/tmp` | Low
27 | File | `/uncpath/` | Medium
28 | File | `/user/upload/upload` | High
29 | File | `/Users` | Low
30 | File | `/var/spool/hylafax` | High
31 | File | `/vendor` | Low
32 | File | `AccessibilityManagerService.java` | High
33 | File | `accountrecoveryendpoint/recoverpassword.do` | High
34 | File | `adclick.php` | Medium
35 | File | `add_contestant.php` | High
36 | File | `admin.php` | Medium
37 | File | `admin/edit_category.php` | High
38 | File | `admin/index.php` | High
39 | File | `admin/make_payments.php` | High
40 | File | `af_netlink.c` | Medium
41 | File | `album_portal.php` | High
42 | File | `api/auth.go` | Medium
43 | File | `api_jsonrpc.php` | High
44 | File | `artreplydelete.asp` | High
45 | ... | ... | ...

There are 392 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://community.blueliv.com/#!/s/62d1143282df41552632f957
* https://www.microsoft.com/en-us/security/blog/2022/07/14/north-korean-threat-actor-targets-small-and-midsize-businesses-with-h0lygh0st-ransomware/
* https://www.microsoft.com/security/blog/2022/07/14/north-korean-threat-actor-targets-small-and-midsize-businesses-with-h0lygh0st-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
