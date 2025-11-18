# doctor
directory
    #include <stdio.h>
struct doctors {
    char location[20];
    char name[20];
    char specialist[20];
    long long contact_number;
    
};
int main() {
    struct doctors doc[3];
    int i;
    for(i=1; i<4; i++){
    printf("enter location:");
    scanf("%s",&doc[i].location);
    printf("enter name of doctor:");
    scanf("%s",&doc[i].name);
    printf("enter specialist:");
    scanf("%s",&doc[i].specialist);
    printf("enter contact number:");
    scanf("%lld",&doc[i].contact_number);
    }
    printf("doctor found");


    return 0;
}
