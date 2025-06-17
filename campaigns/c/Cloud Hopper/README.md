# Cloud Hopper - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Cloud Hopper_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Cloud Hopper:

* [US](https://vuldb.com/?country.us)
* [CH](https://vuldb.com/?country.ch)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 6 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Cloud Hopper or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [APT10](https://vuldb.com/?actor.apt10) | High
2 | [menuPass](https://vuldb.com/?actor.menupass) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Cloud Hopper.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.89.193.34](https://vuldb.com/?ip.23.89.193.34) | - | [APT10](https://vuldb.com/?actor.apt10) | High
2 | [23.110.64.147](https://vuldb.com/?ip.23.110.64.147) | - | [APT10](https://vuldb.com/?actor.apt10) | High
3 | [23.252.105.137](https://vuldb.com/?ip.23.252.105.137) | 23.252.105.137.16clouds.com | [APT10](https://vuldb.com/?actor.apt10) | High
4 | [31.184.197.215](https://vuldb.com/?ip.31.184.197.215) | 31-184-197-215.static.x5x-noc.ru | [APT10](https://vuldb.com/?actor.apt10) | High
5 | [31.184.197.227](https://vuldb.com/?ip.31.184.197.227) | 31-184-197-227.static.x5x-noc.ru | [APT10](https://vuldb.com/?actor.apt10) | High
6 | [31.184.198.23](https://vuldb.com/?ip.31.184.198.23) | - | [APT10](https://vuldb.com/?actor.apt10) | High
7 | [31.184.198.38](https://vuldb.com/?ip.31.184.198.38) | - | [APT10](https://vuldb.com/?actor.apt10) | High
8 | [37.187.7.74](https://vuldb.com/?ip.37.187.7.74) | ns3372567.ip-37-187-7.eu | [APT10](https://vuldb.com/?actor.apt10) | High
9 | [37.235.52.18](https://vuldb.com/?ip.37.235.52.18) | 18.52.235.37.in-addr.arpa | [APT10](https://vuldb.com/?actor.apt10) | High
10 | [38.72.112.45](https://vuldb.com/?ip.38.72.112.45) | - | [APT10](https://vuldb.com/?actor.apt10) | High
11 | [38.72.114.16](https://vuldb.com/?ip.38.72.114.16) | - | [APT10](https://vuldb.com/?actor.apt10) | High
12 | [38.72.115.9](https://vuldb.com/?ip.38.72.115.9) | - | [APT10](https://vuldb.com/?actor.apt10) | High
13 | [45.62.112.161](https://vuldb.com/?ip.45.62.112.161) | 45.62.112.161.16clouds.com | [APT10](https://vuldb.com/?actor.apt10) | High
14 | [46.108.39.134](https://vuldb.com/?ip.46.108.39.134) | - | [APT10](https://vuldb.com/?actor.apt10) | High
15 | [50.2.160.104](https://vuldb.com/?ip.50.2.160.104) | - | [APT10](https://vuldb.com/?actor.apt10) | High
16 | [52.74.71.131](https://vuldb.com/?ip.52.74.71.131) | ec2-52-74-71-131.ap-southeast-1.compute.amazonaws.com | [APT10](https://vuldb.com/?actor.apt10) | Medium
17 | [52.74.213.16](https://vuldb.com/?ip.52.74.213.16) | ec2-52-74-213-16.ap-southeast-1.compute.amazonaws.com | [APT10](https://vuldb.com/?actor.apt10) | Medium
18 | [52.76.51.54](https://vuldb.com/?ip.52.76.51.54) | ec2-52-76-51-54.ap-southeast-1.compute.amazonaws.com | [APT10](https://vuldb.com/?actor.apt10) | Medium
19 | [54.67.66.177](https://vuldb.com/?ip.54.67.66.177) | ec2-54-67-66-177.us-west-1.compute.amazonaws.com | [APT10](https://vuldb.com/?actor.apt10) | Medium
20 | [54.68.71.43](https://vuldb.com/?ip.54.68.71.43) | ec2-54-68-71-43.us-west-2.compute.amazonaws.com | [APT10](https://vuldb.com/?actor.apt10) | Medium
21 | ... | ... | ... | ...

There are 80 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Cloud Hopper. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Cloud Hopper. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin/category/controller.php` | High
2 | File | `/admin/create_product.php` | High
3 | File | `/admin/general.cgi` | High
4 | File | `/admin/reminders/manage_reminder.php` | High
5 | File | `/API/info` | Medium
6 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
7 | File | `/Bloodgroop_process.php` | High
8 | File | `/CCMAdmin/serverlist.asp` | High
9 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
10 | File | `/cgi/get_param.cgi` | High
11 | File | `/csms/admin/inquiries/view_details.php` | High
12 | File | `/cstecgi.cgi` | Medium
13 | File | `/dashboard/updatelogo.php` | High
14 | File | `/ecommerce/support_ticket` | High
15 | File | `/etc/openshift/server_priv.pem` | High
16 | File | `/forum/away.php` | High
17 | File | `/home/search` | Medium
18 | File | `/hrm/employeeview.php` | High
19 | File | `/include/chart_generator.php` | High
20 | File | `/index.php` | Medium
21 | File | `/librarian/bookdetails.php` | High
22 | File | `/licenses` | Medium
23 | File | `/members/view_member.php` | High
24 | File | `/messageboard/view.php` | High
25 | File | `/mhds/clinic/view_details.php` | High
26 | File | `/mkshop/Men/profile.php` | High
27 | File | `/Noxen-master/users.php` | High
28 | File | `/out.php` | Medium
29 | File | `/owa/auth/logon.aspx` | High
30 | File | `/rest/api/latest/projectvalidate/key` | High
31 | File | `/spip.php` | Medium
32 | File | `/SVFE2/pages/feegroups/country_group.jsf` | High
33 | File | `/textpattern/index.php` | High
34 | File | `/uncpath/` | Medium
35 | File | `/upfile.cgi` | Medium
36 | File | `/webui/modules/log/operate.mds` | High
37 | File | `/wordpress/wp-admin/admin.php` | High
38 | File | `/wuser/anyUserBoundHouse.php` | High
39 | File | `/_vti_bin/_vti_log` | High
40 | ... | ... | ...

There are 343 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/janhenrikdotcom/iocs/blob/master/APT10/Operation%20Cloud%20Hopper%20-%20Indicators%20of%20Compromise%20v3.csv
* https://github.com/PwCUK-CTO/OperationCloudHopper/blob/master/cloud-hopper-indicators-of-compromise-v3.csv
* https://www.pwc.co.uk/cyber-security/pdf/cloud-hopper-annex-b-final.pdf
* https://www.threatminer.org/report.php?q=cloud-hopper-indicators-of-compromise-v3-PwC.pdf&y=2017

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2025](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
