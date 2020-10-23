```java
package me.hypersmc.About;

import me.hypersmc.about.Me;

public class About extends Me
{
    public static void getWork()
    {
        try {
          if (Me.getJobs() > 0){
            System.out.println("Currently nothing");
          }
        } catch (Exception e) {
          System.out.println("There was an error trying to fetch jobs. Please try again later.");
          System.out.println("");
          System.out.println("Error code: " + e);
        }
    }

    public static void getDailyKnowledge()
    {
        try {
          if (Me.getKnowledge() > 7 ){
            System.out.println("I currently know Java, JS, PhP, Laravel, C++, C#, Golang");
          }
        } catch (Exception e){
          System.out.println("There was an error trying to fetch knowledge. Please try again later.");
          System.out.println("");
          System.out.println("Error code: " + e);
        }
    }

    public string getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
