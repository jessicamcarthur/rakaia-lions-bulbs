

## Sold out item
When an item is sold out, you have two options to update the website so that customers know it’s no longer available:

1. Add a "SOLD OUT" Message
insert the following line directly below the item's details in the HTML file: 
<p>SOLD OUT</p>

2. Comment Out the Item (Hide It)
If you want to hide the entire item from the website (so it's not visible), you can comment it out by wrapping the code like this example:
<!--
        <div class="product-item">
          <img src="images/tisento.jpg" alt="Tisento Lily">
          <label>Tisento Lily</label>
          <select name="tisentoLily">
            <option value="0">Quantity</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
          </select>
        </div>
-->