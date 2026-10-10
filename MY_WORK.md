# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | YAQOUB YOUSEF ALSHAMMARI  |
| **Student ID** | 442051059 |
| **University Email** | 442051059@std.psau.edu.sa |
| **GitHub Username** | YAQOUB-ALSHAMMARI |
| **Repository Link** | https://github.com/YAQOUB-ALSHAMMARI/OS-Assignment1-YAQOUB-ALSHAMMARI|
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [September 24, 2026, 4:00 PM]
**What I did**: Forked repository and configured student identity.

**Details**:
- Forked the starter repository to my GitHub profile and ensured visibility is Public.
- Cloned the repository and updated line 150 in `SchedulerSimulation.java` with my Student ID (`442051059`).
- Committed the initial configuration and verified the basic Round Robin execution flow.

**Challenges**: Locating the exact student ID print block among multiple ANSI color formatting strings.
**Solution**: Carefully searched for `studentID` in `SchedulerSimulation.java` and matched the string format.
**Time spent**: 40 minutes

---

### Entry 2 - [September 28, 2026, 6:30 PM]
**What I did**: Implemented Feature 1 (Process Priority).

**Details**:
- Added an integer field `priority` to the `Process` class.
- Implemented getter and setter methods (`getPriority()` and `setPriority(int priority)`).
- Assigned random priority values between 1 and 10 during process instantiation.
- Updated the ready queue print statement to include process priority in the output.

**Challenges**: Making sure the random generator generates numbers in the range 1-10 inclusive instead of 0-9.
**Solution**: Used `random.nextInt(10) + 1` to strictly cover the range 1 to 10.
**Time spent**: 50 minutes

---

### Entry 3 - [October 3, 2026, 5:15 PM]
**What I did**: Implemented Feature 2 (Context Switch Counter).

**Details**:
- Declared a static variable `contextSwitchCount` initialized to zero.
- Incremented the counter each time a process thread is dispatched and starts executing.
- Added a console print statement at the end of the simulation to display total context switches.

**Challenges**: Determining the correct placement of the increment operation without counting interrupted empty polling attempts.
**Solution**: Placed the counter increment immediately before starting each process thread execution.
**Time spent**: 45 minutes

---

### Entry 4 - [October 7, 2026, 7:00 PM]
**What I did**: Implemented Feature 3 (Waiting Time, Turnaround Time, and Summary Table).

**Details**:
- Added `creationTime` and `finishTime` tracking variables to the `Process` class.
- Captured timestamps using `System.currentTimeMillis()` at process creation and completion.
- Maintained an `allProcesses` list to retain process references after the queue empties.
- Implemented formatted output printing a tabular summary of burst, waiting, and turnaround times.

**Challenges**: The queue clears after completion, which caused processes to be lost before printing the final table.
**Solution**: Stored instances in a separate `ArrayList<Process> allProcesses` at initialization so their statistics remain available.
**Time spent**: 1 hour 15 minutes

---

### Entry 5 - [October 10, 2026, 8:45 PM]
**What I did**: Final code verification, documentation, and GitHub Actions check.

**Details**:
- Tested all output formats and confirmed that formulas for Turnaround Time and Waiting Time compute correctly.
- Completed all sections of `MY_WORK.md` including student details and technical reflections.
- Pushed changes to GitHub and verified that automated checks passed with green checkmarks.

**Challenges**: Ensuring Markdown table formats and timestamps align accurately with commit history.
**Solution**: Double-checked repository files and Markdown preview in GitHub before finalizing.
**Time spent**: 45 minutes


## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: 4.5 hours

**Most challenging part**: Managing process references across execution cycles so that waiting times and final tabular metrics could be calculated accurately without losing terminated processes.

**Most interesting learning**:Understanding how multi-threading in Java simulates CPU time slicing and witnessing Round Robin scheduling mechanics in real-time console output.

**What I would do differently next time**:I would plan the extra data structures(like the persistent process list)before implementing the timing logic to save debugging time.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

Working on this assignment gave me practical insight into how Java represents concurrent tasks using the `Runnable` interface and `Thread` instances. I learned how `Thread.start()` asynchronously dispatches a process to begin execution independently. Simulating CPU bursts using `Thread.sleep()` clearly demonstrated how time slices are allocated to mimic real hardware scheduling. Using `Thread.join()` showed me how to synchronize and wait for a thread's completion before advancing the scheduler. What surprised me most was how thread state management reflects core operating system principles such as context switching and ready queue manipulation. Overall, it bridged the gap between theoretical operating system concepts and real Java multithreaded code.



## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part of this project was implementing Feature 3 to calculate waiting times and turnaround times correctly. Because processes were popped from the queue and terminated throughout the simulation, their data was initially lost before the summary table could be generated. I had to figure out how to maintain references to all process objects without altering the scheduling queue mechanism. In addition, capturing real execution timestamps using `System.currentTimeMillis()` required careful placement so waiting time formulas stayed accurate. Ensuring that the waiting time calculation never produced negative values due to slight timing variances was tricky. Overcoming this helped me understand how scheduling data persists independently of active CPU execution queues.


## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I overcame these technical hurdles by using an incremental development approach and testing each feature independently. Whenever an unexpected result appeared, I added targeted `System.out.println` debug statements to trace thread execution steps and verify queue contents. I carefully re-read the specifications in `README.md` to confirm the required output formats and arithmetic formulas. To solve the process reference loss, I created a dedicated `ArrayList` that stored every created process at initialization time. Testing small code changes repeatedly allowed me to isolate logic bugs before committing my changes to Git. This systematic troubleshooting strategy made finding and resolving runtime errors much easier.

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading concepts are fundamental across many modern software systems that require responsive multitasking. For instance, in a web browser, separate threads handle network requests, UI rendering, and user input simultaneously without freezing the interface. Video games rely heavily on multithreading to manage physics computations, AI decision-making, and audio streaming across different CPU cores in parallel. Similarly, music players use background threads to decode and buffer audio tracks while keeping the playback controls immediately responsive. In backend web servers, incoming HTTP requests are processed concurrently by assigning distinct worker threads from a thread pool. Applying these concepts demonstrated how real applications achieve smooth concurrency and high throughput.

### Optional: What would you like to learn more about?

I would like to explore thread synchronization primitives in depth, such as Semaphores, Mutex locks, and handling race conditions in concurrent data structures.


### Optional: How confident do you feel about multithreading concepts now?

Intermediate. I understand thread lifecycles, execution flow, and queue dispatching well, but I want more practice with advanced concurrency control and shared memory locks.

### Optional: Feedback on the assignment


The assignment was very well-structured and practical. Linking theoretical OS scheduling algorithms directly with runnable Java code made the concepts much clearer.


---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is an independent executing program with its own dedicated memory space, whereas a thread is a lightweight execution unit that shares code, data, and resources within the same process. In this assignment, our `Process` class is only a simulated model of an operating system task, executed internally by a real Java worker thread using `new Thread(process)` in `addProcessToQueue()`. We utilized Java threads rather than operating system processes because threads have significantly lower creation and destruction overhead. Additionally, threads share heap memory directly, which enables fast inter-thread communication and allows our scheduler to easily manage task states and shared queues.

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, when a process does not complete its burst time within the allocated time quantum, the CPU preempts it, saves its remaining execution state, and places it back at the tail of the ready queue[span_4](start_span)[span_4](end_span). This cycle repeats until the remaining burst time reaches zero or the process becomes the final active task[span_5](start_span)[span_5](end_span). Re-queueing is vital for system fairness because it prevents long processes from monopolizing the CPU, ensuring every ready task receives balanced processing time[span_6](start_span)[span_6](end_span).

Example from my output:
```
Process P3 is running for 1000 ms (Remaining: 2500 ms)
Process P3 paused. Added back to ready queue.
Process P3 is running for 1000 ms (Remaining: 1500 ms)
Process P3 paused. Added back to ready queue.
Process P3 is running for 1000 ms (Remaining: 500 ms)
Process P3 paused. Added back to ready queue.
Process P3 is running for 500 ms (Remaining: 0 ms)
Process P3 finished execution.

```

**Explanation of example:**
In this output trace, process P3 had an initial burst time greater than the time quantum (1000 ms). Because it could not finish in a single round, it was interrupted and re-queued three times via `addProcessToQueue()` until its remaining burst time was fully consumed.


## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*
In our simulation, a process thread transitions through multiple lifecycle states managed by the Java Virtual Machine. It starts in the New state upon instantiation, enters Runnable when queued, and moves to Running once the scheduler dispatches it. If interrupted or paused to simulate work, it enters Waiting/Timed-Waiting, and finally reaches Terminated when its execution completes.


1. **New**: When the thread instance is created via `Thread thread = new Thread(process)` inside the `addProcessToQueue()` method before `thread.start()` is invoked.


2. **Runnable**: When `thread.start()` is called by the scheduler loop, making the thread ready and eligible to be dispatched by the JVM thread scheduler.


3. **Running**: When the operating system allocates CPU execution time to the thread and it actively executes code inside the `process.run()` or `runToCompletion()` method.


4. **Waiting**: The process thread enters a timed waiting state during `Thread.sleep()` to simulate CPU execution, while the main thread waits for the process thread to finish via `thread.join()`.



5. **Terminated**: When the thread finishes executing all code in its `run()` method and its call stack completes, marking the simulated execution burst or full lifetime as finished.



## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): Multitasking OS CPU Scheduling 

**Description**:
In modern desktop and server operating systems like Linux and Windows, multiple user applications run concurrently on limited processor cores. The OS thread scheduler allocates small execution time slices to ready threads so all active applications appear to execute simultaneously.


**Why Round-Robin works well here**:
Round-Robin provides guaranteed fairness by preventing CPU-heavy background tasks from monopolizing the processor. It keeps interactive GUI applications and input listeners responsive, ensuring predictable progress for all active processes.

### Example 2: web Server Request Processing (e.g., Apache / Nginx)

**Description**:

High-traffic web servers handle thousands of concurrent client HTTP connections using worker thread pools. Incoming requests are queued and granted execution time chunks to process data, query databases, and stream responses back to clients.




**Why Round-Robin works well here**:
Round-Robin ensures responsiveness by preventing large file downloads from blocking quick API calls or lightweight page requests. It distributes bandwidth and server computation fairly among all clients, maintaining low latency and balanced response times.


## Summary

**Key concepts I understood through these questions:**
1. The practical difference between operating system processes and lightweight Java threads.
2. How Round-Robin scheduling prevents starvation through time quantum preemption and ready-queue re-queueing.
3. The full Java thread lifecycle from instantiation through waiting states to termination.
**Concepts I need to study more:**
1. Advanced thread synchronization primitives like Semaphores, ReentrantLocks, and atomic variables.
2. Multi-core CPU scheduling algorithms and handling race conditions in concurrent data collections.



---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [x] Student ID is set in `SchedulerSimulation.java` (line 150)
- [x] Code compiles and runs with no errors
- [x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [x] Each feature has clear comments

**Commits**
- [x] **At least 3 meaningful commits, ideally 6 or more**
- [x] **One commit per feature**
- [x] Commits are spread over **different dates** (not all in the last hour)
- [x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [x] Full name and student ID filled in at the top
- [x] Development log has **5+ entries** on different dates
- [x] Reflection: 4 questions, 5-7 sentences each
- [x] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [x] No `[...]` placeholders left
- [x] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
