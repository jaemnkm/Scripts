    /*

    "To work with any number of nested loops, so that you have a function:

        function NameOfGod(n) // n is number of letters
        name_of_god = NameOfGod( 9 )
    "

    #include <stdio.h>

    int main(){

        char a,b,c;

            for(a='A';a<='Z';++a){
                for(b='A';b<='Z';++b){
                    for(c='A';c<='Z';++c){
                        printf("%c%c%c\t",a,b,c);
                    }
                }
        }

    }

    */

I want to write this program so it can handle a depth of any number.

So need to rewrite this without using a,b,c variables.