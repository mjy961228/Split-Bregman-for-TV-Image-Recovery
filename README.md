# Split Bregman for TV Image Recovery

### Author: Anqi Ni
### Email: anqini4@gmail.com

## Dependency:
- numpy
- scipy / imageio
- matplotlib

## Tips:
1. Please download all modules (i.e. numpy, etc.) before you run the project.
2. `gaussian_method2` is an alternative of `gaussian_method` but it runs slower.
3. In `imnoise` function, it parameter **3** can be changed to other numbers, but **lambda** and **mu** must be changed accordingly to make sure it converges.

The following parameters work pretty well:

| noise | lambd | mu   |
|-------|-------|------|
| 3     | 0.1   | 0.05 |
| 2     | 0.1   | 0.1  |
| 1     | 0.05  | 0.1  |

*you can change paramters as you want, the parameters above is just for reference.

Good Luck!

![https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Keep-calm-and-carry-on-scan.jpg/440px-Keep-calm-and-carry-on-scan.jpg](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Keep-calm-and-carry-on-scan.jpg/440px-Keep-calm-and-carry-on-scan.jpg)
