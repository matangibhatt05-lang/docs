efiletax: Income Tax Filing Service Portal
efiletax is a comprehensive web platform designed to simplify the Income Tax Return (ITR) filing process in India. The platform provides CA/CS-assisted services for everyone from salaried individuals to complex business portfolios.

📂 Project Structure
This repository contains the web assets and mirrored structure of the efiletax portal. Based on the local setup (XAMPP/htdocs) shown in the screenshots, the project is organized as follows:

Core Pages:

index.html: The main project index created via HTTrack.

income-tax-filing.html: The primary service landing page featuring the tax enquiry form and compliance details.

Static Assets:

images/: Contains the efiletax logo, favicons, and service banners (e.g., banner_adds.png, google-reviews.png).

css/ & plugins/: Includes Bootstrap 5, Slick slider, and custom stylesheets for layout and responsiveness.


✨ Key Features
Diverse Income Support: Specialized filing workflows for Salary, House Property, Business/Profession, Capital Gains, and Cryptocurrency.

Advanced Trading Compliance: Support for Futures & Options (F&O) and Securities Trading.

Interactive Lead Generation: A dynamic enquiry form that validates user input to ensure at least one income source is selected before submission.

Tax Compliance Guide: Detailed information on ITR forms, tax slabs, and the consequences of late filing.


🛠️ Technical Stack

Component		Technology Used
Frontend		"HTML5, CSS3 (Bootstrap 5 & Custom)"
Scripting		"JavaScript, jQuery (for AJAX form handling)"
Fonts & Icons		"Nunito Sans, Roboto, FontAwesome 6.4.2"
Analytics		"Google Tag Manager (GTM), Clarity"
Archiving		HTTrack Website Copier


📅 Important Tax Deadlines (AY 2024-25)
The platform tracks critical deadlines for the current assessment year:

Standard Filing Deadline: 31-07-2024

Tax Audit / Company Return: 30-09-2024

Belated Return Deadline: 31-12-2024

Revised Return: 31-03-2025

ITR-U (Updated Return): Within 24 months from the end of the relevant assessment year

🚀 Local Setup Instructions
Clone this repository to your local machine.

Move the files into your local server directory (e.g., C:/xampp/htdocs/efiletax/).

Open your browser and navigate to http://localhost/efiletax/income-tax-filing.html.

The enquiry form is configured to send data to the efiletax backend API via AJAX.

⚠️ Compliance & Penalties
As per Section 234F, late filing attracts a penalty of up to ₹10,000. However, if the total income is below ₹5,00,000, the penalty is limited to ₹1,000. Late filing also results in a 1% monthly interest charge on unpaid taxes and the inability to carry forward losses.