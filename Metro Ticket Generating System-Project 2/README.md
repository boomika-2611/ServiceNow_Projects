**Metro Ticket Generating System – ServiceNow**

**Overview**

The Metro Ticket Generating System is an automated ServiceNow solution designed to streamline metro ticket booking through the Service Portal. It allows users to book metro tickets by submitting required travel and payment details, while the system automatically stores booking information in a custom database using Flow Designer.

This project demonstrates end-to-end automation from catalog submission to data persistence with minimal manual intervention.

**Key Features**

» Service Catalog item for metro ticket booking

» User-friendly form with mandatory validations

» Automated data capture using Flow Designer

» Custom Metro Database table to store ticket details

» End-to-end workflow execution without manual processing

» Real-time record creation upon form submission

**Modules Used**

Service Catalog

Service Portal

Flow Designer

Custom Tables (u_metro_database)

Catalog Variables

Flow Execution & Logs

**Workflow Summary**

Service Portal → Book Metro Ticket → Form Submission →
Flow Triggered → Data Captured → Metro Database Record Created → Completion

**Metro Database Details**

The custom Metro Database table stores the following information:

Smart Card Holder Name

Smart Card Number

Mode of Payment

Recharge Amount

User Details

Created Date

Each ticket booking creates a new record automatically in the Metro Database table.

**Testing & Validation**

The system was tested successfully for:

Metro ticket catalog submission

Correct variable mapping in Flow Designer

Automatic record creation in Metro Database

Flow execution completion without errors

**Conclusion**

The Metro Ticket Generating System enhances user experience by automating the metro ticket booking process. It eliminates manual data entry, ensures accurate record creation, and provides a scalable solution for handling metro ticket requests efficiently within ServiceNow.
