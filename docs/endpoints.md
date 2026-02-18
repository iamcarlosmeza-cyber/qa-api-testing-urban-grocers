# API Endpoints Documentation — Urban Grocers

## Overview
This document contains the main endpoints tested during the Urban Grocers API testing project.

---

## Base URL
`[Insert base URL provided by TripleTen]`

---

## Authentication
- Type: [API Key / Bearer Token / None]
- Header: [Authorization / X-API-KEY / etc]

---

## Endpoints List

### 1. Create Resource
**Method:** POST  
**Endpoint:** `/api/v1/[resource]`

**Description:** Creates a new resource.

**Expected Status Codes:**
- 201 Created (valid request)
- 400 Bad Request (invalid body)

---

### 2. Get Resource List
**Method:** GET  
**Endpoint:** `/api/v1/[resource]`

**Description:** Retrieves a list of resources.

**Expected Status Codes:**
- 200 OK

---

### 3. Get Resource by ID
**Method:** GET  
**Endpoint:** `/api/v1/[resource]/{id}`

**Description:** Retrieves a specific resource by ID.

**Expected Status Codes:**
- 200 OK (valid ID)
- 404 Not Found (invalid ID)

---

### 4. Update Resource
**Method:** PUT / PATCH  
**Endpoint:** `/api/v1/[resource]/{id}`

**Description:** Updates an existing resource.

**Expected Status Codes:**
- 200 OK (valid update)
- 400 Bad Request (invalid body)
- 404 Not Found (invalid ID)

---

### 5. Delete Resource
**Method:** DELETE  
**Endpoint:** `/api/v1/[resource]/{id}`

**Description:** Deletes an existing resource.

**Expected Status Codes:**
- 200 OK / 204 No Content
- 404 Not Found (invalid ID)

---

## Notes
This endpoint structure is based on the TripleTen training environment and may reset periodically.

