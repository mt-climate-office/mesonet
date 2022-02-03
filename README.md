# Why do we need version control for the Montana Mesonet?

## [Stations](https://github.com/mt-climate-office/mesonet-ln-programs)
  - Track what code is deployed to what station
    - Ensure consistency within our network
  - Track when code changes on the stations
    - Avoid "rogue code" situations
  - Easily integrate changes that are deployable across stations
    - Streamline program deployment
  - Roll back detrimental changes to well-known version
  - Systematic testing with bench unit(s)
    - Avoid testing code in the "wild"
  - Consistency, Reliability, Trust

[Station program comparison](https://github.com/mt-climate-office/mesonet-ln-programs/compare/aceabsar..acebozem?diff=split)

**Question: How do we define a canonical program, and how do we handle versioning?**<br>
**Question: How do we track station configuration/settings changes, outside of the program?**

## [Loggernet Server](https://github.com/mt-climate-office/mesonet-ln-server)
  - Track changes (equipment additions)
  - Ease troubleshooting
  - Enable rapid deployment to new (or same) compute infrastracture, if necessary
  - Control deployment of new LN versions


# We don't talk about Docker... (today)
Docker is the virtual server deployment system we use on *all* of the MT Mesonet servers (and most of the other MCO servers). It allows for rapid, reproducible deployment of compute resources. We won't talk about it today, but if you hear someone else talk about it, we use it.
