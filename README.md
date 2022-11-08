# notes

(JPA) is a Java specification for accessing, persisting, and managing data between Java objects / classes and a relational database.
JPA is pojo based
Controllers handle requests and responses
Controllers has no business logic
Services handle business logic
Service has @Service annotation
Repository describes has basic crud functions and has @Repository annotation
Setter injection is a dependency injection in which the spring framework injects the dependency object using the setter method
Spring @Autowired annotation is used for automatic dependency injection.
@Enity means a class is tied to a database
@id identifies what field is a primary key
We can use the naming strategy implementation in applicagion properties to make tables uppercase
@OneToOne - One to one represents that a single entity is associated with a single instance of the other entity. An instance of a source entity can be at most mapped to one instance of the target entity.
@OneToMany - used to define a one to many relationship between an object and a list of objects. This is paired with @manyToOne. Mapped by property ties the @ManyToOne object to this list. Mapped by property is set to the name of the variable with the @ManyToOne annotation. The list on the @OneToMany side will be updated by this relationship. one-to-many mapping means that one row in a table is mapped to multiple rows in another table.
@ManyToOne - where one entity contains values that refer to another entity (a column or set of columns) that has unique values.
@ManyToMany - when multiple records in a table are associated with multiple records in another table. For example, a many-to-many relationship exists between customers and products: customers can purchase various products, and products can be purchased by many customers. Fetch Types - used with join types to choose when we want to fetch there are 2 types... Lazy and Eager. Lazy queries the database when the getter for that property is called. Eager queries the database when the object is created.

video 2-
With spring apps, Spring Boot uses build and dependency management. The build tools Maven and Gradle are used to indicate which libraries or dependencies the application will require during compilation and packaging before deployment. Maven project layout and spring annotations are both used in the project layout and structure to help distinguish between the many architectural components of the application.
