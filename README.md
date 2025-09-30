# NGO Donations & Volunteer Management System

This project is a Salesforce-based solution to help NGOs manage **donations**, **volunteers**, and **events** in one place. It was built using **Salesforce Admin + Developer features** with automation, dashboards, and secure role-based access.

## Project Overview

* **Donation Tracking** – Supports one-time & monthly donations (Money, Food, Clothes, Groceries, Others).
* **Volunteer Management** – Registration, skills, availability, and event participation tracking.
* **Event Management** – Create and manage events, link donors and volunteers.
* **Automation** – Thank-you emails, birthday/anniversary greetings, monthly reminders.
* **Reports & Dashboards** – Top donors, donations by occasion, volunteers per event.


## Salesforce Features Used

* Custom Objects: Donation, Volunteer, Event
* Record Types & Page Layouts (One-Time vs Monthly Donations, Volunteer Registration vs Feedback)
* Validation Rules (email format, phone number, donation amount > 0, etc.)
* Profiles & Roles (NGO Admin, Donor Manager, Volunteer Coordinator)
* Flows for automation (emails, reminders, acknowledgements)
* Reports & Dashboards for real-time monitoring


## Testing Summary

* Donation creation → Sends thank-you email
* Monthly donor without donation → Reminder email sent
* Occasion set (e.g., Birthday) → Greeting email sent
* Volunteer registration → Welcome email sent
* Volunteer participation → Thank-you email sent
* Validation rules → Block invalid inputs (email, phone, amount)
* Record type switching → Correct layouts load as expected

## Future Enhancements

* Online payment integration (Razorpay/Stripe)
* Mobile app support (Salesforce Mobile / LWCs)
* Donor analytics with Einstein AI
* Smart volunteer-event matching based on skills & availability


## Author

**Sri Nithya Loka**
[lokasrinithya@gmail.com](mailto:lokasrinithya@gmail.com)


