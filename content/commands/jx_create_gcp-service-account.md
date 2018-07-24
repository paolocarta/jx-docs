---
date: 2018-07-23T18:37:04Z
title: "jx create gcp-service-account"
slug: jx_create_gcp-service-account
url: /commands/jx_create_gcp-service-account/
---
## jx create gcp-service-account

Creates a GCP service account

### Synopsis

Creates a GCP service account

```
jx create gcp-service-account [flags]
```

### Examples

```
  jx create gcp-service-account
  
  # to specify the options via flags
  jx create gcp-service-account --name my-service-account --project my-gcp-project
```

### Options

```
  -b, --batch-mode             In batch mode the command never prompts for user input
      --headless               Enable headless operation if using browser automation
  -h, --help                   help for gcp-service-account
      --install-dependencies   Should any required dependencies be installed automatically
  -n, --name string            The name of the service account to create
      --no-brew                Disables the use of brew on MacOS to install or upgrade command line dependencies
  -p, --project string         The GCP project to create the service account in
      --verbose                Enable verbose logging
```

### SEE ALSO

* [jx create](/commands/jx_create/)	 - Create a new resource

###### Auto generated by spf13/cobra on 23-Jul-2018