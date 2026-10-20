---
title: "Surgery"
---

This covers a full surgery: raise the request, approve it to schedule, do Pre-Op → Intra-Op → Post-Op care (moving the patient each time), and finally bill the items used. (Demo patient DESHPANDE RAJ KUMAR, IP26-00132; surgery PACEMAKER, Cardiology.)

**Flow:** Raise Surgery Request → Approve (schedule) → Pre-Op care → Intra-Op care (surgery) → Post-Op care → Billing

## 6.1 Raise the Surgery Request

**Navigate to:** Inpatient Record → Services → Procedures → Surgery Request

**Steps:**

1. Open the patient's record, go to the Services tab and open Procedures.
2. Under Surgery Request click **Add Row** and fill the details.
3. Set the Department, Procedure Name and the Schedule Date/Time, then click **Save**.

![Services → Procedures → Surgery Request → Add Row](../images/ip-manual-046-101.png)

*Services → Procedures → Surgery Request → Add Row*

![Fill the department, procedure and schedule date](../images/ip-manual-047-103.png)

*Fill the department, procedure and schedule date*

**Expected result:** The surgery request is saved ("Surgery HLC-SR-2026-00094 Requested Successfully").

![Surgery request saved](../images/ip-manual-047-104.png)

*Surgery request saved*

## 6.2 Approve and Schedule the Surgery

**Steps:**

1. Open the saved Surgery Request. Check the details and set the **Priority Level**.
2. Before approving, tick **Fitness Certification Completed** to confirm the patient is physically ready for the surgery.

![Surgery Request — tick Fitness Certification Completed before approving](../images/ip-manual-048-106.png)

*Surgery Request — tick Fitness Certification Completed before approving*

3. At the top right, **Approve** schedules the surgery and **Reject** cancels it. Click **Approve**, then confirm with **Yes**.

![Surgery request — details and Priority; Approve / Reject buttons](../images/ip-manual-049-108.png)

*Surgery request — details and Priority; Approve / Reject buttons*

![Confirm — Approve and create the Surgery Schedule](../images/ip-manual-049-109.png)

*Confirm — Approve and create the Surgery Schedule*

**Expected result:** A Surgery Schedule is made ("Surgery Schedule HLC-SC-2026-000319 created successfully"). The surgery is now scheduled.

![Surgery scheduled](../images/ip-manual-050-111.png)

*Surgery scheduled*

## 6.3 Pre-Op Care

**Steps:**

1. On the schedule, click **Start Pre-Op Care**.
2. In Pre OP Care, set the Check-in Time and choose the doctor who checked in (Check-in By).
3. Click **Add Vital Signs**, enter the patient's vitals before surgery, and **Save**.

![Pre-Op Care — check-in time and check-in doctor](../images/ip-manual-050-112.png)

*Pre-Op Care — check-in time and check-in doctor*

![Add Vital Signs before the surgery](../images/ip-manual-051-114.png)

*Add Vital Signs before the surgery*

4. Under the Details tab, add the **Surgery Resource Type** — the surgeon who will do the surgery.

![Details tab — add the surgeon (Resource Type)](../images/ip-manual-052-116.png)

*Details tab — add the surgeon (Resource Type)*

5. Click **Transfer** (top right) and set where to move the patient and which bed — here to the Operation Theatre / Cath Lab.

![Transfer the patient to the operation theatre](../images/ip-manual-053-118.png)

*Transfer the patient to the operation theatre*

**Expected result:** Vitals are recorded and the patient is moved to the operation theatre.

## 6.4 Intra-Op Care (the Surgery)

**Steps:**

1. After the transfer, the occupancy shows the theatre. Click **Start Intra-Op Care**.

![Occupancy shows the theatre — click Start Intra-Op Care](../images/ip-manual-054-120.png)

*Occupancy shows the theatre — click Start Intra-Op Care*

2. In Intra OP Care, fill the details and timings, then click **Start** to begin the surgery.

![Intra-Op Care — fill details, then Start](../images/ip-manual-054-121.png)

*Intra-Op Care — fill details, then Start*

3. Fill the Start and Completed times. When surgery is done, click **Transfer** to move the patient to the next ward and pick a free bed.

![Surgery start and completed times; Start Post-Op Care](../images/ip-manual-055-123.png)

*Surgery start and completed times; Start Post-Op Care*

![Transfer the patient to the next ward](../images/ip-manual-056-125.png)

*Transfer the patient to the next ward*

**Expected result:** The surgery is done and the patient is moved out of the theatre.

## 6.5 Post-Op Care

**Steps:**

1. Click **Start Post-Op Care**.
2. In Post OP Care, fill all the details — operation and anaesthesia times and recovery details.

![Post-Op Care — operation and anaesthesia details](../images/ip-manual-057-127.png)

*Post-Op Care — operation and anaesthesia details*

![Post-Op Care — recovery details](../images/ip-manual-057-128.png)

*Post-Op Care — recovery details*

3. Click **Transfer** to move the patient back to their own ward.

![Transfer the patient back to the ward](../images/ip-manual-058-130.png)

*Transfer the patient back to the ward*

**Expected result:** Post-op care is recorded and the patient is back in the ward.

## 6.6 Billing

**Steps:**

1. Click **To Be Billed**. In the Billing tab, add all the materials and equipment used in the surgery.

![Billing tab — add the items used](../images/ip-manual-059-132.png)

*Billing tab — add the items used*

2. Click **Save**, then **Add to Bill** to put them on the sales invoice, then **Submit**.

![Items added to the bill](../images/ip-manual-059-133.png)

*Items added to the bill*

3. After the items are added, click **Consume Stock** at the top right. A Surgery Stock Processing message opens — for the unavailable (shortage) items, a Surgery Stock Consumption document is created automatically.

![Surgery Stock Processing — a Surgery Stock Consumption document is created for the shortage items](../images/ip-manual-060-135.png)

*Surgery Stock Processing — a Surgery Stock Consumption document is created for the shortage items*

4. Click the Surgery Stock Consumption number (here HLC-SSC-2026-0000004) to open the document.

![Surgery Stock Consumption document (HLC-SSC-2026-0000004)](../images/ip-manual-060-136.png)

*Surgery Stock Consumption document (HLC-SSC-2026-0000004)*

5. In the Surgery Stock Consumption document, click **Transfer and Consume Stock** at the top right.
6. The stock is transferred and consumed, and all the items are added to the bill.

![Billing tab — stock transferred and consumed, all items Added to Bill](../images/ip-manual-061-138.png)

*Billing tab — stock transferred and consumed, all items Added to Bill*

**Expected result:** All surgery items are on the patient's bill, and any shortage stock is transferred and consumed.
