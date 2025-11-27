
[![](https://img.shields.io/badge/-🌐%20My%20Blog-success)](https://ssst0n3.github.io/)
<!-- [![](https://img.shields.io/website?logo=Google%20Chrome&url=https%3A%2F%2Fssst0n3.github.io%2F)](https://ssst0n3.github.io/) -->

### Hey all. 👋 Container Security newb here.
**Here are the vulnerabilities i've found:**

| status | discovered | project | item | note |
| --- | --- | --- | --- | --- |
| [FIXED] | 2021-02-23 | bitnami/laravel | CVE-2021-21979: APP_KEY is fixed in docker image bitnami/laravel |
| [FIXED] | 2021-04-20 | meshery | [CVE-2021-31856: A Sql Injection in Meshery](https://github.com/ssst0n3/CVE-2021-31856) |
| [FIXED] | 2021-04-30 | docker | [CVE-2021-41089: docker cp allows unexpected chmod of host files](https://github.com/moby/moby/security/advisories/GHSA-v994-f8vw-g7j4)|
| [FIXED] | 2021-05-26 | kernel/cgroups | CVE-2022-0492 (co-author) |
| [FIXED] | 2021-07-14 | runc | host infomation disclosure | same as CVE-2025-31133 |
| [REJECTED] | 2021-08-24 | docker | docker dos | reported but no response |
| [REJECTED] | 2022-06-17 | runc | runc capability escape | maintainer did not think it's a vuln |
| [FIXED] | 2022-07-29 | runc | [CVE-2023-28642: AppArmor/SELinux bypass with symlinked /proc](https://github.com/opencontainers/runc/security/advisories/GHSA-g2j6-57v7-gm8c) |
| [REJECTED] | 2022-08-04 | runc | runc host infomation disclosure | maintainer did not think it's a vuln |
| [FIXED] | 2023-03-10 | apport-cli | [CVE-2023-1326](https://ubuntu.com/security/notices/USN-6018-1) (co-author) |
| [FIXED] | 2023-03-30 | runc | CVE-2025-31133: container escape |
| [FIXED] | 2023-04-07 | runc | escape, containerd only | got fixed unintentionally in runc v1.1.5 |
| [FIXED] | 2024-12-17 | nvidia-container-toolkit| [CVE-2025-23359](https://nvidia.custhelp.com/app/answers/detail/a_id/5616) |
| [FIXED] | 2025-03-13 | nvidia-container-toolkit | [CVE-2025-23267](https://nvidia.custhelp.com/app/answers/detail/a_id/5659) |
| [FIXED] | 2025-04-29 | runc | CVE-2025-52565, container escape (co-author) |

**Here are some of my repositories i want to introduce to you:**
* container
  - [ctrsploit](https://github.com/ctrsploit/ctrsploit): A penetration toolkit for container environment
  - [docker_archive](https://github.com/ssst0n3/docker_archive): Provide many versions of docker and docker's components
  - [registry_v2_client](https://github.com/ssst0n3/registry_v2_client): A cli for registry v2
  - [docker_secret](https://github.com/ssst0n3/docker_secret): An alternative of docker secret
* golang 
  - [go_instrumentation](https://github.com/ssst0n3/go_instrumentation): A generic instrumentation tool for golang
  - [awesome_libs](https://github.com/ssst0n3/awesome_libs)
  - [lightweight_api](https://github.com/ssst0n3/lightweight_api)
  - [lightweight_db](https://github.com/ssst0n3/lightweight_db)
  - [codeql-go-vendor](https://github.com/ssst0n3/codeql-go-vendor): A codeql extractor for go vendor mode project
* my poc/exp
  - [docker-cve-2022-39253-poc](https://github.com/ssst0n3/docker-cve-2022-39253-poc): docker host file read (using cve-2022-39253) poc
* security research
  - [security-research-specification](https://github.com/ssst0n3/security-research-specification)
  - [source-analysis-system](https://github.com/ssst0n3/source-analysis-system): Next Generation Source Analysis Report
  - [GHSA-NOTIFY](https://github.com/ssst0n3/GHSA-NOTIFY): open source software security advisories based on GHSA
* ctf
  - [my_ctf_challenges](https://github.com/ssst0n3/my_ctf_challenges): The ctf challenges i've designed
  - [waterdropctf](https://github.com/waterdropctf/waterdropctf)
  * reverse
    - [opdb](https://github.com/ssst0n3/opdb): an opcode level debugger for python
  * crypto
    - [yafu_docker](https://github.com/ssst0n3/yafu_docker): unofficial container image for yafu
  * awd
    - [portable-git](https://github.com/ssst0n3/portable-git): portable git
* common security tools
  - [sectools](https://github.com/ssst0n3/sectools)
  - [go-shijack](https://github.com/ssst0n3/go-shijack): tcp connection hijacker, go rewrite of shijack from 2001.
* other
  - [awesome_scripts](https://github.com/ssst0n3/awesome_scripts): A collection of awesome scripts
  - [sshtunnel](https://github.com/ssst0n3/sshtunnel): A nice useful ssh tunnel

updated at 2023-04-23

---

<!-- ## &#x1f4dd; Most Used Languages -->
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ssst0n3&hide=javascript,html,css,powershell,Groff)

