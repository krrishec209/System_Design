Here are Top 45 with resources to study them (for free):

1) Design URL Shortener like TinyURL: https://lnkd.in/gB76Pknt

2) Design Text Storage Service like Pastebin: https://lnkd.in/gFHPJxnp

3) Design Netflix: https://lnkd.in/gzwN2ZjJ

4) Design Youtube: https://lnkd.in/gtKw4knw

5) Design Instagram: https://lnkd.in/grQN4rjG

6) Design Twitter: https://lnkd.in/gCjEn5YT

7) Design E-commerce Store like Amazon: https://lnkd.in/gzy6wzHy

8) Design WhatsApp: https://lnkd.in/gKUheB47

9) Design Facebook: https://lnkd.in/g_yurcsQ

10) Design File Sharing System like Dropbox: https://lnkd.in/gQs2vm38

11) Design Autocomplete for Search Engines: https://lnkd.in/g-7QkTCe

12) Design Google Search: https://lnkd.in/gxt65hEW

13) Design Airbnb: https://lnkd.in/gcUQrt8R

14) Design Tinder: https://lnkd.in/grpyXJbc

15) Design Stock Exchange system: https://lnkd.in/gt_PZhzy

16) Design Google Maps: https://lnkd.in/gPjVJr2Z

17) Design Distributed Web Crawler: https://lnkd.in/gZfAzjjV

18) Design Location Based Service like Yelp: https://lnkd.in/gKAGkFBQ

19) Design Uber: https://lnkd.in/gcHvRgkY

20) Design Ticket Booking System like BookMyShow: https://lnkd.in/g3qJgG6r

21) Design Spotify: https://lnkd.in/gArruN9e

22) Design Food Delivery App like Doordash: https://lnkd.in/gGHdAa_i

23) Design Zoom: https://lnkd.in/gcJuhcMG

24) Design Shopify: https://lnkd.in/g85JfHhH

25) Design Google Docs: https://lnkd.in/gAFE7G_m

26) Design TikTok: https://lnkd.in/gT2Ju9-8

27) Design Reddit: https://lnkd.in/grGAf4dR

28) Design Code Deployment System: https://lnkd.in/gr_BJD6f

29) Design Distributed Message Queue like Kafka: https://lnkd.in/gNAeTiCP

30) Design Distributed Cloud Storage like S3: https://lnkd.in/gmFbArYt

31) Design Distributed Job Scheduler: https://lnkd.in/g6T5Dfr7

32) Design Rate Limiter: https://lnkd.in/gEFF6H_f

33) Design Distributed Locking Service: https://lnkd.in/gmx2Bhc4

34) Design Distributed key-value store: https://lnkd.in/gdYCP9w4

35) Design Distributed Cache: https://lnkd.in/gmKpA4qE

36) Design Notification Service: https://lnkd.in/gNNTUSAu

37) Design Metrics & Logging Service: https://lnkd.in/gQM7XTuh

38) Design Content Delivery Network (CDN): https://lnkd.in/gVjBNqr7

39) Design Parking Garage: https://lnkd.in/gHhe84bd

40) Design Flight Booking System: https://lnkd.in/gkVkTb65

41) Design Online Code Editor: https://lnkd.in/gRfCACAV

42) Design Vending Machine: https://lnkd.in/gyhA8QUZ

43) Design Authentication System: https://lnkd.in/gK95Y3mg

44) Design Payment System: https://lnkd.in/gBuJkXUf

45) Design UPI: https://lnkd.in/gP4AatEd


*****************************************************

80% of the System Design interviews I’ve given in the last 7 years…
…have revolved around just 20% of the most repeated, practical problems.

If you’re preparing for FAANG+ interviews or just trying to learn System Design the right way, this is the MUST-SOLVE LIST.

I've categorized them based on themes + added notes on what each one really tests you on.

► Read-Heavy Systems 
These focus on scale, latency, and efficient data fetching. 
1. Design a URL Shortener (Bitly) 
 → Talk about key generation, collisions, and DB storage. 
 → Add caching and DB sharding if traffic is high.

2. Design an Image Hosting Service 
 → Talk about object storage (S3, GCS) + CDN usage. 
 → Consider image deduplication and resizing strategies.

3. Design a Social Media Platform (Twitter/Facebook) 
 → Talk about posts, timelines, relationships (follows, friends). 
 → Focus on denormalized storage and sharding.

4. Design a NewsFeed System (Hard) 
 → Push vs Pull models, Fanout on Write vs Read. 
 → Caching, pagination, and ranking algorithms.

► Write-Heavy Systems 
Here, durability, throughput, and ingestion speed are critical.

5. Design a Rate Limiter 
 → Token bucket or leaky bucket algorithms. 
 → Redis-backed counters + TTL logic.

6. Design a Log Collection and Analysis System 
 → Use Kafka for ingestion, and something like ELK for processing. 
 → Talk about partitioning, buffering, and real-time querying.

7. Design a Voting System 
 → Idempotency, fraud prevention, and result aggregation. 
 → Real-time vs eventual vote count updates.

8. Design a Trending Topics System 
 → Use count-min sketch or approximate counting. 
 → Talk about sliding window aggregation + ranking.

► Strong Consistency Systems 
Transactional integrity and failure handling become the focus.

9. Design an Online Ticket Booking System 
 → Handle race conditions with locking or optimistic concurrency. 
 → Talk about seat reservation + payment flow.

10. Design an E-Commerce Website (Amazon) 
 → Cover product catalog, cart service, order processing. 
 → Include DB consistency, checkout idempotency.

11. Design an Online Messaging App (WhatsApp/Slack) 
 → Talk about message queues, delivery receipts, retries. 
 → Offline storage, notification delivery, scaling chat infra.

12. Design a Task Management Tool 
 → CRUD APIs, user auth, task assignment. 
 → Background jobs, status updates, and audit trails.

► Scheduler Services 
Timing, reliability, and eventual execution are tested here.

13. Design a Web Crawler 
 → BFS vs DFS for crawling, politeness rules. 
 → Distributed queues, duplicate URL filters.

14. Design a Task Scheduler 
 → Job queues, retry logic, cron-based triggers. 
 → Priority queues and task deduplication.

15. Design a Real-Time Notification System 
 → Push vs Polling, webhooks, and device token mgmt. 
 → Scale delivery across millions of users.


► Trie / Proximity Systems 
Efficient data structures and latency-optimized retrieval.

16. Design a Search Autocomplete System 
 → Trie or Ternary Search Tree backed by frequency rank. 
 → Debouncing, caching, and typo-tolerance.

17. Design a Ride-Sharing App (Uber/Lyft) 
 → Matchmaking engine, real-time location tracking. 
 → Talk about ETA algorithms, surge pricing, DB design.

https://www.linkedin.com/posts/anshul-chhabra-46ba9b113_80-of-the-system-design-interviews-ive-activity-7336254700582785024-9ERK?utm_source=share&utm_medium=member_desktop&rcm=ACoAAARSzbgBGEbWHnTkxyPnkFaeZcnK-pW0lqg
