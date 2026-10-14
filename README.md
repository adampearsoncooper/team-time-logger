# Team Time Logger

A single static page with no build step and no dependencies. Advisers are rows
and tasks are columns. Click a box to start a timer, and click it again to stop
and log it. You can export the log as a CSV, or copy it and paste it straight
into Excel.

Everything is saved in the browser's localStorage, so it survives a refresh,
but each device and browser keeps its own log. It isn't shared across the team.

## Deploy on Vercel

Add New → Project → import this repo. Leave Framework Preset as **Other**, with
no build command and no output directory, then click Deploy.
