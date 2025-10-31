<%*
const fileName = tp.file.title;
const date = moment(fileName, "DD-MM-YYYY"); 
const day = date.day();

const focusMap = {
  1: "Monday — ",
  2: "Tuesday — ",
  3: "Wednesday — ",
  4: "Thursday — ",
  5: "Friday — ",
  6: "Saturday — ",
  0: "Sunday — "
};

const focus = focusMap[day] || "Day — any theme";
tR += `### Today's Focus\n${focus}\n`;
%>
### Tasks
- [ ] 
### Notes
- 