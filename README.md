# SHG-analysis.
**Project Brief: Analyzing Booking Data for Shawn Hotel Groups (SHG)**

Greetings from Shawn Hotel Groups (SHG). As a recently recruited Business Intelligence Analyst and Data Analyst, you will be essential to our efforts to solve the puzzles buried in our booking data. Renowned hospitality company SHG aims to improve visitor experiences and streamline corporate processes by utilizing data-driven insights. Your task is to thoroughly examine one of our best resorts' past booking data in order to identify trends, comprehend consumer behavior, and offer useful suggestions for tactical decision-making.

**Project Overview**:

Your task involves a thorough analysis of a comprehensive dataset, featuring intricate details of bookings, guest demographics, distribution channels, and financial metrics. By applying your analytical prowess, we aim to extract meaningful insights that will not only inform operational improvements but also contribute to the overall success of SHG in delivering unparalleled hospitality.


Data Dictionary:

●	Booking ID: Unique identifier for each booking.

●	Hotel: Type or name of the hotel within the Shawn Hotel Group.

●	Booking Date: Date when the booking was made.

●	Arrival Date: Date when the guests are scheduled to arrive.

●	Lead Time: Number of days between the booking date and arrival date.

●	Nights: Number of nights the guests are booked to stay.

●	Guests: Number of guests included in the booking.

●	Distribution Channel: The channel through which the booking was made (e.g., Direct, Online Travel Agent, Offline Travel Agent).

●	Customer Type: Type of customer making the booking (e.g., Transient, Corporate).

●	Country: Country of origin of the guests.

●	Deposit Type: Whether a deposit was made for the booking (e.g., No Deposit, Deposit).

●	Avg Daily Rate: Average daily rate for the booking.

●	Status: Status of the booking (e.g., Check-Out, Canceled).

●	Status Update: Date of the last status update for the booking.

●	Canceled (0/1): Binary indicator of whether the booking was canceled (1 if canceled, 0 if not canceled).

●	Revenue: Revenue generated from the booking.

●	Revenue Loss: Loss in revenue if the booking was canceled (negative value if the booking wasn't canceled).


### Objectives of the Analysis:

*Booking Patterns:*

●	What is the trend in booking patterns over time, and are there specific seasons or months with increased booking activity?

●	How does lead time vary across different booking channels, and is there a correlation between lead time and customer type?

*Customer Behavior Analysis:*

●	Which distribution channels contribute the most to bookings, and how does the average daily rate (ADR) differ across these channels?

●	Can we identify any patterns in the distribution of guests based on their country of origin, and how does this impact revenue?

*Cancellation Analysis:*

●	What factors are most strongly correlated with cancellations, and can we predict potential cancellations based on certain variables?

●	How does the revenue loss from cancellations compare across different customer segments and distribution channels?

*Revenue Optimization:*

●	What is the overall revenue trend, and are there specific customer segments or countries contributing significantly to revenue?

●	Can we identify optimal pricing strategies based on the Average Daily Rate (ADR) for different customer types and distribution channels?

*Geographical Analysis:*

●	How does the distribution of guests vary across different countries, and are there specific countries that should be targeted for marketing efforts?

●	Is there a correlation between the country of origin and the likelihood of cancellations or extended stays?

*Operational Efficiency:*

●	What is the average length of stay for guests, and how does it differ based on booking channels or customer types?

●	Are there patterns in check-out dates that can inform staffing and resource allocation strategies?


### Conclusion of the Analysis

*Booking Patterns*
- The year 2016 has the highest number of bookings with 49% of the total bookings all four years.
- January and February have the combination of 25% of the total bookings in all months.
- The 17th of the month has the highest number of booking while the five lowest number of booking day are 28, 27, 30, 29, and 31. This indicates that custimers don't make much booking on the last days of the month compare to the early days of the month.
- The first and last quarter of the recorded 59% of the total bookings. Q1 has the highest with 33.5%.
- Offline Travel Agent has the highest number of lead time followed by online travel agent.
- Customer types like Contract and Transient-party have the highest number of lead time.
    

*Customer Behaviour Analysis*
- The channel with the most bookings is Online Travel Agent with 62.22% of the total bookings.
- Online Travel Agent and Direct have the highest number of Avg Daily Rate.
- The top 3 countries with the highest revenue contribute to 54.9% of the total revenue

*Cancellation Analysis*
- Transcient has the highest revenue loss from cancellation across different custom segments
- Online Travel agent has the highest revenue loss from cancellations across different customer segments.
