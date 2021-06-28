# nx-lab

## Prerequisites

1. Your favourite IDE (Visual Studio Code was used in the making of this lab)
2. The latest or recent version of [npm](https://www.npmjs.com/)
3. The latest or recent version of [npx](https://www.npmjs.com/package/npx)
4. This lab was created and tested with a Mac but the same commands should work for PC.

## Setup

0. Make sure you have a git `user.email` and `user.name` set. You can do so by entering: 
  - `git config --global user.email "your.email@address.com"`
  - `git config --global user.name "Your Name"`
1. Using a terminal under a directory of your choice: `mkdir nx-lab`.
2. `cd nx-lab`
3. `npx create-nx-workspace`. This will make your project effectively an nx monorepo.
4. Type in `y` and ENTER when prompted 'Ok to proceed'.
5. Enter `nx-lab-workspace` as a workspace name.
6. Select `angular` for the 'What to create in the new workspace...' selection.
7. `nx-lab` for the Application name.
8. `CSS` for the Default stylesheet format.
9. Select `No` for 'Use Nx Cloud?'.
10. When you see the following, you know you have successfully created an nx workspace:

<img width="707" alt="image" src="https://user-images.githubusercontent.com/3400356/123641166-f73c1e80-d7ef-11eb-8006-e31b6b575b6c.png">

