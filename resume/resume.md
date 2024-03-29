<!-- https://markdowntohtml.com/ to convert -->
<!-- tidy -im -w 120 index.html # to tidy -->
<title>Brian Cunnie</title>

<h2 align="center">Brian Cunnie</h2>

<h4 align="center">Software Developer</h4>

<p align="center">
1711 Washington St. Apt 8<br />
San Francisco, CA  94109<br />
cell: 650.968.6262<br />
brian.cunnie@gmail.com
</p>

### Objective

**Not currently looking**, but if I were, it would be for a four-day workweek
software developer position in the San Francisco Bay Area, one accessible by
public transportation, with pair programming.

### Skills

_Programming Languages (Test Frameworks)_: Golang (Ginkgo), Ruby (RSpec), Python
(unittest), Javascript/ReactJS (Jasmine, Jest), Java, bash, Perl, C, C++, APL,
Assembler

_Tools and Declarative Languages_: Cloud Foundry CLI, BOSH, git, JetBrains's
IDEs (Goland, RubyMine, WebStorm, PyCharm), Android Studio, CSS, HTML, Concourse
CI, ZFS, SQL, svn

_Operating System and Infrastructures-as-a-Service (IaaSes)_: macOS, Linux,
FreeBSD, ESXi (vSphere), FreeBSD, MS Windows, Amazon AWS, Microsoft Azure,
Google Cloud Platform (GCP), VMware vSphere

_Network Protocols & Services_: TCP/IP (routing, DHCP, IPv6, NDP, firewalls
(iptables and pf)), DNS (BIND, named, djbdns, PowerDNS), email (Sendmail, qmail,
Postfix), HTTP servers (Apache, nginx)

### Experience

**Software Engineer, [Broadcom](https://broadcom.com/) (formerly VMware, formerly Pivotal), San Francisco, CA<br />
6/11 to present**

- BOSH: maintained BOSH, a virtual machine (VM) orchestrator (Ruby) CPIs:
  maintained the Ruby-based Cloud Provider Interface (CPI,interface between
  BOSH and IaaS). Wrote the underlying API calls for AWS and vSphere. (Ruby)
  Operations Manager: developed and maintained Operations Manager, a
  Ruby-on-Rails application which acts as a front end to Pivotal's commercial
  Cloud Foundry and Kubernetes offerings. Went on-call, helped customers
  resolve technical issues.
- Autoscaler and Scheduler Team: maintained two cloud-based applications
  (written in a smorgasbord of languages: Golang, Kotlin, Java, Groovy, Bash).
  Much of the work was bug fixes and CVE mitigations through dependency bumps
- V3 Acceleration Team: enhanced the Cloud Foundry API (CAPI), a Ruby-based MVC
  application, to include new endpoints, new features. At the same time,
  enhanced the Cloud Foundry CLI, a Golang-based application, to take advantage
  of the new endpoints and new features
- TAS NSX-T: built automated test infrastructure to test interoperability
  between Pivotal's cloud offering (TAS) and VMware's software-defined network
  (NSX-T), addressed issues with appropriate organizations
- Cloud Operations: maintained Pivotal Web Services (PWS), Pivotal's
  public-facing Cloud Foundry. Deployed updates several times a week, addressed
  GDPR compliance, and diagnosed, remedied, and documented outages
- Release Engineering: wrote the tooling that tested the each release of the
  Pivotal Cloud Foundry software (Ruby)
- Toolsmiths: maintained vSphere environments used by the development teams

**Systems Administrator, Arda Technologies (acquired by
[Google](https://www.google.com/)), Mountain View, CA<br />
12/07 to 6/11**

Provided computer support for an IC Design Startup.

* Managed the following machines:
    * 35 Linux machines (mostly RHEL5, one RHEL3, two Fedora (12,13)),
    * 20 Windows machines (mostly laptops, Windows 7, Vista),
    * 3 FreeBSD machines (2 firewalls, 1 backup),
    * 1 NetApp,
    * 3 DD-WRT WiFi access points
* Maintained DNS, LDAP, NFS
* Implemented a fairly complex backup system (using a combination of perl scripts, rsync, cron, svnadmin dump, ZFS snapshots)
* Configured firewalls (FreeBSD) and VPN (OpenVPN)
* Configured redundant Internet connections (Comcast Cable and AT&T DSL)
* Hand-crafted two iterations of the corporate website (using XHTML, PHP, and CSS)
* Troubleshot and tuned as needed. Spec'ed and purchased equipment as needed

**Systems Administrator, Aeluros (acquired by
[Broadcom](https://www.broadcom.com/)), Mountain View, CA<br />
3/02 to 12/07**

Provided computer support for an IC Design Startup.

* Managed the following machines:
    * 100 Linux machines
    * 20 Windows machines (Finance, Marketing, Sales),
    * 3 Solaris 8 (legacy license and print servers),
    * 2 HPUX machines (offline Agilent 8k testers).
* Coded the chip-testing GUI in Perl/Tk for eval kits for our chips to the customers, modified to accommodate new product lines and new features
* Hand-built the external mail server using a combination of cyrus-imapd, sendmail, Apache, SquirrelMail, and OpenLDAP. Also implemented a calendar server using Apache, MySQL, OpenLDAP, and PHP
* Maintained firewalls, redundant internet connections, DNS, YP/NIS, NFS system internally, backups of our corporate intellectual property (IP), spec'd and purchased equipment

### Extracurricular Activities

I run [sslip.io](https://sslip.io/), a DNS service which maps specially-crafted
hostnames to IP addresses. It made the top spot on Hacker News when I announced
it.

I also run five servers in the [NTP pool](https://www.ntppool.org/user/cunnie)
which carry an aggregate of 1% of the US NTP pool traffic.

I (with Dmitriy Kalinin) added [IPv6 support to
BOSH](https://bosh.io/docs/guide-ipv6-on-vsphere/).

I [contribute](https://github.com/cunnie?tab=contributions) to open source
projects. My favorite contribution: updating Ruby's core library, openssl, to
[correctly verify abbreviated IPv6
SANs](https://github.com/ruby/openssl/commit/9322a104d16b02c7a79f9ab589859c9d63fabf52).

I [blog](https://blog.nono.io) what captures my interest, including debugging
the vSphere API via the BOSH vSphere CPI
([1](https://blog.nono.io/post/debugging_vsphere_cpi_api/)), how to install a
TLS certificate on VMware NSX 4.1 ([1](https://blog.nono.io/post/nsx_tls/)),
on-premise is almost four times cheaper than the cloud
([1](https://blog.nono.io/post/on-premise_vs_cloud/)), the least secure way to
backup vCenter 8.0 with TrueNAS 13.0
([1](https://blog.nono.io/post/backup_vcenter_w_truenas/)), creating
multi-platform Docker images with Concourse CI
([1](https://blog.nono.io/post/multi-platform_docker_images_with_concourse/)),
how to install a TLS certificate on vCenter Server Appliance (VCSA) 8.0
([1](https://blog.nono.io/post/vcenter_8.0_tls/)), tuning HAProxy in a vSphere
environment ([1](https://blog.nono.io/post/tuning_haproxy/)), the underground
guide to Cloud Foundry Acceptance Tests
([1](https://blog.nono.io/post/underground_guide_to_cf_acceptance/)), disk
controller benchmarks: VMware Paravirtual's vs. LSI Logic Parallel's
([1](https://blog.nono.io/post/pvscsi/)), Concourse CI on Kubernetes (GKE)
([1](https://blog.nono.io/post/concourse_on_k8s-1/),
[2](https://blog.nono.io/post/concourse_on_k8s-2/),
[3](https://blog.nono.io/post/concourse_on_k8s-3/),
[4](https://blog.nono.io/post/concourse_on_k8s-4/),
[5](https://blog.nono.io/post/concourse_on_k8s-5/),
[6](https://blog.nono.io/post/concourse_on_k8s-6/)) how to best organize your
Golang unit tests
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/flow-your-tests-like-your-code-2)),
how to enable IPv6 on Cloud Foundry's HAProxy
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/how-to-enable-ipv6-on-your-cloud-foundrys-haproxy-2)),
benchmarks of a 10 GbE-backed NAS server
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/a-high-performing-mid-range-nas-server-part-3-10-gbe-2)),
transferring time-based one-time passwords to a new smartphone
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/transferring-time-based-one-time-passwords-to-a-new-smartphone-2)),
uncovering a man-in-the-middle SSH proxy
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/troubleshooting-obscure-openssh-failures-2)),
how to install a TLS Certificate on vCenter server appliance (VCSA)
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/how-to-install-a-tls-certificate-on-vcenter-server-appliance-vcsa-6-7-updated-for-vcenter-7)),
benchmarking the disk speed of IaaSes
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/benchmarking-the-disk-speed-of-iaases-2)),
deploying BOSH VMs with IPv6 addresses to vSphere
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/deploying-bosh-vms-with-ipv6-addresses-on-vsphere-2))
and to AWS
([2](https://tanzu.vmware.com/content/pivotal-engineering-journal/bosh-deployed-to-an-ipv6-environment-on-vsphere)),
maintaining BOSH Directors with Concourse CI and bosh-deployment
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/maintaining-bosh-directors-with-concourse-ci-and-bosh-deployment-2)),
why is my NTP server costing me $500/year
([1](https://tanzu.vmware.com/content/blog/why-is-my-ntp-server-costing-500-year-part-1)
(top spot on Hacker News),
[2](https://tanzu.vmware.com/content/blog/why-is-my-ntp-server-costing-me-500-year-part-2-characterizing-the-ntp-clients),
[3](https://tanzu.vmware.com/content/pivotal-engineering-journal/why-is-my-ntp-server-costing-500-year-part-3-2)),
deploying a BOSH Director With SSL certificates issued by a commercial CA
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/deploying-a-bosh-director-with-ssl-certificates-issued-by-commercial-ca)),
how to customize a BOSH stemcell
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/how-to-customize-a-bosh-stemcell-2)),
updating a BOSH Release
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/updating-a-bosh-release-2)),
Concourse CI has badges
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/concourse-has-badges-3)),
Concourse CI without a load balancer
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/concourse-without-a-load-balancer-3)),
the world's smallest Concourse CI server
([1](https://tanzu.vmware.com/content/pivotal-engineering-journal/the-worlds-smallest-concourse-ci-server-2)),
setting up and benchmarking the iSCSI performance of a ZFS fileserver
([1](https://tanzu.vmware.com/content/blog/a-high-performing-mid-range-nas-server),
[2](https://tanzu.vmware.com/content/blog/a-high-performing-mid-range-nas-server-part-2-performance-tuning-for-iscsi)),
installing Cloud Foundry in a home lab
([1](https://tanzu.vmware.com/content/blog/worlds-smallest-iaas-part-1),
[2](https://tanzu.vmware.com/content/blog/worlds-smallest-iaas-part-2),
[3](https://tanzu.vmware.com/content/blog/worlds-smallest-iaas-part-3-the-paas),
and
[4](https://tanzu.vmware.com/content/blog/worlds-smallest-iaas-part-4-hello-world)),
setting up a DNS, NTP and nginx server in the cloud
([1](https://tanzu.vmware.com/content/blog/setting-up-a-freebsd-server-on-hetzner-part-1-base-install-and-ssh),
[2](https://tanzu.vmware.com/content/blog/setting-up-a-freebsd-server-on-hetzner-part-2-dns-nameserver),
[3](https://tanzu.vmware.com/content/blog/your-server-has-participated-in-a-very-large-scale-attack),
[4](https://tanzu.vmware.com/content/blog/setting-up-a-freebsd-server-on-hetzner-part-4-nginx),
and
[5](https://tanzu.vmware.com/content/blog/setting-up-a-freebsd-server-on-hetzner-part-5-php-ssi-ssl-redirects)),
configuring and troubleshooting an IPv6 firewall
([1](https://tanzu.vmware.com/content/blog/configuring-freebsd-9-1-as-a-native-ipv6-dhcp-client),
[2](https://tanzu.vmware.com/content/blog/a-barebones-pf-ipv6-firewall-ruleset),
[3](https://tanzu.vmware.com/content/blog/how-i-grabbed-18-quintillion-ip-addresses-from-comcast-and-they-didnt-even-care),
and
[4](https://tanzu.vmware.com/content/blog/troubleshooting-ipv6-firewall-rulesets-using-tcpdump-and-pflog)),
using Ruby Expect to control network appliances
([1](https://tanzu.vmware.com/content/blog/using-ruby-expect-library-to-reboot-ruckus-wireless-access-points-via-ssh)),
using DNS-SD to make printing easier
([1](https://tanzu.vmware.com/content/blog/making-printers-and-common-resources-available-to-separate-network-segments-via-bonjour-and-dns-sd)),
locking down an ethernet network
([1](https://tanzu.vmware.com/content/blog/shunting-ethernet-guests-to-a-safe-network)),
and many more. I've written blog posts as part of my job as well, and do not
include those posts in the above list.

I swim in the San Francisco Bay and play rugby.

### Education

[Stevens Institute of Technology](https://www.stevens.edu/sit/), June 1989<br />
Master of Science and Engineering, Major in Telecommunications Engineering

[University of Pennsylvania](https://www.upenn.edu/), August 1986<br />
Bachelor of Science and Engineering, Major in Computer Science Engineering

Ongoing, non-degree-related education:

- [Front-End Web Development with React](https://www.coursera.org/account/accomplishments/certificate/VS6C5XTSSF6K) (2019)
- Build a Modern Computer from First Principles: Nand to Tetris: Parts
  [1](https://www.coursera.org/account/accomplishments/certificate/3GXLPXU6MFRM) (2015) and
  [2](https://www.coursera.org/account/accomplishments/certificate/8PFEYLD45R) (2018)
- Programming Mobile Applications for Android Handheld Systems: Part
  [1](https://www.coursera.org/account/accomplishments/certificate/YCZ54M3QJU) (2015)
- [Web Application
  Architectures](https://www.coursera.org/account/accomplishments/certificate/BT4R5EZX9Z)
  (Ruby on Rails) (2014)
- An Introduction to Interactive Programming in Python: Parts
  [1](https://www.coursera.org/account/accomplishments/certificate/NC9TKC5YDE) and
  [2](https://www.coursera.org/account/accomplishments/certificate/6FCYBUF2MX) (2013)

### Honors

National Merit Scholar
