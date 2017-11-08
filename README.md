<div align="center">
<img align="center" src="https://user-images.githubusercontent.com/4115778/32569683-b5075996-c4b9-11e7-8a60-7412bcd7356b.png" height="200"></img>
</div>
<div align="center">
<br/>
</div>
  
# Structure

_security-template_ is a static website template for security pages, powered by Jekyll. The template directory structure is as follows:

```
.
├── 404.html # 404 page.
├── advisories.md # Security advisories list.
├── assets # Page assets.
│   ├── css
│   │   └── styles.css
│   └── images
│       └── icon.png
├── _config.yml # Config file with all your variables.
├── _drafts
├── Gemfile
├── Gemfile.lock
├── hof.md # Hall of fame page.
├── _includes
│   └── advisory-list.html
├── index.md # Security policy.
├── _layouts
│   ├── default.html
│   └── post.html
├── LICENSE
├── _posts
│   └── 2017-07-22-cve-2017-0914.md # Example security advisory.
├── README.md
└── report.md
```

![Example policy](https://user-images.githubusercontent.com/4115778/32572136-9d388d50-c4c1-11e7-879c-0de12c411949.png)


## `index.md`

The index file is where your security policy lives. To learn more about writing good security policies, please refer to https://support.hackerone.com/hc/en-us/articles/205624665-How-do-we-write-a-good-policy-.

## `advisories.md`

This is where you can list your security advisories. The list is updated every time you add a security advisory to the `_posts` folder.

## `report.md`

This file should contain contact information for security researchers to use when reporting a security vulnerability. You can use the embedded Bugcrowd submission form too. Just uncomment the form, and add your Bugcrowd embed token under `bugcrowd_id` in the `_config.yml` file.

## `hof.md`

This is your security acknowledgements page. List the details of security researchers that reported valid security issues (and wished to be listed publicly).

## `.well-known/security.txt`

`security-template` contains a security.txt template file. _security.txt_ defines a standard to help organizations define the process for security researchers to safely disclose vulnerabilities via a simple text file. For more on this, please refer to https://securitytxt.org/.

# Contributing

Contributions from the public are welcome.

### Using the issue tracker 💡

The issue tracker is the preferred channel for bug reports and features requests. [![GitHub issues](https://img.shields.io/github/issues/EdOverflow/security-template.svg?style=flat-square)](https://github.com/EdOverflow/security-template/issues)

### Issues and labels 🏷

The bug tracker utilizes several labels to help organize and identify issues.

### Guidelines for bug reports 🐛

Use the GitHub issue search — check if the issue has already been reported.
