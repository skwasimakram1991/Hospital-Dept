# The Mater Hospital Dashboard

This repository contains the source code for The Mater Hospital Dashboard, a centralized platform designed to streamline appointment scheduling, form submissions, and overall hospital management.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Appointment Management**: Track and manage hospital appointments effectively.
- **Surgeon Availability**: View the list of available surgeons.
- **Form Submissions**: Efficiently handle and track form submissions.
- **Doctor Directory**: Access a list of doctors along with their departments and contact information.
- **Daily Appointments**: View detailed schedule of appointments for each day.

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/mater-hospital-dashboard.git
   cd mater-hospital-dashboard
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the server**

   ```bash
   npm start
   ```

4. **Open in browser**
   Navigate to `http://127.0.0.1:5500/index.html` in your web browser to view the dashboard.

## Usage

### Dashboard Overview

- **Appointments This Month**: Displays the total number of appointments scheduled for the current month.
- **Surgeons Available**: Shows the count of available surgeons.
- **Forms Filled**: Indicates the number of forms submitted and processed.

### Doctors List

A searchable list of doctors displaying their names, departments, and email addresses. For example:

- **Talan Dias** (Neurology) - georgia.young@example.com
- **Kianna Aminoff** (Neurology) - bill.sanders@example.com

### Daily Appointments

Displays a detailed schedule of appointments for each day, including:

- **Time**
- **Procedure**
- **Doctor Name**
- **Patient Name**

For example:

- **03:44 AM** - Liposculpture by Dr. Annette Black for patient Kyle
- **07:12 AM** - Breast augmentation by Dr. Kristin Watson for patient Arthur

## Contributing

We welcome contributions to improve The Mater Hospital Dashboard. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

Please ensure your code adheres to our coding standards and includes tests for new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

© 2024 The Mater Hospital. All rights reserved.
