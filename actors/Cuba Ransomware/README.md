# Cuba Ransomware - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Cuba Ransomware](https://vuldb.com/?actor.cuba_ransomware). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.cuba_ransomware](https://vuldb.com/?actor.cuba_ransomware)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cuba Ransomware:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* ...

There are 10 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cuba Ransomware.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [10.13.102.1](https://vuldb.com/?ip.10.13.102.1) | - | - | High
2 | [10.13.102.58](https://vuldb.com/?ip.10.13.102.58) | - | - | High
3 | [10.14.100.20](https://vuldb.com/?ip.10.14.100.20) | - | - | High
4 | [10.133.78.41](https://vuldb.com/?ip.10.133.78.41) | - | - | High
5 | [23.227.198.246](https://vuldb.com/?ip.23.227.198.246) | 23-227-198-246.static.hvvc.us | - | High
6 | [31.184.192.44](https://vuldb.com/?ip.31.184.192.44) | - | - | High
7 | [37.44.253.21](https://vuldb.com/?ip.37.44.253.21) | - | - | High
8 | [37.120.247.39](https://vuldb.com/?ip.37.120.247.39) | - | - | High
9 | [38.108.119.121](https://vuldb.com/?ip.38.108.119.121) | - | - | High
10 | [45.32.229.66](https://vuldb.com/?ip.45.32.229.66) | - | - | High
11 | [45.86.162.34](https://vuldb.com/?ip.45.86.162.34) | - | - | High
12 | ... | ... | ... | ...

There are 42 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Cuba Ransomware_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Cuba Ransomware. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.FBCIndex` | Medium
2 | File | `/.ssh/authorized_keys` | High
3 | File | `/admin/` | Low
4 | File | `/admin/settings/save.php` | High
5 | File | `/back/index.php/user/User/?1` | High
6 | File | `/bsms_ci/index.php` | High
7 | File | `/bsms_ci/index.php/user/edit_user/` | High
8 | File | `/carbon/ndatasource/validateconnection/ajaxprocessor.jsp` | High
9 | File | `/cgi-bin/luci` | High
10 | File | `/cgi-bin/wlogin.cgi` | High
11 | File | `/common/info.cgi` | High
12 | File | `/Content/Template/root/reverse-shell.aspx` | High
13 | File | `/debug/pprof` | Medium
14 | File | `/device/signin` | High
15 | File | `/event/admin/?page=user/list` | High
16 | File | `/export` | Low
17 | File | `/forum/away.php` | High
18 | File | `/goform/QuickIndex` | High
19 | File | `/goform/setMacFilterCfg` | High
20 | File | `/goform/WifiMacFilterGet` | High
21 | File | `/h/calendar` | Medium
22 | File | `/horde/util/go.php` | High
23 | File | `/hrm/controller/employee.php` | High
24 | File | `/index.php?action=seomatic/file/seo-file-link` | High
25 | File | `/index.php?module=entities/fields&entities_id=24` | High
26 | File | `/irj/portal/` | Medium
27 | File | `/lib` | Low
28 | File | `/mkshope/login.php` | High
29 | File | `/nova/bin/sniffer` | High
30 | File | `/out.php` | Medium
31 | File | `/product/savenewproduct.php?flag=1` | High
32 | File | `/public/launchNewWindow.jsp` | High
33 | File | `/purchase_order/admin/?page=system_info` | High
34 | File | `/Redcock-Farm/farm/category.php` | High
35 | File | `/rules/REQUEST-942-APPLICATION-ATTACK-SQLI.conf` | High
36 | File | `/self.key` | Medium
37 | File | `/services/Card/findUser` | High
38 | File | `/services/view_service.php` | High
39 | File | `/sys/user/putRecycleBin` | High
40 | File | `/TestJDBC_Web/test2` | High
41 | ... | ... | ...

There are 351 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cisa.gov/uscert/ncas/alerts/aa22-335a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
