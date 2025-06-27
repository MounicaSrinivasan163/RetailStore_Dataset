# RetailStore_Dataset
🛒 The Story of Retail Performance: A Data Journey


Once upon a time in a nationwide retail chain, hundreds of stores operated across various regions. To understand how well these stores performed, three powerful scrolls of data were compiled. Each scroll held a different piece of the puzzle.
 **************************************
📜 Scroll 1: stores_data_set.csv – The Store Ledger
This scroll tells us who the characters are in this story. Each entry is a store, described by:

Store 🏪 – a unique ID that acts like the store’s name.

Type 🏷️ – a classification such as A, B, or C. Perhaps “Type A” stores are bigger or flagship stores, while “Type C” are smaller ones.

Size 📏 – the size of the store, possibly in square feet. A useful indicator of capacity and scale.

This csv  helps us understand the identity and scale of each store in the kingdom.
************************************************
📜 Scroll 2: sales_data_set.csv – The Book of Sales
This scroll records the daily happenings in each department across all stores:

Store 🏪 – linking it to the first scroll.

Dept 🗂️ – the department inside the store, like electronics, groceries, etc.

Date 📆 – the time when sales occurred.

Weekly_Sales 💵 – the total sales for that department and week.

IsHoliday 🎉 – a flag to tell if the week includes a major holiday (which might influence sales!).

This csv  is crucial to track performance, highlight trends, and detect whether holidays bring boosts or dips.
*******************************************************

📜 Scroll 3: Features_data_set.csv – The Book of Conditions
But what affects the sales? This third scroll holds the external and promotional influences that could sway customer behavior:

Store 🏪 and Date 📆 – to link with the Sales scroll.

Temperature 🌡️ – because people shop differently when it's hot vs. cold.

Fuel_Price ⛽ – transportation cost impacts retail footfall and logistics.

MarkDown1 to MarkDown5 🏷️ – different promotional campaigns and discounts, possibly for different categories.

CPI (Consumer Price Index) and Unemployment 📉 – economic indicators showing customer spending power and job market.

IsHoliday 🎊 – again, to flag if it's a special season.

This csv paints the environmental and economic backdrop to sales, helping us understand why people bought what they did.
******************************************************************

🧠 Together, they tell the full story:
The Store Ledger (first scroll) tells us who and where.

The Sales Book (second scroll) tells us what was sold, when, and by how much.

The Book of Conditions (third scroll) tells us why sales may have risen or fallen.

By merging these three scrolls, the kingdom's analysts can unlock deep insights:

Which store type performs best during holidays?

Do markdowns truly increase sales?

Does store size correlate with sales volume?
