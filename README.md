# Transactional-Database-Design

**Business Case Study:** A grocery Customer Relation Manager is worried in keeping the list of customers in an excel sheets due to the exponential growth of customers as a result of 90% discount on every category of products purchase this year to celebrate 153 years Canada Anniversary.
Customers geographical distribution is essential to determine the most demanded products in every store across Canada. Supervisors are assigned to each category of products to keep track of the product volumes.
Budget is already in place to develop a Customer Database. As a data modeler, you are required to come up with a refined data model.

**Design of the Conceptual, Logical and Physical data model**

To solve the problem of developing a refined data model for the client's Customer Database, the following steps were taken:
1.	Identification of Entities and Relationships: The first step involved identifying the entities and relationships in the system. Some of the entities identified included Sales Transaction, Customer, Product, Promotion, Employee, etc.
2.	Relational Model Design: The model was designed based on the relational model proposed by E.F. Codd. The entities were mapped to tables, and the relationships between the entities were established using foreign keys.
3.	Normalization to Third Normal Form: The model was then normalized to the third normal form (3NF). This normalization process ensured that every non-prime attribute depended solely on the primary key, and partial dependencies on the primary key were eliminated. This helped maintain data integrity, reduce redundancy, and improve data consistency.
4.	Data Integrity and Efficiency: By adhering to the relational model principles and normalizing the data model, data integrity was ensured, and redundancy was minimized. The use of foreign keys facilitated establishing relationships between tables and enabled efficient querying and data management.


Figure 1-3 shows the conceptual, Logical and the physical data models.
**Conceptual Data Model:**
The conceptual data model (Figure 1) represents the high-level view of the database without focusing on implementation details. It identifies the main entities, attributes, and relationships within the system.

**Logical Data Model:**
The logical data model (Figure 2) translates the conceptual model into a more detailed representation using the relational database. It defines the tables, columns, primary keys, foreign keys, and relationships between tables.

**Physical Data Model:**
The physical data model shown in Figure 3 represents how the model will be built in the database. The model shows all table structures, including column name, column data type, column constraints, primary key, foreign key, and relationships between tables

By implementing this refined data model, the Customer Relation Manager can effectively track customer information, analyze geographical distribution, monitor product demand, assign supervisors to specific categories, and manage purchase records. The model provides a solid foundation for organizing and managing the customer database, enabling improved decision-making and customer relationship management within the company. 

![image](https://github.com/okwoli200/Transactional-Database-Design/assets/99350558/170bf60e-726a-4d6c-bf38-5647657b8d9a)

**Figure 1:** The Conceptual Data Model

![image](https://github.com/okwoli200/Transactional-Database-Design/assets/99350558/9887fcad-6538-463a-a235-133af103458d)

**Figure 2:** The Logical Data Model

![image](https://github.com/okwoli200/Transactional-Database-Design/assets/99350558/b86c3e0d-d32e-4d4c-87fa-6745f5fc00d6)

**Figure 3:** The Physical Data Model

