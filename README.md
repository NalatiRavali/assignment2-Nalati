# assignment2-Nalati
# Ravali Nalati
###### Las Vegas  
Driving into the famous town of **Las Vegas**, you wouldn't imagine that you were about to enter a twenty-four hour party. But that's exactly what I was about to experience. As I crossed the dry Nevada desert and topped the last bare hill, I couldn't believe the sight that was right before my very eyes. Everywhere I looked I saw flashing fluorescent lights, buildings that seemed to touch the sky, people walking the entire length of the Vegas Strip, taxis and buses speeding and so much more. I really love in with this place.


---

# Directions from Maryville to Las Vegas
1. The distance from Maryville to Las Vegas is 1,350 miles via flight transport.
2. Book a cab and go to kansas airport.
    1. After reaching kansas airport take a flight from kansas to Arizona airport.
    2. At Arizona airport we have to change our terminal from 2 to 3
3. The flight from Arizona to Las Vegas will arrive within half an hour, take the flight.
    1. It takes 3 hours to reach Las Vegas from Arizona.
    2. After landing take all your belogings safe.
4. finally we have reached to our destination.  


* I would like to Carry:
  * Groceries:
    * Vegetables
    * Fruits
    * Chocolates
  * Drinks:
    * Fanta
    * Thumps up
    * Coco Cola
  * Accessories:
    * Goggles
    * Sanitizer

   **[AboutMe.md](AboutMe.md)** 


   ---


   # food i suggest to others to try
   I am creating a table with 4 food items that I would suggest someone try. The food items I would suggest are  butter chicken, pizza, panner masala,parota.

   |Food Item|Location|Price|
   |---|---|---|
   |butter chicken|Bawarchi|$10|
   |pizza|pizza hut|$2|
   |panner masala|restaurant|$5|
   |parota|kinara grand|$8|


   ---

   # Pithy Quotes

> "The greatest glory in living lies not in never falling, but in rising every time we fall."-Nelson Mandela*<Br>
> "If you look at what you have in life, you'll always have more. If you look at what you don't have in life, you'll never have enough."-"Oprah Winfrey"

  ---

  # Disjoint Set Union

> In computer science, a disjoint-set data structure, also called a union–find data structure or merge–find set, is a data structure that stores a collection of disjoint (non-overlapping) sets. Equivalently, it stores a partition of a set into disjoint subsets.

[Click here to know more](https://en.wikipedia.org/wiki/Disjoint-set_data_structure)

```

void make_set(int v) {
    parent[v] = v;
}

int find_set(int v) {
    if (v == parent[v])
        return v;
    return find_set(parent[v]);
}

void union_sets(int a, int b) {
    a = find_set(a);
    b = find_set(b);
    if (a != b)
        parent[b] = a;
}

```

[code Source](https://cp-algorithms.com/data_structures/disjoint_set_union.html)
   
   



