
### Filter Array A bằng các phần tử của Array B, nếu tồn tại thì bỏ qua, không có thì thêm vào Array A

const beasts = ['ant', 'bison', 'camel', 'duck', 'bison'];
const beasts_2 = ['ant', 'cong']


beasts_2.forEach(item => {
if (beasts.indexOf(item) < 0){
  beasts.push(item)}
  else {console.log("Item Exists")}
})
console.log(beasts)

beasts.forEach(item => {
  console.log(item + beasts.length)
})