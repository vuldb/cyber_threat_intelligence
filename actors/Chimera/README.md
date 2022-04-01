# Chimera - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Chimera](https://vuldb.com/?actor.chimera). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.chimera](https://vuldb.com/?actor.chimera)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Chimera:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Chimera.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.3.35.342](https://vuldb.com/?ip.1.3.35.342) | - | - | High
2 | [5.254.64.234](https://vuldb.com/?ip.5.254.64.234) | - | - | High
3 | [5.254.112.226](https://vuldb.com/?ip.5.254.112.226) | - | - | High
4 | [14.229.140.66](https://vuldb.com/?ip.14.229.140.66) | static.vnpt.vn | - | High
5 | ... | ... | ... | ...

There are 16 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Chimera_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chimera. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `./clients/client` | High
2 | File | `//` | Low
3 | File | `/assets/ctx` | Medium
4 | File | `/cgi-bin/luci` | High
5 | File | `/cgi-bin/portal` | High
6 | File | `/config/getuser` | High
7 | File | `/forum/away.php` | High
8 | File | `/horde/util/go.php` | High
9 | File | `/hostapd` | Medium
10 | File | `/include/chart_generator.php` | High
11 | File | `/MTFWU` | Low
12 | File | `/my_photo_gallery/image.php` | High
13 | File | `/ptms/classes/Users.php` | High
14 | File | `/public/admin.php` | High
15 | File | `/public/login.htm` | High
16 | File | `/public/login.htm?errormsg=&loginurl=%22%3E%3Csvg%20onload=prompt%28/XSS/%29%3E` | High
17 | File | `/public/plugins/` | High
18 | File | `/rest/api/1.0/render` | High
19 | File | `/rest/api/latest/user/avatar/temporary` | High
20 | File | `/s/` | Low
21 | File | `/secure/admin/InsightDefaultCustomFieldConfig.jspa` | High
22 | File | `/sm/api/v1/firewall/zone/services` | High
23 | File | `/sys/attachment/uploaderServlet` | High
24 | File | `/uncpath/` | Medium
25 | File | `/user-utils/users/md5.json` | High
26 | File | `/userRpm/popupSiteSurveyRpm.html` | High
27 | File | `/usr/bin/pkexec` | High
28 | File | `/wp-admin/admin-ajax.php` | High
29 | File | `/wp-json` | Medium
30 | File | `102/tcp` | Low
31 | File | `accountrecoveryendpoint/recoverpassword.do` | High
32 | File | `admin.php` | Medium
33 | File | `admin.remository.php` | High
34 | File | `admin/conf_users_edit.php` | High
35 | ... | ... | ...

There are 299 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cycraft.com/download/%5BTLP-White%5D20200415%20Chimera_V4.1.pdf
* https://vxug.fakedoma.in/archive/APTs/2021/2021.01.12/Chimera.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
