# OpenVent project documentation

## Basic structure

We are using [Docsify](https://github.com/docsifyjs/docsify) to generate this documentation on the fly from the Markdown files in `/docs` of the [repository](https://www.github.com/mhollfelder/openvent).\
Basically, writing documentation means adding additional Markdown files plus modifying Docsify settings if required.

The documentation can also be hosted locally by executing the following command from the repository root: 

```console
npm i docsify-cli -g
cd ./docs
docsify serve
```

Afterwards, you can visit the documentation via `http://localhost:3000` in the browser.

## Folder and file structure of docs

```console
docs/
┣ 01_getstarted/    // A Get Started guide
┣ 02_concept/       // The overall concept and generic explanation
┣ 03_hardware/      // The hardware documentation
┣ 04_software/      // All software related documentation
┣ 05_mechanics/     // Documentation of the mechanical design
┣ 03_prototype/     // Documentation of prototypes
┣ 04_knowledge/     // The knowledge hub around this topic
┣ 08_development/   // The overall development flow
┣ _sidebar.md       // The sidebar for Docsify
┣ .gitkeep          // Keep this folder tracked in Git even if it is empty   
┣ .nojekyll         // Configure Jekyll for GitHub pages to not ignore files starting with underscore
┣ home.md           // The Docsify homepage
┣ index.html        // Docsify index.html file for Docsify configuration
┗ README.md         // This README file
```

## Disclaimer

:warning: We would like include a warning and disclaimer here:

Please check the full disclaimer as well before proceeding.

- The material and documentation here is provided with no warranties explicit or implied.
- No material on this site is intended to provide medical advice. All designs are intended for investigational use only.
- This site does not represent any official policies or procedures.

The project is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement.\
In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.

Only use **this repository, designs, documentation or any provided information** if you accept the above disclaimer.

## Project description

:wave: Clearly, the first choice is **always** available, professional, certified medical equipment.

During the Corona (COVID-19) pandemic it became obvious that a lack of medical equipment can cause a severe impact.\
Often, also simple equipment and designs can be helpful as long as no professional equipment is available.

This documentation and repository contains generic information about an open-source ventilator device.\
Main purpose of this project is to build a ventilator when no professional and medical equipment is available.\
Easy to assemble and available components are used with a clear focus on simplicity, availability and scalability.

This project started as part of the hackathon [#WirvsVirus](https://wirvsvirushackathon.org/) of the German government.

## Current status

Right now, a prototype is in development with a bag valve mask, a 3D printed fixture and a motor.\
The prototype is tested and in an iterative, agile approach improved to provide a simple design.\
We are right now uploading the designs and design files for next steps and testing.

The latest prototype can be found in the folder `docs/03_prototype`.

## Development branches

We have the following tracks:

- `Docs`
- `Software`
- `Hardware`
- `Mechanics`

The development flow and more details are right now documented.\
We will soon upload it to `docs/08_development` and present you more details.

## Development flow

We have a Slack channel for exchange on the overall development and exchange on the project itself.\
Moreover, we use GitHub [projects](https://github.com/mhollfelder/openvent/projects?query=sort%3Aname-asc+) to track the process, requirements, etc.

If you want to contribute, please open an issue, create a pull request or ping us at contact.openvent@gmail.com.

## Contributors

### Core team

The core team which started this project:

- [Mahmoud Ismail](https://github.com/mahmoudgo)
- [Nico Kelling](https://github.com/nicokelling)
- [Daniel Gernert](https://github.com/DanielGernert)
- [Alexander Maier](https://github.com/alex-km)
- [Manuel Hollfelder](https://github.com/mhollfelder)

### Additional contributors

So far, we have no additional contributors, but if you feel like contributing, please:

- Check out open action items or issues
- Fork the project
- Contribute to the repository
- Create a pull request

Additionally, please get in contact with us via contact.openvent@gmail.com for more details and the Slack channel.

## Similar projects

We will provide a list of similar projects in the `docs/04_knowledge` folder soon.
