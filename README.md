<!-- Logo -->
<h1 align="center">
  <img src="https://raw.githubusercontent.com/willtheorangeguy/Snoopy-Landing-Page/master/docs/images/logo.png" height="250px" width="400px" alt="Snoopy Landing Page">
  <br>
  PyWorkout
  <br>
</h1>

<!-- Copy -->
<h4 align="center">A simple under construction landing page that features Charles M. Schulz's iconic Snoopy Beagle.</h4>

<!-- Badges -->
<div align="center">
  <!-- Stability -->
  <img alt="GitHub Actions State" src="https://github.com/willtheorangeguy/Snoopy-Landing-Page/actions/workflows/pages/pages-build-deployment/badge.svg">
  <!-- Version -->
  <img alt="GitHub Version" src="https://img.shields.io/github/v/release/willtheorangeguy/Snoopy-Landing-Page">
  <!-- Issues -->
  <img alt="GitHub Issues" src="https://img.shields.io/github/issues/willtheorangeguy/Snoopy-Landing-Page">
  <!-- Pull Requests -->
  <img alt="GitHub Pull Requests" src="https://img.shields.io/github/issues-pr/willtheorangeguy/Snoopy-Landing-Page">
  <!-- Discord -->
  <img alt="Discord Server ID" src="https://img.shields.io/discord/960376610240987176">
  <!-- Downloads -->
  <img alt="Downloads" src="https://img.shields.io/github/downloads/willtheorangeguy/Snoopy-Landing-Page/total">
  <!-- Language Count -->
  <img alt="GitHub Languages" src="https://img.shields.io/github/languages/count/willtheorangeguy/Snoopy-Landing-Page">
</div>

<!-- Navigation -->
<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#download">Download</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#support">Support</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#changelog">Changelog</a> •
  <a href="#credits">Credits & Contributors</a>
</p>

<!-- Screenshot(s) -->
![screenshot](https://raw.githubusercontent.com/willtheorangeguy/Snoopy-Landing-Page/master/docs/images/landing.png)

## Key Features

* Easy to run and understand with simple commands.
* Large list of muscle groups and workout activities.
* Automatic workout selection by day.
* Time and percentage complete indicators.
* Step by step guide through a workout program.
* Statistics view.
* Can skip unlikeable workouts.
* Able to customize number of workouts, muscle groups, type of workout and more.
* Cross platform.

## Download

You can **[download](https://github.com/willtheorangeguy/PyWorkout/releases/latest) the source code** to run the scripts from the command line on Windows, macOS and Linux. **This will require [Python](https://www.python.org/downloads/).**

You can **[download](https://github.com/willtheorangeguy/PyWorkout/releases/latest) the latest executable version** of PyWorkout for Windows. **This does not require Python.**

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com/downloads) and [Python](https://www.python.org/downloads/) installed on your computer. If you would rather not use Git, you can just download the scripts from GitHub above. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/willtheorangeguy/PyWorkout

# Go into the repository
$ cd PyWorkout

# Run the CLI
$ python main.py

# Run the GUI app
$ python gui.py
```

## Support

**The following commands are available (can be generated by using the `help` command):**

```text
list    Lists the workout activities by muscle group.
start   Starts the workout and displays the first workout activity.
next    Moves to the next workout activity.
skip    Skips the current workout activity.
end     Completes the workout and display full workout statistics.
stats   Shows workout statistics at any point (does not work with the `skip` command).
video   Opens the workout video assigned to each muscle group.
license Shows the license.
help    Prints this help text.
quit    Ends the program.
```

Note: the `skip` command cannot be used in conjunction with the `stats` command.

**To use the `video` command, you must change the video variables.** To do so:

1. Open `main.py` in a text editor.
2. Change the _Video File Paths_ variables to the **absolute** path for each video by muscle group (double slashes (`\\`) are only necessary on Windows).

```python
# Video File Paths
abs_video = "D:\\Videos\\Workout Videos\\10 Minute Ab Workout.mp4" # change these to personal video path
```

3. Running the `video` command will now include your local workout videos.

Customizing the list of workouts, workout activities and number of activities can be found in [`CUSTOMIZATION.md`](https://github.com/willtheorangeguy/PyWorkout/tree/main/docs). More documentation is available in the **[Documentation](https://github.com/willtheorangeguy/PyWorkout/tree/main/docs)** and on the **[Wiki](https://github.com/willtheorangeguy/PyWorkout/wiki)**. If more support is required, please open a **[GitHub Discussion](https://github.com/willtheorangeguy/PyWorkout/discussions/new)** or join our **[Discord](https://discord.gg/YFMcACG9rh)**.

## Contributing

Please contribute using [GitHub Flow](https://guides.github.com/introduction/flow). Create a branch, add commits, and [open a pull request](https://github.com/willtheorangeguy/PyWorkout/compare).

Please read [`CONTRIBUTING`](CONTRIBUTING.md) for details on our [`CODE OF CONDUCT`](CODE_OF_CONDUCT.md), and the process for submitting pull requests to us.

## Changelog

See the [`CHANGELOG`](CHANGELOG.md) file for details.

## Credits

This software uses the following open source packages, projects, services or websites:

<!-- Credits Table -->
<table>
  <tr>
    <th align="center"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="150" height="150" alt="GitHub"/></th>
    <th align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/182px-Python-logo-notext.svg.png" width="150" height="150" alt="PSF"/></th>
    <th align="center"><img src="https://pyinstaller.readthedocs.io/en/v4.2/_static/pyinstaller-draft1a.ico" width="150" height="150" alt="PyInstaller"/></th>
    <th align="center"><img src="https://pbs.twimg.com/profile_images/912151274551885824/sjzD5vK9_400x400.jpg" width="150" height="150" alt="Carbon"/></th>
  </tr>
  <tr>
    <td align="center">GitHub</td>
    <td align="center">Python Software Foundation</td>
    <td align="center">PyInstaller</td>
    <td align="center">Carbon</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/">Web</a> - <a href="https://github.com/pricing">Plans</a></td>
    <td align="center"><a href="https://www.python.org/">Web</a> - <a href="https://psfmember.org/civicrm/contribute/transact?reset=1&id=2">Donate</a></td>
    <td align="center"><a href="https://pyinstaller.readthedocs.io/en/stable/">Web</a> - <a href="https://www.pyinstaller.org/funding.html#funding-by-individuals">Donate</a></td>
    <td align="center"><a href="https://carbon.now.sh/">Web</a></td>
  </tr>
</table>

## Contributors

* [@willtheorangeguy](https://github.com/willtheorangeguy) - Sponsor on [PayPal](https://paypal.me/wvdg44?country.x=CA&locale.x=en_US)

## You may also like...

* [Running Calculator](https://github.com/willtheorangeguy/Running-Calculator) - A running speed calculator for any unit of distance.
* [Python Logo Widgets](https://github.com/willtheorangeguy/Python-Logo-Widgets) - Python Powered Logo widgets that can be added to any GUI project.
* [Random Lotto Number Chooser](https://github.com/willtheorangeguy/Random-Lotto-Number-Chooser) - Randomly pick lucky lotto numbers.

## License

This project is licensed under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) - see the [`LICENSE`](LICENSE.md) file for details. See the [Privacy Policy](https://github.com/willtheorangeguy/PyWorkout/blob/main/docs/legal/PRIVACY.md) and [Terms and Conditions](https://github.com/willtheorangeguy/PyWorkout/blob/main/docs/legal/TERMS.md) for legal information.
