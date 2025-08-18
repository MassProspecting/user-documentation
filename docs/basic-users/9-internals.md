## MassProspecting Internals

You you are getting started...

- [🚀 Try MassProspecting here](https://massprospecting.com).
- [📚 Find More Documentation](https://github.com/MassProspecting/docs).
- [👥 Join Our Facebook Group](https://www.facebook.com/groups/massprospecting).
- [🔗 Follow Us on LinkedIn](https://www.linkedin.com/company/massprospecting).

If you are a **Developer**:

- [💻 Check out our SDK](https://github.com/MassProspecting/mass-sdk) _(private access)_.
- [🔌 Check out our API client](https://github.com/massprospecting/mass-client).
- [⭐️ Follow MassProspecting on GitHub](https://github.com/MassProspecting).

If you are part of the **MassProspecting Team**, helping us to develop this wonderful product:

- [🛠️ Learn the MassProspecting Architecture](https://github.com/MassProspecting/docs/blob/main/internals/01-architecture.md).
- [🖥️ Learn How to Install Your MassProspecting Environment](https://github.com/MassProspecting/docs/blob/main/internals/02-installation.md).
- [🧩 Data Model](https://github.com/MassProspecting/docs/blob/main/internals/03-data-model.md).
- [🧪 QA Operations](https://github.com/MassProspecting/docs/blob/main/internals/04-qa-operations.md).

## Features

Introducing some of the features of MassProspecting.

1. [MassProspecting Lead Scraping Features](#massprospecting-lead-scraping-features)
2. [Automation Rules for Lead Processing](#2-automation-rules-for-lead-processing)
3. [Unibox Communication Management](#3-unibox-communication-management)
4. [Marketplace for Sales Assistants](#4-marketplace-for-sales-assistants)
5. [Profiles Dashboard](#5-profiles-dashboard)
6. [Leads Management](#6-leads-management)

### 1. Lead Scraping Sources Overview

MassProspecting provides several automated lead scraping features that simplify the process of gathering data from various platforms. Below are some of the key features shown in the screenshots:

![Lead Scraping Sources Overview](../../assets/beta-test.1.1%20-%20leads%20scraping%20sources%201.jpeg)

MassProspecting offers multiple lead scraping tools, including:

- **Apollo PeopleSearch**: Run an Apollo search using RPA to get email, company, and LinkedIn information.
- **Facebook GroupPosts**: Scrape posts from Facebook groups you’re a part of, including post content, leads, and images.
- **LinkedIn PublicFeed**: Scrape public posts on LinkedIn, gather leads, and collect post content and images.

### 2. Automation Rules for Lead Processing

MassProspecting also provides an automation rules feature that allows you to create custom workflows for lead processing. These workflows can include actions, filters, and triggers to help automate the handling of scraped data.

#### 2.1 Rule Management Overview

![Automation Rules Overview](../../assets/beta-test.2.1%20-%20automation%20rules%201.jpeg)

The rules management interface provides a list of all created rules, with details such as:

- **Rule Name**: A descriptive name for each rule.
- **Creation Time**: Indicates when each rule was created.
- **Instances**: Shows the number of times the rule has been triggered.
- **Description**: Details of the trigger and action for each rule.
- **Active Status**: Shows if the rule is currently active.

#### 2.2 Creating and Editing Rules

![Rule Creation and Editing](../../assets/beta-test.2.2%20-%20automation%20rules%202.jpeg)

To create or edit a rule, the interface allows you to:

- **Define Triggers**: Specify an event, such as when a new lead is scraped, to start the rule.
- **Add Filters**: Optionally add filters to refine which leads the rule should act on.
- **Define Actions**: Specify the actions to take, such as adding tags or performing email verification.

These features allow for powerful automation capabilities, making lead management streamlined and efficient.

### 3. Unibox Communication Management

The Unibox feature in MassProspecting provides a consolidated interface for managing communication with leads from different channels.

![Unibox Communication Management](../../assets/beta-test.3.1%20-%20unibox.jpeg)

#### 3.1 Unified Inbox for All Channels

The Unibox gathers all communications across multiple platforms (LinkedIn, Facebook, Email) into a single interface. This makes it easy to:

- **View Conversations**: All conversations are displayed in a list, sorted by the most recent activity.
- **Identify Channels**: Icons beside each contact indicate the channel of communication, such as LinkedIn, Facebook, or Gmail.

#### 3.2 Tagging and Tracking

- **Tag Conversations**: You can choose tags to categorize conversations, making it easier to track communication progress.
- **Conversation Details**: On selecting a contact, the detailed conversation history appears on the right side, allowing you to follow up effectively.

The Unibox feature ensures that you never miss an important message and can efficiently manage communications across all your lead generation platforms.

### 4. Marketplace of Profiles

The MassProspecting Marketplace allows you to rent access to other people's social accounts and use them as your "Sales Assistants" to boost your outreach capabilities.

![Marketplace for Profiles](../../assets/beta-test.4.1%20-%20marketplace%20of%20sending%20profiles.jpeg)

#### 4.1 Renting Social Accounts

- **Diverse Options**: The marketplace offers a variety of accounts from different locations, including LinkedIn and Facebook, allowing you to choose the account that fits your needs.
- **Monthly Rates**: Each profile is available for rent at a monthly rate, which varies depending on the account owner and location, ranging from $15 to $90 per month.

#### 4.2 Permissions and Features

- **Unlimited Proxy Bandwidth Included** (✨ New Feature): Every rented account comes with 1GB of proxy bandwidth to ensure secure use.
- **Customization Permissions**: The owner of the social account allows you to:
  - **Edit Account Headline**: Modify the headline of their account to suit your marketing strategy.
  - **Change Profile Banner**: Update the banner to reflect your business branding.
  - **Add a Job Position**: Add a current job position in your company, making it easier to leverage the account for outreach.

This feature is designed to make your sales outreach more efficient by increasing the number of social profiles you can use, all while ensuring you have the permissions necessary to personalize the accounts for effective engagement.

### 5. Profiles Dashboard

The Profiles Dashboard in MassProspecting provides a centralized view of all available profiles used for outreach, enrichment, scraping, and other RPA activities. 

![Profiles Dashboard](../../assets/beta-test.5.1%20-%20sending%20profiles%20dashboard.jpeg)

#### 5.1 Profile List Overview

- **Profile Names**: The dashboard displays a list of all profiles, including individual and business accounts used for various activities.
- **Tags and Types**: Each profile is labeled with relevant tags to indicate its purpose (e.g., "private", "testing-facebook") and type (e.g., LinkedIn, Facebook, Gmail). This helps in categorizing the profiles for easy identification.
- **Accessing Types**: The profiles indicate the type of access or integration, such as:
  - **API**: Used for automated connections via available APIs.
  - **RPA**: Used for robotic process automation activities.
  - **MTA**: Used for email and message sending.
- **State**: The current status of each profile is visible, indicating whether a profile is idle or actively being used (e.g., "scraping_inbox").

#### 5.2 Managing Profiles

- **View and Edit Profiles**: The settings icon next to each profile allows users to view and make modifications to the profile's configuration.
- **Multi-Channel Access**: Profiles can access multiple platforms, such as LinkedIn, Facebook, Gmail, etc., allowing for a wide variety of outreach options.
  
The Profiles Dashboard allows users to effectively manage and track the various accounts used for lead generation, ensuring efficient use and easy organization of available resources.

### 6. Leads Management

MassProspecting provides a comprehensive Leads Management system, enabling you to organize, filter, and tag leads to streamline your outreach and engagement processes.

#### 6.1 Lead Overview and Search Filters

![Leads Management Overview](../../assets/beta-test.6.1%20-%20leads%20management%201.png)

- **Lead Information**: The leads dashboard displays key information such as social profiles (LinkedIn, Facebook, Email), first and last name, timezone, job title, and company. This helps you quickly access important details about each lead.
- **Search and Filters**: You can easily filter leads using keywords, such as names or tags.
- **Actions**: The leads can be edited or tagged using the options provided in each row. This ensures that lead information is always up-to-date.

#### 6.2 Tagging Leads for Better Organization

![Lead Tagging](../../assets/beta-test.6.2%20-%20leads%20management%202.jpeg)

- **Add and Remove Tags**: Tags can be added to leads to better organize them based on specific attributes, making it easier to manage campaigns and target specific groups.
- **Create New Tags**: You can create new tags as needed to categorize leads in a customized manner. This allows for flexibility in organizing leads based on changing campaign requirements.

The Leads Management feature in MassProspecting helps ensure that you have a structured and organized way of handling your leads, allowing for more effective segmentation and targeted outreach.
