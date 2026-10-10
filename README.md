# if-else-project
#include <stdio.h>

int main() {
    int age;

    // User se age input lena
    printf("Apni umr (age) daaliye: ");
    scanf("%d", &age);

    // Condition check karna
    if (age >= 18) {
        printf("Aap vote de sakte hain! (Eligible to vote)\n");
    } 
    else {
        printf("Aap vote nahi de sakte. Abhi aap 18 saal ke nahi hue hain.\n");
    }

    return 0;
}
