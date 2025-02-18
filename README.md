# home-work

// minutni soniyaga otqizish

// let sec = Number(prompt("soniya kirit"))

// let org_min = Math.floor(sec / 60)
// let org_sec = sec % 60
// console.log(`${org_min}:${org_sec}`)

//TODO 1-chisi

// let arr = [7,4,1,9,5]

// function re_0(arr){
//     return arr[0]
// }
// console.log(re_0(arr))

//TODO 2-chisi

// let arr = [7,4,9,1,6, 5]

// function onlyEven(arr){
//     return arr.filter(num => num % 2 == 0)
// }
// console.log(onlyEven(arr))

//TODO 3-chisi

// let arr = [7,4,9,1,6, 5]

// function upBy1(arr){
//     for(let i = 0; i < arr.length; i++){
//         arr[i]+=1
//     }
//     return arr
// }
// console.log(upBy1(arr))

//TODO 4-chisi

// let arr = [7,4,1,9,5]

// function reLast(arr){
//     return arr[arr.length - 1]
// }
// console.log(reLast(arr))

//TODO 5-chisi

// let arr = [7,4,1,9,5]
// let t = 1

// function findIt(arr, target){
//     for(let i = 0; i < arr.length;i++){
//         if(arr[i] === target){
//             return i
//         }
//     }
//     return -1
// }
// console.log(findIt(arr, t))

//TODO 6-chisi

// let arr = [7,4,9,1,6,5]

// function sum(arr){
//     result = 0
//     for(let i = 0; i < arr.length;i++){
//         result += arr[i]
//     }
//     return result
// }
// console.log(sum(arr))

//TODO 7-chisi
// let money = 10000

// function divider(money){
//     let divIt = {
//         "ilm": Math.round(money/0.5),
//         "xarajat": Math.round(money/0.3),
//         "kelajak": Math.round(money/0.2)
//     }
//     return divIt 
// }

// console.log(divider(money))

//TODO 8-chisi

// let Arr = [1, 5, 95, 0, 4, 7]
// let num1 = 3
// let num2 = 8

// function betweenArr(n1, n2, arr){
//     return arr.filter(num => num >= n1 && num <= n2)
// }
// console.log(betweenArr(3,8,Arr))

//TODO 9-chisi

// let Arr = [1, 5, 95, 0, 4, 7]
// let num1 = 4

// function inIt(arr, num){
//     return arr.indexOf(num) 
// }
// console.log(inIt(Arr, num1))

//TODO 10chisi

// let diffArr =  [1, 2, "salom"]

// function showType(arr){
//     let resArr = []
//     for(let i = 0; i < arr.length;i++){
//         resArr.push(typeof arr[i])
//     }
//     return resArr
// }
// console.log(showType(diffArr))

//TODO 11-chisi

// let arr = [1, 2, 3, 4, 5, 6];

// function sumEvenOdd(arr) {
//     let evenSum = 0;
//     let oddSum = 0;

//     for (let i = 0; i < arr.length; i++) {
//         if (i % 2 === 0) {
//             evenSum += arr[i];
//         } else {
//             oddSum += arr[i];
//         }
//     }
//     return [evenSum, oddSum];
// }
// const result = sumEvenOdd(arr)
// console.log(result[0])
// console.log(result[1])

//TODO 12-chisi

let word = "helllo word! nma gap?"

function delSpaces(sentence){
    return sentence.split("").filter(let => let !== " ").join("")
}
console.log(delSpaces(word))
