# Git Scavenger Hunt

Hey there, welcome to the scavenger hunt! 🥳

This README file has everything you need to get started. Grab your team members and make sure to read it **CAREFULLY**!

If you need help, please raise your hand and make sure to engage in intense eye contact with one of the volunteers.

## 1. Prerequisites

**Each participant will need:**

- A GitHub account
- Git

## 1.1 Create a GitHub Account

On GitHub, click **Sign Up** at the top of the page. Any email will work for this. Just make sure to use the same email when you configure Git in the next section.

## 1.2 Install Git

**Each participant will need to complete these steps:**



1. Check if Git is already installed by opening a terminal and entering the following command. If you're on Windows, it's recommended you install [Windows Terminal](https://apps.microsoft.com/detail/9n0dx20hk701?hl=en-GB&gl=CA) from the Microsoft Store.

```
git --version
```

2. If the command fails, install Git from here: https://git-scm.com/install. **If you're on macOS:** It's recommended you install Git using Homebrew. Homebrew install instructions are here: https://brew.sh/

3. Once Git is installed, you will need to enter these commands into your terminal (Make sure to change the name and email):

```
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL"
```

4. It's also recommended that you change the default branch name to `main` with:

```
git config --global init.defaultBranch main
```

**Extra steps for Linux and macOS users:**

5. It's recommended you use `gh` for authentication with HTTPS (for simplicity). Follow the install steps here: https://cli.github.com/

6. Enter:

```
gh auth login
```

7. Here are the recommended settings to choose from the setup dialog:

```
? What account do you want to log into? GitHub.com
? What is your preferred protocol for Git operations on this host? HTTPS
? Authenticate Git with your GitHub credentials? Yes
? How would you like to authenticate GitHub CLI? Login with a web browser
```

8. Copy the one-time code and paste it into your web browser. You will have to log into your GitHub account, first.

## 1.3 Fork the Repository

**Only one participant from each group needs to complete these steps:**

1. Scroll to the top of the page and hit the **Fork** button.

![alt text](screenshots/image.png)

2. On the next page, make sure to **uncheck** the "Copy to the `main` branch only" checkbox, and hit **Create Fork**.

![alt text](screenshots/image-1.png)

You now have a personal copy of this repository on your GitHut account. It's time to add your group members!

3. From your fork, find the **Settings** tab.

![alt text](screenshots/image-2.png)

4. Find **Collaborators** in the sidebar.

![alt text](screenshots/image-3.png)

5. Click **Add People**.

![alt text](screenshots/image-4.png)

6. Search for your group members and add them. **Your group members will need to accept the invites from their email inboxes!**

![alt text](screenshots/image-5.png)

## 1.4 Clone the Forked Repository

**Each participant will need to complete these steps:**

1. Copy the URL from the **Code** dropdown.

![alt text](screenshots/image-6.png)

2. Now clone the repo using the URL you copied:

```
git clone https://your-forks-url.git
```

## 2. Scavenger Hunting!

Now that your team is all set up, it’s time to begin the hunt! 🎉

Your team has been tasked with maintaining a long-abandoned project that once powered your company’s highly sophisticated computer network.

Unfortunately, the original maintainers have mysteriously disappeared, and it’s now up to you to bring the project back to its former working glory!

Luckily, they left behind a few instructions to help you get started:

> **Dear new maintainers,**
>
> This project is riddled with bugs and unnecessary branches. There’s a to-do list in the main code file, along with instructions for organizing your team in `CONTRIBUTING.md`. You may find those useful.
>
> Good luck,
>
> *[Inked-out name]*
>
> **P.S.** You may need to install Python.

Well... that was sort of helpful.

Anyways, good luck!

## 3. Running

When you're finished making changes to the code:

Click on the play button on the top right corner of your screen.
Your terminal below should display the texts below from running the code with no errors:

```
=== Autonomous System Initialization Sequence ===

[System] Synchronizing the flux capacitor...
[System] Flux capacitor synchronized.

[QuantumCalibrator] Defuncing the defibrillator...
[QuantumCalibrator] Defibrillator successfully defunced.

[QuantumCalibrator] Oscillating the harmonic oscillator...
[QuantumCalibrator] Oscillator resonance stabilized.

[MechanicalSubsystem] Applying lubricant to the thingamajig...
[MechanicalSubsystem] Thingamajig successfully oiled.

[MechanicalSubsystem] Rotating the auxiliary gizmo...
[MechanicalSubsystem] Gizmo rotation nominal.

[DataPipeline] Initializing hyperbuffer...
[DataPipeline] Validating hyperbuffer coherency...
[DataPipeline] Hyperbuffer is coherent.

[DataPipeline] Transmuting the datastream...
[DataPipeline] Processing packet 1...
[DataPipeline] Processing packet 2...
[DataPipeline] Processing packet 3...
[DataPipeline] Processing packet 4...
[DataPipeline] Datastream transmutation complete.

[System] Recalibrating neural matrix...
[System] Neural matrix recalibrated.

[System] Engaging final operational sequence...
[System] Aligning quantum manifolds...
[System] Reversing polarity of the neutron flow...
[System] Stabilizing pseudo-gravitational harmonics...
[System] Re-indexing hyperspatial lookup tables...
[System] Verifying thingamajig lubrication levels...

[System] All systems nominal.
[System] The device is now fully operational.

=== Initialization Complete ===
```

If there are certain cut-offs and error, it means you did not make the correct changes to the code.

Please try again following the to-do list in the main code file.
Good Luck and most importantly Have Fun!