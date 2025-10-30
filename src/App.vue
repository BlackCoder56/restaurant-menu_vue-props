<template>
  <div id="menu-frame">
    <h1>Menu</h1>
    <ol >
      <h4><li>
        <food-item food-name="Plain Chips" food-price="sh.5,000" />
      </li></h4>
      <h4><li>
        <food-item food-name="Chips & Beef gravy" food-price="sh.12,000" />
      </li></h4>
      <h4><li>
        <food-item food-name="Chips & Chicken" food-price="sh.15,000" />
      </li></h4>
      <h4><li>
        <food-item food-name="Beef (with any food)" food-price="sh.8,000" />
      </li></h4>
      <h4><li>
        <food-item food-name="Beans (with any food)" food-price="sh.4,000" />
      </li></h4>
      <h4><li>
        <food-item food-name="Cowpeas (with any food)" food-price="sh.6,000" />
      </li></h4>
      <h4><li>
        <food-item food-name="Vegetbles" />
      </li></h4>
    </ol>
  </div>
</template>

<style>
  #app > div {
    border: dotted black 1px;
    display: inline-block;
    margin-top:20px;
    margin-left: 30%;
    background-color: lightgreen;
    padding:20px;
    text-align: left;
  }

  #app > div > h1 {
    text-align: center;
  }

  ol{
    padding-right: 30px;
  }
</style>