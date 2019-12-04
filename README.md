
# Amortization With Sinking Fund

This project was created to determine three questions for a mortgage with annual lump sum payments. The EXCEL File contains the questions and an amortization table relating to the mortgage. The orange table takes the inputs of the problem

## The terms of the mortgage

The mortgage will be repaid using equal monthly payments calculated using the initial monthly mortgage rate. There is also a sinking fund to which the holder makes monthly deposits. The sinking fund will make annual lump sum payments, to a maximum percentage of the nominal monthly mortgage payments. The payments to the sinking fund also increase with inflation once a year.

## Methods Used to Answer Each Question

### Question 1 When will the mortgage be paid off?

To answer this question, we created an amortization table with monthly payments on the loan as well as lump sum payments from the sinking fund. The lump sum payments were as large as possible, either being the entire accumulated value of the monthly deposits, or the maximum. The interest payments were calculated using the mortgage payments at time, either the expected renewal rate or the original mortgage rate. This made the principle repaid equal to the total payment at time t minus the interest.

The mortage will be paid off with a drop payment at the time that the outstading balance on the morgage equal to 0 or a balloon payment at t+1.

### Question 2 What minimum initial monthly deposit into the sinking fund is required in order to fully repay the mortgage by a given target date (for example, after 20 years)?

The deposit is found by dividing the outstanding balance without lumpsum payments at the target date by the sinking fund accumulation factor to the target date. The minimum deposit must then be checked, as the maximum annual lump sum deposit may make repaying the mortgage by the target date impossible

### Question 3 What is the highest renewal mortgage rate for which the homebuyer would still be able to fully repay the  loan by the end of the amortization period by making the same monthly payments and using the side fund to make annual lump sum prepayments?

The method used to calculate this is equating the outstanding balance at the end of the mortgage term to the remaining payments on the loan and using the IRR() function to find the maximum mortgage renewal rate.

## Authors
*Carrie Luk*
*Timothy Zintel*

## Case Created by 

*Gary Parker* for ACMA-210 in Fall 2019

