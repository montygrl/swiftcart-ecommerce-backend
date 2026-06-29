# SwiftCart — Part 1: Design & Planning

Completed November 2025 as part of BDV 102: Interactivity and Databases  
McMaster University Continuing Education

## Overview

This folder contains all design and planning work completed prior to 
development. The goal was to design a normalized relational database, 
document the API using OpenAPI standards, and produce a design rationale 
report before writing any implementation code.

## Contents

### `erd/`
Entity Relationship Diagram modeled in LucidChart showing all entities,
attributes, and relationships. Designed to Third Normal Form (3NF).

Public link: https://lucid.app/lucidchart/da9349b4-f9db-4943-b098-8327c570273c/edit?viewport_loc=-733%2C518%2C2157%2C910%2C0_0&invitationId=inv_f556754a-6ff7-4915-8f69-ba887d662042

### `schema/`
SQL table definitions (`create_tables.sql`) for all nine entities:
User, Address, Category, Product, PaymentMethod, CartItem, WishlistItem,
Order, and OrderItem.

### `design-report/`
Full design rationale covering ERD decisions, API design approach, 
schema iteration notes, and trade-offs made during planning.

## API Specification

Designed using OpenAPI 3.0.3 standard in APIDog before development began.  
Public documentation: https://0ewuo26ghz.apidog.io
