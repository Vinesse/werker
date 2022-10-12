# a simple cloudflare worker

* configured my worker subdomain in cf (***.workers.dev)
* on wrangler publish, my worker can be found at `my-worker` as defined under `name` in wrangler.toml followed by the subdomain: my-worker.***.workers.dev
* `wrangler publish` is run on merge to main by a github action workflow