# LimeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LimeRAT](https://vuldb.com/?actor.limerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.limerat](https://vuldb.com/?actor.limerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LimeRAT:

* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* [IN](https://vuldb.com/?country.in)
* ...

There are 17 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LimeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.212.39](https://vuldb.com/?ip.2.56.212.39) | ip-2-56-212-39-59599.vps.hosted-by-mvps.net | - | High
2 | [3.17.7.232](https://vuldb.com/?ip.3.17.7.232) | ec2-3-17-7-232.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.22.30.40](https://vuldb.com/?ip.3.22.30.40) | ec2-3-22-30-40.us-east-2.compute.amazonaws.com | - | Medium
4 | [3.124.142.205](https://vuldb.com/?ip.3.124.142.205) | ec2-3-124-142-205.eu-central-1.compute.amazonaws.com | - | Medium
5 | [3.131.207.170](https://vuldb.com/?ip.3.131.207.170) | ec2-3-131-207-170.us-east-2.compute.amazonaws.com | - | Medium
6 | [3.141.177.1](https://vuldb.com/?ip.3.141.177.1) | ec2-3-141-177-1.us-east-2.compute.amazonaws.com | - | Medium
7 | [3.142.81.166](https://vuldb.com/?ip.3.142.81.166) | ec2-3-142-81-166.us-east-2.compute.amazonaws.com | - | Medium
8 | [3.142.167.4](https://vuldb.com/?ip.3.142.167.4) | ec2-3-142-167-4.us-east-2.compute.amazonaws.com | - | Medium
9 | [13.229.238.144](https://vuldb.com/?ip.13.229.238.144) | ec2-13-229-238-144.ap-southeast-1.compute.amazonaws.com | - | Medium
10 | [20.199.13.167](https://vuldb.com/?ip.20.199.13.167) | - | - | High
11 | [20.231.17.198](https://vuldb.com/?ip.20.231.17.198) | - | - | High
12 | [27.3.162.17](https://vuldb.com/?ip.27.3.162.17) | - | - | High
13 | [31.210.55.103](https://vuldb.com/?ip.31.210.55.103) | 31-210-55-103.hostlab.net.tr | - | High
14 | [38.242.239.137](https://vuldb.com/?ip.38.242.239.137) | vmi1081127.contaboserver.net | - | High
15 | ... | ... | ... | ...

There are 57 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LimeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-36 | Pathname Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LimeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/admin/?n=logs&c=index&a=dode` | High
3 | File | `/admin/?page=orders/manage_request` | High
4 | File | `/admin/addbookmark.php` | High
5 | File | `/admin/files` | Medium
6 | File | `/admin/update_s6.php` | High
7 | File | `/admin/users/index.php` | High
8 | File | `/alphaware/details.php` | High
9 | File | `/api/v2/cli/commands` | High
10 | File | `/api/ZRQos/set_online_client` | High
11 | File | `/articles/welcome-to-your-site#comments-head` | High
12 | File | `/batm/app/admin/standalone/deployments` | High
13 | File | `/binbloom-master/src/helpers.c` | High
14 | File | `/blog` | Low
15 | File | `/boafrm/formHomeWlanSetup` | High
16 | File | `/cgi-bin/kerbynet` | High
17 | File | `/ci_hms/massage_room/edit/1` | High
18 | File | `/classes/Master.php?f=delete_reservation` | High
19 | File | `/core/kernels/ctc_decoder_ops.cc` | High
20 | File | `/crmeb/app/admin/controller/store/CopyTaobao.php` | High
21 | File | `/dashboard/settings` | High
22 | File | `/dashboard/system/express/entities/forms/save_control/[GUID]` | High
23 | File | `/dev/dri/card1` | High
24 | File | `/diagnostic/login.php` | High
25 | File | `/ecrire/tools/blogroll/index.php` | High
26 | File | `/employeeview.php` | High
27 | File | `/enterprise/www/student.php` | High
28 | File | `/etc/config/image_sign` | High
29 | File | `/etc/sudoers` | Medium
30 | File | `/files/$username/Myfolder/Mysubfolder/shared.txt` | High
31 | File | `/forum/away.php` | High
32 | File | `/garage/editclient.php` | High
33 | File | `/gasmark/assets/myimages/oneWord.php` | High
34 | File | `/hocms/classes/Master.php?f=delete_phase` | High
35 | File | `/hrm/controller/employee.php` | High
36 | File | `/index.php` | Medium
37 | File | `/lam/tmp/` | Medium
38 | File | `/logs/sql-error.log` | High
39 | File | `/ManageRoute/postRoute` | High
40 | File | `/mkshop/Men/profile.php` | High
41 | File | `/newVersion` | Medium
42 | File | `/onlineordering/GPST/admin/design.php` | High
43 | File | `/out.php` | Medium
44 | File | `/PC/WebService.asmx` | High
45 | File | `/preauth` | Medium
46 | File | `/search.php` | Medium
47 | File | `/Source/C++/Core/Ap4DataBuffer.cpp` | High
48 | File | `/spip.php` | Medium
49 | ... | ... | ...

There are 427 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
