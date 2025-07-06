WellTegra Data Solutions
WellTegra Data Solutions is a comprehensive web application designed for real-time monitoring and management of well interventions. It provides a live operational dashboard that simulates a real-time well intervention, offering a dynamic and engaging experience for users. The application is built to enhance decision-making, safety, and efficiency in oilfield operations.
Table of Contents
Features (#features)
Installation (#installation)
Usage (#usage)
Contributing (#contributing)
Code Structure (#code-structure)
License (#license)

Features
Live Performer Dashboard:
A three-column layout displaying:
Operational Procedure: Step-by-step guide with progress tracking.
Key Performance Indicators (KPIs): Real-time metrics like Hookload, Pump Pressure, CT Speed, and Depth.
Dynamic Chart: Compares planned vs. actual performance using Chart.js.
Interactive Elements:
KPIs that update in real-time.
A dynamic chart with zooming and tooltips for detailed analysis.
An operations log for system events and user entries.
Alarm System:
Visual and audible alerts for off-plan events, ensuring safety and operational efficiency.
Simulation Controls:
Manual controls to step forward or backward through the simulation for training or analysis.
Additional Modules:
Planner: For well selection and intervention planning.
Logistics: Manages equipment and personnel.
Commercial: Tracks financials and validates invoices.
HSE & Risk: Monitors health, safety, and environmental risks.
POB & ER: Manages personnel on board and emergency response.
Analyzer: Provides post-job analysis and lessons learned.

Installation
Clone the repository:
bash
git clone https://github.com/yourusername/welltgra-data-solutions.git
Open the index.html file in a web browser.
Note: This is a client-side application and does not require a server. Ensure that external scripts (e.g., Chart.js, Tailwind CSS) are accessible via CDN or locally.

Usage
Navigation:
Use the header navigation links to switch between modules (e.g., Performer, Planner, Logistics).
Performer View:
Procedure Panel: View operational steps and track progress.
KPIs: Monitor real-time metrics with trend indicators.
Chart: Observe planned vs. actual performance; zoom for details.
Operations Log: Add entries to document events or observations.
Simulation Controls: Use "Step Forward" and "Step Back" to manually control the simulation.
Other Modules:
Each module offers specific tools for planning, logistics, financial tracking, safety, personnel management, and post-job analysis.
Screenshots
Performer View
Caption: The Performer view with live KPIs, procedure steps, and dynamic chart.Planner View
Caption: The Planner view for selecting wells and defining intervention plans.
Contributing
We welcome contributions to improve WellTegra Data Solutions. To contribute:
Fork the repository.
Create a new branch for your feature or bugfix.
Make your changes and commit them with descriptive messages.
Push your changes to your fork.
Create a pull request to the main repository.
Please ensure your code follows the project's coding standards and includes appropriate tests.
Code Structure
HTML:
The main structure is defined in index.html, with sections for each view (e.g., Performer, Planner).
CSS:
Styles are managed using Tailwind CSS, with custom styles in the <style> tag for specific components.
JavaScript:
The application logic is contained within the <script> tag at the end of the HTML file.
Data Store: Static data for wells, objectives, problems, etc.
Global State: Manages the application's state, including the current view and selected well.
Functions: Various functions for rendering views, handling events, and updating the UI.
Developers can extend the application by adding new modules, enhancing existing features, or integrating with external APIs.
License
This project is licensed under the MIT License. See the LICENSE file for details.This README.md provides a clear and structured overview of the WellTegra Data Solutions application, making it easy for users to get started and for developers to contribute. It includes essential sections like features, installation, usage, and code structure, ensuring that both technical and non-technical audiences can understand the project's value and functionality.

