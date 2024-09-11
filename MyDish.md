# Sravya Geethika Sala


My favorite food is pizza. It’s simple, delicious, and can be customized in endless ways. The combination of a crispy crust, melted cheese, and flavorful toppings is irresistible. Whether it's a classic pepperoni or something more unique, pizza always hits the spot. Plus, it's perfect for sharing!

![Pizza Picture](pizza.jpeg)

---

### Table

This table below showcases four Indian restaurants that are known for their flavorful dishes, excellent service, and unique dining experiences. Each restaurant is recommended for a specific reason, whether it's the authenticity of the cuisine or the atmosphere of the restaurant. If you're in the mood for Indian food, these places are sure to satisfy your cravings.

| **Restaurant Name** | **Reason for Recommendation** | **Location** |
| --- | --- | --- |
|Spice Symphony | Authentic Indian Flavours with modern twists | New York,NY |
| Chaat house | Famous for its street food-inspired menu | San Fransico,CA |
| Biryani Pot | Best for a variety of flavorful biryanis | Houston, TX |
| Tandoor Palace | Cozy atmosphere with traditional dishes | Chicago, IL |

---

### Quotes

> "The early bird might get the worm, but the second mouse gets the cheese." - ***Steven Wright***

> "I’m reading a book about anti-gravity. It’s impossible to put down." - ***George Carlin***

---

### Code Fencing

This TypeScript snippet creates a debounce function that delays the execution of a given function until after a specified delay, preventing it from being called repeatedly in quick succession.

```
const debounce = (fn: Function, ms = 300) => {
	let timeoutId: ReturnType;
  return function (this: any, ...args: any[]) {
	  clearTimeout(timeoutId);
    timeoutId = setTimeout(() => fn.apply(this, args), ms);
  };
};

```
[TypeScript Snippet](https://code.pieces.app/collections/typescript)