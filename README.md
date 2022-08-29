# myCodewars
there will be my code wars solutions. js language;


// the feast of many beasts -->

function feast(beast, dish) {
   return beast[0] === dish[0] && beast[beast.length - 1] === dish[dish.length - 1] ? true : false;
}

// thinkful - logic drills: traffic lights

function updateLight(current) {
  
  if (current === "green") {
    return "yellow";
  } else if (current === "yellow") {
    return "red";
  } else if (current === "red") {
    return "green";
  }
}

// count by X

function countBy(x, n) {
  let z = [];
for (let i = 1; i <= n; i++) {
  z.push(x * i);
}
  return z;
}
