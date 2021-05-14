<p align="center">
  <img src="https://prakashchokalingam.github.io/vue-cli-plugin-pod/icon.png" height="100px" width="100px">
 </p>

<h1 align="center">vue-cli-plugin-pod</h1>
<p align="center">Extended cli to manage file templates for vue projects</p>
<p align="center">
  <img src="https://flat.badgen.net/badge/Built%20With/TypeScript/blue">
  <img src="https://img.shields.io/npm/v/vue-cli-plugin-pod?color=%2322d422&logoColor=%23fff&style=flat-square">
  <img src="https://img.shields.io/npm/dt/vue-cli-plugin-pod?style=flat-square">
</p>

---

## Installation

Add this [vue cli plugin](https://cli.vuejs.org/guide/plugins-and-presets.html) to your awesome vue project using the below command.

```
vue add pod
```

> once installed you have access to the following  tasks,

---

### Generate

Create template files for the specified file type.

```
npm run generate <filetype> <file name or path>
```

Example: `npm run generate component UI/Button`


### Rename

Rename template files for the specified file type.

```
npm run rename <filetype> <old file name or path> <new file name or path>
```

Example: `npm run rename component icon avatar`

### Delete

Delete template files for the specified file type.

```
npm run delete <filetype> <file name or path>
```

Example: `npm run delete component UI/Button`

### Config
Get clone of default config file and customize on top of it.

```
npm run config
```


## TODO:
* Extensive documentation
* VUE UI integration








