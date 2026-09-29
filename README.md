# Interactive Job Counter

A small React application for tracking jobs interactively in the browser. The
default view uses the advanced counter, which lets you add and remove jobs,
reset the list, and switch between Development and Production environments.

## Why use it?

- Track a live job count without a backend or external services.
- Add and remove individual jobs from the rendered list.
- Reset the counter when starting a new batch.
- Switch the displayed environment to represent different workflows.
- Use the project as a straightforward example of React state and event
  handling.

## Getting started

### Prerequisites

- Node.js 18 or a newer LTS release
- npm (included with Node.js)

### Installation

Clone the repository, enter the project directory, and install its dependencies:

```bash
git clone https://github.com/VoidLance/course-files-javascript-react-interactive-job-counter.git
cd course-files-javascript-react-interactive-job-counter
npm install
```

### Run the app

Start the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in a browser. The page
reloads automatically as you edit the source files.

### Use the counter

1. Select **Add Job** to append a job to the list.
2. Select **Remove** beside a job to delete that job.
3. Select **Reset Jobs** to clear all jobs.
4. Select **Switch Environment** to toggle between Development and Production.

The counter message changes as the number of jobs changes: zero jobs, a few
jobs (fewer than five), or many jobs (five or more).

## Development commands

Run these commands from the project directory:

| Command | Purpose |
| --- | --- |
| `npm start` | Start the development server on port 3000. |
| `npm test` | Run the test suite in interactive watch mode. |
| `npm run build` | Create an optimized production build in `build/`. |
| `npm run eject` | Expose the Create React App configuration. This is irreversible. |

## Project structure

```text
src/
├── App.js                 # Application entry component
├── AdvancedJobCounter.js  # Main counter UI and state logic
├── JobCounter.js          # Basic counter example
├── App.css                # Application styles
└── index.js               # React bootstrap
public/                    # Static assets and the HTML shell
package.json               # Scripts and dependencies
```

The application is built with React and Create React App. The main component
is `src/AdvancedJobCounter.js`; `src/JobCounter.js` is retained as a simpler
counter example.

## Support

For questions or problems:

- Check the [React documentation](https://react.dev/learn).
- Check the [Create React App documentation](https://create-react-app.dev/docs/getting-started/).
- [Open an issue](https://github.com/VoidLance/course-files-javascript-react-interactive-job-counter/issues)
  with steps to reproduce the problem and the command you ran.

## Contributing

Contributions are welcome. To propose a change:

1. Fork the repository and create a focused branch.
2. Install dependencies with `npm install`.
3. Make the change and add or update tests where appropriate.
4. Run `npm test` and `npm run build`.
5. Open a pull request describing the change and validation performed.

Please keep pull requests focused and follow the existing JavaScript and React
patterns in `src/`.

## Maintainer

This project is maintained by [VoidLance](https://github.com/VoidLance).

## License

No license file is currently included. Contact the maintainer before
redistributing or reusing the project.
