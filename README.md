# JavascriptEventLoop

This repro is here to reproduce a bug chrome has in the JS event loop.

Instruction:
- Open index.html
- click on the page
- look at the logs and compare them with the other browsers.

I Chrome the rendering happens only when the task queue is exhausted. In other Firefox and Edge the rendering has higher priority that the tasks already queued
