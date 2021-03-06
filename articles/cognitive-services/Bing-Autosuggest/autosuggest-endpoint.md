---
title: Autosuggest endpoint | Microsoft Docs
description: Summary of the Autosuggest API endpoint.
services: cognitive-services
author: mikedodaro
manager: rosh
ms.service: cognitive-services
ms.technology: bing-autosuggest-search
ms.topic: article
ms.date: 12/05/2017
ms.author: v-gedod
---

# Autosuggest endpoint

The **Autosuggest API**  includes one endpoint, which returns a list of suggested queries from a partial search term. 

##Endpoint
To get suggested queries using the Bing API, send a `GET` request to the following endpoint. Use the headers and URL parameters to define further specifications.

Endpoint `GET`:  
https://api.cognitive.microsoft.com/bing/v7.0/Suggestions 

Returns search suggestions as JSON results that are relevant to the users input defined by `?q=""`.


For details about headers, parameters, market codes, response objects, errors, etc., see the [Bing Autosuggest API v7](https://docs.microsoft.com/en-us/rest/api/cognitiveservices/bing-autosuggest-api-v7-reference) reference.

##Response JSON
The response to a videos search request includes results as JSON objects. For examples of parsing the results see the [tutorial](https://docs.microsoft.com/en-us/azure/cognitive-services/Bing-Autosuggest/tutorials/autosuggest) and [source code](https://docs.microsoft.com/en-us/azure/cognitive-services/Bing-Autosuggest/tutorials/autosuggest-source).

##Next steps
The **Bing** APIs support search actions that return results according to their type. All search endpoints return results as JSON response objects.  All endpoints support queries that return a specific language and/or location by longitude, latitude, and search radius.

For complete information about the parameters supported by each endpoint, see the reference pages for each type.
For examples of basic requests using the Autosuggest API, see [Autosuggest Quick-starts](https://docs.microsoft.com/en-us/azure/cognitive-services/Bing-Autosuggest).