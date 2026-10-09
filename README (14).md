# Matching AI to the Problem

An interactive class session on how to choose the right kind of AI for a problem. Students work through 26 screens in a browser. Thirteen of the screens have a 3D chart the student controls.

The whole session is one HTML file. There is nothing to install and nothing to build.

**Open it:** `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## What it teaches

A four-step method:

1. **Name the problem type.** Classification, regression, clustering, anomaly detection, recommendation, or generation.
2. **Plan with a framework.** The AI Canvas and CRISP-DM, with one case study carried through both.
3. **Match the technology.** Structured and unstructured data, neural network depth, how GenAI makes new content, and four real-world limits.
4. **Judge success by the industry.** The same technology built three ways, language AI in two industries, and six patterns behind successful projects.

## The session

| Segment | Minutes | What happens |
| --- | --- | --- |
| Welcome | 5 | The plan and a warm-up question |
| The Loop | 30 to 45 | Each student describes an AI system from an article they read |
| Lecture | 40 to 55 | 16 screens. Students read, use the controls, and type answers |
| Break | 10 | |
| Escape room | 60 | A separate team game. This page gives the briefing and the link |
| Projects and capstone | 15 | Deadlines, a grade calculator, and a finished example paper |
| Wrap | 5 | Checklist for the week |

The Loop and the lecture share 85 minutes. A longer Loop means a shorter lecture.

## For students

1. Open the link, or download `index.html` and open it in a browser.
2. Use **Next** and **Back**, or the arrow keys.
3. Follow the **Do this** steps on each screen.
4. Drag any 3D chart to turn it.

What you type is saved in your own browser. It is not sent anywhere. Clearing your browser data erases it.

## For the instructor

Press **Instructor view** on the bottom bar. It shows controls that students do not see:

- **Class setup** on the first screen: start time, minutes for the Loop, and the escape room link.
- **The Loop:** a speaker timer, Next speaker, Pick at random, and a class list. Click a seat on the ring to choose a student.
- **Break:** a ten-minute countdown.
- **Class list** on the "Which problem type is your system?" screen.

Instructor settings are saved in your browser only.

### Change the class list

**On the page.** Open the Loop screen in Instructor view. Open "Set up the Loop." Type the names, one per line. This lasts in that browser only.

**In the file.** Open `index.html` in a text editor and search for `var ROSTER`. Replace the names. Keep each name in single quotes, with commas between them:

```js
var ROSTER=['Name one','Name two','Name three'];
```

To use numbered seats instead of names, empty the list:

```js
var ROSTER=[];
```

## Requirements

- A current browser: Chrome, Edge, Firefox, or Safari.
- An internet connection. The page loads its 3D library and fonts from the web. Without a connection the text and questions still work, but the charts do not appear.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole session |
| `README.md` | This page |

## Notes on the content

- The housing maintenance office and Bayside Family Dental are made-up examples written for teaching. Their numbers are not real data.
- The real cases named on the screens are Amazon's hiring tool, a hospital sepsis warning system, Zillow's home-buying program, JPMorgan's COIN, IDx-DR, and PlantVillage Nuru.
- The example paper cites Samorani, Harris, Blount, Lu, and Santoro (2022), "Overbooked and Overlooked: Machine Learning and Racial Bias in Medical Appointment Scheduling."

## Author

Cynthia McGinnis
