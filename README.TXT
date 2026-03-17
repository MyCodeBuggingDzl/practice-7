------------------------------------------------------------------------
This is the project README file. Here, you should describe your project.
Tell the reader (someone who does not know anything about this project)
all they need to know. The comments should usually include at least:
------------------------------------------------------------------------

PROJECT TITLE:
PURPOSE OF PROJECT:
VERSION or DATE:
HOW TO START THIS PROJECT:
AUTHORS:
USER INSTRUCTIONS:


p3 q4

* @author (your name)
 * @version (a version number or a date)
 */
public class MapTester
{
    // instance variables - replace the example below with your own
    private HashMap<String, String> phonebook;

    /**
     * Constructor for objects of class MapTester
     */
    public MapTester()
    {
        phonebook = new HashMap<>();
    }

    public void enterNumber(String name, String number){
        phonebook.put(name, number);
    }
    
    public String lookupNumber(String name){
        return phonebook.get(name);
    }
}
