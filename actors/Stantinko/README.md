# Stantinko - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Stantinko](https://vuldb.com/?actor.stantinko). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.stantinko](https://vuldb.com/?actor.stantinko)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Stantinko:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)
* [UA](https://vuldb.com/?country.ua)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Stantinko.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.16.30.155](https://vuldb.com/?ip.3.16.30.155) | ec2-3-16-30-155.us-east-2.compute.amazonaws.com | - | Medium
2 | [3.16.31.23](https://vuldb.com/?ip.3.16.31.23) | ec2-3-16-31-23.us-east-2.compute.amazonaws.com | - | Medium
3 | [3.16.150.123](https://vuldb.com/?ip.3.16.150.123) | ec2-3-16-150-123.us-east-2.compute.amazonaws.com | - | Medium
4 | [3.16.152.64](https://vuldb.com/?ip.3.16.152.64) | ec2-3-16-152-64.us-east-2.compute.amazonaws.com | - | Medium
5 | [3.16.152.201](https://vuldb.com/?ip.3.16.152.201) | ec2-3-16-152-201.us-east-2.compute.amazonaws.com | - | Medium
6 | [3.16.167.92](https://vuldb.com/?ip.3.16.167.92) | ec2-3-16-167-92.us-east-2.compute.amazonaws.com | - | Medium
7 | [3.17.23.144](https://vuldb.com/?ip.3.17.23.144) | ec2-3-17-23-144.us-east-2.compute.amazonaws.com | - | Medium
8 | [3.17.25.11](https://vuldb.com/?ip.3.17.25.11) | ec2-3-17-25-11.us-east-2.compute.amazonaws.com | - | Medium
9 | [3.17.59.6](https://vuldb.com/?ip.3.17.59.6) | ec2-3-17-59-6.us-east-2.compute.amazonaws.com | - | Medium
10 | [3.17.61.161](https://vuldb.com/?ip.3.17.61.161) | ec2-3-17-61-161.us-east-2.compute.amazonaws.com | - | Medium
11 | [3.17.167.43](https://vuldb.com/?ip.3.17.167.43) | ec2-3-17-167-43.us-east-2.compute.amazonaws.com | - | Medium
12 | [3.18.108.152](https://vuldb.com/?ip.3.18.108.152) | ec2-3-18-108-152.us-east-2.compute.amazonaws.com | - | Medium
13 | [3.18.223.195](https://vuldb.com/?ip.3.18.223.195) | ec2-3-18-223-195.us-east-2.compute.amazonaws.com | - | Medium
14 | [13.58.22.81](https://vuldb.com/?ip.13.58.22.81) | ec2-13-58-22-81.us-east-2.compute.amazonaws.com | - | Medium
15 | [13.58.23.11](https://vuldb.com/?ip.13.58.23.11) | ec2-13-58-23-11.us-east-2.compute.amazonaws.com | - | Medium
16 | [13.58.77.225](https://vuldb.com/?ip.13.58.77.225) | ec2-13-58-77-225.us-east-2.compute.amazonaws.com | - | Medium
17 | [13.58.182.92](https://vuldb.com/?ip.13.58.182.92) | ec2-13-58-182-92.us-east-2.compute.amazonaws.com | - | Medium
18 | [13.58.249.138](https://vuldb.com/?ip.13.58.249.138) | ec2-13-58-249-138.us-east-2.compute.amazonaws.com | - | Medium
19 | [13.59.31.61](https://vuldb.com/?ip.13.59.31.61) | ec2-13-59-31-61.us-east-2.compute.amazonaws.com | - | Medium
20 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Stantinko_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-307, CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 8 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Stantinko. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%SYSTEMDRIVE%` | High
2 | File | `/admin.php?action=editpage` | High
3 | File | `/admin/web_config.php&amp` | High
4 | File | `/alphaware/details.php` | High
5 | File | `/core/kernels/ctc_decoder_ops.cc` | High
6 | File | `/etc/controller-agent/agent.conf` | High
7 | File | `/etc/shadow` | Medium
8 | File | `/evaluate/index.php` | High
9 | File | `/forum/away.php` | High
10 | File | `/goform/setmac` | High
11 | File | `/goform/setportList` | High
12 | File | `/goform/setVLAN` | High
13 | File | `/gofrom/setwanType` | High
14 | File | `/hcms/admin/index.php/language/ajax` | High
15 | File | `/index.class.php` | High
16 | File | `/knowage/restful-services/documentnotes/saveNote` | High
17 | File | `/log_download.cgi` | High
18 | File | `/MIME/INBOX-MM-1/` | High
19 | File | `/new` | Low
20 | File | `/nova/bin/diskd` | High
21 | File | `/nova/bin/lcdstat` | High
22 | File | `/proc/pid/syscall` | High
23 | File | `/servlet/AdapterHTTP` | High
24 | File | `/tmp` | Low
25 | File | `/user/ldap_user/add` | High
26 | File | `/wp-admin/upload.php?page=instant-images` | High
27 | File | `admin/article/add.html` | High
28 | File | `admin/navbar.php?action=add_page` | High
29 | File | `admin/plugin-settings.php` | High
30 | File | `admin/user_import.php` | High
31 | File | `admin/wenjian.php?wj=../templets/pc` | High
32 | File | `administrative` | High
33 | File | `Administrative` | High
34 | ... | ... | ...

There are 287 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/stantinko

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
