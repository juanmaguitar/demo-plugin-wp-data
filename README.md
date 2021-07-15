# Demo plugin using React and wp-data

This demo shows a plugin using React and `@wordpress/data` to manage the state of its components. The project is based in the one explained at:

- https://neliosoftware.com/blog/introduction-to-react-1/
- https://neliosoftware.com/blog/introduction-to-react-2/
- https://neliosoftware.com/blog/introduction-to-react-3/
- https://neliosoftware.com/blog/introduction-to-react-4/


## Prerequisites

This demo uses [`@wordpress/env`](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-env/) to set the development environment so [the requisites of this package must be installed](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-env/#prerequisites)

## Installation

### Backend (Docker and `@wordpress/env` package)

To launch all Backend Docker services required for WordPress development you have to execute _from the root of the project_:

```
npm run wp-env start
``` 

This will start a few Docker containers (WordPress, MySQL, ...) listening to specific ports that we can use to access these related services

We should be able to access to the dashboard panel of the WordPress installation at `http://localhost:8888/wp-admin` (user: admin, password: password)

### Frontend (plugin)

From the plugin folder (`plugins/react-wp-data-example`) we can generate the `build` folder by doing

```
npm run build
```

Or we can execute `npm start` to launch a watching process that will generate the `build` folder every time changes are detected under the `src` folder


