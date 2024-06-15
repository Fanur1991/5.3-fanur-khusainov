# MongoDB data structure

Development of MongoDB database structures for managing an optician's office, a food delivery store, and a scaled-down version of YouTube.

### Level 1 - Optic

The project focuses on managing an optician's office called. Here are the key points detailed:

| **Collections** | **Attributes**                                                       |
| --------------- | -------------------------------------------------------------------- |
| Glasses         | Brand, frame_types, provider, telephone, fax, nif, price, bought_by. |
| Customers       | Name, address, telephone, email, registration_date, last_shoppings   |

#### Modeling:

1. **Database design according to the customer's view of the optician.**

- The exercise asks you to consider the information necessary to display the graphical interface provided.
<p align="center">
    <img src="./01-level-1/01-exercise-1/taskView/view1.jpg">
</p>

2. **Design of the database according to the vision of the glasses.**

- The exercise asks you to consider the information necessary to display the glasses interface.
<p align="center">
    <img src="./01-level-1/02-exercise-2/taskView/view2.jpg">
</p>

### Level 2 - Food delivery store

This level focuses on the design of an ordering website for a food delivery ordering store. Highlights:

| **Collections** | **Attributes**                                                                        |
| --------------- | ------------------------------------------------------------------------------------- |
| Customers       | id, first_name, last_name, address, postal_code, city, province, telephone            |
| Order           | customer_id, shop_id, order_date, delivery_type, total_price, note, delivery,products |
| Employee        | id, first_name, last_name, nif, telephone, role, shop_id.                             |
| Shop            | id, address, postal_code, city, province                                              |

### Modeling:

1. **Database design for online order management.**

- The exercise asks you to consider the information needed to manage orders, customers and products.
<p align="center">
  <img src="./02-level-2/taskView/view.jpg">
</p>

2. **Database design from a pizza perspective.**

- The exercise asks you to consider the information needed to manage the different pizza categories and products.

### Level 3 - YouTube

This level represents a reduced version of YouTube with the following features:

| **Collections** | **Attributes**                                                                                                               |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| User            | id, email, password, username, birthdate, gender, country, postal_code, subscriptions                                        |
| Video           | id, title, description, size, video_file_name, duration, thumbnail, views, likes, dislikes, status, tags, uploader, comments |
| Channel         | id, name, description, creation_date date.                                                                                   |
| Playlist        | id, name, creation_date, status, videos                                                                                      |

#### Modeling:

1. **Database design for a scaled-down version of YouTube.**

- The exercise asks you to consider the information needed to manage users, videos, channels and playlists.
<p align="center">
 <img src="./03-level-3/taskView/view.jpg">
</p>

## License

This project is distributed under the Apache 2.0 license.

---

Developed by [Fanur Khusainov](https://www.linkedin.com/in/fanur-khusainov-ab86b2102/) with ❤️ and ☕.
