# Fodcha - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Fodcha](https://vuldb.com/?actor.fodcha). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.fodcha](https://vuldb.com/?actor.fodcha)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fodcha:

* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* [RU](https://vuldb.com/?country.ru)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fodcha.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.0.58.143](https://vuldb.com/?ip.3.0.58.143) | ec2-3-0-58-143.ap-southeast-1.compute.amazonaws.com | - | Medium
2 | [3.65.206.229](https://vuldb.com/?ip.3.65.206.229) | ec2-3-65-206-229.eu-central-1.compute.amazonaws.com | - | Medium
3 | [3.70.127.241](https://vuldb.com/?ip.3.70.127.241) | ec2-3-70-127-241.eu-central-1.compute.amazonaws.com | - | Medium
4 | [3.121.234.237](https://vuldb.com/?ip.3.121.234.237) | ec2-3-121-234-237.eu-central-1.compute.amazonaws.com | - | Medium
5 | [3.122.255.225](https://vuldb.com/?ip.3.122.255.225) | ec2-3-122-255-225.eu-central-1.compute.amazonaws.com | - | Medium
6 | [13.229.98.186](https://vuldb.com/?ip.13.229.98.186) | ec2-13-229-98-186.ap-southeast-1.compute.amazonaws.com | - | Medium
7 | [15.204.18.203](https://vuldb.com/?ip.15.204.18.203) | hosted-by.100up.net | - | High
8 | [15.204.18.232](https://vuldb.com/?ip.15.204.18.232) | shezmu.xyz | - | High
9 | [15.204.128.25](https://vuldb.com/?ip.15.204.128.25) | hosted-by.100up.net | - | High
10 | [18.136.209.2](https://vuldb.com/?ip.18.136.209.2) | ec2-18-136-209-2.ap-southeast-1.compute.amazonaws.com | - | Medium
11 | [18.185.188.32](https://vuldb.com/?ip.18.185.188.32) | ec2-18-185-188-32.eu-central-1.compute.amazonaws.com | - | Medium
12 | [23.183.83.171](https://vuldb.com/?ip.23.183.83.171) | - | - | High
13 | [31.214.245.253](https://vuldb.com/?ip.31.214.245.253) | vps-zap883671-1.zap-srv.com | - | High
14 | [45.41.240.145](https://vuldb.com/?ip.45.41.240.145) | hosted-by.100up.net | - | High
15 | [45.61.139.116](https://vuldb.com/?ip.45.61.139.116) | - | - | High
16 | [45.88.221.143](https://vuldb.com/?ip.45.88.221.143) | copouts.tinyblazer.com | - | High
17 | [45.135.135.33](https://vuldb.com/?ip.45.135.135.33) | - | - | High
18 | [45.140.169.122](https://vuldb.com/?ip.45.140.169.122) | wehomebuy.shop | - | High
19 | [45.147.200.168](https://vuldb.com/?ip.45.147.200.168) | - | - | High
20 | [46.17.41.79](https://vuldb.com/?ip.46.17.41.79) | mail.ama-fypf.ga | - | High
21 | ... | ... | ... | ...

There are 78 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Fodcha_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-425 | Pathname Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Injection | High
4 | T1059 | CWE-94 | Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Fodcha. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/CCMAdmin/serverlist.asp` | High
2 | File | `/cgi-bin/editBookmark` | High
3 | File | `/cgi-bin/koha/acqui/supplier.pl?op=enter` | High
4 | File | `/cgi-bin/wlogin.cgi` | High
5 | File | `/config` | Low
6 | File | `/debug/pprof` | Medium
7 | File | `/downloadmaster/dm_apply.cgi?action_mode=initial&download_type=General&special_cgi=get_language` | High
8 | File | `/etc/ajenti/config.yml` | High
9 | File | `/Items/*/RemoteImages/Download` | High
10 | File | `/main.php` | Medium
11 | File | `/Main_Login.asp?flag=1&productname=RT-AC88U&url=/downloadmaster/task.asp` | High
12 | File | `/new` | Low
13 | File | `/nova/bin/traceroute` | High
14 | File | `/opt/zimbra/jetty/webapps/zimbra/public` | High
15 | File | `/phpcollab/users/emailusers.php` | High
16 | File | `/proc/sys/kernel/rh_features` | High
17 | File | `/product.php` | Medium
18 | File | `/public/common/umeditor/php/getcontent.php` | High
19 | File | `/service/upload` | High
20 | File | `/Site/Troubleshooting/DiagnosticReport.asp` | High
21 | File | `/sitemagic/index.php` | High
22 | File | `/siteminderagent/pwcgi/smpwservicescgi.exe` | High
23 | File | `/sub?target=%TARGET%&url=%URL%&config=%CONFIG%` | High
24 | ... | ... | ...

There are 204 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.netlab.360.com/ddosmonster_the_return_of__fodcha_cn/
* https://blog.netlab.360.com/men-sheng-fa-da-cai-fodchajiang-shi-wang-luo/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
