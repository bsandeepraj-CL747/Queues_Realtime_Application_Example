# Kimi AI Queue Management Simulator

An interactive website that demonstrates how **Kimi AI handles high user demand** through a simplified queue-management model. It uses a restaurant analogy to explain server capacity, waiting queues, paid-user priority, and overload rejection.

## Kimi AI Queue Structure

* **AI Servers (2):** Represent concurrent processing capacity for handling user requests.
* **Waiting Queue (3 slots):** Holds incoming requests when all servers are busy.
* **Paid-User Priority:** Paid users move ahead of free users in the waiting queue.
* **Queue Overflow:** When capacity is exhausted, additional users may receive a "Too many people, try again" message.
* **Request Processing:** Each request takes several simulation steps to complete before a server becomes available.

## Features

* Add free and paid users manually.
* Simulate automatic user arrivals.
* Control simulation speed, pause, resume, and reset.
* Track queue status, server availability, rejected users, and activity logs.

## Tech Stack

HTML, CSS, JavaScript.

## How to Run

Open the HTML file in any modern web browser.

**Note:** The server count, queue size, processing duration, and priority rules are illustrative simulation settings, not verified details of Kimi AI's actual internal infrastructure.
