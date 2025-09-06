# Web Interview Questions

## Java EE
- Difference between **stateless** and **stateful** beans.
- What are **message-driven beans**?
- What is **EJB**?
- How can we inject beans?
- Difference between **Local** and **Remote** interfaces.
- What is a **Session (EJB) Context**? How can it be used?

---

## General Web
- Mapping **HTTP methods** to **CRUD operations**.
- Differences between **SOAP** and **REST** web services.
- HTTP status codes: categories (1xx, 2xx, 3xx, 4xx, 5xx) and examples (e.g., 404).
- When should we use the **HTTP OPTIONS** method?
- Where can we utilize HTTP protocol? Is it stateful or stateless?
- Restrictions of the **HTTP GET** method.
- How can we implement **sessions** in a stateless HTTP protocol?
- How can we configure caching of HTTP requests/responses on a proxy server?
- How to ensure **HTTP GET** requests are cached by proxy servers?
- How to determine where HTTP headers end and the body begins in a POST request?
- How do you secure a **REST web service**?
- Difference between **TLS** and **SSL**.
- Difference in **charset declaration** between HTML5 and XHTML 1.1.
- How can we switch a browser from **Quirks/Compatibility mode** into **Standards mode**?
- What is **XSS** and how can we prevent it?
- Choosing a web service when the main concern is **security/confidentiality** – which and why?
- Choosing a web service when the main concern is **payload size** – which and why?
- Which type of web service guarantees that content has been sent by the correct sender?
- What is a **connection leak** and how to prevent it? What is **pool exhaustion**?

---

## REST
- What is the **REST protocol**?
- What are the **side effects** of using REST?
- Characteristics of a well-designed REST API (best practices, perspective of exposed API).

---

## SOAP
- What is the **SOAP protocol**?
- How can we describe SOAP web service interfaces so they are understandable for third-party developers?
- What is **WSDL**?
- Structure of a **SOAP envelope**.
- Side effects of using SOAP.
- What part of a SOAP envelope can be encrypted?

---

## JSF / JSP / Servlets
- Describe **JSF technology**.
- What is **JSP (Java Server Pages)**?
- Pros and cons of using JSF vs JSP.
- What is **JSF EL (Expression Language)**?
- Relationship between a **JSP page** and a **Servlet**.
- Can we write **multithreaded code** in a servlet? Do servlet fields need synchronization?
- Lifecycle of a servlet (`init → service → destroy`). What is `service()` method used for?
- How to create a servlet (`extends HttpServlet`, `implements Servlet`).
- How can we register a servlet? (`web.xml`, `@WebServlet` annotation).
- Implicit objects in JSP (e.g., `pageContext`, `out`, `request`, `response`) – usage.
- How do **filters** work? How can we register them? (`web.xml`, `@WebFilter` annotation). Purpose of filters.
- Lifecycle of filters (`init → doFilter → destroy`).

---

## Security
- What is a **SQL injection** and how to prevent it?
- What is **XSS (Cross-Site Scripting)** and how to prevent it?
- How does **HTTPS** work?
- What are **HMAC, SHA, passwords, and salt**? How are they used in security?
