# Demo plugin using React and wp-data

This demo shows a plugin using React and `@wordpress/data` to manage the state of its components. The project is based in the one explained at:

- https://neliosoftware.com/blog/introduction-to-react-1/
- https://neliosoftware.com/blog/introduction-to-react-2/
- https://neliosoftware.com/blog/introduction-to-react-3/
- https://neliosoftware.com/blog/introduction-to-react-4/


## Prerequisites

This demo uses [`@wordpress/env`](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-env/) to set the development environment so [the requisites of this package must be installed](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-env/#prerequisites)

## Settings

To launch all Backend Docker services required for WordPress development you have to execute _from the root of the project_:

```
npm run wp-env start
``` 

This will start a few Docker containers (WordPress, MySQL, ...) listening to specific ports that we can use to access these related services
