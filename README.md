<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" />
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution
This guide explains the journey of a ticket in osTicket from the time it’s created to when it’s resolved, step by step in a simple way.

## Tools and Technologies Used
- **Microsoft Azure** (for Virtual Machines)
- **Remote Desktop** (to connect to the system)
- **IIS (Internet Information Services)** (to run osTicket)

## Operating System
- **Windows 10 Pro (21H2)**

---

## Ticket Lifecycle Steps
Here’s how a ticket moves through osTicket:
1. **Intake:** A ticket is created by the customer.
2. **Assignment & Communication:** The ticket is assigned to a helper (Agent), and updates are shared with the customer.
3. **Working the Issue:** The helper works to solve the problem.
4. **Resolution:** The ticket is solved and marked as complete.

---

## Key Terms to Know
| **Term**             | **What It Means**                                                                                     |
|-----------------------|-----------------------------------------------------------------------------------------------------|
| **Assigned**          | A ticket is given to an Agent, Team, or Department to handle.                                       |
| **Working the Issue** | The Agent talks to the customer and updates the ticket with steps they are taking to fix the issue. |
| **Resolution**        | The issue is solved, and the ticket is closed.                                                     |

---

## Lifecycle Stages Explained

### 1. Customer Creates a Ticket
The customer uses osTicket to submit their problem. They get a confirmation that their request was received.

<p align="center">
  <img src="https://i.imgur.com/d4GVlJF.png" height="65%" width="65%" alt="end-user experience" />
</p>

<p align="center">
  <img src="https://i.imgur.com/S82KGP1.png" height="80%" width="80%" alt="check request submission" />
</p>

---

### 2. Intake: Viewing the New Ticket
When an Agent (helper) logs in, they see all the tickets. Tickets show:
- **Ticket Number**
- **Who Created It**
- **Priority Level** (how urgent it is)
- **Who It’s Assigned To**

Agents can assign tickets to themselves, or a manager can assign them.

<p align="center">
  <img src="https://i.imgur.com/9TfvRro.png" height="80%" width="80%" alt="helpdesk dashboard" />
</p>

---

### 3. Working the Issue: Updating the Ticket
Let’s say the customer reports, "The entire mobile banking is down." This is serious! The Agent changes the ticket’s priority from **Normal** to **Emergency** and adds notes about the issue.

<p align="center">
  <img src="https://i.imgur.com/bKvZzmJ.png" height="80%" width="80%" alt="changing priority" />
</p>

Next, the ticket is assigned to **Jane Doe** and moved to the **System Administrators Department** (specialized team) for resolution.

<p align="center">
  <img src="https://i.imgur.com/NtzUgK9.png" height="65%" width="65%" alt="ticket updates" />
</p>

Now the ticket shows:
- **Assigned to:** Jane Doe
- **Priority:** Emergency

<p align="center">
  <img src="https://i.imgur.com/8Iywct3.png" height="65%" width="65%" alt="updated ticket info" />
</p>

---

### 4. Resolution: Closing the Ticket
The System Administrators fix the issue and add comments to the ticket explaining the solution.

<p align="center">
  <img src="https://i.imgur.com/3q7KJ5c.png" height="65%" width="65%" alt="ticket resolved" />
</p>

Finally, the ticket is marked as **Closed** because the problem is solved. It moves to the **Closed Tickets** section.

<p align="center">
  <img src="https://i.imgur.com/BtPSpZs.png" height="65%" width="65%" alt="ticket marked as closed" />
</p>

---

## That’s a Wrap!
You’ve now seen how a ticket goes through osTicket from start to finish. 
This system is great for organizing and solving customer issues quickly!

<p align="center">
  <b>"Ask yourself: How uncomfortable are you willing to become to reach your fullest potential?"</b>
</p>
