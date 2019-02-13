##  Here's some things to do in IntelliJ:

### 1.  Set up your header comment template (We'll walk through the settings menu)

### 2.  Make a new Java class in IntelliJ

### 3.  Set up the right margin and text wrap if you want (We can walk through this too)

### 4.  Copy the following code into your main method and use the reformat code to clean it up quickly

            for(int i=1;i<=4*(5+4);i+=6){System.out.println("Bret?");System.out.println(
                            "Present");for(int j=0;j<i/5;j++){System.out.println("Yay repetition");}int
                            somenumber=0;for(int y=9;y>5;y--){somenumber++;}System.out.println(somenumber);
                            }System.out.println("done");

### 5.  Copy this comment somewhere into your program:

        //TODO: Copy this comment into your class

### Notice anything? Try using the TODO and FIXME keywords in other comments

### 6.  Copy the following method into your class:


            public static boolean javadocExampleMethod (int a, int b, double c, String name,
                                                        boolean isBowieInSpace){
                    return (name.charAt(0) == name.toUpperCase().charAt(0)) && ((a != b) || ((int)c == b))
                            && !isBowieInSpace;
                            }

### 7.  Write a Javadoc comment for this method by typing "/**" above the method and then hit enter. Fill in the appropriate fields.

### 8.  (Time permitting) Copy the following method into your class and call it in your main method. We'll walk through some debugger basics if we have time.


                /**
                     * This method is supposed to reverse each section of 4 characters in the string and build
                     * a new string off of the results. This method has a bug though! Use the debugger to
                     * figure out what's going on.
                     */
                    public static void funWithStrings(){
                        String letters = "YyaYiFuoTdexuBehTnIgeMehdoht";
                        String newLetters = "";
                        for(int i = 0; i < letters.length()/4; ++i){
                            String tempString = "";
                            for(int j = 3; j >0; --j){
                                tempString += letters.charAt((4*i) + j);
                            }
                            newLetters += tempString;
                        }
                        System.out.println(newLetters);
                    }

### 9.  Submit your Java class file to Brightspace if you haven't already!