# LimeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LimeRAT](https://vuldb.com/?actor.limerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.limerat](https://vuldb.com/?actor.limerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LimeRAT:

* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 32 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LimeRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [2.56.212.39](https://vuldb.com/?ip.2.56.212.39) | ip-2-56-212-39-59599.vps.hosted-by-mvps.net | - | High
2 | [3.17.7.232](https://vuldb.com/?ip.3.17.7.232) | ec2-3-17-7-232.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.22.30.40](https://vuldb.com/?ip.3.22.30.40) | ec2-3-22-30-40.us-east-2.compute.amazonaws.com | - | Medium
4 | [3.124.142.205](https://vuldb.com/?ip.3.124.142.205) | ec2-3-124-142-205.eu-central-1.compute.amazonaws.com | - | Medium
5 | [3.125.209.94](https://vuldb.com/?ip.3.125.209.94) | ec2-3-125-209-94.eu-central-1.compute.amazonaws.com | - | Medium
6 | [3.131.207.170](https://vuldb.com/?ip.3.131.207.170) | ec2-3-131-207-170.us-east-2.compute.amazonaws.com | - | Medium
7 | [3.141.177.1](https://vuldb.com/?ip.3.141.177.1) | ec2-3-141-177-1.us-east-2.compute.amazonaws.com | - | Medium
8 | [3.142.81.166](https://vuldb.com/?ip.3.142.81.166) | ec2-3-142-81-166.us-east-2.compute.amazonaws.com | - | Medium
9 | [3.142.167.4](https://vuldb.com/?ip.3.142.167.4) | ec2-3-142-167-4.us-east-2.compute.amazonaws.com | - | Medium
10 | [13.229.238.144](https://vuldb.com/?ip.13.229.238.144) | ec2-13-229-238-144.ap-southeast-1.compute.amazonaws.com | - | Medium
11 | [18.158.249.75](https://vuldb.com/?ip.18.158.249.75) | ec2-18-158-249-75.eu-central-1.compute.amazonaws.com | - | Medium
12 | [18.192.31.165](https://vuldb.com/?ip.18.192.31.165) | ec2-18-192-31-165.eu-central-1.compute.amazonaws.com | - | Medium
13 | [18.229.146.63](https://vuldb.com/?ip.18.229.146.63) | ec2-18-229-146-63.sa-east-1.compute.amazonaws.com | - | Medium
14 | [18.229.248.167](https://vuldb.com/?ip.18.229.248.167) | ec2-18-229-248-167.sa-east-1.compute.amazonaws.com | - | Medium
15 | [18.231.93.153](https://vuldb.com/?ip.18.231.93.153) | ec2-18-231-93-153.sa-east-1.compute.amazonaws.com | - | Medium
16 | [20.199.13.167](https://vuldb.com/?ip.20.199.13.167) | - | - | High
17 | [20.231.17.198](https://vuldb.com/?ip.20.231.17.198) | - | - | High
18 | [27.3.162.17](https://vuldb.com/?ip.27.3.162.17) | - | - | High
19 | ... | ... | ... | ...

There are 73 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LimeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LimeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/Account/login.php` | High
3 | File | `/accounts_con/register_account` | High
4 | File | `/admin` | Low
5 | File | `/admin/` | Low
6 | File | `/admin/?page=user/list` | High
7 | File | `/admin/assets/` | High
8 | File | `/admin/bookList?page=1&limit=10` | High
9 | File | `/admin/category.php` | High
10 | File | `/admin/category/view_category.php` | High
11 | File | `/admin/cmsTagType/save` | High
12 | File | `/admin/convert/export_z3950.php` | High
13 | File | `/admin/edit-card-detail.php` | High
14 | File | `/admin/emp-profile-avatar.php` | High
15 | File | `/admin/foreigner-search.php` | High
16 | File | `/admin/index.php` | High
17 | File | `/admin/index2.html` | High
18 | File | `/admin/process_category_add.php` | High
19 | File | `/admin/read.php` | High
20 | File | `/admin/regester.php` | High
21 | File | `/admin/registration.php` | High
22 | File | `/admin/system.html` | High
23 | File | `/adminapi/system/crud` | High
24 | File | `/ajax.php?action=delete_deductions` | High
25 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
26 | File | `/api/swaggerui/static` | High
27 | File | `/api/sys/login` | High
28 | File | `/api/wizard/setsyncpppoecfg` | High
29 | File | `/apps/system/api/user.go` | High
30 | File | `/apps/system/router/upload.go` | High
31 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
32 | File | `/backend/admin/his_admin_register_patient.php` | High
33 | File | `/be/erpc.php` | Medium
34 | File | `/blog` | Low
35 | File | `/boafrm/formStaticDHCP` | High
36 | File | `/cap.js` | Low
37 | File | `/cgi-bin/cstecgi.cgi` | High
38 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
39 | File | `/cgi-bin/info.cgi` | High
40 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
41 | File | `/cgi-bin/nas_sharing.cgi` | High
42 | File | `/cgi-bin/p1_ftpserver.php` | High
43 | File | `/cgi-bin/s3.cgi` | High
44 | File | `/cgi-bin/vitogate.cgi` | High
45 | File | `/classes/Master.php` | High
46 | File | `/classes/Master.php?f=delete_category` | High
47 | File | `/com/esafenet/servlet/ajax/MultiServerAjax.java` | High
48 | File | `/common/info.cgi` | High
49 | File | `/control/register_case.php` | High
50 | File | `/controllers/add_client.php` | High
51 | File | `/customer_demo/index2.html` | High
52 | File | `/customer_register.php` | High
53 | File | `/dataSet/resolveSql` | High
54 | File | `/details2.php` | High
55 | File | `/downloadFile.php` | High
56 | ... | ... | ...

There are 490 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/5ec2650940db1e24271b84e5553d8454f17a7c99cbb36579aa843aa09798efe3/
* https://bazaar.abuse.ch/sample/93a09a5ecefc75e6fda23d83deffeffddf544da2103a75422e768d26cfe9ee7f/
* https://lab52.io/blog/apt-c-36-from-njrat-to-apt-c-36/
* https://threatfox.abuse.ch

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
