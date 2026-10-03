<h1 align="center">KERBEROASTING</h1>

<p align="center">
  An Active Directory lab exploring Kerberos service tickets, offline password recovery, and service-account protection.
</p>

<p align="center">
  <a href="https://delriscotechnologies.github.io/kerberoastingwriteup/">Full Write-Up</a>
</p>

---

This write-up follows a controlled Active Directory lab, from requesting service tickets with Rubeus to testing passwords offline with Hashcat and John the Ripper.

It explains SPNs, legacy RC4 encryption, the impact of service-account permissions, and practical controls such as managed accounts, AES, and least privilege. The displayed credentials and ticket values are adapted lab examples.

## References

- [CrowdStrike: What is a Kerberoasting attack?](https://www.crowdstrike.com/en-us/cybersecurity-101/cyberattacks/kerberoasting/)
- [GhostPack: Rubeus](https://github.com/GhostPack/Rubeus)
- [NIST SP 800-63B-4](https://pages.nist.gov/800-63-4/sp800-63b.html)
