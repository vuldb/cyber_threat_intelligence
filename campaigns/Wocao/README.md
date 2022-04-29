# Wocao - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Wocao_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Wocao:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [IL](https://vuldb.com/?country.il)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Wocao or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Wocao](https://vuldb.com/?actor.wocao) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Wocao.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.254.211.108](https://vuldb.com/?ip.23.254.211.108) | hwsrv-871243.hostwindsdns.com | [Wocao](https://vuldb.com/?actor.wocao) | High
2 | [31.222.185.215](https://vuldb.com/?ip.31.222.185.215) | 31-222-185-215.static.cloud-ips.co.uk | [Wocao](https://vuldb.com/?actor.wocao) | High
3 | [45.77.229.10](https://vuldb.com/?ip.45.77.229.10) | 45.77.229.10.vultr.com | [Wocao](https://vuldb.com/?actor.wocao) | Medium
4 | ... | ... | ... | ...

There are 13 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Wocao. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/admin/art/data.html` | High
2 | File | `/admin.php/admin/vod/data.html` | High
3 | File | `/admin.php?id=siteoptions&social=edit&sid=2` | High
4 | File | `/admin.php?r=admin/AdminBackup/del` | High
5 | File | `/admin/edit.php` | High
6 | File | `/admin/goods/update` | High
7 | File | `/admin/inbox.php&action=delete` | High
8 | File | `/admin/inbox.php&action=read` | High
9 | File | `/admin/pagerole.php&action=edit` | High
10 | File | `/admin/posts.php` | High
11 | File | `/admin/posts.php&action=delete` | High
12 | File | `/admin/siteoptions.php&action=displaygoal&value=1&roleid=1` | High
13 | File | `/admin/siteoptions.php&social=remove&sid=2` | High
14 | File | `/admin/uesrs.php&&action=delete&userid=4` | High
15 | File | `/admin/uesrs.php&action=display&value=Hide` | High
16 | File | `/admin/uesrs.php&action=display&value=Show` | High
17 | File | `/admin/uesrs.php&action=type&userrole=User` | High
18 | File | `/administrator/alerts/alertLightbox.php` | High
19 | File | `/api/eventinstance` | High
20 | File | `/api /v3/auth` | High
21 | File | `/appliance/users?action=edit` | High
22 | File | `/apps/acs-commons/content/page-compare.html` | High
23 | File | `/blog/blog.php` | High
24 | File | `/cdsms/classes/Master.php?f=delete_package` | High
25 | File | `/cmd?cmd=connect` | High
26 | File | `/cwms/admin/?page=articles/view_article/` | High
27 | File | `/cwms/classes/Master.php?f=save_contact` | High
28 | File | `/etc/puppetlabs/puppetserver/conf.d/ca.conf` | High
29 | File | `/etc/zarafa/license` | High
30 | File | `/goform/login_process` | High
31 | File | `/hocms/classes/Master.php?f=delete_member` | High
32 | File | `/hocms/classes/Master.php?f=delete_phase` | High
33 | File | `/include/make.php` | High
34 | File | `/index.php?m=admin&c=custom&a=plugindelhandle` | High
35 | File | `/jpg/image.jpg` | High
36 | File | `/login` | Low
37 | File | `/manager/files` | High
38 | File | `/module/api.php?mobile/wapNasIPS` | High
39 | ... | ... | ...

There are 340 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/fox-it/operation-wocao

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
