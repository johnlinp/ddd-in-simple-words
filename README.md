# Domain-Driven Design in Simple Words

The book: [Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)

<img src="book-cover.jpg" alt="book cover" height="300"/>

## What is Domain-Driven Design?

It's a strategy to build a software from domain models.

## What is a Domain?

A domain is an area of knowledge.

## What is a Model?

A model is simplified version of knowledge, with a specific purpose, and written in a ubiquitous language.

## What is a Ubiquitous Language?

A ubiquitous language is a set of terms. One term can have only one meaning, and one meaning can only be expressed by one term.

## It's too difficult to create a single domain model for our software!

We can divide our domain into subdomains. Each subdomain are within a bounded context.

## What is a Bounded Context?

A bounded context defines a boundary for a subdomain. The boundary should be physical, e.g. organization, code.

## How to define good subdomains and bounded contexts?

A good subdomain/bounded context should have high cohesion and low coupling, so that it can work on its own and doesn't rely on too much communication with others.
