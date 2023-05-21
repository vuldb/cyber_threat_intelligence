# xHunt - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [xHunt](https://vuldb.com/?actor.xhunt). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.xhunt](https://vuldb.com/?actor.xhunt)

## Campaigns

The following _campaigns_ are known and can be associated with xHunt:

* BumbleBee

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with xHunt:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [NL](https://vuldb.com/?country.nl)
* ...

There are 36 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of xHunt.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.92.127.18](https://vuldb.com/?ip.23.92.127.18) | - | BumbleBee | High
2 | [46.246.3.253](https://vuldb.com/?ip.46.246.3.253) | - | BumbleBee | High
3 | [46.246.3.254](https://vuldb.com/?ip.46.246.3.254) | - | BumbleBee | High
4 | [77.243.191.20](https://vuldb.com/?ip.77.243.191.20) | - | BumbleBee | High
5 | [82.102.21.219](https://vuldb.com/?ip.82.102.21.219) | - | BumbleBee | High
6 | [84.17.55.68](https://vuldb.com/?ip.84.17.55.68) | unn-84-17-55-68.cdn77.com | BumbleBee | High
7 | [85.203.46.99](https://vuldb.com/?ip.85.203.46.99) | - | BumbleBee | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _xHunt_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-37 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
5 | T1059.007 | CWE-79, CWE-80, CWE-87 | Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by xHunt. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.../gogo/` | Medium
2 | File | `.procmailrc` | Medium
3 | File | `//proc/kcore` | Medium
4 | File | `/?ajax-request=jnews` | High
5 | File | `/admin/?page=user/manage` | High
6 | File | `/admin/addemployee.php` | High
7 | File | `/admin/edit.php` | High
8 | File | `/admin/index.PHP` | High
9 | File | `/admin/login.php` | High
10 | File | `/admin/maintenance/view_designation.php` | High
11 | File | `/admin/manage_academic.php` | High
12 | File | `/admin/products/manage_product.php` | High
13 | File | `/admin/students/manage.php` | High
14 | File | `/admin/students/view_student.php` | High
15 | File | `/adms/admin/?page=vehicles/view_transaction` | High
16 | File | `/alerts/alertConfigField.php` | High
17 | File | `/api/user/upsert/<uuid>` | High
18 | File | `/appliance/users?action=edit` | High
19 | File | `/backup.pl` | Medium
20 | File | `/bits/stl_vector.h` | High
21 | File | `/bsms_ci/index.php` | High
22 | File | `/cgi-bin/wlogin.cgi` | High
23 | File | `/dashboard/add-portfolio.php` | High
24 | File | `/dashboard/updatelogo.php` | High
25 | File | `/edoc/doctor/patient.php` | High
26 | File | `/etc/gsissh/sshd_config` | High
27 | File | `/etc/ldap.conf` | High
28 | File | `/etc/shadow` | Medium
29 | File | `/face-recognition-php/facepay-master/camera.php` | High
30 | File | `/foms/place-order.php` | High
31 | File | `/forum/away.php` | High
32 | File | `/goform/wizard_end` | High
33 | File | `/h/calendar` | Medium
34 | File | `/h/compose` | Medium
35 | File | `/h/search?action=voicemail&action=listen` | High
36 | File | `/hrm/employeeview.php` | High
37 | File | `/index.php` | Medium
38 | File | `/loginVaLidation.php` | High
39 | File | `/manage-apartment.php` | High
40 | File | `/manager/index.php` | High
41 | File | `/mcategory.php` | High
42 | File | `/mkshop/Men/profile.php` | High
43 | File | `/modules/projects/vw_files.php` | High
44 | File | `/Noxen-master/users.php` | High
45 | File | `/opac/Actions.php?a=login` | High
46 | File | `/pages/animals.php` | High
47 | File | `/pet_shop/admin/orders/update_status.php` | High
48 | File | `/php-scrm/login.php` | High
49 | File | `/php-sms/classes/Master.php` | High
50 | File | `/php-sms/classes/SystemSettings.php` | High
51 | File | `/php_action/createOrder.php` | High
52 | File | `/php_action/createUser.php` | High
53 | File | `/php_action/editProductImage.php` | High
54 | File | `/reservation/add_message.php` | High
55 | File | `/ResiotQueryDBActive` | High
56 | File | `/reviewer_0/admins/assessments/pretest/questions-view.php` | High
57 | File | `/royal_event/companyprofile.php` | High
58 | ... | ... | ...

There are 508 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://unit42.paloaltonetworks.com/bumblebee-webshell-xhunt-campaign/
* https://unit42.paloaltonetworks.com/xhunt-campaign-backdoors/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
