Personal Mobility Financial Calculator
This is a comprehensive financial calculator designed to help users in Abu Dhabi make an informed decision about their personal transportation. It directly compares the total net financial impact of three distinct models over a chosen period:

Buying a Car

Renting a Car (Long-Term)

A Hybrid Model (Ride-Sharing + Short-Term Rentals)

The app is built as a single, self-contained HTML file that runs entirely in your browser.

How It Works: The Logic Explained
The calculator's core logic is based on a detailed financial framework that models the total cost of each option.

1. Global Inputs
First, the app asks for your Usage Pattern. This is the most critical data, as it drives the variable costs for all three models:

Daily Commute (km & days/week): This determines the base cost for fuel, tolls, parking, and ride-sharing.

Weekend Driving (km/week): Accounts for your regular leisure and errand trips.

Yearly Road Trips (km & days): This is used to calculate short-term rental needs in the Hybrid model.

2. The "Buy" Model (Total Cost of Ownership)
This model calculates the Total Cost of Ownership (TCO), which is the "true" cost of owning a car, not just the sticker price.

Initial Cash Outlay (CAPEX): The immediate money you pay, including the Down Payment, Loan Fees, and Initial Registration.

Financing: Calculates your Monthly EMI and the total Loan Interest you'll pay over the loan term.

Operational Costs (OPEX): These are your recurring expenses:

Fuel: Calculated from your total mileage and the car's efficiency.

Parking: A major factor, combining Daily Office Parking, residential permits, and ad-hoc fees.

Tolls (DARB): Calculated from your daily commute pattern.

Insurance, Maintenance & Repairs: Budgeted on an annual basis.

Depreciation & Resale: This is the "hidden cost." The app projects the car's Resale Value after the analysis period.

Final Net Cost: (Initial Fees + Loan Interest + All OPEX) - (Resale Value)

3. The "Rent" Model
This model calculates the cost of a long-term rental contract.

Initial Cash Outlay: The (refundable) Security Deposit.

Fixed Costs: The Monthly Rental Fee, which includes maintenance and basic insurance.

Variable Costs: You still pay for your own Fuel, Parking, and Tolls.

Overage Risk: The app calculates your average mileage and compares it to the Monthly Mileage Limit. Any excess is calculated as a penalty fee.

Final Net Cost: (Total Rental Fees + Total Variable Costs + Total Overage Fees)

4. The "Hybrid" Model
This model assumes you do not own a car and rely on on-demand services.

Initial Cash Outlay: Zero.

Daily Costs (Ride-Sharing): Calculates your total commute and weekend costs based on the average trip prices you provide.

Key Benefit: This model assumes AED 0 for parking and tolls, as these are included in the ride-sharing fare.

Long-Distance (Short-Term Rental): Uses your "Yearly Road Trip" inputs to calculate the cost of renting a car for those specific days (Daily Rate + Fuel).

Final Net Cost: (Total Commute Rides + Total Weekend Rides + Total Ad-hoc Rides) + (Total Short-Term Rental Costs)

The Final Comparison
The app presents the Initial Cash Outlay, Average Monthly Cost, and Total Net Cost for all three models side-by-side, allowing you to see the immediate, short-term, and long-term financial implications of your choice.

How to Use This Repository
This entire application is contained in the index.html file (originally mobility_calculator.html). To host it yourself, you can simply follow the GitHub Pages guide.
