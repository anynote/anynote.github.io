---
title:  "What is a microservice"
tags: microservices
---
Have you ever heard about `microservices` ?

Microservice is :
- self contained process that provides a unique business capability
- communicating with each other through a `well-defined interface`, usually `REST` or `messaging queue`. The `communication` is almost always `stateless`

Why use microservices:
- make system `loosely coupled`: no need rebuild entire application when upgrade/repair/replace
- allow each of them just focus on 1 business capability
- small team can focus on a simple task
- use of different languages and tools

A good microservice
- Focus on a `single business capability`
- each microservice has its own datastore
- make comuniccaiton statelss
- the team should have all designer, developer, db admin, operation,...

Example: Amazon website:
- service for accepting orders
- service for determining list of recommended items to buy
- service to handle wishlist
- service for authenticating
- ..

They are `mini applications`, each perform a single business capability
Make organization not organized around `software layer` (not `web layer`, `business layer`, `database layer`) => microservices created by `business capability`

Reference

- [Youtube](https://www.youtube.com/watch?v=PY9xSykods4/)

`two pizza rule` by `Jeff Bezos`
