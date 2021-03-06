---
title: Changes
order: -10
---

## 10.05.2019

- GraphQL API for [cancelled trip times](../apis/1-routing-api/cancelled-triptimes) is now available in production
- [Disruption info API](../apis/1-routing-api/disruption-info/#query-disruptions-and-their-severity-levels) has details of the severity of disruptions

## 10.04.2019

 - New GraphQL API for querying cancelled trip times introduced as [preview](../apis/1-routing-api/preview/).
   - All cancelled departures can be queried through this API.
   - Severe disruptions will have separate alerts which can be queried through [Disruption info](..apis/1-routing-api/disruption-info/) GraphQL API.
 - [Service alerts](../apis/4-realtime-api/service-alerts/) API in [Real-time APIs](../apis/4-realtime-api/) will be deprecated in the future in favor of [Disruption info](..apis/1-routing-api/disruption-info/) GraphQL API.
   - This is part of an effort to reduce overlapping API functionalities and to concentrate APIs under the GraphQL APIs.
 - [Trip updates](../apis/4-realtime-api/trip-updates/) API in [Real-time APIs](../apis/4-realtime-api/) will be deprecated in the future in favor of [Stop times](../apis/1-routing-api/stops/) GraphQL API.
   - This is part of an effort to reduce overlapping API functionalities and to concentrate APIs under the GraphQL APIs.
