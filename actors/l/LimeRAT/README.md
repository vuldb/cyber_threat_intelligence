# LimeRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [LimeRAT](https://vuldb.com/?actor.limerat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.limerat](https://vuldb.com/?actor.limerat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LimeRAT:

* [US](https://vuldb.com/?country.us)
* [UA](https://vuldb.com/?country.ua)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 31 more country items available. Please use our online service to access the data.

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

There are 72 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LimeRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LimeRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?ajax-request=jnews` | High
2 | File | `/Account/login.php` | High
3 | File | `/admin` | Low
4 | File | `/admin/` | Low
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/assets/` | High
7 | File | `/admin/category/view_category.php` | High
8 | File | `/admin/emp-profile-avatar.php` | High
9 | File | `/admin/foreigner-search.php` | High
10 | File | `/admin/index3.php` | High
11 | File | `/admin/regester.php` | High
12 | File | `/admin/system.html` | High
13 | File | `/admin/update_s6.php` | High
14 | File | `/ajax.php?action=delete_deductions` | High
15 | File | `/api/swaggerui/static` | High
16 | File | `/api/sys/login` | High
17 | File | `/apps/system/api/user.go` | High
18 | File | `/apps/system/router/upload.go` | High
19 | File | `/batm/app/admin/standalone/deployments` | High
20 | File | `/be/erpc.php` | Medium
21 | File | `/blog` | Low
22 | File | `/boafrm/formHomeWlanSetup` | High
23 | File | `/cap.js` | Low
24 | File | `/cgi-bin-igd/sys_log_clean.cgi` | High
25 | File | `/cgi-bin/nas_sharing.cgi` | High
26 | File | `/cgi-bin/p1_ftpserver.php` | High
27 | File | `/cgi-bin/s3.cgi` | High
28 | File | `/cgi-bin/vitogate.cgi` | High
29 | File | `/cgi-bin/wapopen` | High
30 | File | `/classes/Master.php` | High
31 | File | `/classes/Master.php?f=delete_category` | High
32 | File | `/common/info.cgi` | High
33 | File | `/control/register_case.php` | High
34 | File | `/controllers/add_client.php` | High
35 | File | `/customer_demo/index2.html` | High
36 | File | `/customer_register.php` | High
37 | File | `/DXR.axd` | Medium
38 | File | `/emloyee_akpoly/Account/login.php` | High
39 | File | `/EXCU_SHELL` | Medium
40 | File | `/forum/away.php` | High
41 | File | `/HNAP1` | Low
42 | File | `/index/ajax/lang` | High
43 | File | `/inventory/transactions_view.php` | High
44 | File | `/jfinal_cms/system/role/list` | High
45 | File | `/labvantage/rc?command=file&file=WEB-CORE/elements/files/filesembedded.jsp&size=32` | High
46 | File | `/librarian/bookdetails.php` | High
47 | File | `/manage_receiving.php` | High
48 | File | `/manage_sy.php` | High
49 | File | `/mhds/clinic/view_details.php` | High
50 | File | `/nagiosxi/admin/banner_message-ajaxhelper.php` | High
51 | File | `/ndmComponents.js` | High
52 | File | `/net-banking/delete_beneficiary.php` | High
53 | File | `/net-banking/edit_customer.php` | High
54 | File | `/net-banking/manage_customers.php` | High
55 | File | `/net-banking/send_funds.php` | High
56 | File | `/net-banking/send_funds_action.php` | High
57 | File | `/net-banking/transactions.php` | High
58 | File | `/oauth/idp/.well-known/openid-configuration` | High
59 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
60 | File | `/path/to/uploads/` | High
61 | File | `/plain` | Low
62 | ... | ... | ...

There are 538 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

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

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
