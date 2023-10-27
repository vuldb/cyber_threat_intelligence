# Vobfus - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Vobfus](https://vuldb.com/?actor.vobfus). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.vobfus](https://vuldb.com/?actor.vobfus)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Vobfus:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Vobfus.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [13.107.21.200](https://vuldb.com/?ip.13.107.21.200) | - | - | High
2 | [18.211.9.206](https://vuldb.com/?ip.18.211.9.206) | ec2-18-211-9-206.compute-1.amazonaws.com | - | Medium
3 | [23.20.239.12](https://vuldb.com/?ip.23.20.239.12) | ec2-23-20-239-12.compute-1.amazonaws.com | - | Medium
4 | [37.48.65.148](https://vuldb.com/?ip.37.48.65.148) | - | - | High
5 | [45.202.208.234](https://vuldb.com/?ip.45.202.208.234) | - | - | High
6 | [46.166.182.115](https://vuldb.com/?ip.46.166.182.115) | - | - | High
7 | [52.137.90.34](https://vuldb.com/?ip.52.137.90.34) | - | - | High
8 | [64.32.8.67](https://vuldb.com/?ip.64.32.8.67) | customer.sharktech.net | - | High
9 | [67.225.218.50](https://vuldb.com/?ip.67.225.218.50) | lb01.parklogic.com | - | High
10 | ... | ... | ... | ...

There are 38 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Vobfus_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Vobfus. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/adfs/ls` | Medium
2 | File | `/admin/inquiries/view_details.php` | High
3 | File | `/api/RecordingList/DownloadRecord?file=` | High
4 | File | `/api/sys/set_passwd` | High
5 | File | `/app/controller/Books.php` | High
6 | File | `/bin/boa` | Medium
7 | File | `/cgi-bin/wapopen` | High
8 | File | `/config/getuser` | High
9 | File | `/context/%2e/WEB-INF/web.xml` | High
10 | File | `/dev/urandom` | Medium
11 | File | `/etc/ajenti/config.yml` | High
12 | File | `/etc/quantum/quantum.conf` | High
13 | File | `/etc/shadow` | Medium
14 | File | `/exec/` | Low
15 | File | `/forum/away.php` | High
16 | File | `/getcfg.php` | Medium
17 | File | `/goform/dir_setWanWifi` | High
18 | File | `/HNAP1` | Low
19 | File | `/mgmt/tm/util/bash` | High
20 | File | `/MIME/INBOX-MM-1/` | High
21 | File | `/modules/projects/vw_files.php` | High
22 | File | `/opt/tms/bin/cli` | High
23 | File | `/out.php` | Medium
24 | File | `/plain` | Low
25 | File | `/server-status` | High
26 | File | `/setSystemAdmin` | High
27 | File | `/staff/tools/custom-fields` | High
28 | File | `/tmp/phpglibccheck` | High
29 | File | `/uncpath/` | Medium
30 | File | `/WebMstr7/servlet/mstrWeb` | High
31 | File | `/webpages/data` | High
32 | File | `/wp-admin/options.php` | High
33 | File | `/wp-content/plugins/updraftplus/admin.php` | High
34 | File | `/wp-content/plugins/woocommerce/templates/emails/plain/` | High
35 | File | `/wp-json/oembed/1.0/embed?url` | High
36 | File | `/xyhai.php?s=/Auth/editUser` | High
37 | File | `/_next` | Low
38 | File | `account.asp` | Medium
39 | File | `actionHandler/ajax_managed_services.php` | High
40 | File | `adclick.php` | Medium
41 | ... | ... | ...

There are 350 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/04/threat-roundup-0329-0405.html
* https://blog.talosintelligence.com/2019/04/threat-roundup-0412-0419.html
* https://blog.talosintelligence.com/2019/06/threat-roundup-0607-0614.html
* https://blog.talosintelligence.com/2019/07/threat-roundup-0628-0705.html
* https://blog.talosintelligence.com/2019/11/threat-roundup-1115-1122.html
* https://blog.talosintelligence.com/2020/01/threat-roundup-0117-0124.html
* https://blog.talosintelligence.com/2020/04/threat-roundup-0417-0424.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0617-0624.html
* https://blog.talosintelligence.com/threat-roundup-0106-0113/
* https://blog.talosintelligence.com/threat-roundup-0414-0421-3/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
