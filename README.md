# UB Eats
### Framework: Flask / Python
This is @7's CSE 312 Final Project. This repository contains the necessary files to launch our web application. Click on the drop-down arrows to get more information on each Project Part or Testing procedure. The publicly available deployment is at [ubcommons.com](https://ubcommons.com "Visit our website"). 

![UBeats Overview](static/video/docker.gif)

</details> <details> <summary> <h2> How to Locally Run: </h2></summary>

Clone the repository:

```bash
git clone git@github.com:h3rogam3r8/cse-312.git
cd cse-312
```

In the Terminal:

```bash
docker compose up --build --force-recreate
```
</details> <details> <summary> <h2> Dark Mode (P3AO3) : </h2></summary>

<h3> Description: </h3>

```bash
Dark mode is an additional theme that allows users to enjoy our website without added strain 
on their eyes, especially during low-light conditions.
```

<h3> Testing Procedure: </h3>

```bash
1. Run the general testing procedure in "How to Locally Run:" and navigate to localhost:8080.
2. Click on the Dark Mode button and verify your screen is now displaying a dark mode.
3. Click on the Light Mode button and verify your screen has gone back to light mode.
4. Click on another restaurant page and repeat steps 2 and 3.
5. Click on the Dark Mode button again.
6. Next, click on another restaurant page and ensure you are still displaying dark mode.
7. Login and Register an account.
8. Once logged in, repeat steps 1 through 5.
```
