# time-tracker
Track and record time spent on tasks.

## How to run
First, build the project:
```bash
npm run build
```
Go to `chrome://extensions`, enable `Developer mode`. Lastly, `Load unpacked` and point it to the 
`build` directory. You can open the extension from the menu.

## TODO
Stages define a progression. Do not skip an unfinished stage! If you pick a task, link issue or PR.
### Stage 1. :checkered_flag: <!--- https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#symbols -->
 * [x] -- init project [#1](https://github.com/revolko/time-tracker/issues/1)

### Stage 2. :fire:
 * [ ] -- frontend (desing and implementation)
 * [ ] -- tracking logic (task, project, tag, start, end)
 * [ ] -- synchronization with google sheet (upload and download)
 * [ ] -- display current task duration
 * [ ] -- display todays sum of tasks

### Stage 3. :stop_sign:
 * [ ] -- record fix logic
 * [ ] -- advanced sync (dealing with conflicts, usefull for fixes)

### Nice to have :rainbow:
 * [ ] -- browse past records (week, month, year)
