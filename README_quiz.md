# MCS4204 Interactive MCQ (Lectures 1–3)

An offline, self-contained quiz you can open in any modern browser.

## Open

- Double-click `interactive_quiz.html` to open it in your default browser, or right-click and open with Chrome/Edge/Firefox.

## Use

- Select topics (L1–L3), set question count, and toggle options:
  - `Immediate feedback` – see correct/wrong instantly.
  - `Shuffle answers` – randomize option order.
  - `Include dynamic generators` – unlimited variants (EVM, PERT, NPV, channels, risk PI, COQ).
  - `Timer` – track time (aggregate shown automatically).
- Click `Start Quiz`.
- Navigate with `Prev`/`Next`. Click `Finish` to see summary and review incorrect answers.
- `Export History (CSV)` will download your attempt history saved in localStorage (browser storage).

## Notes

- Everything runs locally; no internet required. History is stored in your browser on this machine.
- If double-click doesn’t open, drag the file into a browser window.
- To reset history, clear your browser site data for `file://` or use the browser dev tools localStorage key `mcs4204_quiz_history_v1`.

## Extend

- The code contains a `staticBank` and multiple `generators`. Add more static questions or new generators to expand coverage.
