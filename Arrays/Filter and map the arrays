const movies = [
  { title: "a", year: 2018, ratting: 4.5 },
  { title: "b", year: 2018, ratting: 4.7 },
  { title: "c", year: 2018, ratting: 3 },
  { title: "d", year: 2017, ratting: 4.5 },
];
//all the movies in 2018 with rating>4
//sort them by their rating
//descending order
//pick their title
//'b'
//'a'
let newMovies = [...movies];
const abc = movies
  .filter((m) => m.year == "2018" && m.ratting > 4)
  .sort((a, b) => {
    if (a.title < b.title) return 1;
    if (a.title > b.title) return -1;
    return 0;
  })
  .map((m) => m.title);
console.log(abc);
