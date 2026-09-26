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
