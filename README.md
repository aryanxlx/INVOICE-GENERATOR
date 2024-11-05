Smart Invoice Generator
The Smart Invoice Generator is an innovative Java-based invoicing application designed to streamline invoicing while providing advanced features for dynamic pricing, real-time analytics, and multi-currency support. With capabilities such as AI-driven due date predictions, QR code payments, and personalized customer engagement, this tool is ideal for businesses seeking an intelligent solution to manage their invoicing needs.

Features
Dynamic Customer Pricing: Tailors discounts and pricing based on customer segmentation (loyalty, volume).
Real-Time Currency Conversion: Fetches live exchange rates for invoicing in multiple currencies.
QR Code Integration: Generates QR codes for quick and secure payments on each invoice.
AI-Powered Due Date Prediction: Predicts possible payment delays based on past data, helping optimize cash flow.
Customizable UI: Java Swing-based interface with dynamic themes to match business branding.
Analytics Dashboard: Provides insights on top customers, popular products, and overall sales trends.
PDF Invoice Export: Generates professional, customizable PDF invoices using JasperReports.
Technology Stack
Java: Core language for building the application.
Java Swing: Used for building the GUI.
MySQL: Stores customer, product, and invoice data.
REST API (Exchange Rate API): Fetches real-time currency exchange rates.
ZXing Library: Generates QR codes for payment links.
Weka Library: Powers basic machine learning for due date predictions.
JasperReports: Used to create and export PDF invoices.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/smart-invoice-generator.git
cd smart-invoice-generator
Set up the database:

Create a MySQL database named invoice_db and import the provided SQL schema.
Update the database credentials in DatabaseManager.java.
Install dependencies:

Download and add ZXing, Weka, and JasperReports libraries to your project.
Run the application:

Compile and run the main class InvoiceGenerator.java.
Usage
Generate Invoices: Input customer details and product data, and select payment and currency options.
View Analytics: Use the analytics dashboard for insights into customer behavior and sales.
Export Invoices: Save or print invoices as PDFs with QR codes for easy payment access.
Future Enhancements
Enhanced customer segmentation.
Additional payment gateways.
Expanded machine learning models for improved predictions.
