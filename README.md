<h1 align="center">KERBEROASTING</h1>

<p align="center">
  An Active Directory lab exploring Kerberos service tickets, offline password recovery, and service-account protection.
</p>

<p align="center">
  <a href="https://delriscotechnologies.github.io/kerberoastingwriteup/">Full Write-Up</a>
</p>

---

This write-up follows a controlled Active Directory lab, from requesting service tickets with Rubeus to testing passwords offline with Hashcat and John the Ripper.

It explains SPNs, legacy RC4 encryption, and the impact of service-account permissions. The controls cover NIST’s user-password guidance, stronger service-account secrets, automatic password management by Windows, AES, and least privilege. A short reflection considers AI-assisted guessing as part of password cracking.

This lab is for educational research only. No enterprise or personal credentials are disclosed. The displayed values are adapted lab examples; the lab credentials are retired and will not be reused.

## References

- [GhostPack: Rubeus](https://github.com/GhostPack/Rubeus)
- [NIST SP 800-63B-4](https://pages.nist.gov/800-63-4/sp800-63b.html)
