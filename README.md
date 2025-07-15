  <img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/f303c4d6-b741-4385-9a1e-308db0a7a133" /># Amazon-case-study-Ayobami-Eyiaro
The following cleaning and preprocessing steps were applied to prepare the data for analysis:

I removed Redundancy and Duplicates:
Duplicate product_id entries were dropped to ensure product uniqueness.

Handled Missing Values
Rows with missing actual_price, discounted_price, or Product Category were removed or corrected.

Standardized Column Formats:
I ensured all monetary columns (discounted_price, actual_price) were treated as numeric types.
I reformatted inconsistent category naming (e.g., spacing and symbols).

Calculated Discount Percentage:
I created a new discount_percentage column using the formula:

Discount %
=
Actual Price
−
Discounted Price
Actual Price
×
100
Discount %= Actual Price−Discounted Price×100

📊 Average Discount Percentage by Product Category
	Product Category	Average Discount (%)
	Home Improvement	57.5%
	Computers & Accessories	53.1%
	Health & PersonalCare	53.0%
	Electronics	49.9%
 	Musical Instruments	46.0%
	Car & Motorbike	42.0%
 	Home & Kitchen	40.2%
	Office Products	12.4%
	Toys & Games	0.0%


Home Improvement products had the highest average discount rate at 57.5%.

Toys & Games had no recorded discounts, indicating possible exclusion from promotional strategies.

Categories like Computers & Accessories and Electronics are highly discounted, likely due to competitive tech markets.

C:\Users\hp user\Desktop\DATA ANALYSIS\Amazon case study Ayobami  Eyiaro.xlsx!

[Uploading Screenshot (6).png…]()<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/ee693571-ee0d-40e1-8a84-5c30bf4dec09" />

<img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/ebbc6ff1-0cd1-4d74-b5f9-a8a2b16a0f78" />
<img width="1920" height="1080" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/4289897d-6fce-4285-bcfa-087d80aaaf5c" />
