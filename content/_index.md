---
name: "Tsvetan Gerov"
tagline: "Site Reliability Engineer"
location: "Bulgaria"
company: "hosting.com"
about: "Senior Site Reliability Engineer with 10+ years of experience spanning Sysadmin, DevOps, and SRE roles. I design and operate large-scale infrastructure, lead teams through the hard problems, and keep complex systems reliable under pressure. Deeply passionate about open source, Linux, automation, and modern observability."

origin: "It started with a disc on the cover of a PC Magazine. I was 12, maybe 13, when I peeled it off and found Red Hat 6.x — the old one, long before RHEL existed. I had no idea what I was holding, but I had to find out. Hours of reading led to more questions than answers, and the installation never quite worked. Resources were thin back then, and almost nothing existed in Bulgarian. Then my father did something that changed everything: he bought me a book — in Bulgarian — about Red Hat 7.3. I still have it on my shelf. That book was my window into a world that made sense to me in a way nothing else had. I read it cover to cover, and somewhere between the chapters on filesystems and package management, I knew exactly who I was going to become."

skill_groups:
  - category: "Operating Systems"
    accent: "#FCC624"
    span: 2
    items:
      - { name: "RHEL", color: "#EE0000", icon: "devicon-redhat-plain" }
      - { name: "Fedora", color: "#3C6EB4", icon: "devicon-fedora-plain" }
      - { name: "CloudLinux", color: "#008000" }
      - { name: "Ubuntu", color: "#E95420", icon: "devicon-ubuntu-plain" }
      - { name: "Debian", color: "#A80030", icon: "devicon-debian-plain" }
      - { name: "Gentoo", color: "#54487A", icon: "devicon-gentoo-plain" }
      - { name: "Slackware", color: "#4A4A4A" }
      - { name: "FreeBSD", color: "#AB2B28", icon: "devicon-freebsd-plain" }
      - { name: "OpenBSD", color: "#F5A623" }
  - category: "Scripting"
    accent: "#4EAA25"
    span: 1
    items:
      - { name: "Bash", color: "#4EAA25", icon: "devicon-bash-plain" }
      - { name: "Python", color: "#3776AB", icon: "devicon-python-plain" }
      - { name: "PHP", color: "#777BB4", icon: "devicon-php-plain" }
  - category: "Automation & IaC"
    accent: "#EE0000"
    span: 2
    items:
      - { name: "Ansible / AWX", color: "#EE0000", icon: "devicon-ansible-plain" }
      - { name: "Salt", color: "#57BCAD" }
      - { name: "Puppet", color: "#FFAE1A", icon: "devicon-puppet-plain" }
      - { name: "Terraform", color: "#7B42BC", icon: "devicon-terraform-plain" }
      - { name: "CI/CD", color: "#3fb950", icon: "devicon-githubactions-plain" }
  - category: "Containers & Virtualisation"
    accent: "#2496ED"
    span: 2
    items:
      - { name: "Podman", color: "#892CA0", icon: "devicon-podman-plain" }
      - { name: "Docker", color: "#2496ED", icon: "devicon-docker-plain" }
      - { name: "LXC / LXD", color: "#E95420" }
      - { name: "OpenVZ", color: "#3A7DBD" }
      - { name: "Proxmox", color: "#E57000" }
      - { name: "KVM", color: "#F46800" }
      - { name: "Xen", color: "#0078C8" }
  - category: "Databases"
    accent: "#336791"
    span: 1
    items:
      - { name: "MariaDB / MySQL", color: "#00758F", icon: "devicon-mysql-plain" }
      - { name: "PostgreSQL", color: "#336791", icon: "devicon-postgresql-plain" }
  - category: "Observability"
    accent: "#F46800"
    span: 2
    items:
      - { name: "Prometheus", color: "#E6522C", icon: "devicon-prometheus-plain" }
      - { name: "Thanos", color: "#6D41FF" }
      - { name: "Grafana", color: "#F46800", icon: "devicon-grafana-plain" }
      - { name: "AlertManager", color: "#E6522C" }
      - { name: "PagerDuty", color: "#06AC38" }
      - { name: "Icinga / Nagios", color: "#06A694" }
      - { name: "Zabbix", color: "#CC0000" }
  - category: "DNS & Hosting"
    accent: "#58A6FF"
    span: 1
    items:
      - { name: "PowerDNS", color: "#58A6FF" }
      - { name: "Bind", color: "#8b949e" }
      - { name: "Web Servers", color: "#009639", icon: "devicon-nginx-plain" }
      - { name: "cPanel", color: "#FF6C2C" }
      - { name: "Plesk", color: "#52BBE6" }
  - category: "Mail Servers"
    accent: "#F46800"
    span: 1
    items:
      - { name: "Exim", color: "#336791" }
      - { name: "Postfix", color: "#CC0000" }
      - { name: "Dovecot", color: "#1A73E8" }

experience:
  - company: "Hosting.com"
    tenure: "Apr 2023 — Present · 3 yrs"
    roles:
      - title: "Senior Site Reliability Engineer & Team Lead"
        period: "Sep 2024 — Present"
        description: "Leading a team of administrators while managing a large-scale global server fleet. Working alongside the team to gradually transform a traditional sysadmin culture into an SRE mindset — a journey still in progress. Part of that work involved building the company's SRE runbooks and playbooks from the ground up, giving the team a shared foundation to operate from. A big piece of the day-to-day is Ansible — writing playbooks to cover more and more of our operations as we push toward an Ansible-first approach for managing infrastructure at global scale. I work closely with the DevOps and Platform Development teams to resolve issues quickly and keep things moving. Beyond that I stay hands-on: deploying Proxmox clusters, writing internal tools and scripts, and stepping in on the complex incidents that need a deeper look."
      - title: "Senior System Administrator"
        period: "Apr 2023 — Oct 2024"
        description: "Deployed and automated a global fleet of Proxmox clusters using Ansible — from bare metal to production-ready. Collaborated with teammates on the technical onboarding of brands acquired by Hosting.com, aligning them with internal standards, monitoring stack, and management tooling."
  - company: "MochaHost"
    tenure: "Aug 2013 — Mar 2023 · 9 yrs 8 mos"
    roles:
      - title: "Senior Linux Administrator"
        period: "2018 — Mar 2023"
        description: "Led the migration from ad-hoc bash scripts and runbooks into structured Ansible roles, enabling fully automated end-to-end provisioning of new cPanel servers — from bare OS to production-ready hosting node."
      - title: "System Administrator L2"
        period: "Oct 2014 — 2018"
        description: "Handled complex issues escalated from Tier 1 admins, provisioned and configured new servers, and drove ongoing configuration improvements across the fleet."
      - title: "System Administrator"
        period: "Aug 2013 — Sep 2014"
        description: "Install, configure, maintain and upgrade servers, operating systems and web applications. Provide technical support via ticket system. Manage 24/7 server and service monitoring. Recognise and troubleshoot problems with server hardware and application software."
  - company: "SunService Ltd."
    tenure: "Jun 2012 — Jul 2013 · 1 yr 2 mos"
    roles:
      - title: "System Administrator"
        period: "Jun 2012 — Jul 2013"
        description: "Build, manage and support company network and servers (web, FTP, LDAP, DHCP, Tomcat). Develop web-based software, integrate new technologies, and troubleshoot TCP/IP and RS485 networking problems."
  - company: "Opticnet Ltd."
    tenure: "Sep 2009 — Jun 2012 · 2 yrs 10 mos"
    roles:
      - title: "Network Support"
        period: "Sep 2009 — Jun 2012"
        description: "Troubleshoot TCP/IP networking problems, monitor and control company networks. Build and support VPNs based on PPTP and OpenVPN. Build, manage and support MikroTik-based and Linux routers."

certificates:
  - name: "Linux Foundation Certified Engineer"
    abbr: "LFCE"
    issuer: "The Linux Foundation"
    issued: "Nov 2019"
    expires: "Nov 2029"
    credential_id: "LFCE-1900-0511-0200"
    url: ""
  - name: "cPanel & WHM System Administrator I Certification"
    abbr: "CWSA-1"
    issuer: "cPanel"
    issued: "Oct 2019"
    expires: "Oct 2020"
    credential_id: "e38c-2d29-62c8-7933"
    url: ""

projects_note: "Most of my work over the years is owned by the companies I've worked for. Here's what I can share."

projects:
  - name: "UnixWorld"
    description: "An active tech blog and community platform dedicated to Linux, Unix-based systems, and open-source technologies. A place to share knowledge, write about real-world ops experience, and give back to the community."
    url: "https://unixworld.org"
    tags: ["Linux", "Open Source", "Community"]
    private: false
  - name: "vpcs.spec"
    description: "RPM spec file for packaging VPCS (Virtual PC Simulator) for Fedora and RHEL — bringing a useful network lab tool into the native package ecosystem."
    url: "https://github.com/tgerov/vpcs.spec"
    tags: ["RPM", "Fedora", "RHEL"]
    private: false
  - name: "lve_exporter"
    description: "Prometheus exporter that scrapes metrics from CloudLinux LVE Stats 2, exposing per-account resource usage (CPU, memory, I/O, processes) for Grafana dashboards."
    url: "https://github.com/tgerov/lve_exporter"
    tags: ["Go", "Prometheus", "CloudLinux"]
    private: false
  - name: "check_truenas_scale"
    description: "Icinga/Nagios-compatible monitoring plugin that queries the TrueNAS Scale REST API to surface alerts, pool health, and disk status."
    url: "https://github.com/tgerov/check_truenas_scale"
    tags: ["Python", "Icinga", "TrueNAS"]
    private: false
  - name: "Proxmox Bare Metal Automation"
    description: "Fully automated bare metal Proxmox deployment using a custom-built ISO and Ansible playbooks — zero-touch from power-on to production-ready cluster."
    url: ""
    tags: ["Proxmox", "Ansible", "Linux"]
    private: true
  - name: "Redis for cPanel"
    description: "cPanel plugin that provisions and manages Redis instances per hosting account. Used in production at Hosting.com."
    url: ""
    tags: ["cPanel", "Redis", "PHP"]
    private: true
  - name: "Memcached for cPanel"
    description: "cPanel plugin that provisions and manages Memcached instances per hosting account. Used in production at Hosting.com."
    url: ""
    tags: ["cPanel", "Memcached", "PHP"]
    private: true

---
