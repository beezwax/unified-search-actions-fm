# Unified Search + Actions, using Semantic Search with FileMaker 2024
Demo tutorial file packaged as Beezwax Unified Search + Actions.fmp12

Requires FileMaker 2024 (v21.x)

Note: This demo tutorial (Beezwax Unified Search **+ Actions**) is different from the more basic tutorial (Beezwax Unified Search).

## Introduction
FileMaker 2024 delivers native semantic search, and it’s awesome. Now you can search records whose text is similar to the semantic meaning of your search term, even if those records don’t include your exact search term. Using natural language, users can be freed from trying to recall exactly how data was input.

The tutorial files (and the reference blog posts) explore implementing semantic search in FileMaker, using the 'Perform Semantic Find' script step. The 'CosineSimilarity' function helps expose how (semantically) similar each result is to a user's search term. The 'Set AI Call Logging' script step reveals what information these steps are passing to and receiving from your selected model. 

A basic example of "unified search" shows how a find across multiple tables, using natural language to construct a semantic search.

This more advanced example, shows "unified search **+ actions**".

We recommend you read the Reference Blog Posts for details and links to all demo/tutorial file downloads.

## Reference Blog Posts
https://blog.beezwax.net/filemaker-semantic-search-part-1-fundamental-power/

https://blog.beezwax.net/filemaker-semantic-search-part-2-key-details/

https://blog.beezwax.net/filemaker-semantic-search-part-3-advanced-fun/

## Quickstart
This tutorial file requires FileMaker 2024 (v21.x).

You'll need to supply your own AI credentials to use the file (via the gear icon in the top right of the UI).

If you employ credentials that aren't from OpenAI, you'll also need to configure the LLM Embedding Model field and execute the embeddings script (to build embeddings compatible with the embedding model you've chosen).

Copyright © 2024 Beezwax Datatools, Inc.
