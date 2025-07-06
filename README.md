# Amazon Product Review Analysis

## Overview
Exploratory analysis of Amazon product review data to uncover patterns in pricing, discounts, ratings, and customer engagement.

## Dataset
- 1,465 products
- 16 columns: product name, category, actual & discounted prices, discount %, ratings, number of reviews, etc.

## Tools Used
- Microsoft Excel: pivot tables, charts, dashboard

## Key Questions & Answers

### Q1: Average discount % by category
Category	                Average Discount
Car&Motorbike	             42.00%
Computers&Accessories	     54.02%
Electronics	               50.83%
Health&PersonalCare	       53.00%
Home&Kitchen	             40.12%

### Q2: Number of products per category
Category	            Number of Products
Car&Motorbike	            1
Computers&Accessories	    453
Electronics	              526
Health&PersonalCare	       1
Home&Kitchen	            448

### Q3: Total number of reviews per category
Product Category				Total Reviews
Car & Motorbike				       1
Computers & Accessories			7,968
Electronics					        8,889
Home & Kitchen			      	7,053
Others					          	327


### Q4: Products with the highest average ratings
Product Name								                                  Rating
Amazon Brand - Solimo 65W Fast Charging Braided Type C Cable	5
7SEVEN Compatible for Tata Sky Remote				                	5
NGI Store 2 Pieces Pet Hair Removers					                5


### Q5: Average actual price vs discounted price by category
Category		          	Average Actual Price  	Average Discounted Price
Car & Motorbike			          499			            289
Computers & Accessories		    699			            321
Electronics				            599		            	293
Home & Kitchen			          749		            	392
Others					              599		            	299


### Q6: Products with the highest number of reviews
Product Name							                                    Number of Reviews
Amazon Brand - Solimo 65W Fast Charging Braided Type C Cable	94,363
7SEVEN Compatible for Tata Sky Remote				                	93,477
NGI Store 2 Pieces Pet Hair Removers			                		90,213


### Q7: Number of products with ≥50% discount
Count:										537
### Q8: Distribution of product ratings
Rating				Number of Products
3.0			    	124
3.5				    210
4.0			    	536
4.5			    	432
5.0			    	163


### Q9: Total potential revenue (actual_price × rating_count) by category
Category			    		    Potential Revenue
Car & Motorbike				    499
Computers & Accessories		3,564,000
Electronics				      	4,293,000
Home & Kitchen			    	3,123,000
Others						        276,000


### Q10: Number of unique products per price range bucket
< ₹200					125
₹200–₹500				873
> ₹500					467


### Q11: How does the rating relate to the level of discount?


### Q12: Number of products with <1,000 reviews
Count:								1,085

### Q13: Categories with the highest discounts
Category				          Average Discount
Computers & Accessories		54%
Electronics			        	51%


### Q14: Top 5 products by combined rating & reviews
Product Name							                                    Combined Score
Amazon Brand - Solimo 65W Fast Charging Braided Type C Cable	473,000
7SEVEN Compatible for Tata Sky Remote				                	467,385
NGI Store 2 Pieces Pet Hair Removers				                	451,065
Portronics Konnect L Cable							                      390,213
Sounce Fast Charging Cable						                      	379,895




## Insights & Recommendations
- High discounts are observed in Computers & Accessories (~54%) and Electronics (~51%). These categories can leverage discounts for promotions.
- Products with discounts ≥50% tend to have slightly lower ratings; quality checks may help improve ratings.
- Most reviews come from Electronics and Home & Kitchen categories — focus engagement efforts there.
- Products above ₹500 contribute significantly to revenue despite fewer units — premium products seem to perform well.
- Recommend improving visibility for highly rated products with fewer reviews to boost sales.


## Author
EMMANUEL OBITE
