<template>
  <div>
    <div id = 'header' class = "bg-[url('/hero-bg.jpg')] px-20">
      <div id = 'menu' class ="grid grid-cols-2 py-5">
        <div id = 'menu-left'>
          <img src ='logo.png' class ="w-[150px]" alt = "">
        </div>

        <div id = 'menu-right'>
          <ul class = 'grid grid-cols-4 text-lg font-oswald text-white uppercase pt-5'>
            <li>About us</li>
            <li>Our Menu</li>
            <li>Locations</li>
            <li>Contacts</li>
          </ul>
        </div>
      </div>
      <div class ="grid grid-cols-2 pb-20 pt-10">
        <img src = 'hero-burger.png' class="pr-8 mt-10" alt = "">
        <div>
          <h1 class ='text-8xl text-white text-center font-lilita uppercase'>
            Classic Burger
          </h1>
          <h2 class = "text-6xl text-white text-center font-lilita uppercase my-5">
            With Onion
          </h2>
          <p class = "text-white font-roboto font-light text-center">
            Our signature burger now comes with onion and cheese. You can customize it to your likings. Freshly made to order, all in a Brioche style bun.
          </p>
        </div>
      </div>
    </div>
    <div id ='section-1' class="text-center bg-[url('/three-burger.jpg')] pb-96 bg-cover">
        <h1 class = "text-6xl uppercase font-oswald text-center pt-20 px-24">
          The burger tastes better when you eat with your family
        </h1>
        <p class = 'font-roboto font-light text-grey-500 text-center text-lg py-6 px-24'>
          Spend quality time with your family and eat and afforadable, nutritious and delicious meal together. Not all burgers are fast foods. All our burgers are handmade to orders for you and your family members to enjoy.
        </p>
        <button class ="font-oswald uppercase bg-red-500 text-white py-3 px-8">
          Explore Full Menu
        </button>
    </div>
    <div id="section-3" class = "text-center">
      <h2 class="text-6xl font-oswald text-red-500 uppercase font-medium">
        Our Crazy Burgers
      </h2>
      <p class="text-gray-500 font-light text-xl my-10 px-20">
        Whether you are looking for the classics, our specialties, or just wrap, salads, and fries. We have it all. We always have something that rewards your tastebud.
      </p>
      <div class = 'grid grid-cols-2 px-40 gap-5'>
        <div id = 'left-item-column'>
          <div class ="border rounded-md bored-gray-200 text-left pb-5">
            <img src="crispy-chicken.jpg" alt ="">
            <h3 class="font-oswald font-medium text-2xl uppercase text-grey-500 mt-5 mb-5 ml-5">
              Crispy Chicken
            </h3>
            <p class = "font-light text-grey-500 mb-5 ml-5">Chicken brest,chill sauce, tomatoes,pickles, coleslaw</p>
            <span class = "bg-amber-800 text-yellow-400 font-bold text-xl font-oswald ml-5 rounded rounded-lg px-5 py-2">
              RM 11.99
            </span>
          </div>
        </div>
        <div id = 'right-item-column'>
          <Item image="crispy-chicken.jpg" title="Crispy Chicken" description = "Chicken breast" price="11.90"/>
          <Item image="double-burger.jpg" title = "Double Burger" description = "Double Burger La what you want" price ="20.99" />
        </div>
      </div>
    </div>
  </div>
</template>
