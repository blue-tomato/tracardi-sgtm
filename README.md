# Tracardi Server Google Tag Manager Template

This repository contains a custom **Server Google Tag Manager (sGTM)** template for integrating [Tracardi](https://tracardi.com/) into **Server Google Tag Manager**. This is specifically designed for **Server GTM** and is not compatible with the standard Web GTM.

## Features

- Easy integration of Tracardi into Server Google Tag Manager
- Support for custom events
- Flexible configuration options
- GDPR-compliant tracking options

## Installation

1. Open your **Google Tag Manager (Server Container)**.
2. Navigate to **Templates** and select **New**.
3. Click **Import** and upload the file `Tracardi sGTM.tpl`.
4. Configure the template according to your requirements.
5. Save the template and use it in your tags.

## Configuration

- **API Endpoint:** The URL of your Tracardi server
- **Tracradi Source ID:** Define your Source ID
- **Prefix for GA4 user_id:** Use this if you want to prefix your GA4's user_id with a custom string before sending it as "anonids" to Tracardi

## License

This project is licensed under the MIT License. For more details, see the `LICENSE` file.
