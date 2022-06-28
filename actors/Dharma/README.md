# Dharma - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Dharma](https://vuldb.com/?actor.dharma). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.dharma](https://vuldb.com/?actor.dharma)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dharma.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [178.239.173.172](https://vuldb.com/?ip.178.239.173.172) | 172.173.239.178.baremetal.zare.com | - | High
2 | [185.20.187.20](https://vuldb.com/?ip.185.20.187.20) | 185.20.187.20.deltahost-ptr | - | High
3 | [217.138.202.116](https://vuldb.com/?ip.217.138.202.116) | - | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dharma_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1008 | CWE-757 | Algorithm Downgrade | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dharma. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/deluser.php` | High
2 | File | `/admin/dl_sendmail.php` | High
3 | File | `/admin/operations/tax.php` | High
4 | File | `/admin/showbad.php` | High
5 | File | `/admin/ztliuyan_sendmail.php` | High
6 | File | `/api/v2/config` | High
7 | File | `/appinfo/save` | High
8 | File | `/ATL/VQ23` | Medium
9 | File | `/cgi-bin/ExportAllSettings.sh` | High
10 | File | `/coreframe/app/pay/admin/index.php` | High
11 | File | `/dashboard/snapshot/*?orgId=0` | High
12 | File | `/dl/dl_sendmail.php` | High
13 | File | `/dl/dl_sendsms.php` | High
14 | File | `/ffos/admin/categories/manage_category.php` | High
15 | File | `/ffos/admin/categories/view_category.php` | High
16 | File | `/ffos/admin/menus/manage_menu.php` | High
17 | File | `/ffos/admin/sales/receipt.php` | High
18 | File | `/ffos/classes/Master.php?f=delete_category` | High
19 | File | `/ffos/classes/Master.php?f=delete_img` | High
20 | File | `/ffos/classes/Master.php?f=delete_menu` | High
21 | File | `/hprms/admin/?page=patients/view_patient` | High
22 | File | `/hprms/admin/?page=user/manage_user` | High
23 | File | `/hprms/admin/doctors/manage_doctor.php` | High
24 | File | `/hprms/admin/doctors/view_doctor.php` | High
25 | ... | ... | ...

There are 210 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-Dharma-RaaS.csv
* https://thedfirreport.com/2020/04/14/dharma-ransomware/
* https://thedfirreport.com/2020/06/16/the-little-ransomware-that-couldnt-dharma/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
