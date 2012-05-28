Exercise 1
==========

Goal
----

Create a classic "RPC over HTTP" application.

Background
----------

You are working for a company that has a classified advertisements
website. The task is to create a server used to create new ads. For
now, you only need to implement the server side.

Requirements
------------

The server shall expose two endpoints:

### Create ad endpoint: `http://localhost:3000/create-ad`

This is where clients should POST a json object to create a new ad.
The JSON should look like this:

    {
      "title": "Fin bolig til salgs!",
      "body": "Fire rom, nytt bad."
    }

### View ad endpoint:  `http://localhost:3000/ad?id=...`
 
Clients can GET this with an "id" query parameter. The server will
respond with something like this:

```json
{
  "result": "ok",
  "data": {
    "title": "Fin bolig til salgs!",
    "body": "Fire rom, nytt bad."
  }
}
```

Steps
-----

### Step 1: Create an ad


### Step 2: View an ad
