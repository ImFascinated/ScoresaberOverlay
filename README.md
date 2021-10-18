# ScoresaberOverlay
Simple OBS overlay for scoresaber

# Setup
Add a OBS browser and use the following config:</br>
`file:\\\<file path>\ScoresaberOverlay\index.html`

# Config
Put your scoresaber id in the html file under `OPTIONS`</br>
If you wish to not show any comparisions make the `comparison_ids` array empty with `[]`

```js
const OPTIONS = {
  scoresaber_api: "https://new.scoresaber.com/api/",
  my_scoresaber: "76561198449412074",

  // who to compare your scores with o.O
  comparison_ids: [
    "76561198858351567",
    "76561198389705676"
  ]
}
