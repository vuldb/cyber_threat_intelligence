# Black KingDom - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Black KingDom](https://vuldb.com/?actor.black_kingdom). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.black_kingdom](https://vuldb.com/?actor.black_kingdom)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Black KingDom:

* US
* FR
* RU

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Black KingDom.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 104.21.89.10 | - | - | High
2 | 172.64.80.0 | - | - | High
3 | 185.220.101.204 | tor-exit-204.relayon.org | - | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Black KingDom. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 10 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Black KingDom. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/admin_manage/delete` | High
2 | File | `/admin/login.php` | High
3 | File | `/administrator/components/table_manager/` | High
4 | File | `/adminzone/index.php?page=admin-commandr` | High
5 | File | `/ajax_crud` | Medium
6 | File | `/anony/mjpg.cgi` | High
7 | File | `/application/common.php#action_log` | High
8 | File | `/base/ecma-helpers-string.c` | High
9 | File | `/cms/ajax.php` | High
10 | File | `/core/table/query` | High
11 | File | `/data-service/users/` | High
12 | File | `/dev/ion` | Medium
13 | File | `/ecma/operations/ecma-objects.c` | High
14 | File | `/GetCopiedFile` | High
15 | File | `/jerry-core/ecma/base/ecma-literal-storage.c` | High
16 | File | `/jerry-core/ecma/builtin-objects/ecma-builtin-date-prototype.c` | High
17 | File | `/jerry-core/parser/js/js-parser-expr.c` | High
18 | File | `/js/app.js` | Medium
19 | File | `/leave_system/classes/Login.php` | High
20 | File | `/music/ajax.php` | High
21 | File | `/orms/` | Low
22 | File | `/parser/js/js-parser-mem.c` | High
23 | File | `/uncpath/` | Medium
24 | File | `/user/login/oauth` | High
25 | File | `/userRpm/PingIframeRpm.htm` | High
26 | File | `/usr/bin/pkexec` | High
27 | File | `/usr/local/bin/mjs` | High
28 | File | `/usr/local/www/pkg.php` | High
29 | ... | ... | ...

There are 250 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Ransomware_BlackKingDom.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
