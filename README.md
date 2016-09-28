# atom_package_list
List of packages for the Atom (atom.io) editor

### Export Atom Package List to a File

To export your Atom packages to a text file, use the following command:

```
apm list --installed --bare > atom-package-list.txt
```

### Installing Atom Packages from a File

To _install_ packages from a file list, use the following command:

```
apm install --packages-file atom-package-list.txt
```
