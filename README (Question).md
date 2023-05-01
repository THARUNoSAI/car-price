ABC car showroom sells various types of cars such as Hatchback, Sedan,
SUVs, and MUV. Due to the year-end sale, the showroom provides a 3%, 5%,
10%, and 15% discount for various car models Hatchback, Sedan, SUV, and
MUV respectively. Also applies 12% of GST for the total amount of purchase
Write a C program to implement the above scenario which will read the
type_of_the_car, price_of_the_car and extra-fitting_price_of_the_car as input
from the user and estimate the Net amount to be paid to the showroom. If the
type of car is other than Hatchback, Sedan, SUV, and MUV then display
“Invalid Type”. (Difficulty Level: Easy)
The net amount to be paid to the showroom is estimated as follows:
(For example-if the purchased car is Hatchback)
Total = price_of_the_car + extra-fitting_price_of_the_car
Discount = Total * 0.03 // 0.03 denotes 3%
wastage
gst = (Total - Discount) * 0.12 // 0.12 denotes
12% GST
net = Total – Discount + gst
