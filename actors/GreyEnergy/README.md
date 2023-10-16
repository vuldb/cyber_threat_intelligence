# GreyEnergy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [GreyEnergy](https://vuldb.com/?actor.greyenergy). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.greyenergy](https://vuldb.com/?actor.greyenergy)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with GreyEnergy:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* ...

There are 14 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of GreyEnergy.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.23.82.72](https://vuldb.com/?ip.1.23.82.72) | - | - | High
2 | [2.2.82.64](https://vuldb.com/?ip.2.2.82.64) | - | - | High
3 | [2.12.51.56](https://vuldb.com/?ip.2.12.51.56) | arennes-655-1-148-56.w2-12.abo.wanadoo.fr | - | High
4 | [3.95.29.25](https://vuldb.com/?ip.3.95.29.25) | ec2-3-95-29-25.compute-1.amazonaws.com | - | Medium
5 | [5.149.248.77](https://vuldb.com/?ip.5.149.248.77) | - | - | High
6 | [19.2.45.3](https://vuldb.com/?ip.19.2.45.3) | - | - | High
7 | [21.15.46.55](https://vuldb.com/?ip.21.15.46.55) | - | - | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _GreyEnergy_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24, CWE-28 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by GreyEnergy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/about.php` | Medium
3 | File | `/admin.php/accessory/filesdel.html` | High
4 | File | `/admin/?page=user/manage` | High
5 | File | `/admin/add-new.php` | High
6 | File | `/admin/doctors.php` | High
7 | File | `/admin/submit-articles` | High
8 | File | `/alphaware/summary.php` | High
9 | File | `/api/` | Low
10 | File | `/api/admin/store/product/list` | High
11 | File | `/api/baskets/{name}` | High
12 | File | `/api/stl/actions/search` | High
13 | File | `/api/v2/cli/commands` | High
14 | File | `/attachments` | Medium
15 | File | `/bin/ate` | Medium
16 | File | `/boat/login.php` | High
17 | File | `/booking/show_bookings/` | High
18 | File | `/bsms_ci/index.php/book` | High
19 | File | `/cgi-bin` | Medium
20 | File | `/cgi-bin/luci/api/wireless` | High
21 | File | `/cgi-bin/wlogin.cgi` | High
22 | File | `/Content/Template/root/reverse-shell.aspx` | High
23 | File | `/context/%2e/WEB-INF/web.xml` | High
24 | File | `/dashboard/add-blog.php` | High
25 | File | `/debug/pprof` | Medium
26 | File | `/DXR.axd` | Medium
27 | File | `/env` | Low
28 | File | `/etc/hosts` | Medium
29 | File | `/forum/away.php` | High
30 | File | `/goform/formSetEmail` | High
31 | File | `/goform/setmac` | High
32 | File | `/goform/wizard_end` | High
33 | File | `/group1/uploa` | High
34 | File | `/InternalPages/ExecuteTask.aspx` | High
35 | File | `/medicines/profile.php` | High
36 | File | `/modules/caddyhttp/rewrite/rewrite.go` | High
37 | File | `/opac/Actions.php?a=login` | High
38 | File | `/owa/auth/logon.aspx` | High
39 | File | `/php-sms/admin/?page=user/manage_user` | High
40 | File | `/proxy` | Low
41 | File | `/reservation/add_message.php` | High
42 | File | `/resources//../` | High
43 | File | `/spip.php` | Medium
44 | ... | ... | ...

There are 381 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/greyenergy
* https://github.com/eset/malware-ioc/tree/master/quarterly_reports/2020_Q3
* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
