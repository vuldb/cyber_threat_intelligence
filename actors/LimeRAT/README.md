# LimeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LimeRAT](https://vuldb.com/?actor.limerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.limerat](https://vuldb.com/?actor.limerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LimeRAT:

* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* [IN](https://vuldb.com/?country.in)
* ...

There are 18 more country items available. Please use our online service to access the data.

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
15 | [41.225.34.198](https://vuldb.com/?ip.41.225.34.198) | - | - | High
16 | [45.88.79.224](https://vuldb.com/?ip.45.88.79.224) | free.example.com | - | High
17 | ... | ... | ... | ...

There are 64 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LimeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-29, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LimeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/admin/?n=logs&c=index&a=dode` | High
3 | File | `/admin/?page=orders/manage_request` | High
4 | File | `/admin/files` | Medium
5 | File | `/admin/regester.php` | High
6 | File | `/admin/update_s6.php` | High
7 | File | `/admin/users/index.php` | High
8 | File | `/alphaware/details.php` | High
9 | File | `/api/sys/login` | High
10 | File | `/api/v2/cli/commands` | High
11 | File | `/articles/welcome-to-your-site#comments-head` | High
12 | File | `/batm/app/admin/standalone/deployments` | High
13 | File | `/be/erpc.php` | Medium
14 | File | `/binbloom-master/src/helpers.c` | High
15 | File | `/blog` | Low
16 | File | `/boafrm/formHomeWlanSetup` | High
17 | File | `/cgi-bin/kerbynet` | High
18 | File | `/ci_hms/massage_room/edit/1` | High
19 | File | `/classes/Master.php?f=delete_reservation` | High
20 | File | `/common/info.cgi` | High
21 | File | `/core/kernels/ctc_decoder_ops.cc` | High
22 | File | `/crmeb/app/admin/controller/store/CopyTaobao.php` | High
23 | File | `/dashboard/settings` | High
24 | File | `/dashboard/system/express/entities/forms/save_control/[GUID]` | High
25 | File | `/diagnostic/login.php` | High
26 | File | `/ecrire/tools/blogroll/index.php` | High
27 | File | `/employeeview.php` | High
28 | File | `/enterprise/www/student.php` | High
29 | File | `/etc/config/image_sign` | High
30 | File | `/etc/sudoers` | Medium
31 | File | `/files/$username/Myfolder/Mysubfolder/shared.txt` | High
32 | File | `/forum/away.php` | High
33 | File | `/garage/editclient.php` | High
34 | File | `/gasmark/assets/myimages/oneWord.php` | High
35 | File | `/hocms/classes/Master.php?f=delete_phase` | High
36 | File | `/hrm/controller/employee.php` | High
37 | File | `/inventory/transactions_view.php` | High
38 | File | `/lam/tmp/` | Medium
39 | File | `/logs/sql-error.log` | High
40 | File | `/ManageRoute/postRoute` | High
41 | File | `/mkshop/Men/profile.php` | High
42 | File | `/newVersion` | Medium
43 | File | `/oauth/idp/.well-known/openid-configuration` | High
44 | File | `/out.php` | Medium
45 | File | `/PC/WebService.asmx` | High
46 | File | `/preauth` | Medium
47 | File | `/search.php` | Medium
48 | File | `/Source/C++/Core/Ap4DataBuffer.cpp` | High
49 | File | `/spip.php` | Medium
50 | ... | ... | ...

There are 433 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://lab52.io/blog/apt-c-36-from-njrat-to-apt-c-36/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
