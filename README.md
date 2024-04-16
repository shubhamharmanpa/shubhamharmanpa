// let name="shubham"

// let stringvalues=String(name)
// console.log(typeof stringvalues)

// var name="shubham"
// var recount = 50

// console.log("shubham ${name} this is largest number")

// var shub=new String("harmans")

// console.log(shub[0])
// console.log(shub.length)
// console.log(shub.toUpperCase())

// var newshub=shub.substring(0,6)
// console.log(newshub)

// var shub1=" trim  "
// console.log(shub1)
// console.log(shub1.trim())

// var url="shubham.23.com"
// console.log(url.replace("shubham","harman"))
// console.log(url.includes("shubham"))

// number and math

// var number1=300

// console.log(number1)

// var shub=new Number(100)
// console.log(shub)

// console.log(shub.toString().length);
// console.log(shub.toFixed(2));

// var counr=1000000
// console.log(counr.toLocaleString('en-IN'));


// -------maths------------------
// console.log(Math);
// console.log(Math.max(12,45));
// console.log(Math.sqrt(10));

// console.log(Math.random);
// console.log(Math.random()*10);
// console.log(Math.floor(Math.random()*10)+1);

// var max=20
// var min=10

// console.log(Math.floor(Math.random()*(max - min + 1 )) + min);


// -------------------- date and time --------------------------
// var mydate = new Date()
// console.log(mydate.toString())
// console.log(mydate.toLocaleDateString())
// console.log(mydate.toISOString())
// console.log(typeof mydate)

// var create=new Date("07-06-2004")
// console.log(create.getTime());
// console.log(Math.floor(Date.now()/1000))

// console.log(create.toLocaleString('default',{
//     weekday:"long"
// }));

// ------------------ Array------------

var hello=[1,2,3,4,5]
var mymom=["father","mother","brother"]
var my=["hello","hii","how are you"]
// console.log(hello[0]);
// hello.push(4)
// hello.unshift(7)
// console.log(hello);
// // console.log(hello.includes(10));

// var myarr= hello.join()
// console.log(myarr);

// console.log("A", hello);
// var myarr1=hello.slice(1,4)
// console.log(myarr1);
// console.log("B", hello);

// var myarr2=hello.splice(1,4)
// console.log("C", hello);
// console.log(myarr2);

// // mymom.push(my)
// // console.log(mymom);

// var home1=mymom.concat(my)
// console.log(home1);

// var another_array = [1,2,3[4,5,6],7,8[1,2],5,6]

// var realnumber= another_array.flat(Infinity)
// console.log(realnumber);

// console.log(Array.isArray("shubham"));
// console.log(Array.from("shubham"));


// ------------------- object -----------------
// var sym= Symbol("key1")
// var obejct1={
//     name:"shubham",
//     [sym]:"key",
//     age:24,
//     email:"shubhamkashwala121@gmall.com",
//     phonenumber:992558600
// }
// console.log(obejct1.name);
// console.log(obejct1["email"])
// console.log(typeof obejct1[sym]);

// obejct1.email="shubhamkashwala12@chatgpt.com"
// Object.freeze(obejct1)

// obejct1.email="shubhamkashwala12@chat.com"
// console.log(obejct1);


// var tinderuser = {}
// tinderuser.id="shu123"
// tinderuser.name="shubham"
// tinderuser.isLoggedIn = false

// // console.log(tinderuser);

// var regularuser={
//     email:"shubhamkashwala2@gmail.com",
//    fullname: {
//         userfullname:{
//             firstname:"shubham",
//             lastname:"kashwala"
//         }
//     }
// }

// console.log(regularuser.fullname);

// var ob1={1:"a", 2: "b"}
// var ob2={3:"a", 4: "b"}
// // var ob3=Object.assign(ob1,ob2)
// var ob3={...ob1,...ob2}
// console.log(ob3);

// var user=[
//     {
//         id:"121",
//         name:"shubham"
//     },{
//         id:"121",
//         name:"shubham"
//     },
//     {
//         id:"121",
//         name:"shubham"
//     }
// ]
// user[1].name;
// console.log(Object.keys(tinderuser));

var name={
    ID:"123",
    Name:"shubham"
}

var {Name}= name
console.log(Name);

//randomer user me is api website and json formatter
