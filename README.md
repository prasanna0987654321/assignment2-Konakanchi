

# Prasanna Konakanchi

###### Hyderabad Marketplace 


The Hyderabad market place is one of the biggest in the country. It has a wide range of stores and a lot of people from all over the world come here to shop. There are also many ***restaurants*** and ***cafes*** that are found here. I like this place very much.

There are some amazing places to eat, shop, and hang out in Hyderabad. Some of these places include:


- Birla Mandi

- Falaknuma Palace

- Golconda Fort

- Charminar
---
## ROUTE
The closest airport to your food location in Hyderabad is the Rajiv Gandhi International Airport.
This airport is located at Shamshabad, which is 8 km away from the city center of Hyderabad.The closest airport to Hyderabad is Hyderabad International Airport. It is about 20 miles away from the city center.There are many airports in Hyderabad, but the closest one would be the Rajiv Gandhi International Airport.

 The following are step by step directions on how to reach your food destination from the airport.

1. Take a taxi from the airport to the city center.

2. From the city center, take a 427 bus  to hyderabad food market  location.

3. Once you have arrived at your desired location, take a cab or walk to get there.

Hyderabad has a lot of places to eat. Here are some places that are within walking distance from the airport.
The nearest subway station is at Baiyyappanahalli and the nearest bus stop is at Hosur Main Road<br>

Here i want to share some list of specific foods items<br>


- Samosa
- Biryani
- Chai

[click here to know about me](https://github.com/prasanna0987654321/assignment2-Konakanchi/blob/main/AboutMe.md)

# SPORTS
I would like  to refer the following sports to others are Tennis, Cricket, Hockey, Table tennis.
|  Name        |  Location  | Amount to pay  |
| ----------   | ---------- | -------------- |
|  Tennis      | Ohio       |   $55          |
| Basket Ball  | Texas      |   $45          |
|  Hockey      | Iowa       |   $25          |
|   Shuttle    | Arkansas   |   $60          |

---

# Pithy Quote
> If you fell down yesterday, stand up today.-*H. G. Wells*<br>
> Set your goals high, and don't stop till you get there. -*Bo Jackson*

---

# String Processing

> String hashing is the way to convert a string into an integer known as a hash of that string.
An ideal hashing is the one in which there are minimum chances of collision (i.e 2 different strings having the same hash).

Link to string hashing code <https://www.geeksforgeeks.org/string-hashing-using-polynomial-rolling-hash-function/#:~:text=What%20is%20String%2DHashing%3F,strings%20having%20the%20same%20hash).>

~~~
long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}
~~~

Link to source code <https://cp-algorithms.com/string/string-hashing.html>