function findMinMax(add) {
  return {
    min: Math.min(...add),
    max: Math.max(...add)
  };
}
const numbers = [3, 4, 10, 25, 7, 2, 8];
console.log(findMinMax(numbers));
