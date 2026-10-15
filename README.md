# Physics

Interactive physics simulation labs for intro college physics. Each lab is a single self-contained web page that runs in any modern browser.

## Labs

| Lab | Topic | Open |
| --- | --- | --- |
| [Gravity Force Lab](gravity-lab/) | Newton's law of universal gravitation | [Launch](https://neogio73.github.io/Physics/gravity-lab/) |

### Gravity Force Lab

A 3D bench (three.js) with two masses on a meter rail. Students drag the masses, set them from 1 to 1000 kg, and read the force each one feels, in scientific or decimal notation. They can record trials to a data log (copy as CSV) and work through the four handout questions. Answers are submitted in the Lab Quiz on the course website.

## Running locally

Open `gravity-lab/index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000/gravity-lab/.
