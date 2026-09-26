GET, POST, PUT, PATCH…

Most developers know these words.

But here’s the real question:

Do you know what each one is actually asking the server to do? 🤔

Meet Alex.

He’s building a food delivery API.

His client sends requests like:

GET /orders/123

The server understands:

“Give me order 123.”

Then Alex learns something important:

HTTP methods aren’t random verbs.
They communicate intent.

🍔 The 9 HTTP methods, as a restaurant conversation

1️⃣ GET — “Show me.”

GET /restaurants

Retrieve a resource.

It is safe and idempotent.

⸻

2️⃣ POST — “Create this.”

POST /orders

Create a new resource.

Two identical POST requests can create two resources, so POST is not idempotent.

⸻

3️⃣ PUT — “Replace this.”

PUT /users/123

Replace or create the resource at that location.

Repeated identical PUT requests have the same intended effect → idempotent.

⸻

4️⃣ PATCH — “Change just this part.”

PATCH /users/123

Maybe Alex only wants to change:

email

No need to replace the entire user.

⸻

5️⃣ DELETE — “Remove this.”

DELETE /orders/123

Delete a resource.

Repeated identical DELETE requests have the same intended effect → idempotent.

⸻

Now come the methods developers often forget. 👀

6️⃣ HEAD — “Tell me about it, but don’t send the body.”

Like GET, but the response doesn’t include the body.

Useful for checking metadata such as headers.

⸻

7️⃣ OPTIONS — “What can I do here?”

Ask the server about the communication options supported for a resource.

You’ll often encounter it with CORS preflight requests.

⸻

8️⃣ CONNECT — “Create a tunnel.”

Used to establish a tunnel to the target server, commonly through a proxy.

⸻

9️⃣ TRACE — “Show me the request path.”

Performs a loop-back test so the client can see how the request was received.

It can be useful for diagnostics, but should generally be disabled in production because of security concerns.

⸻

The cheat sheet 🧠

GET → Read

POST → Create

PUT → Replace

PATCH → Partially update

DELETE → Remove

HEAD → Headers only

OPTIONS → Capabilities

CONNECT → Tunnel

TRACE → Diagnostic loop-back

The deeper lesson:

Good APIs don’t just return data.
They communicate intent clearly.

When developers see:

GET /users/123

they shouldn’t have to guess what it means.

And when they see:

DELETE /users/123

they should know exactly what you’re asking the server to do.

Use the HTTP method to say what you mean.

That’s how APIs become predictable. 🚀

<img width="800" height="855" alt="image" src="https://github.com/user-attachments/assets/db5a3aea-e7e3-4692-b282-082534076421" />

https://lnkd.in/p/dXwNMwGF


****


You’ve copied thousands of URLs. But can you explain what every symbol inside one actually does? 👀

Alex was in a system design interview.

Interviewer:
“Take this URL and explain it.”

https://lnkd.in/dfg3fEtr

Alex:
“Umm… it’s a link?” 💀

Let’s decode it:

🔐 https:// → Scheme
How the resource should be accessed.

🌐 www → Subdomain
An optional subdivision of the domain.

🏠 example.com → Domain
Identifies the host.

🚪 :8080 → Port
Which network service to connect to.

📁 /products/shoes → Path
The resource/path being requested.

🔎 ?color=black&size=10 → Query parameters
Extra inputs sent with the request.

#️⃣ #reviews → Fragment
Points to a specific section of the resource.

So remember:

Scheme = HOW
Domain = WHERE
Port = WHICH SERVICE
Path = WHAT
Query = WITH WHAT OPTIONS
Fragment = WHICH SECTION

A URL isn’t just a “link.”

It’s a compact way of describing how to access something, where it lives, what you want, and sometimes which part you want to see.

Bonus: the fragment (#reviews) is typically handled by the browser/client and isn’t sent to the server in the HTTP request.

Next time you see a scary-looking URL, don’t panic.

Read it like a sentence. 😄

<img width="800" height="835" alt="image" src="https://github.com/user-attachments/assets/a85857bc-3261-460e-a554-aaef62c8b419" />

https://lnkd.in/p/dBYk4_c5

