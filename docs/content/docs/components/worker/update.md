---
title: "update"
notitle: true
notoc: true
---
# worker update

`worker update [flags]`

## Synopsis

Update worker from CDS API or from CDS Release

Update from Github:

		worker update --from-github

Update from your CDS API:

		worker update --api https://your-cds-api.localhost
		

```
worker update [flags]
```

## Options

```
      --api string    URL of CDS API
      --from-github   Update binary from latest github release
      --insecure      (SSL) This option explicitly allows curl to perform "insecure" SSL connections and transfers.
```

## SEE ALSO

* [worker](/docs/components/worker/worker/)	 - CDS Worker

