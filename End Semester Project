import java.util.*;
class Event_Management implements Display, Display_Details 
{
    //Declaring static variables
    static public String Customer_Name;
    static protected int Contact_Number;
    static public String Email_ID;
    static public String Address;
    static public int SchoolEvent_Choice;
    static public String date, venue, theme;
    static protected int Number_of_people;
    static public String cake, food, Food_drinks, Food_boxes;
    static public String Cards, cards_gifts;
    static public String Festival_name;
    static public String offerings;
    static public String Stage_settings;
    static public String Certificate, Awards_certificates, Medals_Trophies_Certificate;
    static public String details;
    static public String event;
    static public int Event_Choice;    
    protected int getEventChoice() 
    {  
        return Event_Choice;  
    }  
    protected void setEventChoice(int Event_Choice) 
    {  
        this.Event_Choice = Event_Choice;  
    }      
    //Constructor
    Event_Management()
    {
        Customer_Name = "";
        Contact_Number = 0;
        Address = "";
        Email_ID = "";
    }
    //Constructor Overloading
    Event_Management(String cn, int n, String a, String e)
    {
        Customer_Name = cn;
        Contact_Number = n;
        Address = a;
        Email_ID = e;
    }
    //static block
    static
    {
        System.out.println("\f");
        System.out.println("Welcome to Creative corner");
    }
    //Method Overloading
    protected final void choose_event(int c)
    {
        Event_Choice = c;
    }
    //Method Overloading
    protected final void choose_event()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Choose the event: ");
        System.out.println("1. Birthday Party");
        System.out.println("2. Festivals");
        System.out.println("3. Weddings");
        System.out.println("4. Engagements");
        System.out.println("5. Receptions");
        System.out.println("6. Baby Shower");
        System.out.println("7. School Events");
        System.out.println("8. Parties");
        System.out.println("9. Office Parties");
        System.out.println("10. Others");
        Event_Choice = sc.nextInt();
        //switch case
        switch(Event_Choice)
        {
            case 1 : 
                    Birthday_Party obj1 = new Birthday_Party();
                    obj1.input();
                    System.out.println("");
                    break;
            case 2 : 
                    Festivals obj2 = new Festivals();
                    obj2.input();
                    System.out.println("");
                    break;
            case 3 : 
                    Weddings obj3 = new Weddings();
                    obj3.input();
                    System.out.println("");
                    break;
            case 4 :
                    Engagements obj4 = new Engagements();
                    obj4.input();
                    System.out.println("");
                    break;
            case 5 : 
                    Receptions obj5 = new Receptions();
                    obj5.input();
                    System.out.println("");
                    break;
            case 6 : 
                    Baby_Shower obj6 = new Baby_Shower();
                    obj6.input();
                    System.out.println("");
                    break;
            case 7 : 
                    School_Events obj7 = new School_Events();
                    obj7.input();
                    System.out.println("");
                    break;
            case 8 : 
                    Parties obj8 = new Parties();
                    obj8.input();
                    System.out.println("");
                    break;
            case 9 : 
                    Office_Parties obj9 = new Office_Parties();
                    obj9.input();
                    System.out.println("");
                    break;
            case 10 : 
                    Others obj10 = new Others();
                    obj10.input();
                    System.out.println("");
                    break;
            default: 
                    System.out.println("");
        }
    }   
    protected void design()
    {
        for (int i=1; i<=30 ; i++)
        {
            System.out.print(" *  ");
        }  
        System.out.println("");
        for(int j=1; j<=30; j++)
        {
            System.out.print("*** ");
        }
        System.out.println("");
        System.out.println("");
    }
    public void Details()
    {
        System.out.println("***************** CUSTOMER DETAILS *****************");
        System.out.println("Name: "+Customer_Name);
        System.out.println("Contact Number: "+Contact_Number);
        System.out.println("Address: "+Address);
        System.out.println("E-Mail ID: "+Email_ID);
    }
    public void EventDetails()
    {
        System.out.println("****************** EVENT DETAILS ******************");
        if(Event_Choice == 1)
        {
            System.out.println("Date of the Party: "+date);
            System.out.println("Venue: "+venue);
            System.out.println("Theme: "+theme);
            System.out.println("Number of people: "+Number_of_people);
            System.out.println("Cake flavours and description: "+cake);
            System.out.println("Food Items: "+food);
            System.out.println("Cards and Gifts: "+cards_gifts);
            System.out.println("Additional Details: "+details);
        }
        else if(Event_Choice == 2)
        {
            System.out.println("Festival's name: "+Festival_name);
            System.out.println("Date of the Festival: "+date);
            System.out.println("Venue: "+venue);
            System.out.println("Theme: "+theme);
            System.out.println("Number of people: "+Number_of_people);
            System.out.println("Offerings: "+offerings);
            System.out.println("Additional Details: "+details);
        }
        else if(Event_Choice == 3)
        {
            System.out.println("Date of the Wedding: "+date);
            System.out.println("Venue: "+venue);
            System.out.println("Theme: "+theme);
            System.out.println("Number of people: "+Number_of_people);
            System.out.println("Food Items: "+food);
            System.out.println("Cards: "+Cards);
            System.out.println("Additional Details: "+details);
        }
        else if(Event_Choice == 4)
        {
            System.out.println("Date of the Engagement: "+date);
            System.out.println("Venue: "+venue);
            System.out.println("Theme: "+theme);
            System.out.println("Number of people: "+Number_of_people);
            System.out.println("Stage settings: "+Stage_settings);
            System.out.println("Food Items: "+food);
            System.out.println("Additional Details: "+details);
        }
        else if(Event_Choice == 5)
        {
            System.out.println("Date of the Reception: "+date);
            System.out.println("Venue: "+venue);
            System.out.println("Theme: "+theme);
            System.out.println("Number of people: "+Number_of_people);
            System.out.println("Stage settings: "+Stage_settings);
            System.out.println("Cake flavours and description: "+cake);
            System.out.println("Food Items: "+food);
            System.out.println("Cards: "+Cards);
            System.out.println("Additional Details: "+details);
        }
        else if(Event_Choice == 6)
        {
            System.out.println("Date of the Baby Shower: "+date);
            System.out.println("Venue: "+venue);
            System.out.println("Theme: "+theme);
            System.out.println("Number of people: "+Number_of_people);
            System.out.println("Cake flavours and description: "+cake);
            System.out.println("Food Items: "+food);
            System.out.println("Cards: "+Cards);
            System.out.println("Additional Details: "+details);
        }
        else if(Event_Choice == 7)
        {
            if(SchoolEvent_Choice == 1)
            {
                System.out.println("Date of the Annual Day: "+date);
                System.out.println("Venue: "+venue);
                System.out.println("Theme: "+theme);
                System.out.println("Number of people: "+Number_of_people);
                System.out.println("Food Boxes: "+Food_boxes);
                System.out.println("Stage settings: "+Stage_settings);
                System.out.println("Awards and Certificates: "+Awards_certificates);                
                System.out.println("Additional Details: "+details);
            }
            else if(SchoolEvent_Choice == 2)
            {
                System.out.println("Date of the Sports Day: "+date);
                System.out.println("Venue: "+venue);
                System.out.println("Theme: "+theme);
                System.out.println("Number of people: "+Number_of_people);
                System.out.println("Food Boxes: "+Food_boxes);
                System.out.println("Medals, Trophies and and Certificates: "+Medals_Trophies_Certificate);                
                System.out.println("Additional Details: "+details);
            }
            else if(SchoolEvent_Choice == 3)
            {
                System.out.println("Date of the Graduation Day: "+date);
                System.out.println("Venue: "+venue);
                System.out.println("Theme: "+theme);
                System.out.println("Number of people: "+Number_of_people);
                System.out.println("Food Boxes: "+Food_boxes);
                System.out.println("Stage settings: "+Stage_settings);
                System.out.println("Certificates: "+Certificate);                
                System.out.println("Additional Details: "+details);
            }
            else if(SchoolEvent_Choice == 4)
            {
                System.out.println("Date of General Events: "+date);
                System.out.println("Venue: "+venue);
                System.out.println("Theme: "+theme);
                System.out.println("Number of people: "+Number_of_people);
                System.out.println("Food Boxes: "+Food_boxes);
                System.out.println("Stage settings: "+Stage_settings);               
                System.out.println("Additional Details: "+details);
            }
        }
        else if(Event_Choice == 8)
        {
            System.out.println("Date of the Party: "+date);
            System.out.println("Venue: "+venue);
            System.out.println("Theme: "+theme);
            System.out.println("Number of people: "+Number_of_people);
            System.out.println("Food Items and Drinks: "+Food_drinks);
            System.out.println("Additional Details: "+details);
        }
        else if(Event_Choice == 9)
        {
            System.out.println("Date of the Office Party: "+date);
            System.out.println("Venue: "+venue);
            System.out.println("Theme: "+theme);
            System.out.println("Number of people: "+Number_of_people);
            System.out.println("Food Items and Drinks: "+Food_drinks);
            System.out.println("Additional Details: "+details);
        }
        else if(Event_Choice == 10)
        {
            System.out.println("Date of the Event: "+event);
        }
    }
    public static void main(String []args)
    {
        //creating an object for the Event_Management class
        Event_Management obj = new Event_Management();
        
        Scanner sc = new Scanner(System.in);
        System.out.println("To start of, please enter the following details");
        System.out.println("Name: ");
        String Customer_Name = sc.next();
        System.out.println("Contact Number: ");
        int Contact_number = sc.nextInt();
        System.out.println("Address: ");
        String Address = sc.next();
        System.out.println("Email ID: ");
        String Email_ID = sc.next();
        
        obj.choose_event();        
        obj.design();
        //creating object for the interface class
        Display obj1 = new Event_Management(Customer_Name, Contact_number, Address, Email_ID);
        obj1.Details();
        //creating object for the interface class
        Display_Details obj2 = new Event_Management();
        obj2.EventDetails();
        //creating object for the abstract class
        MessageEmail obj3 = new MessageEmail();
        obj3.Email(); 
        obj3.Design();
    }
}
//inheritance
class Birthday_Party extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Birthday Party");
        System.out.println("Date of the Party: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Cake flavors and description: ");
        cake = sc.next();
        System.out.println("Food Items: ");
        food = sc.next();
        System.out.println("Cards and Gifts: ");
        cards_gifts = sc.next();
        System.out.println("Additional details: ");        
        details = sc.next();
    }
}
class Festivals extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Festival");
        System.out.println("Festival's Name: ");
        Festival_name = sc.next();
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Offerings: ");
        offerings = sc.next();
        System.out.println("Additional details: ");   
        details = sc.next();
    }
}
class Weddings extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Wedding");
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Food items: ");
        food = sc.next();
        System.out.println("Cards: ");
        Cards = sc.next(); 
        System.out.println("Additional details: ");      
        details = sc.next();  
    }
}
class Engagements extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Engagement");
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Stage Settings: ");
        Stage_settings = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Food items: ");
        food = sc.next();
        System.out.println("Additional details: ");     
        details = sc.next();     
    }
}
class Receptions extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Engagement");
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Stage Settings: ");
        Stage_settings = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Cake flavors and description: ");
        cake = sc.next();
        System.out.println("Food: ");
        food = sc.next();
        System.out.println("Cards: ");
        Cards = sc.next(); 
        System.out.println("Additional details: ");     
        details = sc.next();   
    }
}
class Baby_Shower extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Baby Shower");
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Cake flavors and description: ");
        cake = sc.next();
        System.out.println("Food: ");
        food = sc.next();
        System.out.println("Cards: ");
        Cards = sc.next(); 
        System.out.println("Additional details: ");     
        details = sc.next();    
    }
}
class School_Events extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("School events");
        System.out.println("1. Annual day");
        System.out.println("2. Sports Day");
        System.out.println("3. Graduation day");
        System.out.println("4. General Event");
        System.out.println("5. Others");
        System.out.println("Choose the School Event");
        SchoolEvent_Choice = sc.nextInt();
        switch(SchoolEvent_Choice)
        {
            case 1 : 
                    Annual_Day obj1 = new Annual_Day();
                    obj1.input();
                    System.out.println("");
                    break;
            case 2 : 
                    Sports_Day obj2 = new Sports_Day();
                    obj2.input();
                    System.out.println("");
                    break;
            case 3 : 
                    Graduation_Day obj3 = new Graduation_Day();
                    obj3.input();
                    System.out.println("");
                    break;
            case 4 :
                    General_Events obj4 = new General_Events();
                    obj4.input();
                    System.out.println("");
                    break;
                    
            default:
                    System.out.println("Please enter a school event and its details");
        }      
    }
}
class Parties extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Party");
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Food and drinks: ");
        Food_drinks = sc.next();
        System.out.println("Additional details: ");        
        details = sc.next();     
    }
}
class Office_Parties extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Party");
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Food and drinks: ");
        Food_drinks = sc.next();
        System.out.println("Additional details: ");        
        details = sc.next();
    }
}
class Others extends Event_Management
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Event");     
        event = sc.nextLine();
    }
}
class Annual_Day extends School_Events
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Annual Day");
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Food boxes: ");
        Food_boxes = sc.next();
        System.out.println("Awards and Certificates: ");
        Awards_certificates = sc.next();
        System.out.println("Stage Settings: ");
        Stage_settings = sc.next();
        System.out.println("Additional details: ");  
        details= sc.next();     
    }
    public static void main(String []args)
    {
        Annual_Day obj = new Annual_Day();
        obj.input();
    }
}
class Sports_Day extends School_Events
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Sports Day");
        System.out.println("Date: ");
        date= sc.next();
        System.out.println("Venue: ");
        venue= sc.next();
        System.out.println("Theme: ");
        theme= sc.next();
        System.out.println("Number of people: ");
        Number_of_people= sc.nextInt();
        System.out.println("Food boxes: ");
        Food_boxes = sc.next();
        System.out.println("Medals, Trophies and Certificates: ");
        Medals_Trophies_Certificate= sc.next();
        System.out.println("Additional details: ");   
        details= sc.next();     
    }
    public static void main(String []args)
    {
        Sports_Day obj = new Sports_Day();
        obj.input();
    }
}
class Graduation_Day extends School_Events
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Graduation Day");
        System.out.println("Date: ");
        date = sc.next();
        System.out.println("Venue: ");
        venue = sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Food boxes: ");
        Food_boxes = sc.next();
        System.out.println("Certificates: ");
        Certificate = sc.next();
        System.out.println("Stage Settings: ");
        Stage_settings = sc.next();
        System.out.println("Additional details: "); 
        details = sc.next();       
    }
    public static void main(String []args)
    {
        Graduation_Day obj = new Graduation_Day();
        obj.input();
    }
}
class General_Events extends School_Events
{
    static void input()
    {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the details for the Event");
        System.out.println("Date: ");
        date= sc.next();
        System.out.println("Venue: ");
        venue= sc.next();
        System.out.println("Theme: ");
        theme = sc.next();
        System.out.println("Number of people: ");
        Number_of_people = sc.nextInt();
        System.out.println("Food boxes: ");
        Food_boxes = sc.next();
        System.out.println("Stage Settings: ");
        Stage_settings = sc.next();
        System.out.println("Additional details: ");  
        details = sc.next();      
    }
    public static void main(String []args)
    {
        General_Events obj = new General_Events();
        obj.input();
    }
}
//interface
interface Display
{
    public void Details();
}
interface Display_Details extends Display
{
    public void EventDetails();
}
//abstract
public abstract class EmailMessage extends Event_Management
{
    void Email()
    {
        //exception
        try
        {
            if(Event_Choice == 1 || Event_Choice == 2 || Event_Choice == 3 || Event_Choice == 4 || Event_Choice == 5 
            || Event_Choice == 6 || Event_Choice == 7 || Event_Choice == 8 || Event_Choice == 9 || Event_Choice == 10)
            {
                System.out.println("");
                System.out.println("");
                throw new Message("The details of your choices have been sent to your registered Email ID");
            }
            else
            {
                System.out.println("Invalid Input");
            }
        }
        catch(Message n)
        {
            System.out.println(n);
        }
    }
}
class MessageEmail extends EmailMessage
{
    void Design()
    {
        System.out.println("");
        System.out.println("");
        for (int i=1; i<=30 ; i++)
        {
            System.out.print(" *  ");
        }  
        System.out.println("");
        for(int j=1; j<=30; j++)
        {
            System.out.print("*** ");
        }
        System.out.println("");
        System.out.println("");
    }   
}
class Message extends Exception
{
    public Message(String n)
    {
        super(n);
    }
}
