<h1 align="center">Devapriyan Sampath</h1>

<p align="center">
  <strong>Machine Learning Engineer</strong><br>
  I build ML tools that work on data they've never seen before.
</p>

<p align="center">
  <a href="https://devapriyan-s.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/portfolio-devapriyan--s.github.io-39d6d0?style=for-the-badge"></a>
  <a href="https://www.linkedin.com/in/deva-priyan-sampath-2091a7288/"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:devapriyan1723@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-devapriyan1723%40gmail.com-7c5ce0?style=for-the-badge"></a>
</p>

---

### Eleven projects. All live. None of them hardcode a dataset.

You bring your own CSV and they figure it out. Most run real Python —
scikit-learn, statsmodels, scipy — compiled to WebAssembly in your browser, so
there's no server to wake up, nothing to sign up for, and nothing you upload
ever leaves your machine.

| Project | What it does | Try it |
|---|---|:--:|
| **[AutoML Studio](https://github.com/Devapriyan-S/automl-studio)** | Infers column types, detects the task, builds the pipeline, trains a model family — on any CSV | [demo](https://devapriyan-s.github.io/automl-studio/) |
| **[Drift Detector](https://github.com/Devapriyan-S/data-drift-detector)** | PSI, KS and chi-square between two data snapshots, ending in one actionable verdict | [demo](https://devapriyan-s.github.io/data-drift-detector/) |
| **[A/B Test Analyzer](https://github.com/Devapriyan-S/ab-test-analyzer)** | Significance, power and Bayesian P(B&gt;A) — statistics validated against scipy on 464 cases | [demo](https://devapriyan-s.github.io/ab-test-analyzer/) |
| **[Time Series Forecaster](https://github.com/Devapriyan-S/timeseries-forecaster)** | Eight models scored by walk-forward validation against naive baselines | [demo](https://devapriyan-s.github.io/timeseries-forecaster/) |
| **[Clustering Explorer](https://github.com/Devapriyan-S/clustering-explorer)** | Finds segments, then checks them against a shuffled null | [demo](https://devapriyan-s.github.io/clustering-explorer/) |
| **[Digit Recognizer](https://github.com/Devapriyan-S/digit-recognizer)** | 97.58% on held-out MNIST, running as a 40-line forward pass in plain JavaScript | [demo](https://devapriyan-s.github.io/digit-recognizer/) |
| **[EDA Report](https://github.com/Devapriyan-S/eda-report)** | Ranked findings plus associations `df.corr()` cannot see; exports one self-contained HTML file | [demo](https://devapriyan-s.github.io/eda-report/) |
| **[Dataset Explorer](https://github.com/Devapriyan-S/dataset-explorer)** | Opens a 100,000-row CSV in 461 ms and scrolls it at 60 fps | [demo](https://devapriyan-s.github.io/dataset-explorer/) |
| **[Chart Studio](https://github.com/Devapriyan-S/chart-studio)** | Seven chart types as hand-written SVG, with SVG and PNG export | [demo](https://devapriyan-s.github.io/chart-studio/) |
| **[Gesture Drive](https://github.com/Devapriyan-S/gesture-drive)** | Steer a car with your index finger — MediaPipe plus a One Euro filter tuned against a jitter-matched EMA | [demo](https://devapriyan-s.github.io/gesture-drive/) |
| **[Expression Reader](https://github.com/Devapriyan-S/expression-reader)** | Teach a face-expression classifier your own face in ten seconds — softmax regression written from scratch, trained in the browser | [demo](https://devapriyan-s.github.io/expression-reader/) |

---

### How I work

**The model is the easy part.** Calling `.fit()` is four characters. What
decides whether a project works is everything around it — and each of these got
the wrong answer at some point, producing *plausible output rather than an
error*:

- Is an all-unique integer column an ID, or a rounded price? (Getting it wrong
  turned a regression into a nonsense 4-class problem.)
- Does `resample().sum()` return `0` or `NaN` for a month with no sales?
  (It returns `0`, so three missing months became a revenue collapse that never
  happened.)
- Is `01/02/2023` January 2nd or February 1st? (pandas parses both happily, so
  counting successful parses cannot tell them apart.)

**A number nobody checked is a guess.** The A/B analyser's distribution
functions are validated against `scipy` on 464 committed cases at 1e-12. The
digit recognizer's JavaScript forward pass matches its NumPy original to
4.77e-6. Writing those checks is where most of the bugs turned up — including
`normCdf(-20)` returning `0` instead of `2.75e-89`.

**Say when the answer is weak.** k-means will happily partition pure noise. A
40-row dataset will report 94% cross-validated accuracy and 56% on held-out
data. A test checked twenty times has a 64% false-positive rate, not 5%. These
tools say so, in plain language, at the point where you'd otherwise draw the
wrong conclusion.

---

### Tools

`Python` · `scikit-learn` · `pandas` · `NumPy` · `SciPy` · `statsmodels` · `FastAPI`
<br>
`Computer vision` · `MediaPipe` · `Signal processing` · `Canvas`
<br>
`JavaScript` · `SVG` · `Canvas` · `Web Workers` · `Pyodide / WebAssembly`
<br>
`Git` · `GitHub Actions` · `Playwright` · `Docker`

---

<p align="center">
  <a href="https://devapriyan-s.github.io/"><strong>See all eleven projects →</strong></a>
  <br><br>
  <sub>
    <a href="https://www.linkedin.com/in/deva-priyan-sampath-2091a7288/">LinkedIn</a> ·
    <a href="mailto:devapriyan1723@gmail.com">devapriyan1723@gmail.com</a>
  </sub>
</p>
