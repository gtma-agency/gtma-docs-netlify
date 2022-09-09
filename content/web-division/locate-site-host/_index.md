---
title: "Troubleshoot Site Hosting"
date: 2022-01 04T14:15:42-07:00
lastmod: 2021-04-19T14:15:42-07:00
weight: ""
keywords: [""]
---

## For a GTMA Site

1. Look in the ManageWP interface. There should be a tag on the site that says who it's hosted with
2. Review the Kickoff survey. If this client came to us with existing hosting, the information may be in the Kickoff Survey.
3. Search Dashlane. We may have server and FTP logins for the site here.

## Non-GTMA site

1. Use a whois lookup
   * Open Terminal and type `whois mydomain.com` and you can find a lot of helpful information.
2. [Digital.com: Who is Hosting This?](https://digital.com/best-web-hosting/who-is/) - This tool is helpful as well

## Cloudflare

You may discover that Cloudflare is creating the issue
All GTMA Devs have access to our Cloudflare account

## Email Hosts

1. MX Toolbox has a number of email deliverability and troubleshooting.

## Other Troubleshooting tools

1. [Redirect Checker](https://www.redirect-checker.org/) - find out the type of redirect on a url, and if there is a redirect chain.
2. [MX Toolbox](https://mxtoolbox.com/) has a number of email deliverability and troubleshooting tools.
3. [DNS Checker](https://dnschecker.org/) - Find out if the IP address has propogated across datacenters around the world

