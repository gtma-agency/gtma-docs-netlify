---
title: "Staging Server Setup"
date: 2021-03-16T12:41:43-07:00
lastmod: 2021-03-16T12:41:43-07:00
weight: ""
draft: true
keywords: [""]
---

## Spin up new WordPress instance

1. Log in to Digital Ocean
2. Create a new Droplet
3. From Marketplace choose WordPress
4. Choose the $5/mo server option
5. Name the droplet with the clients initials + `-staging`
6. Add your SSH Key and the SSH Key for Buddy Works

## Set up Github repo

1. Log in to Github
2. Got to the GTMA-agency Organization
3. Create a new repo names with the clients initials + `-site`
4. Leave the repo as Private
5. Take defaults
6. Click "Create"
7. Click Settings -> Manage access
8. Click `Invite teams or people` and add devs for the project
