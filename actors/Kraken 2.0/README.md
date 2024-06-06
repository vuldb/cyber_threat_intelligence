# Kraken 2.0 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Kraken 2.0](https://vuldb.com/?actor.kraken_2.0). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.kraken_2.0](https://vuldb.com/?actor.kraken_2.0)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Kraken 2.0:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [VN](https://vuldb.com/?country.vn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Kraken 2.0.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Kraken 2.0_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-29 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Kraken 2.0. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/` | Low
2 | File | `/admin/admin_user.php` | High
3 | File | `/admin/category/save` | High
4 | File | `/admin/list_ipAddressPolicy.php` | High
5 | File | `/admin/subject.php` | High
6 | File | `/auth/auth.php?user=1` | High
7 | File | `/boaform/device_reset.cgi` | High
8 | File | `/cgi-bin/cstecgi.cgi` | High
9 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
10 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
11 | File | `/cgi-bin/nas_sharing.cgi` | High
12 | File | `/cgi-bin/system_mgr.cgi` | High
13 | File | `/cgi-bin/wlogin.cgi` | High
14 | File | `/cgi/cpaddons_report.pl` | High
15 | File | `/common/dict/list` | High
16 | File | `/debug/pprof` | Medium
17 | File | `/DXR.axd` | Medium
18 | File | `/forum/away.php` | High
19 | File | `/goform/DhcpListClient` | High
20 | File | `/goform/goform_get_cmd_process` | High
21 | File | `/HNAP1/` | Low
22 | File | `/hrm/leaverequest.php` | High
23 | File | `/importexport.php` | High
24 | File | `/install/` | Medium
25 | File | `/Interface/DevManage/VM.php` | High
26 | File | `/main/doctype.php` | High
27 | File | `/main/webservices/additional_webservices.php` | High
28 | File | `/mc` | Low
29 | File | `/ndmComponents.js` | High
30 | File | `/net/bluetooth/rfcomm/core.C` | High
31 | File | `/oauth/idp/.well-known/openid-configuration` | High
32 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
33 | File | `/pdf` | Low
34 | File | `/register.php` | High
35 | File | `/remote/put_file` | High
36 | File | `/setting/NTPSyncWithHost` | High
37 | File | `/spip.php` | Medium
38 | File | `/squashfs-root/etc_ro/custom.conf` | High
39 | File | `/src/c-blosc2/plugins/codecs/ndlz/ndlz4x4.c` | High
40 | ... | ... | ...

There are 343 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
