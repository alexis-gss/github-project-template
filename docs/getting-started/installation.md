---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 📥 Installation

Add the [Github Project Template](https://github.com/alexis-gss/github-project-template) as a **remote template** in your project :

```
git remote add template https://github.com/alexis-gss/github-project-template.git
```

Then **pull all modification** of the theme :

```
git fetch template master
```

Finally, **merge modifications** to your main branch :

```
git merge template/master --allow-unrelated-histories
```

If you want to remove the template in your project, use this command :

```
git remote remove template
```

You can now use the [Github Project Template](https://github.com/alexis-gss/github-project-template).
