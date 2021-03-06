---
layout: "docs"
page_title: "Commands: quota"
sidebar_current: "docs-commands-quota"
description: >
  The quota command is used to interact with quota specifications.
---

# Command: quota

The `quota` command is used to interact with quota specifications.

~> Quota commands are new in Nomad 0.7 and are only available with Nomad
Enterprise.

## Usage

Usage: `nomad quota <subcommand> [options]`

Run `nomad quota <subcommand> -h` for help on that subcommand. The following
subcommands are available:

- [`quota apply`][quotaapply] - Create or update a quota specification
- [`quota delete`][quotadelete] - Delete a quota specification
- [`quota init`][quotainit] - Create an example quota specification file
- [`quota inspect`][quotainspect] - Inspect a quota specification
- [`quota list`][quotalist] - List quota specifications
- [`quota status`][quotastatus] - Display a quota's status and current usage

[quotaapply]: /docs/commands/quota/apply.html
[quotadelete]: /docs/commands/quota/delete.html
[quotainit]: /docs/commands/quota/init.html
[quotainspect]: /docs/commands/quota/inspect.html
[quotalist]: /docs/commands/quota/list.html
[quotastatus]: /docs/commands/quota/status.html
