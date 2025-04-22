<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Define Roles & Access
- Organize Departments & Teams
- Adjust Ticket Submission Rules
- Set SLA Priorities
- Create Help Topics

<h2>Configuration Steps</h2>

Follow these instructions to configure your ticketing system.

Login Information
Admin/Analyst Access: Admin Login Page

End Users Access: User Portal

Understanding the Panels
The Agent Panel is used by customer service staff to manage tickets and communicate with users.

The Admin Panel is where system administrators configure settings, assign roles, and manage access.

Setting Up Roles
Navigate to Admin Panel → Agents → Roles

Assign permissions to different roles (e.g., "Super Admin" for full access).

Creating Departments
Go to Admin Panel → Agents → Departments

Organize departments based on ticket visibility (e.g., IT Support, Networking, General Help Desk).

Building Teams
Open Admin Panel → Agents → Teams

Teams can include agents from multiple departments to handle different needs (e.g., Online Services Team).

Managing Ticket Access
Visit Admin Panel → Settings → User Settings

Adjust access:

Allow anyone to submit tickets.

Require registration and login before ticket submission.

Adding Agents (Support Staff)
Navigate to Admin Panel → Agents → Add New

Example setup:

Alex (Dept: IT Support)

Sam (Dept: Customer Service)

Adding Users (Customers)
Go to Agent Panel → Users → Add New

Example setup:

Jordan

Casey

Setting Up SLA (Ticket Response Times)
Open Admin Panel → Manage → SLA

Define different priority levels:

(Keep in mind you can set these times to whatever makes sense for the company or your business)

High Priority: 1-hour response, available 24/7.

Medium Priority: 4-hour response, available 24/7.

Low Priority: 8-hour response, available during business hours.

Creating Help Topics (For Ticket Submission)
Go to Admin Panel → Manage → Help Topics

Add relevant categories:

System Outages

Hardware Issues

Software Requests

Password Reset

Miscellaneous

This is a general guideline. You may change some of the information if needed
