//Create the variables

public class Main{
    private String name;
    private String address;
    private String city;
    private String state;
    private String zipCode;

    // Constructor
    public Main(String name, String address, String city, String state, String zipCode) {
        this.name = name;
        this.address = address;
        this.city = city;
        this.state = state;
        this.zipCode = zipCode;
    }

    // Print method
    public void displayInfo() {
        System.out.println("Restaurant Name: " + name);
        System.out.println("Business Address: " + address);
        System.out.println("City: " + city);
        System.out.println("State: " + state);
        System.out.println("Zip Code: " + zipCode);
    }

    public static void main(String[] args) {
        // Create the restaurant information 
        Main myRestaurant = new Main ("Texas Roadhouse", "23750", "Kingwood", "TX", "77339");

        // Output 
        myRestaurant.displayInfo();
    }
}

