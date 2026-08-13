<div align="center">

```
██████╗  ██████╗  ██████╗ ██████╗ ██╗    ██╗██████╗ ██████╗ ██╗   ██╗
██╔══██╗██╔═══██╗██╔═══██╗██╔══██╗██║    ██║██╔══██╗██╔══██╗╚██╗ ██╔╝
██████╔╝██║   ██║██║   ██║██████╔╝██║ █╗ ██║██████╔╝██████╔╝ ╚████╔╝
██╔═══╝ ██║   ██║██║▄▄ ██║██╔═══╝ ██║███╗██║██╔═══╝ ██╔═══╝   ╚██╔╝
██║     ╚██████╔╝╚██████╔╝██║     ╚███╔███╔╝██║     ██║        ██║
╚═╝      ╚═════╝  ╚══▀▀═╝ ╚═╝      ╚══╝╚══╝ ╚═╝     ╚═╝        ╚═╝
```

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=18&duration=2800&pause=900&color=39FF14&center=true&vCenter=true&width=650&lines=root%40khoa%3A~%23+whoami;>+intern+penetration+tester;>+breaking+things+so+others+don't+have+to;>+status%3A+still+patching+my+own+homelab" alt="terminal typing" />

</div>

<div align="center">

[![linkedin](https://img.shields.io/badge/LINKEDIN-poqpwppy-39FF14?style=for-the-badge&logo=linkedin&logoColor=0d1117&labelColor=39FF14)](https://www.linkedin.com/in/poqpwppy/)

</div>

<div align="center">

[![github](https://img.shields.io/badge/-poqpwppy-black?style=flat-square&logo=github&logoColor=39FF14&labelColor=0d1117)](https://github.com/poqpwppy)
[![blog](https://img.shields.io/badge/-poqpwppy.fyi-black?style=flat-square&logo=rss&logoColor=39FF14&labelColor=0d1117)](https://poqpwppy.fyi)
[![writeups](https://img.shields.io/badge/-ctf_writeups-black?style=flat-square&logo=hackthebox&logoColor=39FF14&labelColor=0d1117)](https://poqpwppy.fyi/en/writeups)
[![mail](https://img.shields.io/badge/-khoa.dang%40viethope.org-black?style=flat-square&logo=protonmail&logoColor=39FF14&labelColor=0d1117)](mailto:khoa.dang@viethope.org)

</div>

<br>

```bash
guest@readme:~$ cat whoami.txt
```

```
name        Đặng Lê Đăng Khoa
alias       poqpwppy
role        intern penetration tester
base        FPT University, Da Nang — Information Assurance, exp. 2027
squad       ARESx (CTF — web exploitation & vulnerability triage)
location    Da Nang, VN
uptime      3rd year, still exploiting things to learn them
```

```bash
guest@readme:~$ ./run.sh --current-focus
```

```
[+] hardening my own homelab before hardening anyone else's
[+] mapping API endpoints, finding what shouldn't be public
[+] writing findings people can actually act on, not just admire
[+] grinding CTFs until the write-up writes itself
```

```bash
guest@readme:~$ grep -r "philosophy" ./about.md
```

```
"the most effective way to learn is to exploit things yourself,
 document every step, and share it publicly.
 a good writeup has to explain the why — not just the what."
```

---

### `> ctf/aresx`

Web exploitation & vulnerability triage, competing under team **ARESx** — national and international CTFs, multi-stage challenges, flags under a clock.

```
$ ls writeups/ --sort=recent
```

```
old-website.md            BushBash CTF 2026     [web/medium]   react → shell, nextjs
bitsctf-web-challenge.md  BITSCTF 2026           [web/hard]     reverse-proxy, rust
vsl-ctf-web-challenges.md VSL CTF 2026            [web/medium]   graphql
safeupload-challenge.md   CyberCon 2025           [web/medium]   toctou
canteen-food.md           community-sourced       [web/medium]   sql, php
need-for-speed.md         picoCTF                 [rev/hard]     reverse engineering
trickster.md              picoCTF                 [web/easy]     image processing
```

full breakdown → [poqpwppy.fyi/en/writeups](https://poqpwppy.fyi/en/writeups)

---

### `> exploits/`

**IDOR + payment-logic break — homestay booking platform**
Traced an unauthorized-access flow across a live booking system, mapped its API surface, and turned up two things nobody wanted to find: national-ID images sitting behind a guessable object reference, and a way to confirm bookings without paying for them. Reported both with clean repro steps, not just a scary screenshot.

**self-hosted infra, held together on purpose**
8+ services running under Docker Compose, herded through Portainer, reachable only over Tailscale — nothing exposed to the raw internet. AdGuard Home eats roughly 90% of the ad/tracker noise before it hits any device on the network.

**tattoo studio, shipped and hardened**
Built and deployed a small production site end to end, then spent more time on the input validation than the CSS.

**adguard home on an MXQ S805**
Turned an old $15 TV box into a network-wide DNS sinkhole via LibreELEC — because a homelab doesn't have to be expensive to be real. Full methodology on [poqpwppy.fyi/en/research](https://poqpwppy.fyi/en/research).

---

### `> currently.log`

```diff
+ VietHope — technical / security-compliance support (volunteer), since Mar 2026
+ reviewing internal systems against NIST / SOC 2 baselines for a team that can't afford to get this wrong
```

---

### `> toolbelt`

```
recon/exploit   nmap · burp suite · sqlmap · ffuf · metasploit · wireshark
scripting       python · javascript · c++ · bash · sql
infra           docker · portainer · tailscale · adguard home
os              linux (kali, ubuntu) · wsl
```

```bash
guest@readme:~$ cat tags.txt | column
```

```
#web            #rce            #auth-bypass    #command-injection
#toctou         #reverse-proxy  #misconfiguration  #cloudflare
#sql            #php            #graphql        #vhost
#rust           #flask          #bun            #elysia
#url-encoding   #cookie         #git            #re
```

---

### `> contact`

```bash
guest@readme:~$ finger poqpwppy
```

```
linkedin    linkedin.com/in/poqpwppy
github      github.com/poqpwppy
blog        poqpwppy.fyi
writeups    poqpwppy.fyi/en/writeups
email       khoa.dang@viethope.org
status      open to internship offers — reach out, don't ghost
```

---

<div align="center">

```
> the most effective way to learn is to exploit things yourself,
  document every step, and share it publicly.
  a good writeup has to explain the why — not just the what.
```

*— poqpwppy*

![profile views](https://komarev.com/ghpvc/?username=poqpwppy&color=39FF14&style=flat-square&label=connections+established)

</div>
