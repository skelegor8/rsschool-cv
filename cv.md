# Egor Shkel

### Junior Frontend Developer

* * *

### Contact information:

- Phone: +48 571 426 960

* * *

### About Myself:

* * *

### Skills and Proficiency:

* * *

### Code example:

**Let's Recycle! KATA from CODEWARS:** You will be given a list of objects. Each object has type, material, and possibly secondMaterial. The existing materials are: paper, glass, organic, and plastic. Your job is to sort these objects across the 4 recycling bins according to their material (and secondMaterial if it's present), by listing the type's of objects that should go into those bins.

```JavaScript
function recycle(array) {
  let paper = [];
  let glass = [];
  let organic = [];
  let plastic = [];
  let recyclingBins = ["paper", "glass", "organic", "plastic"];
  let resultRecycle = [paper, glass, organic, plastic];

  for (let i = 0; i < recyclingBins.length; i++) {
    for (let j = 0; j < array.length; j++) {
      if (array[j].material == recyclingBins[i] | array[j].secondMaterial == recyclingBins[i]) {
        resultRecycle[i].push(array[j].type);
      }
    }
  }
  return resultRecycle;
}
```

* * *

### My Projects:

This is part of the assignments I did on The Rolling Scopes courses:

- https://skelegor8.github.io/rsschool-tasks/rsschool-tasks-deploy/portfolio/
- https://skelegor8.github.io/rsschool-tasks/rsschool-tasks-deploy/shelter/pages/main/
- https://skelegor8.github.io/rsschool-tasks/rsschool-tasks-deploy/image-galery/
- https://skelegor8.github.io/rsschool-tasks/rsschool-tasks-deploy/tic-tac-toe/
- https://skelegor8.github.io/rsschool-tasks/rsschool-tasks-deploy/cssMemSlider/

Trying to create a "MineSweeper" game in JS:

- https://skelegor8.github.io/minesweeper/

* * *

### Courses:

* * *

### Languages: