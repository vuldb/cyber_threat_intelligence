# Campaign 0 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Campaign 0_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Campaign 0:

* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)
* [CO](https://vuldb.com/?country.co)
* ...

There are 1 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Campaign 0 or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Campaign 0.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.13.139.105](https://vuldb.com/?ip.5.13.139.105) | 5-13-139-105.residential.rdsnet.ro | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
2 | [5.59.65.104](https://vuldb.com/?ip.5.59.65.104) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
3 | [5.108.69.57](https://vuldb.com/?ip.5.108.69.57) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
4 | [6.70.116.102](https://vuldb.com/?ip.6.70.116.102) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
5 | [6.119.67.75](https://vuldb.com/?ip.6.119.67.75) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
6 | [8.47.71.43](https://vuldb.com/?ip.8.47.71.43) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
7 | [10.33.44.94](https://vuldb.com/?ip.10.33.44.94) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
8 | [10.118.75.18](https://vuldb.com/?ip.10.118.75.18) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
9 | [10.143.48.52](https://vuldb.com/?ip.10.143.48.52) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
10 | [12.40.29.71](https://vuldb.com/?ip.12.40.29.71) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
11 | [13.65.24.145](https://vuldb.com/?ip.13.65.24.145) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
12 | [14.47.117.104](https://vuldb.com/?ip.14.47.117.104) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
13 | [16.9.79.28](https://vuldb.com/?ip.16.9.79.28) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
14 | [16.29.27.126](https://vuldb.com/?ip.16.29.27.126) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
15 | [16.95.70.136](https://vuldb.com/?ip.16.95.70.136) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
16 | [16.127.81.67](https://vuldb.com/?ip.16.127.81.67) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
17 | [16.127.136.51](https://vuldb.com/?ip.16.127.136.51) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
18 | [19.140.51.9](https://vuldb.com/?ip.19.140.51.9) | - | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
19 | [23.24.92.121](https://vuldb.com/?ip.23.24.92.121) | 23-24-92-121-static.hfc.comcastbusiness.net | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
20 | [24.54.58.144](https://vuldb.com/?ip.24.54.58.144) | 24-54-58-144.resi.cgocable.ca | [Kwampirs](https://vuldb.com/?actor.kwampirs) | High
21 | ... | ... | ... | ...

There are 82 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Campaign 0. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-88, CWE-94 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Campaign 0. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=email/api/mark&op=delFromSend` | High
2 | File | `/admin/maintenance/view_designation.php` | High
3 | File | `/analysisProject/pagingQueryData` | High
4 | File | `/api/admin/system/store/order/list` | High
5 | File | `/api/baskets/{name}` | High
6 | File | `/apply_noauth.cgi` | High
7 | File | `/bin/ate` | Medium
8 | File | `/bin/sh` | Low
9 | File | `/booking/show_bookings/` | High
10 | File | `/classes/Master.php?f=delete_category` | High
11 | File | `/classes/Master.php?f=save_service` | High
12 | File | `/common/sysFile/list` | High
13 | File | `/concat?/%2557EB-INF/web.xml` | High
14 | File | `/context/%2e/WEB-INF/web.xml` | High
15 | File | `/Controller/Ajaxfileupload.ashx` | High
16 | File | `/data/remove` | Medium
17 | File | `/debug/pprof` | Medium
18 | File | `/Default/Bd` | Medium
19 | File | `/etc/openstack-dashboard/local_settings` | High
20 | File | `/etc/passwd` | Medium
21 | File | `/goform/addressNat` | High
22 | File | `/goform/AdvSetLanip` | High
23 | File | `/goform/fromSetWirelessRepeat` | High
24 | File | `/goform/setmac` | High
25 | File | `/goform/setMacFilterCfg` | High
26 | File | `/goform/SetSysTimeCfg` | High
27 | File | `/goform/WifiGuestSet` | High
28 | File | `/inc/jquery/uploadify/uploadify.php` | High
29 | File | `/js/player/dmplayer/dmku/index.php` | High
30 | File | `/kelasdosen/data` | High
31 | File | `/KK_LS9ReportingPortal/GetData` | High
32 | File | `/modules/snf/index.php` | High
33 | File | `/news/*.html` | Medium
34 | File | `/orrs/admin/?page=user/manage_user` | High
35 | File | `/secure/QueryComponent!Default.jspa` | High
36 | File | `/Service/ImageStationDataService.asmx` | High
37 | File | `/static/ueditor/php/controller.php` | High
38 | File | `/subtitles.php` | High
39 | File | `/usr/sbin/httpd` | High
40 | File | `/views/directive/sys/SysConfigDataDirective.java` | High
41 | File | `/wp-admin/admin-ajax.php` | High
42 | File | `/x_program_center/jaxrs/invoke` | High
43 | File | `/_next` | Low
44 | File | `?r=article/category/del` | High
45 | File | `?r=dashboard/roleadmin/edit&op=member` | High
46 | File | `adclick.php` | Medium
47 | ... | ... | ...

There are 406 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blog.reversinglabs.com/hubfs/Blog/IOC%20list/Campaign_0_IOC.txt

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
