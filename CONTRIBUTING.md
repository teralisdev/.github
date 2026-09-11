# Contributing

## House rules

**No em dashes or en dashes.** Not in copy, not in titles, not in generated
output, not in commit messages. The site repo enforces this in code and will
fail a build over it.

**No invented facts.** No founding date, headcount, funding, cheque size,
metrics or uptime figures. If it cannot be verified from the repos, the servers
or the live sites, it does not ship. A page with no numbers that is true beats a
page with numbers that are not.

**No infrastructure in public.** No IPs, hostnames, ports, paths or versions,
and nothing describing the private network. This applies to issues and pull
request descriptions as much as to code.

**No third party requests on the site.** Fonts are self hosted so that no
visitor's address reaches anyone else, and the privacy policy says so in as many
words. No CDN, no analytics script, no embed, no hosted font.

## Before you open a pull request

Most of the HTML on the site is generated. Check the table in `AGENTS.md` before
editing any file with a `<nav>` in it, or your change will be overwritten by the
next build.

Run the generators, and check every page at 1440 and 390 wide for console
errors, failed requests and horizontal overflow.
