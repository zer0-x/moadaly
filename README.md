# Moadaly
A **feature-rich** Qt6 application to calculate the grade point average and other related stuff for university students.

## Features
- ๐งพ Free software under the [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html) licence.
- ๐๏ธ Create multible profiles and switch between them in the fly, to manage multible CGPAs.
- ๐พ All data are saved in a database to be loaded in the next session.
- ๐ค Export & ๐ฅ Import database data to a json file. `(import functionality is not yet implemented)`
- 5๏ธโฃ point scale & 4๏ธโฃ point scale systems are both supported. `(4 point scale is not yet implemented)`
- ๐ฏ Both grading systems, noramel and curve are supported. `(curve system is not yet implemented)`
- ๐งฎ A dynamic grades panel for semesters and ther courses.
- ๐งฐ Some extra tools thet may help you in your calculation. `(Not yet implemented)`
- ๐ Some charts to make you understand your grades better. `(Not yet implemented)`
- ๐จ๏ธ Printable reports. `(Not yet implemented)`
- ๐ Database encreption. `(Under thought, may or may not be implemented)`


## Installation
### Flatpak
Not available yet...
### AppImage
Not available yet...
### AUR
Not available yet...
### pypi <sup>`(Not recomended)`</sup>
Not available yet...
### From the git repo <sup>`(Not recomended)`</sup> 
1. Clone the repo from github and cd to it
```shell
git clone https://github.com/zer0-x/moadaly.git
cd modaly
```
2. Use the `setup.py` file to install it
```shell
python3 setup.py install
```
> You can create a virtual environment before that if you wanted.
3. Now it should be in your path. Just type `moadaly` to run the GUI
```shell
moadaly
```

## Development
For development you are recomended to use [Pipenv](https://pipenv.pypa.io) for reproducing the same environment.
1. Install pipenv if you  don't have it
```shell
python3 -m pip install pipenv
```
2. Run the folowing command in the project's root directory to install all the dependencies form `Pipfile.lock`
```shell
pipenv install --dev
# Don't use the `--dev` flag to not install the development packages
```
3. Then you can activate the virtual environment and run the application as a python module
```shell
pipenv shell
python3 -m moadaly
```

## Troubleshooting
If you got some issues with the PySide6 module that prevent the app from starting, try running:
```shell
python3 -m pip install --force-reinstall --no-cache-dir PySide6
```

## Q&A

Q: What does `Moadaly` mean?
- It is an Arabic word `ููุนูุฏููููู` that could be translated to `My GPA` in english.
