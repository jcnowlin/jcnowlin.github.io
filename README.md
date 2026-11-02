# jcnowlin.github.io

Single-purpose GitHub Pages site. Its only job is to serve the
MTA-STS policy for nowlin.io at:

https://mta-sts.nowlin.io/.well-known/mta-sts.txt

The CNAME file claims the mta-sts.nowlin.io subdomain for this
site. The .nojekyll file makes GitHub Pages serve the .well-known
directory literally. If nowlin.io mail ever moves off
mail.thundermail.com, update the mx line in the policy and bump
the id in the _mta-sts DNS TXT record to match.
