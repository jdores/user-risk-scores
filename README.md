Cloudflare Worker project that retrieves the user risk scores from the Zero Trust dashboard and updates a zero trust list with the current list of high risk users.

To set up the Worker correctly define the account ID and API user/key using Workers Secrets and add the ZT list id as a variable in wrangler.jsonc

Cron schedule for this worker is also set in wrangler.jsonc