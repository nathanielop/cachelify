# cachelify
A simple client-side caching API taking advantage of the IndexedDB API.

Easily hook this cache up to an existing REST API calling function in order to reuse cached data.

## Goals

1. Streamline existing IndexedDB API into a more digestable format for use.
2. Bridge gap between API and caching in a non-specific manner for use with a multitude of API types.

## Baked in functions

### Set

> cachelify.set(key, value);

Sets a key value pair in the cache.

### Delete

> cachelify.delete(key);

Deletes a key value pair in the cache

### Get

> cachelify.get(key);

Get the value for a certain key in the cache
