<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Login</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <link href="https://cdn.jsdelivr.net/npm/remixicon@4.9.0/fonts/remixicon.css" rel="stylesheet" />
  <script src="https://cdn.tailwindcss.com"></script>

</head>
<body>
<p class="font-bold text-3xl" >Card Count = <span class="textcount">0</span></p>
<div class="flex gap-2 items-center justify-center">
<input type="text" class="border-2 hover:border-green-500 outline-none border-teal-300 " placeholder="Enter Your Text..">
<button class="text-white p-1 rounded-md font-semibold bg-blue-600">Search</button>
</div>
<section class="p-4 flex flex-col sm:flex-row sm:flex-wrap gap-3 justify-center md:justify-between">
  <!--Card 1-->
  <div class="h-[300px] flex flex-col items-center justify-evenly w-[220px] rounded-md shadow-md shadow-black bg-white ">
     <img class="h-20" src="https://images.pexels.com/photos/54334/running-shoe-shoe-brooks-highly-functional-54334.jpeg?cs=srgb&dl=shoe-sneakers-footwear-54334.jpg&fm=jpg " alt="">
     <h1 class="font-semibold text-lg">Shoes</h1>
     <p class="pl-3 p-1 text-[12px] font-light">Shoes are an essential part of daily life, providing both comfort and style.</p>
     <h2 class="font-bold ">₹450</h2>
    <div class="m-1 flex gap-3 text-lg ">
    <i class="text-orange-400 ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i>
     </div>
     <i class="border-2 text-blue-400 bg-blue-100 h-6 w-6 rounded-md cursor-pointer  border-blue-400  ri-add-line"></i>
    <div class="btnBox flex gap-2">
     <button class="btn1 text-white font-bold bg-red-500 p-2 w-full rounded-md">Add to Cart</button>
     <button class="btn2 hidden text-white font-bold bg-red-500 p-2 rounded-md">Undo</button>
  </div>
  </div>
<!--Card 2-->
  <div class="h-[300px] flex flex-col items-center justify-evenly w-[220px] rounded-md shadow-md shadow-black bg-white ">
     <img class="h-[90px]" src="data:image/webp;base64,UklGRlwFAABXRUJQVlA4IFAFAADQMACdASovAS8BPp1Ook0lpCOiIXcJgLATiWlu4XHhG/NcqZqe1xjSufJ+hRz9PUe/9/cP2KxN2y9OnDReTovJ0Xk6LydF5Oi8nRMX9Hb1TEH4OkYit6n2b9XrG71NtCrcSNsD5q4NynxkHzWnkQL3FCLJRcwasfAMtQh1i6qJcubAhLKKOLHy42/xOsbvUzouFDG6q6LzkKgexzg9d5uu2/XH7dzAtqSK5uSNblGm9Y1sWdTXcYmnUoDcLALf2Xly9xFr786bxbhw0XimnHsQTIQYa01QfAdJMsqiJ0Mnptn1A/teWSG1Erg53tkyI39B2fUD/Au/yfjzPMyx/Jy6vysOSSWN1hVeUAsb5C9YhzNF5OYlc5LMEOnOkuveDL+5J41KGXYIvWN3hjaOL76zBDpzpLr3hhCVR8npOmzhEPqB/WIBoHMzRclmCH1AJ0Sny3Q2C4ahACEgZA7LZ737hRTnKIqAeUlWbdRleC6gh9QEsgXPBuboJyMNsvTpw0Xk6LydF5Oi8nReTovJyoAA/v7X4AGd1pR7C7IvZkAnx8lw4AE2u21+3MkrziXFE8hO8lqY5jnY7wP27kazGf+KIbTnKBFNWdU27NJkK3oCqZgdba4PTZPxxwbNGW9246HmWg1VVEKHhEw6x0FG0+MyY8tKzzMlbO3V1Tx2tsEhLl15+o22cnGw/VEPagmKIDtVx2An78MusUjkzvd58H/0XSfwkNMGxJ4IAW2e+2dSWo2icR5y2bDoG0XigFJAL0yz5loJqTA+xm0xI58wU3YT4uz6aOZ1ZFcpNpYRkvho3w8i0s+BrrHQ7R8N67FfElhoEXlyDVMjnYNh3GtnaymK0h+Ux3Lfb3PMD17rgAY3Q1W81rRBPCiGkbHEow+oqZcq/8uvUJmrEPjHvptvc66a/MFOBNRHL6CHmzpF7N73P9ZhU/t8z8p+5RmkTaKNLmTPDXYUut1Iiikqw8G62y7aGY1LhbNe7BXnPmEM5ZtaksTCD3J1sBt61RSVI/Lr1n4UD3r8TZ/6Yy50qQ34GIf6EFUbdkdU4VmSSnjaGWh+47sfp9lLiO6EawIqs2WKDaGcgvPLXU7X4rZiYIBGzGhnutpMMVjyxFjstnqls0dnNvmi207j20x9rr7ea73FsbfWuys4bi+tUH35o2XWy2tf8f3RK7xnXQyzVLQwV0A+jdYIMZdoyfuyEX3npAtJJIaZmSTJqSEaciEVcfdTZIuFfIXkt/KUHWg4KRquNUI+U28ttZHwP4PiXf3SK5A0vaIlB+2DGwAyHoYr0BzudNbn02jMhEFygqJJ2GAc/20dCEeHs28PT33AYf2ILpp/xMv07DZcUZMAfWnTtC/qrFbySGrvqhuvG7C24G88upiaH7JeDARcVII/loHznJCtdu5YJ6taF1UmswE1/ViwxkFm+tdQ+thPQh8puuHvtmA2VlEXwHUJdJjuPYOaHpp8+ia74RqOu2o4eucVqvpJQF1KZkH0HeO53e0PgurWCUxltEMzDnwigvD/mzHJbHusjTytlRK4OwmAyCmwub82E9So6ypsIgOWvPnUaB31rISKUKEbETNiSgWJ3YXXj18tMo2Egz+xGcsi6Kl4xk0fXT8z/5+U/6Ma8KxxZIsuuyzSsbIPoPprE0uL8K+kQWdNP6dRJBkvgzxG+OOwpI32YB2wlLFf+M02kNhw0PRq70n/EyfUCNdiaIsmsEuJUKyTVX/x12Ol80v8qrnbTQr2fQ+sAqXpQ1QKBz8CtMfUFi5mJlDDaYwaHJ4o7xLOnFTxomqix3jRcTdfDPBQAAAAAAAA" alt="">
     <h1 class="font-semibold text-lg">Phone</h1>
     <p class="pl-3 p-1 text-[12px] font-light">The iPhone is a popular smartphone known for its sleek design interface.</p>
     <h2 class="font-bold ">₹85,999</h2>
    <div class="m-1 flex gap-3 text-lg ">
    <i class="text-orange-400 ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i>
     </div>
     <i class="border-2 text-blue-400 bg-blue-100 h-6 w-6 rounded-md cursor-pointer  border-blue-400  ri-add-line"></i>
    <div class="btnBox flex gap-2">
     <button class="btn1 text-white font-bold bg-red-500 p-2 w-full rounded-md">Add to Cart</button>
     <button class="btn2 hidden text-white font-bold bg-red-500 p-2 rounded-md">Undo</button>
  </div>
  </div>

  <!--Card 3-->
  <div class="h-[300px] flex flex-col items-center justify-evenly w-[220px] rounded-md shadow-md shadow-black bg-white ">
     <img class="h-20" src="https://th.bing.com/th/id/OIP.nYPqnZqo72dAQgYZYjVp_QHaE8?w=282&h=189&c=7&r=0&o=7&dpr=1.5&pid=1.7&rm=3" alt="">
     <h1 class="font-semibold text-lg">Watch</h1>
     <p class="pl-3 p-1 text-[12px] font-light">A watch is a useful accessory that helps you keep track of time while also adding style to your outfit.</p>
     <h2 class="font-bold ">₹999</h2>
    <div class="m-1 flex gap-3 text-lg ">
    <i class="text-orange-400 ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i>
     </div>
     <i class="border-2 text-blue-400 bg-blue-100 h-6 w-6 rounded-md cursor-pointer  border-blue-400  ri-add-line"></i>
    <div class="btnBox flex gap-2">
     <button class="btn1 text-white font-bold bg-red-500 p-2 w-full rounded-md">Add to Cart</button>
     <button class="btn2 hidden text-white font-bold bg-red-500 p-2 rounded-md">Undo</button>
  </div>
  </div>
  <!--Card 4-->
  <div class="h-[300px] flex flex-col items-center justify-evenly w-[220px] rounded-md shadow-md shadow-black bg-white ">
     <img class="h-[90px]" src="https://th.bing.com/th/id/OIP.Gj6VHjsxY81npikVyC9UDQHaH3?w=156&h=180&c=7&r=0&o=7&dpr=1.5&pid=1.7&rm=3" alt="">
     <h1 class="font-semibold text-lg">Earphone</h1>
     <p class="pl-3 p-1 text-[12px] font-light">Earphones are small audio devices your ears to music, calls, or videos privately</p>
     <h2 class="font-bold ">₹1,899</h2>
    <div class="m-1 flex gap-3 text-lg ">
    <i class="text-orange-400 ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i>
     </div>
     <i class="border-2 text-blue-400 bg-blue-100 h-6 w-6 rounded-md cursor-pointer  border-blue-400  ri-add-line"></i>
    <div class="btnBox flex gap-2">
     <button class="btn1 text-white font-bold bg-red-500 p-2 w-full rounded-md">Add to Cart</button>
     <button class="btn2 hidden text-white font-bold bg-red-500 p-2 rounded-md">Undo</button>
  </div>
  </div>
  <!--Card 5-->
  <div class="h-[300px] flex flex-col items-center justify-evenly w-[220px] rounded-md shadow-md shadow-black bg-white ">
     <img class="h-20" src="data:image/webp;base64,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" alt="">
     <h1 class="font-semibold text-lg">T-Shirt</h1>
     <p class="pl-3 p-1 text-[12px] font-light">A T-shirt is a comfortable and casual piece of clothing worn by people of all ages.</p>
     <h2 class="font-bold ">₹299</h2>
    <div class="m-1 flex gap-3 text-lg ">
    <i class="text-orange-400 ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i><i class="ri-star-fill"></i>
     </div>
     <i class="border-2 text-blue-400 bg-blue-100 h-6 w-6 rounded-md cursor-pointer  border-blue-400  ri-add-line"></i>
    <div class="btnBox flex gap-2">
     <button class="btn1 text-white font-bold bg-red-500 p-2 w-full rounded-md">Add to Cart</button>
     <button class="btn2 hidden text-white font-bold bg-red-500 p-2 rounded-md">Undo</button>
  </div>
  </div>

</section>

<script>
  
let icons = document.querySelectorAll("i");
let buttons = document.querySelectorAll(".btn1");
let undoButtons = document.querySelectorAll(".btn2");
let textcount = document.querySelector(".textcount");

let count = 0;

// har card ke liye status store
let added = Array(buttons.length).fill(false);

buttons.forEach((btn, index) => {
  btn.addEventListener("click", function () {

    // agar already added hai to kuch na karo
    if (added[index]) return;

    added[index] = true;
    count++;
    textcount.innerHTML = count;

    btn.classList.add("bg-blue-500", "text-white", "w-[130px]");
    btn.innerHTML = "Added to Cart";

    undoButtons[index].classList.remove("hidden");
  });
});
  // oudo Button k liye
undoButtons.forEach((btn2, index) => {
  btn2.addEventListener("click", function () {

    if (!added[index]) return;

    added[index] = false;
    count--;
    textcount.innerHTML = count;

    let btn1 = buttons[index];
    btn1.classList.remove("bg-blue-500", "w-[130px]");
    btn1.classList.add("bg-red-500");
    btn1.innerHTML = "Add to Cart";

    btn2.classList.add("hidden");
  });
});

// icons star k liye 
let iconAdded = Array(icons.length).fill(false);

icons.forEach((icon, index) => {
  icon.addEventListener("click", function () {

    iconAdded[index] = !iconAdded[index];

//     for(let i = 0; i<=iconAdded[index]; i++){
//        icon.classList.add("text-orange-400");
// }
    if (iconAdded[index]) {
      icon.classList.add("text-orange-400");
    } else {
      icon.classList.remove("text-orange-400");
    }
  });
});

                // input search k liye 
  
  let searchInput = document.querySelector("input");
let searchBtn = document.querySelector("button");
let cards = document.querySelectorAll("section > div");

searchBtn.addEventListener("click", function () {
  let value = searchInput.value.toLowerCase();

  cards.forEach((card) => {
    let title = card.querySelector("h1").innerText.toLowerCase();

    if (title.includes(value)) {
      card.style.display = "flex"; // show
    } else {
      card.style.display = "none"; // hide
    }
  });
});

</script>


 
</body>
</html>
