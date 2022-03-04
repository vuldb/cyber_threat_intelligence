# Wocao - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Wocao](https://vuldb.com/?actor.wocao). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.wocao](https://vuldb.com/?actor.wocao)

## Campaigns

The following _campaigns_ are known and can be associated with Wocao:

* Wocao

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wocao:

* US
* FR

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wocao.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 23.254.211.108 | hwsrv-871243.hostwindsdns.com | Wocao | High
2 | 31.222.185.215 | 31-222-185-215.static.cloud-ips.co.uk | Wocao | High
3 | 45.77.229.10 | 45.77.229.10.vultr.com | Wocao | Medium
4 | ... | ... | ... | ...

There are 13 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 11 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/admin_manage/delete` | High
2 | File | `/administrator/components/table_manager/` | High
3 | File | `/adminzone/index.php?page=admin-commandr` | High
4 | File | `/ajax_crud` | Medium
5 | File | `/anony/mjpg.cgi` | High
6 | File | `/application/common.php#action_log` | High
7 | File | `/core/admin/comment.php` | High
8 | File | `/data-service/users/` | High
9 | File | `/etc/wpa_supplicant.conf` | High
10 | File | `/jeecg-boot/sys/user/queryUserByDepId` | High
11 | File | `/js/app.js` | Medium
12 | File | `/js/js-parser.c` | High
13 | File | `/main?cmd=invalid_browser` | High
14 | File | `/ms/file/uploadTemplate.do` | High
15 | File | `/ping.html` | Medium
16 | File | `/SASWebReportStudio/logonAndRender.do` | High
17 | File | `/sys/user/queryUserComponentData` | High
18 | File | `/template/unzip.do` | High
19 | File | `/uncpath/` | Medium
20 | File | `/user/login/oauth` | High
21 | File | `/userRpm/PingIframeRpm.htm` | High
22 | File | `/usr/bin/pkexec` | High
23 | File | `/usr/local/bin/mjs` | High
24 | File | `/usr/local/www/pkg.php` | High
25 | File | `/yzmcms/comment/index/init.html` | High
26 | File | `AAVCAssembler.cpp` | High
27 | File | `about.php` | Medium
28 | ... | ... | ...

There are 238 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/fox-it/operation-wocao

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
