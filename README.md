# EV_Service_Tracker

A comprehensive **Electric Vehicle (EV) Service & Maintenance Tracker** application built using **Zoho Creator** and **Deluge scripting**. This app helps EV owners and service centers manage vehicle registrations, service requests, and service history efficiently with automated workflows and dashboards.

---

## Features

- **Vehicle Registration**: Register EVs with all essential details.
- **Service Request Management**: Create, edit, and track service requests.
- **Service History Tracking**: Maintain detailed records of past services.
- **Automated Date Calculation**: Auto-calculate next service dates based on last service.
- **Custom Workflows**: Trigger actions on form events like create, edit.
- **Email & SMS Notifications**: Automated notifications on service status changes.
- **Interactive Dashboards**: Visualize key metrics using charts (pie, bar graphs).
- **User-friendly UI**: Easy-to-use forms and pages for smooth operation.

---

## Technology Stack

- **Platform:** Zoho Creator Low-Code Platform  
- **Scripting Language:** Deluge (Zoho's scripting language)  
- **UI:** Zoho Creator forms, reports, and dashboards  
- **Notifications:** Email and SMS via Zoho workflows

---

## Application Structure

| Form Name           | Purpose                                  |
|---------------------|------------------------------------------|
| Vehicle_Registration | Manage EV owner and vehicle details      |
| Service_Request     | Create and update service requests        |
| Service_History     | Maintain records of completed services    |

---

## Key Workflows & Automations

- Auto-calculate next service date on service completion.
- Trigger email and SMS notifications on request creation and status updates.
- Update dashboards dynamically based on live data.
- Conditional workflows based on record events (create, edit).

---

## Dashboards

- **Service Status Breakdown:** Pie chart/bar graph showing the count of requests by status.
- **Recent Service History:** List of recent service records.
- **Total Registered Vehicles:** Summary widget displaying the count of registered EVs.

---

## How to Deploy

1. Import the `.ds` file (Deluge script export) into your Zoho Creator account.
2. Set up required forms (`Vehicle_Registration`, `Service_Request`, `Service_History`).
3. Add workflows and schedules as per the included scripts.
4. Create dashboards and bind report widgets to corresponding forms.
5. Configure user permissions as needed.
6. Test workflows with sample data.

---

## Sample Data

You can use the sample data included in the `sample_data.csv` files (if available) to quickly populate the forms and test the app functionalities.

---

## Screenshots

![Dashboard](screenshots/dashboard.png)  
*EV Service Tracker Dashboard with service status pie chart*

![Service Request Form](screenshots/service_request_form.png)  
*Service Request creation form*

---

## Author

**Your Name**  
Email: your.email@example.com  
LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)  
GitHub: [github.com/yourusername](https://github.com/yourusername)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Zoho Creator Documentation: https://www.zoho.com/creator/help/  
- Deluge Script Guide: https://www.zoho.com/deluge/help/

---

If you want me to generate the actual Deluge code or more detailed instructions for any section, let me know!
