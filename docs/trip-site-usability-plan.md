# Trip site usability plan

For Karl. Two jobs: a new member joining a trip, and a leader creating a trip. Checked in a browser on 5 Nov 2026.

## What this plan is for

This plan is for the trip app at [https://cmc.adventureanywhere.org/trip/nov-second-saturday](https://cmc.adventureanywhere.org/trip/nov-second-saturday).

That URL is a different product from [https://www.cmc.org/](https://www.cmc.org/). cmc.org is the Colorado Mountain Club Plone site (Find Trips, Routes & Places, Schedule & Manage). Nothing on the path from Karl’s URL goes there: no link, no shared login, no shared trip page. Leave cmc.org out of these tasks.

The host is `cmc.adventureanywhere.org`. The page brands itself **Catholic Mountain Club**. The open trip is **Butler Gulch Hike, November 21, 2026**. Adventure Anywhere is the product (the network page calls it a non-profit trip network). This club is one group on it.

**What the trip page shows, logged out, desktop**

Three columns. Left rail: club mark, Login / Register, a date jump (the view opened on October 5, 2025), a scrollable trip list, and Calendar View. Middle: the trip. Right: a map of the Front Range.

The trip block shows a photo, the title, a **copy** link, the description (6-mile lollipop, spikes, meet at the PnR at 9am, section JJ, carpool, food or beer), an AllTrails link, organizers Jeff DePree and Karl Uschold, and “Got a ride? 2 drivers might have space.” The route line is Wooly Mammoth Lot, 9:00AM Saturday, 38.53 miles, Butler Gulch Trailhead, the hike (1h 54min, 572m, 5.5mi), return around 3:00PM to Wooly Mammoth Lot. Then three buttons: **Register for this trip** (green), **Thinking about it**, **Wrong time for me**. Under that, a 5-day weather chart for the trailhead.

The left list, in the same view, included The Dunes (Mar 7–8, 2026), Creatio: Herman Gulch, Hagar Mountain, Eclipsed Camino (Aug 6–18, 2026, $1000, bike icon), and Butler Gulch. The list ended at “No Future Trips.” Clicking a trip name loads that trip in the middle column.

**Phone width (390px)**

The left list and the map are gone. A bottom bar shows Calendar, Main, and Map. The description, the route line, the AllTrails URL, and **Wrong time for me** are cut off on the right. Confirm that on a real phone. It is already visible in a narrow browser window.

**Join**

All three buttons are on the page without an account. They do not open a signup form. They go to **Login to your account**: Google, Facebook, email or username, password, register, forgot password. The trip and the left list stay on screen behind the login card. The signup form after a successful login was not opened. Do not design it until someone is logged in.

**Create**

The public create control on this trip is **copy**, next to the title. Following it stops at the same login card. There is no public trip form. A second phrase, “organize trip,” appears on the trailhead page linked from the route line. That control was not completed while logged out. Treat the editor, save, and “did the new trip show up in the list” as behind login.

**Other trips and other groups**

Trip to trip, on this host: the left list, Calendar View, and the places on the route (Wooly Mammoth Lot, Butler Gulch Trailhead). Each place page lists trips there.

Group to group: the globe under the club mark opens Explore the Network (`/sn`). That page lists other groups, each on its own host (The Tuesdays, Western Outdoor Adventure Hub, Wilderness Adventure Club, Northern California Outdoor Adventure Recreation, Outdoor Adventure Recreation, Advanced Adventures Club), plus “Start a new group.” Leaving this club means leaving this host.

**Hypotheses, still unproven**

The UI looks outdated. The affordances are hard to understand. Moving between trips or groups is unclear. The narrow-window clip is something to reproduce on a phone, not a finished finding. Write down what the tasks show.

---

## 1. Assess the existing site

Do this before interviews. Start every task from Karl’s URL, logged out, unless the task says otherwise.

### Access first

Ask for a new-member login and an organizer login on this host, plus permission to copy Butler Gulch into a disposable trip and delete it. Do not register a real person for November 21. If there is no login this week, use the fallback at the end of this section and keep going on the public page.

Viewports: 390px and 1280px. A real phone for the narrow pass if you have one.

### Heuristic pass

One designer, both widths. Pages from this trip only:

- The Butler Gulch URL.
- One other trip from the left list (use The Dunes, a past trip, and Eclipsed Camino, which shows a price).
- Calendar View.
- The trailhead linked from the route.
- Explore the Network (the globe).
- Login, reached by Register and by copy.
- Register a new account, only as far as the form. Do not create an account unless staff ask you to.

Score only these:

- Can someone tell what Register, Thinking about it, and Wrong time for me will do before they click?
- Does the page answer when, who leads, where to meet, whether a seat in a car is open, and what happens after Register?
- On the desktop, can you open another trip from the list and get back without typing a URL?
- On the phone, can you reach the trip list, the map, and the third button?
- Is “copy” recognizable as “create a trip”?

Screenshot, URL, one line, severity: blocks the job, slows the job, or cosmetic.

### Task walkthroughs

Think aloud. No hints. Stop at 8 minutes and mark it incomplete. Screenshot every wrong turn.

**Join**

| ID | Task | Pass |
| --- | --- | --- |
| J1 | From the Butler Gulch URL, say whether you can go, where you meet, and how you get a ride. | Answers match the text on the page. |
| J2 | Sign up for the trip, as far as the site lets you. | You reach a confirmation, or you stop at login and name that stop. |
| J3 | Say what Thinking about it and Wrong time for me are for. Then click each. | The result is recorded. A guess made before the click is kept separate from what happened. |
| J4 | Open The Dunes from the list, then come back to Butler Gulch. On the phone, do it with the bottom bar. | Both trips opened. The phone path is written down even if the list is missing. |
| J5 | From Butler Gulch, open the club’s other trips in Calendar View, then open one. | The calendar shows this club’s trips, or you record what it shows instead. |

**Create**

| ID | Task | Pass |
| --- | --- | --- |
| C1 | Logged out, from Butler Gulch, find how a leader would set up a similar hike. | You hit login via copy, or you find another control and record its label. |
| C2 | Logged in as an organizer, copy this hike to a disposable date, save, and find the new trip in the left list and in Calendar View. | The new trip has a URL, or the form blocked you and the blocker is named. Delete it before you finish. |
| C3 | From the trailhead link, use “organize trip” and stop at the first screen that is clearly the editor or clearly login. | URL and screenshot of that stop. |

Run J1–J5 and C1 at both widths. Run C2 on desktop, then repeat the save step on the phone.

### What to capture

- Viewport, logged in or not, start URL, end URL.
- The label of each control used, and the label the person expected.
- The words they said when they paused.
- Screenshot.
- Tag: supports one of the hypotheses, or new.

### When a screen is behind login

If there is no account this week:

1. One screenshare with a member who taps Register on Butler Gulch and stops before a real signup.
2. One screenshare with an organizer who runs C2 on a copy they can delete.
3. A shot list, so both people photograph the same steps: the form after Register, Thinking about it, Wrong time for me, the copy editor, save, and the new trip in the list.

Design nothing for those steps until the stills exist.

### Done

- J1–J5 and C1 done at both widths.
- C2–C3 done with an organizer login, or the screenshares are booked.
- An issue list. Each row has a URL, a viewport, and a severity.
- A one-page sketch of the paths people actually took, including login walls and the jump to other hosts.
- No redesign yet.

---

## 2. Interviews

Run these after the issue list exists.

### Who

- 5 people who have tried to join a Catholic Mountain Club trip in the last year, or who opened one and stopped. At least 2 who finished a signup. At least 2 who did not. At least 3 whose main screen is a phone.
- 4 people who have posted a trip on this host in the last year. Include one person who posted their first trip recently.
- Skip anyone who builds the site. If Jeff handles the “Email Jeff” bugs, talk to him separately and tag that as support history.

Recruit from this club’s list. Do not recruit Colorado Mountain Club members off cmc.org for these sessions. They use a different product.

### How to run a session

45 minutes. Their phone for members. Laptop plus phone for leaders. Start on the Butler Gulch URL. Record the screen.

1. Member task, no tour: “Get as far as you can toward signing up for this hike.” Then: “Find a different trip this club is running.” Then: “See what another club on this network has coming up.”
2. Leader task: “Make a trip like this one, the way you normally would,” on a disposable copy. If they refuse to save, reopen a trip they already posted and walk it without saving.
3. At each pause: “What are you looking for?” Do not point.
4. After the tasks: “What do you use when this gets frustrating?”
5. Last five minutes: “What would you change?” Tag every answer from this question as opinion.

### What not to plant

Do not ask whether it looks old, whether the buttons are confusing, whether the phone layout is broken, or whether switching trips is hard. Those are the hypotheses. If you want a reaction, ask in the last five minutes and tag it prompted.

Do not say “copy,” “calendar,” “network,” or “Adventure Anywhere” before they do. Do not demonstrate the left list.

### Opinion versus friction

Friction is a pause, the wrong control, Back, a question to you, or quitting. Opinion is a wish with no stall.

A change goes into the design only when the same friction shows up for 2 people, or for 1 person and the matching row on the issue list.

### Done

- Notes tied to a task id and a URL.
- A friction list that cleared that bar.
- An opinion list, kept apart.
- Support notes that match a friction row, marked as corroboration.

---

## 3. New flows

Work from the friction list and from the pieces already on this page. Add a field only when a session showed someone needed it.

### Join a trip

The door is this trip URL, the left list, or Calendar View. On a phone those have to be reachable. Today the list and the map disappear under 920px and the bottom bar does not show the list.

1. **Scan.** This club’s upcoming trips. Each row shows date, title, and whether it is a hike or something else (the list already uses icons). Past trips stay reachable and look past.
2. **Read.** One trip, in an order that fits a phone: date and meeting time, where to meet, ride situation, distance and the hike, who is leading, the writeup. Nothing cut off the right edge.
3. **Choose.** Register, Thinking about it, and Wrong time for me say what will happen. Right now all three dump into login, so the labels over-promise. After the logged-in capture, each one should do the thing the label says.
4. **Account.** Google, Facebook, or email, then back on this same trip. Registering a new account joins this club (the register link carries this club’s id).
5. **Confirm.** The screen after Register. Design it only from the logged-in capture. Include where the person sees the signup later.
6. **Carpool.** The ride line is already the most concrete part of the page. Keep it. Do not make someone log in just to see that two drivers might have space.

### Create a trip

The public path stops at login on **copy**. Build the editor only after C2.

The shape to aim for, using what Butler Gulch already shows a member:

1. Start from a trip like this one (**copy**) or from a place (**organize trip** on the trailhead).
2. Date, meeting time, meeting place, destination, and the short description. Those are the things a member reads first.
3. The club is already selected. A leader should not have to hunt for Catholic Mountain Club.
4. Save, then the new trip appears in the left list and on Calendar View, and the public page looks like Butler Gulch.
5. Carpool and the three response buttons come after the trip exists, not before it has a title and a date.

Phone rule: one step on screen, the save button visible, and the leader can stop and resume. Check that on C2 at 390px.

### Group to group, trip to trip

- From a trip, other trips for this club are one tap away on desktop and on the phone. Calendar View is the same set, not a second product.
- A place on the route lists the trips that use it, which is the trail-to-trip jump already started on the trailhead page.
- The globe stays the way out to other groups. Each group is its own site. The switcher should say you are leaving Catholic Mountain Club, and name the group you are opening. “Start a new group” stays a separate request, not a trip-create button.

### Review before anyone builds

1. One diagram each for join, create, and switching trip or group. Boxes are screens you have seen, or screens the login sessions added.
2. A phone-width prototype of join through confirm, and of create through the public URL.
3. Retest with 3 of the members and 2 of the leaders, same tasks as J2, J4, and C2. Pass: they finish with no hint.
4. One pass with whoever runs this club, for the rules you cannot drop: approval, waivers, and the ride list.
5. Engineering says how the overhaul lands in the shared Adventure Anywhere app. Build the phone join path first. It is the page Karl already sent people to. The same screens ship for every club.

### Done

The prototype passed the retest, the club rules are signed off, and engineering named the build slice. Every friction row is addressed, deferred, or dropped, with a reason.

---

## 4. Sequence and owners

Each step finishes before the next one starts.

| Step | Who | Result |
| --- | --- | --- |
| 1. Member login, organizer login, and a disposable copy of Butler Gulch | Karl | Logins, or booked screenshares |
| 2. Heuristics and logged-out tasks at 390 and 1280, starting from Karl’s URL | Karl | Issue list and path sketch |
| 3. Logged-in copy and organize-trip tasks | Karl, or Research if someone else runs them. Engineering sits in on C2 | C2–C3 recorded, or the blocker named |
| 4. Five members and four leaders | Research runs them. Karl watches at least two of each | Friction list apart from opinions |
| 5. Readout | Karl writes it. Research and Engineering comment once | What to change in the shared app, for every club |
| 6. Flows and phone prototype | Karl | Diagrams and prototype |
| 7. Retest and club-rules review | Research retests. Karl runs the rules review | Pass, or one short fix list and one more retest |
| 8. Build join on the phone, then create | Engineering builds. Karl checks each slice on a phone against J2, J4, and C2 | Both jobs work on this host |

Scope is set. The work is an overhaul of the shared Adventure Anywhere product. Catholic Mountain Club is the club we study. The same changes apply to every club.

- **Test access.** If nobody can provide an organizer login and a trip that can be deleted, steps 3 and 8 wait on looking around or screenshares, and the create UI stays blocked. Do not register, copy, edit, or delete anything to get there.

---

## Decisions

Karl, 5 Nov 2026: overhaul the shared Adventure Anywhere product. Catholic Mountain Club is the club we study. The same changes apply to every club on that shell. That is intended.

Agents may look around, including while Karl is logged in. Do not register, copy, edit, or delete anything.

## Open questions

These change the plan. Everything else can wait.

1. Who can give an organizer login and delete a copied test trip? Until then, logged-in screens come from looking around or from a screenshare, not from creating data.
