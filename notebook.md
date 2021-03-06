# Notebook Josh Goodman sp20-516-220

## Week 05/04/2020 - 05/10/2020

* Troubleshot startup error from Gregor.
* Fully implemented profile editor.
* Added ssh login function.
* Added VM log viewer.
* Help docs w/ screenshots

## Week 04/27/2020 - 05/03/2020

* Enabled CMS Cloud switching via option.
* Enabled display of CMS error messages for images and flavors pages.
* Added async and sync support to CMS calls.
* Added main landing page.
* Added CMS profile page with editing features.
* Added cloud provider swtiching feature.

## Week 04/20/2020 - 04/26/2020

* Improved error handling from CMS calls.
* Added cms viewer command support for linux and mac.
* Documented cms viewer command support.
* Added refresh button component.

## Week 04/13/2020 - 04/19/2020

* Added support for CMS flavors to cloudmesh-javascript
* Added support for CMS Images to cloudmesh-javascript
* Added custom React hooks for interfacing with cloudmesh
* Improved CMS path handling.

## Week 04/06/2020 - 04/12/2020

* Added job queue for Electron -> CMS so that only one command at a time can be sent.

## Week 03/30/2020 - 04/05/2020

* Implemented reading of VIRTUAL_ENV.
* Debugged various issues with multi level async handling.
* Attempted several different approaches to tackling async and event streaming problems when interfacing between Javascript and Python.

## Week 03/23/2020 - 03/29/2020

* Extended spring break due to Coronavirus
* Migrated to using IpcRenderer.invoke() method.

## Week 03/16/2020 - 03/22/2020

* Spring break

## Week 03/09/2020 - 03/15/2020

* Added support for Python environment detection.
* Added support for user to update/change their Python environment.

## Week 03/02/2020 - 03/08/2020

* Started new [branch](https://github.com/cloudmesh/cloudmesh-javascript/tree/release/0.1.0-alpha) for first alpha version.
* Worked on electron to cms bridge via PythonShell and the cloudmesh.cloud.Shell library.

## Week 02/24/2020 - 03/01/2020

* Setup a [performance](https://github.com/cloudmesh/cloudmesh-javascript/tree/feature/performance) branch for evaluating electron performance.
* Evaluated various methods for executing Python scripts and the cloudmesh binary (cms).
* Settled on using [PythonShell](https://github.com/extrabacon/python-shell) for executing the electron to cms bridge.


## Week 02/17/2020 - 02/23/2020

* Documented evaluation.
* Moved Nextron prototype to `develop` branch.
* Installed and setup cloudmesh Mongo.
* Installed and setup cmsd.

## Week 02/10/2020 - 02/16/2020

* Worked on proptype using Electron and Next JS
* Evaluated Nextron (Electron + NextJS)
* Evaluated React Node GUI
* Evaluated Proton Native
* Evaluated Electron React Boilerplate
* Finished basic prototype.
* Wrote basic docs for downloading, building, and running the prototype.

## Week 02/03/2020 - 02/09/2020

* Researched the UI project goals
* Met with Dr. Laszewski to discuss UI project.
* Started evaluating UI frameworks (Electron, Proton Native, React NodeGUI, NW.js)

## Week 01/27/2020 - 02/02/2020

* Read Cloud computing architectures
* Read Python chapter.
* Answered venv question (see below).
* Did E.cloudmesh.common exercises 1-5.
* Did E.cloudmesh.Shell exercises 1-3.
* Worked on Provider.py

1. Why do you need to use venv for this class?

  venv sets up an isolated Python runtime environment in a directory of your choosing.  The isolated
  environment helps to keep any installed dependencies isolated across projects and/or the system
  and it doesn't require root access for installing dependencies.  Isolation is the critical aspect here.
  Often times, different projects will require slightly different versions of dependencies, without a virtual
  environment you will end up with broken projects when a dependency in one project
  has resulted in an unplanned upgrade of a dependency in another.

## Week 01/20/2020 - 01/26/2020

* Read *Data Center*  chapter in *Cloud Computing* book.
* Did data center assignments.
* Verified info in [README.yml](./README.yml)
* Verified Chameleon cloud account.
* Setup python on my computers.
* Setup multipass and did assignments.
* Read Multipass in *Cloud computing* book.

## Week 01/13/2020 - 01/19/2020

* Read lecture notes up to week 1.
* Read chapters 1, 2, and 3 of *Cloud Computing*.
* Watched intro video on youtube.
* Watched *Definition of Cloud Computing* on youtube.
* Setup python environment on my desktop and laptop.
* Created required accounts that I didn't already have (chameleon cloud).
* Attended weekly zoom meeting for class.

