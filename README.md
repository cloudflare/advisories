# 📣 Cloudflare Vulnerability/Advisory Disclosure Hub

This repo functions as the hub for "open sourced" closed source vulnerabilities/advisories
as well as educational writeups composed in collaboration with third parties on
discovered vulnerabilities.

## Why?

Every CVE that is filed must contain at least one "public reference". [Section 8.3](https://cve.mitre.org/cve/cna/rules.html#section_8-3_cve_entry_reference_requirements)
and [Section 8.1](https://cve.mitre.org/cve/cna/rules.html#section_8-1_cve_entry_information_requirements)
of the CVE Entry requirements outline what information that reference should contain.

Many organizations maintain a page on their website that lists CVEs that they
have filed. Generally, very little useful information is provided on these pages
outside of the required details. It can also be challenging to discover this page
on the site itself or be notified if a new entry has been added. Through a github
repo we believe we can address these issues (easily discoverable, swift process
for new content, people can watch the repo for updates) while meeting the reference
requirement.

Additionally, many third party researchers compose writeups for their personal
blogs to share on resumes or on social media. This is a great thing for us to
continue to support in terms of helping peer review posts that researchers
choose to share with us before going public. We would additionally like to give
them the optional opportunity to additionally publish on our platform for increased
visibility. Our goal is that this advisories repo will now double as a easily
discoverable learning resource and educational hub on past publicly disclosed
Cloudflare vulnerabilities.

A writeup may follow the format of:

- What happened?
- How it happened?
- How it was fixed?

but can be adapted to the type of vulnerability. The style of these posts will
be more casual and educational (code snippets, etc) than the published public
blog post. The text from these writeups may make it into public blog posts for
CVEs.

## Advisory Process

This repo is owned by the Cloudflare Security Team who follow the below procedures.

### Disclosing Vulnerabilities in Open Source Code

1. Blog post is published on [blog.cloudflare.com](https://blog.cloudflare.com/)
   satisfying the Section 8.1 requirement.
1. [Github security advisory](https://docs.github.com/en/github/managing-security-vulnerabilities/about-github-security-advisories) is published in the github repo itself.
1. (Optional) Collaborate on a writeup [in this repo](https://github.com/cloudflare/advisories/tree/main/writeups).

### Disclosing Vulnerabilities in Closed Source Code

1. Blog post is published on [blog.cloudflare.com](https://blog.cloudflare.com/)
   satisfying the Section 8.1 requirement.
1. [Github security advisory](https://docs.github.com/en/github/managing-security-vulnerabilities/about-github-security-advisories) is published [in this repo](https://github.com/cloudflare/advisories/security/advisories).
1. (Optional) Collaborate on a writeup [in this repo](https://github.com/cloudflare/advisories/tree/main/writeups).

## Feedback

✉️ [security@cloudflare.com](mailto:security@cloudflare.com)
