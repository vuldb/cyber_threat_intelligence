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
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Chimera. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.python-version` | High
2 | File | `/admin/inc/include.php` | High
3 | File | `/admin/index.php` | High
4 | File | `/alarm_pi/alarmService.php` | High
5 | File | `/app/controller/Books.php` | High
6 | File | `/appliance/users?action=edit` | High
7 | File | `/ATL/VQ23` | Medium
8 | File | `/bin/login` | Medium
9 | File | `/catcompany.php` | High
10 | File | `/cdsms/classes/Master.php?f=delete_enrollment` | High
11 | File | `/cgi-bin/kerbynet` | High
12 | File | `/cgi-bin/luci/api/wireless` | High
13 | File | `/cgi-bin/wlogin.cgi` | High
14 | File | `/coreframe/app/pay/admin/index.php` | High
15 | File | `/debug/pprof` | Medium
16 | File | `/etc/hosts` | Medium
17 | File | `/etc/quagga` | Medium
18 | File | `/etc/shadow` | Medium
19 | File | `/filemanager/php/connector.php` | High
20 | File | `/forum/away.php` | High
21 | File | `/h/search?action` | High
22 | File | `/home/iojs/build/ws/out/Release/obj.target/deps/openssl/openssl.cnf` | High
23 | File | `/index.php?action=seomatic/file/seo-file-link` | High
24 | File | `/index.php?p=admin/actions/users/send-password-reset-email` | High
25 | File | `/language/lang` | High
26 | File | `/loginsave.php` | High
27 | File | `/loginVaLidation.php` | High
28 | File | `/menu.html` | Medium
29 | File | `/MicroStrategyWS/happyaxis.jsp` | High
30 | File | `/modules/projects/vw_files.php` | High
31 | File | `/owa/auth/logon.aspx` | High
32 | File | `/ows-bin` | Medium
33 | File | `/public/plugins/` | High
34 | File | `/recreate.php` | High
35 | File | `/rest/collectors/1.0/template/custom` | High
36 | File | `/sql/sql_string.h` | High
37 | File | `/sql/sql_type.cc` | High
38 | ... | ... | ...

There are 326 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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
