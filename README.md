# Burp GraphQL Logger

A very simple, straightforward extension that logs GraphQL operations as a comment in the Proxy view.

<img width="1445" alt="burpy" src="https://user-images.githubusercontent.com/1380527/128707366-387ad98e-2175-4863-b35c-6de803095a67.png">

To enable the highlight, uncomment the line `messageInfo.setHighlight("cyan")` at [graphql.py](graphql.py).

It expects the usual GraphQL format `{"operationName:"SomethingQuery","variables":{}, "query":"..."}` - which is probably 99% of them.

