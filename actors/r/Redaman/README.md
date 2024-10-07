# Redaman - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Redaman](https://vuldb.com/?actor.redaman). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.redaman](https://vuldb.com/?actor.redaman)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Redaman:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [LV](https://vuldb.com/?country.lv)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Redaman.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [35.216.85.217](https://vuldb.com/?ip.35.216.85.217) | 217.85.216.35.bc.googleusercontent.com | - | Medium
2 | [35.216.185.203](https://vuldb.com/?ip.35.216.185.203) | 203.185.216.35.bc.googleusercontent.com | - | Medium
3 | [54.151.91.200](https://vuldb.com/?ip.54.151.91.200) | ec2-54-151-91-200.us-west-1.compute.amazonaws.com | - | Medium
4 | [54.151.172.105](https://vuldb.com/?ip.54.151.172.105) | ec2-54-151-172-105.ap-southeast-1.compute.amazonaws.com | - | Medium
5 | [59.149.85.217](https://vuldb.com/?ip.59.149.85.217) | 059149085217.ctinets.com | - | High
6 | [59.149.171.48](https://vuldb.com/?ip.59.149.171.48) | 059149171048.ctinets.com | - | High
7 | [69.5.100.66](https://vuldb.com/?ip.69.5.100.66) | dynamic-69-5-100-66.molalla.net | - | High
8 | [69.5.172.104](https://vuldb.com/?ip.69.5.172.104) | - | - | High
9 | [72.50.91.200](https://vuldb.com/?ip.72.50.91.200) | adsl-72-50-91-200.prtc.net | - | High
10 | [72.50.185.234](https://vuldb.com/?ip.72.50.185.234) | mca-e-72-50-185-234.resnet.wvu.edu | - | High
11 | [78.108.216.39](https://vuldb.com/?ip.78.108.216.39) | mail.saity.info | - | High
12 | [85.217.59.149](https://vuldb.com/?ip.85.217.59.149) | adsl-85-217-59-149.kotinet.com | - | High
13 | [85.217.94.156](https://vuldb.com/?ip.85.217.94.156) | - | - | High
14 | [85.217.170.51](https://vuldb.com/?ip.85.217.170.51) | - | - | High
15 | [85.217.171.48](https://vuldb.com/?ip.85.217.171.48) | - | - | High
16 | [91.200.69.5](https://vuldb.com/?ip.91.200.69.5) | 91-200-69-5.partnet.com.pl | - | High
17 | ... | ... | ... | ...

There are 62 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Redaman_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Redaman. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/edit.php` | High
2 | File | `/admin/index.php` | High
3 | File | `/api/index.php` | High
4 | File | `/bin/goahead` | Medium
5 | File | `/cgi-bin-sdb/` | High
6 | File | `/cgi-bin/cstecgi.cgi` | High
7 | File | `/cgi-bin/logo_extra_upload.cgi` | High
8 | File | `/debug/pprof` | Medium
9 | File | `/downloadFile.php` | High
10 | File | `/endpoint/delete-account.php` | High
11 | File | `/etc/passwd` | Medium
12 | File | `/etc/shadow.sample` | High
13 | File | `/foms/routers/place-order.php` | High
14 | File | `/inc/extensions.php` | High
15 | File | `/index.php` | Medium
16 | File | `/index.php?page=tenants` | High
17 | File | `/mfeedback.php` | High
18 | File | `/MIME/INBOX-MM-1/` | High
19 | File | `/ServletAPI/accounts/login` | High
20 | File | `/sqfs/bin/sccd` | High
21 | File | `/uncpath/` | Medium
22 | File | `/var/WEB-GUI/cgi-bin/downloadfile.cgi` | High
23 | File | `/wp-admin/admin-ajax.php` | High
24 | File | `/wp-content/plugins/updraftplus/admin.php` | High
25 | ... | ... | ...

There are 206 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://research.checkpoint.com/2019/ponys-cc-servers-hidden-inside-the-bitcoin-blockchain/
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
