## Hi, I'm Zhen-Rong Wu

I'm interested in system programming, kernel development, machine learning and algorithms.
CSIE undergraduate at National Taiwan Normal University.

### AMD SEV for FreeBSD bhyve

I ported AMD SEV (Secure Encrypted Virtualization) to FreeBSD's bhyve hypervisor. bhyve can now launch confidential VMs whose memory is encrypted with a per-VM key that the hypervisor itself cannot read, and the guest owner can verify what was launched (pre-attestation) before sending any secrets.

Code: [freebsd-src](https://github.com/MaxWutw/freebsd-src/tree/sev-virtio-net-1.0) ([diff against main](https://github.com/freebsd/freebsd-src/compare/main...MaxWutw:freebsd-src:sev-virtio-net-1.0)) · [edk2](https://github.com/MaxWutw/edk2/tree/freebsd-sev) · [sevctl](https://github.com/MaxWutw/sevctl/tree/freebsd) · [sev](https://github.com/MaxWutw/sev/tree/freebsd)

Talks:

- EuroBSDCon 2026, Brussels: *Confidential VMs on FreeBSD: A Complete AMD SEV Host Stack for bhyve, with Attestation* (45 min) · [talk](https://events.eurobsdcon.org/2026/talk/HSMCFS/) · [video](https://exquisite.tube/w/r9BbXsKLCeNX1BB5qwcTvq) · [slides](https://drive.google.com/file/d/10cp635sIbVKuJGQOjoJD7MGD647-q6q_/view?usp=sharing)
- FreeBSD Developer Summit 2026, Brussels: *AMD SEV port for FreeBSD: One VM one key, how many ASIDs?* · [slides](https://wiki.freebsd.org/DevSummit/202609?action=AttachFile&do=view&target=AMD_SEV_devsummit.pdf)

I was also on the staff of AsiaBSDCon 2026.

### Embedded systems

Research intern at Academia Sinica CITI (2026), working on embedded systems.

### Competitive programming

- 2025 ICPC Asia Taichung Regional: Bronze Medal
- TOPC 2024, 2025: Bronze Awards

<!--
**MaxWutw/MaxWutw** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
