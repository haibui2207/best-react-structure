*<small>Created 09 Oct 2019</small>*

> **Don't have any **BEST REACT STRUCTURE.** ** - Just based on practical experience!


# # APP STRUCTURE
	| assets
		| images
		| icons
		| fonts
	| constants
	| components
	| containers
	| HOCs
	| middlewares
		| redux
	| utils
		| api
		| storage

> **Explanation**

	|------------------|-----------------------------------------------------------------|
	|     Folder       |                            Content                              |
	|------------------|-----------------------------------------------------------------|
	|     assets       |  images, icons, fonts, font-icons,...                           |
	|------------------|-----------------------------------------------------------------|
	|     constants    | variables constant: route path, api path, theme colors,...      |
	|------------------|-----------------------------------------------------------------|
	|     components   | general components used in containers or other components       |
	|------------------|-----------------------------------------------------------------|
	|     containers   | container is a page or sub-container is used by another         |
	|------------------|-----------------------------------------------------------------|
	|     HOCs         | Reacts HOC components                                           |
	|------------------|-----------------------------------------------------------------|
	|     middlewares  | app's middleware like redux-thunk, redux-promise, redux-saga,   |
	|                  | react-router-routes, ...                                        |
	|------------------|-----------------------------------------------------------------|
	|     utils        | call api, general functions, ...                                |
	|------------------|-----------------------------------------------------------------|

# # FOLDERS STRUCTURE

	| components

		| Button

			| index.js

			| Button.js

			| button.styles.js | button.modules.scss | button.css | ...

	| containers

		| Layout

			| index.js

			| Layout.js

			| layout.styles.js | layout.modules.scss | layout.css | ...

			| components

				| Button

					| index.js

					| Button.js

					| button.styles.js | button.modules.scss | button.css | ...
	 
> **Explanation**

	|------------------|-----------------------------------------------------------------|
	|        File      |                            Description                          |
	|------------------|-----------------------------------------------------------------|
	|  <component>.js  |  includes main logic, layout UI                                 |
	|  <container>.js  |                                                                 |
	|------------------|-----------------------------------------------------------------|
	|     css          | component/container's css                                       |
	|------------------|-----------------------------------------------------------------|
	|     index.js     | expose component/container, css styles, interface,...           |
	|                  | this file will be imported by other components/containers       |
	|------------------|-----------------------------------------------------------------|
	|  sub-components  | includes components only used within container                  |
	|------------------|-----------------------------------------------------------------|
	
# # IMPORT FILES STRUCTURE
	
	| Package modules

	/* space line */

	| External import files

	/* space line */

	| Local import files
