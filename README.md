# NETWORKING-200B-GROUP-12
 private final String Driver = "com.mysql.cj.jdbc.Driver";
    private final String DatabaseName = "transport_management_system";
    private final String DatabaseUser = "root";
    private final String DatabasePassword = "";
    private final String url = "jdbc:mysql://" + DatabaseUser + ":" + DatabasePassword + "@" + "localhost/" + DatabaseName;
    
    tables and entities below
    
   booking(id(PRIMARY), Date, Time, Location )
   drivers(id(PRIMARY), FullNmae, Contact, Vehicle_No)
   signup(id(PRIMARY), Email, Username, Password)
