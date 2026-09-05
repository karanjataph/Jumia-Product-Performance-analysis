# Jumia-Product-Performance-analysis project

## 1. Project Overview

This project analyzes a jumia dataset to identify trends, relationships, and key business insights. The analysis was conducted using Microsoft Excel, with the goal of understanding product performance, sales patterns, and factors that may influence revenue.

The project focuses on:
- Identifying the most and least expensive products
- Analyzing sales trends
- Examining relationships between variables
- Identifying high-performing and underperforming products based on measures such as discount before and after
- Providing business recommendations based on the findings

## 2. Objectives

The main objectives of this project are to:

1. Understand the structure and characteristics of the jumia dataset.
2. Identify the most expensive and least expensive products.
3. Analyze sales trends.
4. Identify relationships between the different important variables.
5. Determine which products perform best.
6. Generate business recommendations.

## 3. Dataset

The dataset contains information about products and their sales performance.

### Key variables

Product	Current price	old price	Discount	Review	Ratings	Rating category	Discount amount	Price category	Discount category
115  Piece Set Of Multifunctional Precision Screwdrivers	950	1,525	38%	2	4.5	Average	575		Medium Discount
Metal Decorative Hooks Key Hangers Entryway Wall Hooks Towel Hooks - Home	527	999	47%	14	4.1	Average	472		High Discount
Portable Mini Cordless Car Vacuum Cleaner - Blue	2,199	2,923	25%	24	4.6	Excellent	724		Medium Discount
Weighing Scale Digital Bathroom Body Fat Scale USB-Black	1,580	2,499	37%	7	4.7	Excellent	919		Medium Discount
Portable Home Small Air Humidifier 3-Speed Fan - Green	1,740	2,356	26%	5	4.8	Excellent	616		Medium Discount
220V 60W Electric Soldering Iron Kits With Tools, Tips, And Multimeter	2,999	3,290	9%	15	4	Average	291		Low Discount
137 Pieces Cake Decorating Tool Set Baking Supplies	2,319	3,032	24%	55	4.6	Excellent	713		Medium Discount
Desk Foldable Fan Adjustable Fan Strong Wind 3 Gear Usb	988	1,580	37%	2	4	Average	592		Medium Discount
LASA FOLDING TABLE SERVING STAND	1,274	2,800	55%	5	4.8	Excellent	1,526		High Discount
13 In 1 Home Repair Tools Box Kit Set	1,600	2,929	45%	5	3.8	Average	1,329		High Discount
Genebre 115 In 1 Screwdriver Repairing Tool Set For IPhone Cellphone Hand Tool	799	999	20%	12	4.1	Average	200		Medium Discount
100 Pcs Crochet Hook Tool Set Knitting Hook Set With Box	990	1,500	34%	39	4.7	Excellent	510		Medium Discount
40cm Gold DIY Acrylic Wall Sticker Clock	552	1,035	47%	12	4.8	Excellent	483		High Discount
LASA Digital Thermometer And Hydrometer	501	860	42%	6	4.5	Average	359		High Discount
Multifunction Laser Level With Adjustment Tripod	1,680	2,499	33%	9	4.2	Average	819		Medium Discount
Anti-Skid Absorbent Insulation Coaster  For Home Office	332	684	51%	2	5	Excellent	352		High Discount
Peacock  Throw Pillow Cushion Case For Home Car	195	360	46%	2	5	Excellent	165		High Discount
LASA Aluminum Folding Truck Hand Cart - 68kg Max	2,025	3,971	49%	3	5	Excellent	1,946		High Discount
LED Wall Digital Alarm Clock Study Home 12 / 24H Clock Calendar	2,999	3,699	19%	5	4.6	Excellent	700		Low Discount
3D Waterproof EVA Plastic Shower Curtain 1.8*2Mtrs	998	1,966	49%	44	4.6	Excellent	968		High Discount
3PCS Single Head Knitting Crochet Sweater Needle Set	38	80	53%	13	3.3	Average	42		High Discount
4pcs Bathroom/Kitchen Towel Rack,Roll Paper Holder,Towel Bars,Hook	1,860	3,220	42%	null	null	Excellent	1,360		High Discount
LED Romantic Spaceship Starry Sky Projector,Children's Bedroom Night Light-Blue	880	1,350	35%	6	4	Average	470		Medium Discount
Foldable Overbed Table/Desk	1,650	2,150	23%	14	4.4	Average	500		Medium Discount
LASA 3 Tier Bamboo Shoe Bench Storage Shelf	2,048	4,500	54%	7	4.3	Average	2,452		High Discount
Electronic Digital Display Vernier Caliper	420	647	35%	49	4.6	Excellent	227		Medium Discount
Portable Wardrobe Nonwoven With 3 Hanging Rods And 6 Storage Shelves	2,880	3,520	18%	12	3.8	Average	640		Low Discount
12 Litre Black Insulated Lunch Box	1,350	1,990	32%	13	3.8	Average	640		Medium Discount
52 Pieces Cake Decorating Tool Set Gift Kit Baking Supplies	1,758	2,499	30%	20	4.1	Average	741		Medium Discount
MultiFunctional Storage Rack Multi-layer Bookshelf	2,200	4,080	46%	null	null	Excellent	1,880		High Discount
Exfoliate And Exfoliate Face Towel - Black	185	382	52%	9	4.3	Average	197		High Discount
12 Litre Insulated Lunch Box Grey	980	1,490	34%	12	4.7	Excellent	510		Medium Discount
LED Eye Protection  Desk Lamp , Study, Reading, USB Fan - Double Pen Holder	1,820	3,490	48%	9	4.3	Average	1,670		High Discount
53Pcs/Set Yarn Knitting Crochet Hooks With Bag - Fortune Cat	1,940	2,650	27%	20	4.7	Excellent	710		Medium Discount
53 Pieces/Set Yarn Knitting Crochet Hooks With Bag - Pansies	1,980	2,699	27%	32	4.5	Average	719		Medium Discount
DIY File Folder, Office Drawer File Holder, Pen Holder, Desktop Storage Rack	1,620	2,690	40%	1	5	Excellent	1,070		Medium Discount
Classic Black Cat Cotton Hemp Pillow Case For Home Car	171	360	53%	2	5	Excellent	189		High Discount
Punch-free Great Load Bearing Bathroom Storage Rack Wall Shelf-White	389	656	41%	36	4.3	Average	267		High Discount
1/2/3 Seater Elastic Sofa Cover,Living Room/Home Decor Chair Cover-Grey	1,980	3,200	38%	2	4.5	Average	1,220		Medium Discount
LASA Stainless Steel Double Wall Mount Soap Dispenser - 500ml	2,750	4,471	38%	null	null	Excellent	1,721		Medium Discount
4M Float Switch Water Level Controller -Water Tank	475	931	49%	null	null	Excellent	456		High Discount
Modern Sofa Throw Pillow Cover-45x45cm-Blue&Red	238	476	50%	null	null	Excellent	238		High Discount
Balloon Insert, Birthday Party Balloon Set, PU Leather	610	1,060	42%	null	null	Excellent	450		High Discount
Shower Cap Wide Elastic Band Cover Reusable Bashroom Cap	2,132	2,169	2%	null	null	Excellent	37		Low Discount
Christmas Elk Fence Yard Lawn Decorations Cute For Holidays	999	2,000	50%	null	null	Excellent	1,001		High Discount
60W Hot Melt Glue Sprayer - Efficient And Stable Glue Dispensing	1,190	1,785	33%	null	null	Excellent	595		Medium Discount
Car Phone Charging Stand	671	1,316	49%	null	null	Excellent	645		High Discount
2pcs Solar Street Light Flood Light Outdoor	1,200	1,950	38%	null	null	Excellent	750		Medium Discount
Creative Owl Shape Keychain Black	199	504	61%	null	null	Excellent	305		High Discount
Brush & Paintbrush Cleaning Tool Pink	299	600	50%	null	null	Excellent	301		High Discount
Pen Grips For Kids Pen Grip Posture Correction Tool For Kids	1,660	1,699	2%	null	null	Excellent	39		Low Discount
Pilates Cloth Bag Waterproof Durable High Capacity Purple	299	384	22%	null	null	Excellent	85		Medium Discount
Multi-purpose Rice Drainage Basket And Fruit And Vegetable Drainage Sieve	1,459	1,499	3%	null	null	Excellent	40		Low Discount
Cute Christmas Fence Garden Decorations For Holiday Home	799	1,343	41%	null	null	Excellent	544		High Discount
Simple Metal Dog Art Sculpture Decoration For Home Office	499	900	45%	null	null	Excellent	401		High Discount
Christmas Fence Garden Decorations Outdoor For Holiday Home	699	1,343	48%	null	null	Excellent	644		High Discount
Angle Measuring Tool Full Metal Multi Angle Measuring Tool	799	1,567	49%	null	null	Excellent	768		High Discount
12V 19500rpm Handheld Electric Angle Grinder Tool - UK - Yellow/Black	2,799	3,810	27%	null	null	Excellent	1,011		Medium Discount
Simple Metal Dog Art Sculpture Decoration For Home Office	399	896	55%	null	null	Excellent	497		High Discount
5 Pieces/set Of Stainless Steel Induction Cooker Pots	2,170	2,500	13%	6	2.5	Poor	330		Low Discount
Mythco 120COB Solar Wall Ligt With Motion Sensor And Remote Control 3 Modes	458	986	54%	10	3	Average	528		High Discount
5-PCS Stainless Steel Cooking Pot Set With Steamed Slices	2,115	4,700	55%	13	2.1	Poor	2,585		High Discount
120W Cordless Vacuum Cleaners Handheld Electric Vacuum Cleaner	445	873	49%	69	2.8	Poor	428		High Discount
Intelligent  LED Body Sensor Wireless Lighting Night Light USB	325	680	52%	15	2.7	Poor	355		High Discount
VIC Wireless Vacuum Cleaner Dual Use For Home And Car 120W High Power Powerful	1,220	1,555	22%	16	2.9	Poor	335		Medium Discount
Artificial Potted Flowers Room Decorative Flowers (2 Pieces)	990	1,814	45%	6	2.2	Poor	824		High Discount
380ML USB Rechargeable Portable Small Blenders And Juicers	1,000	2,000	50%	7	2.3	Poor	1,000		High Discount
32PCS Portable Cordless Drill Set With Cyclic Battery Drive -26 Variable Speed	3,750	6,143	39%	5	3	Average	2,393		Medium Discount
Agapeon Toothbrush Holder And Toothpaste Dispenser	382	700	45%	17	2.6	Poor	318		High Discount
Large Lazy Inflatable Sofa Chairs PVC Lounger Seat Bag	2,300	3,240	29%	5	3	Average	940		Medium Discount
Watercolour Gold Foil Textured Print Pillow Cover	345	602	43%	6	2.3	Poor	257		High Discount
Wrought Iron Bathroom Shelf Wall Mounted Free Punch Toilet Rack	509	899	43%	5	3	Average	390		High Discount
7-piece Set Of Storage Bags, Travel Storage Bags, Shoe Bags	968	1,814	47%	6	2.2	Poor	846		High Discount
Electric LED UV Mosquito Killer Lamp, Outdoor/Indoor Fly Killer Trap Light -USB	1,570	2,988	47%	7	2.1	Poor	1,418		High Discount
2PCS/LOT Solar LED Outdoor Intelligent Light Controlled Wall Lamp	790	1,485	47%	null	null	Excellent	695		High Discount
3PCS Rotary Scraper Thermomix For Kitchen	690	1,200	43%	null	null	Excellent	510		High Discount
Cushion Silicone Butt Cushion Summer Ice Cushion Honeycomb Gel Cushion	1,732	1,799	4%	null	null	Excellent	67		Low Discount
7PCS Silicone Thumb Knife Finger Protector Vegetable Harvesting Knife	230	450	49%	null	null	Excellent	220		High Discount
Memory Foam Neck Pillow Cover, With Pillow Core - 50*30cm	1,189	2,199	46%	1	3	Average	1,010		High Discount
Bedroom Simple Floor Hanging Clothes Rack Single Pole Hat Rack - White	979	1,920	49%	1	5	Excellent	941		High Discount
5m Waterproof Spherical LED String Lights Outdoor Ball Chain Lights Party Lighting Decoration Adjustable	1,460	2,290	36%	null	null	Excellent	830		Medium Discount
2 Pairs Cowhide Split Leather Work Gloves.32â„‰ Or Above Welding Gloves	1,666	1,699	2%	null	null	Excellent	33		Low Discount
Household Pineapple Peeler Peeler	330	647	49%	1	4	Average	317		High Discount
Creative Owl Shape Keychain Black	176	345	49%	null	null	Excellent	169		High Discount
Office Chair Lumbar Back Support Spine Posture Correction Pillow Car Cushion	1,466	1,699	14%	null	null	Excellent	233		Low Discount
Cartoon Car Decoration Cute Individuality For Car Home Desk	274	537	49%	null	null	Excellent	263		High Discount
Outdoor Portable Water Bottle With Medicine Box - 600ML - Black	799	900	11%	null	null	Excellent	101		Low Discount
Angle Measuring Tool Full Metal Multi Angle Measuring Tool	657	1,288	49%	null	null	Excellent	631		High Discount
Wall-Mounted Toothbrush Toothpaste Holder With Multiple Slots	1,468	1,699	14%	null	null	Excellent	231		Low Discount
Multifunctional Hanging Storage Box Storage Bag (4 Layers)	630	1,100	43%	null	null	Excellent	470		High Discount
Wall Clock With Hidden Safe Box	850	1,700	50%	null	null	Excellent	850		High Discount
Portable Wine Table With Folding Round Table	1,300	2,500	48%	null	null	Excellent	1,200		High Discount
Sewing Machine Needle Threader Stitch Insertion Tool Automatic Quick Sewing	105	200	48%	null	null	Excellent	95		High Discount
6 Layers Steel Pipe Assembling Dustproof Storage Shoe Cabinet	899	1,699	47%	null	null	Excellent	800		High Discount
2PCS Ice Silk Square Cushion Cover Pillowcases - 65x65cm	1,200	2,400	50%	null	null	Excellent	1,200		High Discount
Wall Mount Automatic Toothpaste Dispenser Toothbrush Holder Toothpaste Squeezer	1,526	1,660	8%	null	null	Excellent	134		Low Discount
Portable Soap Dispenser Kitchen Detergent Press Box Kitchen Tools	1,462	1,499	2%	null	null	Excellent	37		Low Discount
4 Piece Coloured Stainless Steel Kitchenware Set	248	486	49%	null	null	Excellent	238		High Discount
Metal Wall Clock Silver Dial Crystal Jewelry Round Home Decoration Wall Clock	3,546	3,699	4%	null	null	Excellent	153		Low Discount
Baby Early Education Shape And Color Cognitive Training Toys	525	1,029	49%	null	null	Excellent	504		High Discount
8in1 Screwdriver With LED Light	1,080	1,874	42%	null	null	Excellent	794		High Discount
Konka Healty Electric Kettle, 24-hour Heat Preservation,1.5L,800W, White	3,640	4,588	21%	1	5	Excellent	948		Medium Discount
9pcs Gas Mask, For Painting, Dust, Formaldehyde Grinding, Polishing	1,420	2,420	41%	null	null	Excellent	1,000		High Discount
24 Grid Wall-mounted Sundries Organiser Fabric Closet Bag Storage Rack	1,875	1,899	1%	null	null	Excellent	24		Low Discount
1PC Refrigerator Food Seal Pocket Fridge Bags	198	260	24%	null	null	Excellent	62		Medium Discount
LED Solar Street Light-fake Camera	1,150	1,737	34%	null	null	Excellent	587		Medium Discount
Cartoon Embroidered Mini Towel Bear Cotton Wash Cloth Hand 4pcs	1,190	1,810	34%	null	null	Excellent	620		Medium Discount
Shower Nozzle Cleaning Unclogging Needle Mini Crevice Small Hole Cleaning Brush	1,658	1,699	2%	null	null	Excellent	41		Low Discount
Thickening Multipurpose Non Stick Easy To Clean Heat Resistant Spoon Pad	1,768	1,799	2%	null	null	Excellent	31		Low Discount
6 In 1 Bottle Can Opener Multifunctional Easy Opener	199	553	64%	null	null	Excellent	354		High Discount
Wall-mounted Sticker Punch-free Plug Fixer	450	900	50%	1	2	Poor	450		High Discount
Black Simple Water Cup Wine Coaster Anti Slip Absorbent	169	320	47%	null	null	Excellent	151		High Discount
									Low Discount
=COUNTA(A2:A113)	1,189	1,816	37%	723	3.889473684				Medium Discount
									Low Discount
	3,750								Low Discount
	38								
<img width="2143" height="3423" alt="image" src="https://github.com/user-attachments/assets/46861cf6-a269-474b-9d74-ec057ecf578b" />

### 4. Data Preparation

Before performing the analysis, the dataset was cleaned and prepared in Excel.

The following steps were performed:

- Check for missing values in the dataset (for example missing reviews, ratings, or prices). 
- Remove duplicate records if any exist. 
- Ensure all price columns are stored in numeric format by removing currency symbols and unnecessary characters like negatives. 
- Standardize the rating column into a numeric format. 
- Ensure review numbers are stored correctly as numerical values.
- Check for inconsistencies in the dataset and correct them where necessary. 

## 5. Analysis Process

### 5.1 Descriptive Analysis

Basic statistical measures were calculated to understand the dataset.

These included:

- Average current price of products.
- Average old price of products.
- Average discount percentage.
- Average product rating.
- Total number of products.
- Total number of reviews.
- Most expensive and least expensive products.

Excel functions such as `SUM`, `AVERAGE`, `MIN`, `MAX`, and `COUNT` were used.

### 5.2 Most and Least Expensive Products

The product prices were analyzed to identify the most expensive and least expensive products.

Excel functions such as:

`=MAX(B2:B113)`

and

`=MIN(B2:B113)`

were used to identify the highest and lowest prices.

The corresponding products were then identified using functions such as `XLOOKUP`.

### 5.3 Trend Analysis

Sales were analyzed to identify patterns and trends between the different variables.

- Does a higher discount percentage result in more customer reviews? 
- Do highly rated products receive more customer reviews? 
- Are expensive products rated higher than cheaper products? 
- Identify the top 5 products with the highest ratings. 
- Identify the top 5 products with the lowest ratings. 

A PivotTable was used to summarize the sales.

A chart was then created to visualize changes in sales and the different variables.

The trend analysis helped identify:

- Top 10 products with the highest discounts 
- Top 10 products with the highest number of reviews
- Top 10 highest-rated products
- Products with high discounts but low ratings
- Products with strong customer engagement

### 5.4 Relationship Analysis

Relationships between variables were examined to understand factors that may influence sales.

Examples include:

- Does a higher discount percentage result in more customer reviews? 
- Do highly rated products receive more customer reviews? 
- Are expensive products rated higher than cheaper products? 
- Identify the top 5 products with the highest ratings. 
- Identify the top 5 products with the lowest ratings.

Excel charts were used to visualize relationships between the different numerical variables.

## 6. Key Findings

The analysis produced the following key findings:

### Finding 1: Product Pricing

The analysis identified the most expensive and least expensive products in the dataset.

**Most expensive product:** [32PCS Portable Cordless Drill Set With Cyclic Battery Drive -26 Variable Speed
<img width="949" height="30" alt="image" src="https://github.com/user-attachments/assets/6fb5f0c1-1cdd-46c0-afdd-6bb0d8bf6db9" />
]

**Price:** [3,750
<img width="152" height="30" alt="image" src="https://github.com/user-attachments/assets/7ce11ecd-526b-4221-9f28-e331f161006f" />
]

**Least expensive product:** [3PCS Single Head Knitting Crochet Sweater Needle Set
<img width="949" height="30" alt="image" src="https://github.com/user-attachments/assets/0a0019d8-c3d7-4036-bc47-7afdbabfb836" />
]

**Price:** [38
<img width="152" height="30" alt="image" src="https://github.com/user-attachments/assets/0a95e5c2-ab1f-4102-808f-3eed5cdf7a80" />
]

## 7. Business Insights

The findings provide several useful business insights.

### 1. Focus on high-performing products

Products generating the highest revenue should receive greater attention because they make an important contribution to overall business performance.

### 2. Review underperforming products

Products with consistently low sales should be reviewed to determine whether pricing, customer demand, marketing, or product positioning is affecting their performance.

### 3. Use sales trends for planning

Identifying high and low demand can help the business plan inventory, staffing, and marketing activities more effectively.

### 4. Consider pricing strategy

The relationship between the different variables can provide useful information for pricing decisions. Products with high prices but low sales may require further investigation.

## 8. Recommendations

Based on the analysis, the following recommendations are proposed:

1. **Prioritize high-performing products** by ensuring adequate stock and marketing support.

2. **Investigate low-performing products** to determine whether they should be discounted more, repositioned, improved, or discontinued.

3. **Review pricing strategies** based on the relationship between product prices and sales volumes.

4. **Monitor sales performance regularly** using Excel dashboards, PivotTables, and charts.

5. **Continue collecting customer and sales data** so that future analysis can provide deeper insights into customer behavior.

## 9. Tools Used

- Microsoft Excel
- Excel PivotTables
- Excel Charts
- Excel formulas
- Descriptive statistics
- Relationship analysis

## 10. Conclusion

This project demonstrates how Excel can be used to transform raw sales data into useful business insights.

The analysis identified product pricing differences, sales trends, product performance, and relationships between key variables. These findings can support better decisions around pricing, marketing, and product strategy.

Overall, the analysis provides a data-driven foundation for improving sales performance and making informed business decisions.

## 11. Project Structure

```text
Jumia-Product-Perfomance-analysis/
│
├── README.md
├── data/
│   └── Excel_jumia_dataset(1).xlsx
│
├── analysis/
│   └── sales_analysis.xlsx
│
└── images/
    └── sales_trend.png
````

## 12. Author

**[Kelvin karanja]**

