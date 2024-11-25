# TODO

`providerSlug` should, by definition, be the domain name at which the openapi.json is located

If I agree on this, adding a new OpenAPI into the index is easy: just navigate to https://openapisearch.com/[domain]

Another great URL structure would be: https://openapisearch.com/[domain]/...operationIds to filter them.

Another great feature would be optionally adding .yaml, .json, etc to the URL to get another format back

Example urls now:

https://openapisearch.com/extexe.com/transform.yaml

It's a great benefit to have this because

- every domain is immediately registered if it wasn't already, allowing for easy access to things
- every openapi can be filtered on operations and be shown in multiple formats (yaml, json, md?)
- every openapi is also a chat completion API if we use chatcompletions in front. E.g. https://chatcompletions.com/openapisearch.com/extexe.com/transform

There are lot of edge-cases that would need us to have the other `set` endpoint as well, but this is really neat to have as well.
