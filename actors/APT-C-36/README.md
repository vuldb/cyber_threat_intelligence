# APT-C-36 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [APT-C-36](https://vuldb.com/?actor.apt-c-36). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.apt-c-36](https://vuldb.com/?actor.apt-c-36)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with APT-C-36:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [DE](https://vuldb.com/?country.de)
* ...

There are 20 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of APT-C-36.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [128.90.106.22](https://vuldb.com/?ip.128.90.106.22) | undefined.hostname.localhost | - | High
2 | [128.90.107.21](https://vuldb.com/?ip.128.90.107.21) | undefined.hostname.localhost | - | High
3 | [128.90.107.189](https://vuldb.com/?ip.128.90.107.189) | undefined.hostname.localhost | - | High
4 | ... | ... | ... | ...

There are 5 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _APT-C-36_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by APT-C-36. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.htaccess` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin/conferences/list/` | High
4 | File | `/admin/edit_admin_details.php?id=admin` | High
5 | File | `/admin/generalsettings.php` | High
6 | File | `/admin/payment.php` | High
7 | File | `/admin/reports.php` | High
8 | File | `/admin_page/all-files-update-ajax.php` | High
9 | File | `/bsms/?page=products` | High
10 | File | `/cgi-bin/kerbynet` | High
11 | File | `/cgi-bin/system_mgr.cgi` | High
12 | File | `/cloud_config/router_post/check_reg_verify_code` | High
13 | File | `/debug/pprof` | Medium
14 | File | `/dms/admin/reports/daily_collection_report.php` | High
15 | File | `/ext/phar/phar_object.c` | High
16 | File | `/filemanager/php/connector.php` | High
17 | File | `/forum/away.php` | High
18 | File | `/get_getnetworkconf.cgi` | High
19 | File | `/HNAP1` | Low
20 | File | `/include/chart_generator.php` | High
21 | File | `/info.cgi` | Medium
22 | File | `/Items/*/RemoteImages/Download` | High
23 | File | `/lists/admin/` | High
24 | File | `/MagickCore/image.c` | High
25 | File | `/mgmt/tm/util/bash` | High
26 | File | `/modx/manager/index.php` | High
27 | File | `/public/launchNewWindow.jsp` | High
28 | File | `/replication` | Medium
29 | File | `/siteminderagent/pwcgi/smpwservicescgi.exe` | High
30 | File | `/spip.php` | Medium
31 | File | `/TeleoptiWFM/Administration/GetOneTenant` | High
32 | File | `/type.php` | Medium
33 | File | `/usr/bin/pkexec` | High
34 | File | `/WEB-INF/web.xml` | High
35 | File | `/Wedding-Management/package_detail.php` | High
36 | File | `/wp-content/plugins/woocommerce/templates/emails/plain/` | High
37 | File | `4.2.0.CP09` | Medium
38 | File | `14all.cgi/14all-1.1.cgi/traffic.cgi/mrtg.cgi` | High
39 | File | `802dot1xclientcert.cgi` | High
40 | File | `a2billing/customer/iridium_threed.php` | High
41 | File | `AdClass.php` | Medium
42 | File | `add.exe` | Low
43 | File | `admin.color.php` | High
44 | File | `admin.cropcanvas.php` | High
45 | File | `admin.joomlaradiov5.php` | High
46 | File | `admin.php` | Medium
47 | File | `admin.php?m=Food&a=addsave` | High
48 | File | `admin/conf_users_edit.php` | High
49 | File | `admin/index.php` | High
50 | File | `admin/limits.php` | High
51 | File | `admin/write-post.php` | High
52 | File | `administrator/components/com_media/helpers/media.php` | High
53 | File | `admin_events.php` | High
54 | File | `akocomments.php` | High
55 | File | `allopass-error.php` | High
56 | File | `announcement.php` | High
57 | File | `apply.cgi` | Medium
58 | File | `appointment.php` | High
59 | ... | ... | ...

There are 515 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://web.archive.org/web/20190625182633if_/https://ti.360.net/blog/articles/apt-c-36-continuous-attacks-targeting-colombian-government-institutions-and-corporations-en/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
