db.bands.insertOne({
  name: "Bon Jovi",
  country: "EEUU",
  url: "https://www.bonjovi.com/",
  albums: [
    {
      title: "Bon Jovi",
      dateCreated: new Date(1984, 0, 21),
      songs: [
        { title: "Runaway", author: ["Bon Jovi"], duration: 230 },
        { title: "Roulette", author: ["Bon Jovi"], duration: 280 },
        { title: "She Don't Know Me", author: ["Bon Jovi"], duration: 238 },
        { title: "Shot Through The Heart", author: ["Bon Jovi"], duration: 258 },
        { title: "Love Lies", author: ["Bon Jovi"], duration: 248 },
        { title: "Breakout", author: ["Bon Jovi"], duration: 322 }
      ]
    },
    {
      title: "Keep The Faith",
      dateCreated: new Date(1992, 10, 3),
      songs: [
        { title: "I Believe", author: ["Bon Jovi"], duration: 348 },
        { title: "Keep The Faith", author: ["Bon Jovi"], duration: 347 },
        { title: "I'll Sleep When I'm Dead", author: ["Bon Jovi"], duration: 283 },
        { title: "In These Arms", author: ["Bon Jovi"], duration: 319 },
        { title: "Bed Of Roses", author: ["Bon Jovi"], duration: 394 }
      ]
    }
  ]
})

db.bands.insertMany([
  {
    name: "Guns N' Roses",
    country: "Estados Unidos",
    url: "https://www.gunsnroses.com/",
    albums: [
      {
        title: "Appetite for Destruction",
        dateCreated: new Date(1987, 6, 21),
        songs: [
          { title: "Welcome to the Jungle", author: ["Guns N' Roses"], duration: 273 },
          { title: "It's So Easy", author: ["Guns N' Roses"], duration: 203 },
          { title: "Nightrain", author: ["Guns N' Roses"], duration: 268 },
          { title: "Mr. Brownstone", author: ["Guns N' Roses"], duration: 229 },
          { title: "Paradise City", author: ["Guns N' Roses"], duration: 406 }
        ]
      },
      {
        title: "Use Your Illusion II",
        dateCreated: new Date(1991, 8, 18),
        songs: [
          { title: "Civil War", author: ["Guns N' Roses"], duration: 460 },
          { title: "Yesterdays", author: ["Guns N' Roses"], duration: 197 },
          { title: "Knockin' On Heaven's Door", author: ["Guns N' Roses"], duration: 335 },
          { title: "Estranged", author: ["Guns N' Roses"], duration: 562 },
          { title: "You Could Be Mine", author: ["Guns N' Roses"], duration: 343 }
        ]
      }
    ]
  },
  {
    name: "Soda Stereo",
    country: "Argentina",
    url: "https://sodastereo.com/",
    albums: [
      {
        title: "Canción Animal",
        dateCreated: new Date(1990, 9, 9),
        songs: [
          { title: "(En) El Séptimo Día", author: ["Soda Stereo"], duration: 264 },
          { title: "Un Millón De Años Luz", author: ["Soda Stereo"], duration: 305 },
          { title: "Canción Animal", author: ["Soda Stereo"], duration: 248 },
          { title: "De Música Ligera", author: ["Soda Stereo"], duration: 213 },
          { title: "Cae El Sol", author: ["Soda Stereo"], duration: 263 }
        ]
      },
      {
        title: "Signos",
        dateCreated: new Date(1986, 9, 9),
        songs: [
          { title: "El Rito", author: ["Soda Stereo"], duration: 366 },
          { title: "Prófugos", author: ["Soda Stereo"], duration: 318 },
          { title: "Persiana Americana", author: ["Soda Stereo"], duration: 292 },
          { title: "En Camino", author: ["Soda Stereo"], duration: 270 },
          { title: "Signos", author: ["Soda Stereo"], duration: 315 }
        ]
      }
    ]
  },
  {
    name: "Avril Lavigne",
    country: "Canada",
    url: "https://www.avrillavigne.com/",
    albums: [
      {
        title: "Let Go",
        dateCreated: new Date(2002, 5, 4),
        songs: [
          { title: "Losing Grip", author: ["Avril Lavigne"], duration: 234 },
          { title: "Complicated", author: ["Avril Lavigne"], duration: 245 },
          { title: "Sk8er Boi", author: ["Avril Lavigne"], duration: 204 },
          { title: "I'm With You", author: ["Avril Lavigne"], duration: 223 },
          { title: "Things I'll Never Say", author: ["Avril Lavigne"], duration: 224 }
        ]
      },
      {
        title: "The Best Damn Thing (Expanded Edition)",
        dateCreated: new Date(2007, 3, 17),
        songs: [
          { title: "Girlfriend", author: ["Avril Lavigne"], duration: 217 },
          { title: "When You're Gone", author: ["Avril Lavigne"], duration: 241 },
          { title: "Hot", author: ["Avril Lavigne"], duration: 204 },
          { title: "Innocence", author: ["Avril Lavigne"], duration: 232 },
          { title: "The Best Damn Thing", author: ["Avril Lavigne"], duration: 190 }
        ]
      }
    ]
  },
  {
    name: "Green Day",
    country: "Estados Unidos",
    url: "https://www.greenday.com/",
    albums: [
      {
        title: "Dookie",
        dateCreated: new Date(1994, 1, 1),
        songs: [
          { title: "Basket Case", author: ["Green Day"], duration: 181 },
          { title: "When I Come Around", author: ["Green Day"], duration: 178 },
          { title: "Longview", author: ["Green Day"], duration: 233 },
          { title: "She", author: ["Green Day"], duration: 134 },
          { title: "Welcome to Paradise", author: ["Green Day"], duration: 224 }
        ]
      },
      {
        title: "American Idiot",
        dateCreated: new Date(2004, 8, 21),
        songs: [
          { title: "American Idiot", author: ["Green Day"], duration: 174 },
          { title: "Boulevard of Broken Dreams", author: ["Green Day"], duration: 260 },
          { title: "Holiday", author: ["Green Day"], duration: 232 },
          { title: "Wake Me Up When September Ends", author: ["Green Day"], duration: 285 },
          { title: "Jesus of Suburbia", author: ["Green Day"], duration: 548 }
        ]
      }
    ]
  }
])

db.bands.updateOne(
  { name: "Bon Jovi" },
  {
    $unset: {
      "albums.$[].dateCreated": ""
    }
  }
)

db.bands.updateOne(
  {
    name: "Green Day",
    "albums.title": "Dookie"
  },
  {
    $unset: {
      "albums.$.songs": ""
    }
  }
)
