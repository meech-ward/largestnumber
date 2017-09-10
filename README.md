# largestnumber
LHL Assignment 3

//c style array w/5 elements
        int x[] = {15, 12, 27, 10, 45};
        int greatest = x[0];
        int i;
            //for (i = 0; i<=4; i++) {}
            //greatest = x[0];
        for (i = 0; i<=4; i++) {
            if(x[i] > greatest) {
                greatest =x[i];
                NSLog(@" The greatest value is %i\n", greatest);
                    //break;
            }//else { NSLog(@"it aint working");
             //}
        }

    
    
    
    
    }
    return 0;
}
