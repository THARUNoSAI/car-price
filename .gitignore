#include <stdio.h>

int main() {
    char carType[10];
    float price, fittingPrice, total, discount, gst, net;

    printf("Enter the type of car (Hatchback/Sedan/SUV/MUV): ");
    scanf("%s", carType);

    printf("Enter the price of the car: ");
    scanf("%f", &price);

    printf("Enter the extra-fitting price of the car: ");
    scanf("%f", &fittingPrice);

    total = price + fittingPrice;

    if (strcmp(carType, "Hatchback") == 0) {
        discount = total * 0.03;
    } else if (strcmp(carType, "Sedan") == 0) {
        discount = total * 0.05;
    } else if (strcmp(carType, "SUV") == 0) {
        discount = total * 0.1;
    } else if (strcmp(carType, "MUV") == 0) {
        discount = total * 0.15;
    } else {
        printf("Invalid Type\n");
        return 0;
    }

    gst = (total - discount) * 0.12;
    net = total - discount + gst;

    printf("Net amount to be paid to the showroom: %.2f\n", net);

    return 0;
}
