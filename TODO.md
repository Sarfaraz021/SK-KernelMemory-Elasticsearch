# TODOs

1. Complete article about IMemoryConnector
    - Now that the repo is clean, add code examples to article (MOSTLY DONE)

1. Make properties of the mapping not nullable as per the postgres [code](https://github.com/microsoft/kernel-memory-postgres/blob/58df8fa4cee89add3ba6e49e00535aa1f7b43b02/PostgresMemoryStorage/Db/PostgresDbClient.cs#L142)

1. Make custom column available.
    1. See [PostgresConfig](https://github.com/microsoft/kernel-memory-postgres/blob/main/PostgresMemoryStorage/PostgresConfig.cs)

# Done

1. Add a new content (text) column to the ES mapping to index the content that is inside the Payload
    - Q: Look into Payload as it stores JSON like ```{"file": "blabla.txt", "text": "...the chunk's text...", "vector_provider": "xxxx", "vector_generator: "TODO", "last_update": "20023-12-05T16:23:19" }```
    - [See image here](https://github.com/freemindlabsinc/FreeMindLabs.KernelMemory.Elasticsearch/blob/main/content/images/DataPage2.jpg)

- See if I need to integrate more of Davis' thoughts into the article