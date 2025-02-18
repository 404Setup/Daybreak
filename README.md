# Daybreak
It's basically usable now, and I'm working on the caching and protection against malicious access parts.

## Why do this?
Github's Maven repository must use BasicAuth, and I don't want people using my repository to see the key, or have them enter the key themselves, which is an extremely cumbersome step.

Of course, this makes the positioning of Daybreak a bit strange, but this is not to allow you to build a proxy for your own repository, 

but to solve the BasicAuth in the Github Maven repository, and other repositories that are too slow to access (or inaccessible) due to the network environment.
