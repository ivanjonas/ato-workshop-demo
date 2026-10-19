# Riverbend Club Quiz — brief v0.1

A short browser quiz where a player answers five questions about a fictional reading club and sees their score out of five.

Player: anyone who wants a quick, beginner-friendly quiz. No prior club knowledge is required; answer feedback explains the fictional rules.

Main action: choose one of three answer buttons. Each round uses the five course questions below in fixed order. Correct answers earn one point; wrong answers earn zero. An answer locks that question and shows an explanation. Next continues; after question five it shows the final score. There is no pass/fail threshold: the goal is to finish and see your score. Play again begins a fresh round at question one with zero points.

Controls: ordinary buttons usable with mouse, touch, or keyboard Tab and Enter. Instructions and Start appear before play.

## Question content

| Question | A | B | C | Correct answer and feedback |
| --- | --- | --- | --- | --- |
| How often does this fictional club choose a book? | Once a year | Once a month | Every day | B. The club chooses one short book each month. |
| What kind of book does the example club choose? | A short book | Only dictionaries | Only cookbooks | A. The fictional club chooses a short book. |
| What should you bring to the practice gathering? | A sales pitch | A ticket payment | A question about the book | C. Bring a question and a passage you want to discuss. |
| What does the website's main button do? | Takes a payment | Opens the next gathering section | Creates an account | B. It takes the visitor to the gathering details. |
| Which description matches this project? | A fictional classroom exercise | A confirmed real event | A real booking service | A. The group and gathering are fictional. |

The website mentioned in question four is part of the fictional course example; no website project is required to run this quiz.

## Five observable completion checks

1. Opening index.html shows instructions and Start; Start shows question 1 of 5 and score 0.
2. Each question shows the supplied three answers; one answer shows its explanation and locks scoring until Next.
3. B, A, C, B, A produces 5/5; A, B, A, A, B produces 0/5; B, B, C, A, A produces 3/5 in separate rounds.
4. After question five, Next shows the final score and Play again; replay resets to question one, zero points, and no previous answer or feedback.
5. A player can complete and restart a round using ordinary buttons with mouse or Tab and Enter. Phone touch remains a separate device check.

## First-version boundaries

One self-contained index.html with embedded CSS and JavaScript, runnable directly in a browser without installation. No timer, login, database, saved score, sound, randomized questions, streaks, lives, animations, external assets, or paid APIs. Decoration and optional features can wait until the basic round passes its checks.
