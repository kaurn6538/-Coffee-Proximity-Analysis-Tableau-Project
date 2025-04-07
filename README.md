☕ Coffee Proximity Analysis – Tableau Project

📍 Project Overview
The Megabucks Coffee Company is expanding its presence in Manhattan, New York City, and has a new vision:

“No customer should be more than half a mile from their nearest coffee store.”

To support this vision, this project analyzes the current distribution of Megabucks coffee stores and identifies potential geographic gaps between stores. Using Tableau, we visualized existing store locations, analyzed inter-store distances, and highlighted stores that are “too far” from others.

📊 Project Goals
Display all current store locations, including:

Monthly turnover

Number of months in operation

Calculate distances between each store and identify:

Stores that are more than 0.5 miles from the nearest other store

Visually represent store proximity using:

Custom coffee cup shapes

Color indicators to distinguish distant stores

Dynamic sizing of shapes based on minimum distance

📌 Key Features
🗺️ Custom Map Background: Enhanced readability and focus on NYC geography.

☕ Coffee Cup Shape Marks: Custom shape loaded from the Tableau shapes folder and used via the Shape Marks card.

📏 Distance Visualization:

Size of coffee cup represents the minimum distance from other stores (larger = further away).

Color scale:

🟦 Blue: Store is within proximity (not too far)

🟧 Orange: Store is too far from any other branch (> 0.5 miles)

🧭 Interactive filters to view details per store.

🛠️ Tools & Techniques
Tableau (Mapping, Distance Calculations, Custom Shapes)

Spatial Analysis (Using latitude & longitude to calculate inter-store distances)

Custom Assets:

Client's logo integrated into the dashboard

Coffee cup shapes added to Tableau’s Shapes folder and selected via dropdown in Shape Marks card

📸 Final Dashboard Preview

🚀 How to Use
Clone the repository or open the Tableau file.

Ensure the custom coffee cup shape is added to your Tableau My Tableau Repository > Shapes folder.

Open the dashboard and interact with filters and maps to explore store proximity insights.

