# Welcome!
#include <stdio.h>
#include <stdlib.h>
#include "drawing.h"

int main() {
    int i; 

    init_drawing(1050,500,0.5);
    
    for (i=0;i<2;i++) {
        draw(100);
        move(110);
        turn(60,LEFT);
        draw(50);
        move(60);
        turn(120,LEFT);
    }    
    
    display_drawing();

    return 0;
