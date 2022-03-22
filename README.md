# javascipt-groupby

🎉 { number: [ 1, 3 ], string: [ '2', '4' ] }
console.log(groupBy([1, '2', 3, '4'], (val) => typeof val));

🎉 { '1': [ [ 1 ], [ 3 ] ], '2': [ [ 1, 2 ], [ 3, 4 ] ] }
console.log(groupBy([[1], [1, 2], [3], [3, 4]], (val) => val.length));
