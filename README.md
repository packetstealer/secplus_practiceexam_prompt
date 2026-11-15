# Reusable Prompt: Build Your Own Interactive CompTIA Security+ (SY0-701) Practice Exam Simulator

Copy and paste the prompt below into Gemini (or another AI coding assistant) and attach/paste your own purchased Professor Messer Practice Exam PDF(s) along with the Answer Key & Explanations:

## Prompt to Copy & Paste:

Build a complete, single-file interactive CompTIA Security+ (SY0-701) Practice Exam Simulator in HTML, Tailwind CSS, and vanilla JavaScript using the practice exam questions, PBQs, answers, and explanations I have attached/provided.

Core Requirements:

Single-File Architecture: Put all HTML, CSS (Tailwind CDN), and JavaScript inside one self-contained .html file, storing the structured question bank inside an inert <script type="application/json"> block.

Multi-Exam Support: If I provide multiple practice exams (e.g., Practice Exam A, B, and/or C), include an exam selector on the start screen so I can choose which 90-question exam to launch. Distribute the 5 Performance-Based Questions (PBQs) evenly throughout the 85 Multiple-Choice Questions just like the real CompTIA exam.

Interactive Question Types:

Performance-Based Questions (PBQs): Support drag-and-drop AND click-to-assign interaction for matching rows, assigning security controls to architectural/physical zones, ordering incident response steps, and configuring firewall ACL rules via dropdowns (Source IP, Destination IP, Protocol, Port, Action), plus a "Reset Answers" button on each PBQ.

Single & Multi-Select MCQs: Clearly badge (Select TWO) or (Select THREE) questions and enforce the exact selection limit. Format log snippets and terminal outputs in dark monospace code blocks.

Realistic Exam Workspace & Controls:

Sticky top header showing current question progress (Question X of 90), a Flag for Review button, a Question Navigator modal grid (color-coded for Current, Answered, Unanswered, and Flagged), a live 90-minute countdown timer (turning urgent red under 5 minutes and auto-submitting at 00:00), and a Submit Exam button.

Bottom navigation bar with Previous, Skip, Next, keyboard arrow navigation (← / →), and an End-of-Exam Checkpoint screen listing all skipped, unanswered, and flagged questions before final submission.

Post-Exam Score Report & Mistake Review Mode:

Calculate total score, percentage, time taken, and pass/fail readiness against an 85% (77/90) benchmark, broken down across all five CompTIA SY0-701 domains (1.0 through 5.0).

Include a Review Missed Questions step-by-step walkthrough mode and filterable results (All, Incorrect Only, Correct Only, PBQs) that show:

- Side-by-side comparison of Your Answer vs. Correct Answer

- Why Your Answer Was Incorrect (pinpointing the exact wrong MCQ option, missed multi-select pick, PBQ row/zone mismatch, or firewall rule field error)

- Why the Correct Answer Applies (mapped to the SY0-701 exam objective).
