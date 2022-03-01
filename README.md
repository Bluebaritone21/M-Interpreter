# M-Interpreter

Use `python3 main.py filename.m` to run a M program.

You Might want to run (in the same Directory as the repo.):

```bash
mkdir ~/Mlang
mv ./main.py ~/Mlang/main.py
echo -e "\nalias m=\"~/Mlang/main.py\"" >> ~/.bashrc
source ~/.bashrc
```

---

## Syntax

Programs start with `{` and end with `}`
Assign variables with `is` as in `SomeVar is 5;`

Satements end in `;`
