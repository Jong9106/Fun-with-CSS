# Fun with CSS

-   By Guillaume, CTO at Holberton School
-   Weight: 1
-   Ongoing second chance project - started
    
    May 16, 2022
    
    , must end by
    
    Jun 6, 2022
    
    - you're done with  0% of tasks.
-   **Manual QA review must be done**  (request it when you are done with the project)

In this project, you will experiment and implement fun layout with HTML and CSS  **ONLY**!

Yes, no JavaScript!

Enjoy!

## Tasks

### 0. Sprite languages

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 0- Sprite</title>

        <link href="0-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <ul>
            <li>HTML<span class="icon i-html"></span></li>
            <li>CSS<span class="icon i-css"></span></li>
            <li>JavaScript<span class="icon i-js"></span></li>
        </ul>
    </body>
</html>

```

And this image file:  [0-sprite.png](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/d416199ca6ecdbd0f8a3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220606%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220606T041232Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=8f7f6185f11474d9c256b05c82ed4d6bc7be615b505a64fc774ad11c891b4d1f "0-sprite.png")

Create  `0-styles.css`  and generate this layout:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/94aa60f76c412f40a87b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220606%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220606T041232Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e0191bf6f2e3774a8d2d930f23f5391bf3491e9c31f5aa01a089993bb7754ad5)

You are not allowed to change the image and the HTML -  _sprite is cool!_

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `0-styles.css`


### 1. Move the (under)line

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 1- Underline</title>

        <link href="1-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <h2>
            Hello <a href="https://www.holbertonschool.com">Holberton!</a>
        </h2>
    </body>
</html>

```

Create  `1-styles.css`  and generate this layout where the underline is hidden by default and appeared slowly…:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/b791cfdbd11c0eefa5f7.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220606%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220606T041232Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2116961d12afdef1d53055cf6815fdb071aab2f9ff48fff48e8032aa0b751a76)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `1-styles.css`


### 2. Toggle

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link href="2-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="toggle">
            <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
            <label class="toggle-label" for="toggle-0">
                <div class="toggle-inner"></div>
                <div class="toggle-switch"></div>
            </label>
        </div>
    </body>
</html>

```

Create  `2-styles.css`  and generate this layout where the  `<input>`  is has this custom toggle layout:

**Checked:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/3848b025c8f25636bba5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220606%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220606T041232Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=62177734689f6b114dbb0993d292b0b2a6c07591f77ab3792bdcd30498b84364)

**Unchecked:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/aeae59fdee93b17f360f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220606%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220606T041232Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b05de9a7855e5bdfe04e0651ecd226122e7faa1c759a09a788a880eb17c1a64f)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `2-styles.css`


### 3. Menu

#advanced

By using this HTML:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>HBTN - 2- toggle</title>

        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
        <link href="3-styles.css" media="all" rel="stylesheet" type="text/css">
    </head>
    <body>

        <nav class="menu">
            <input type="checkbox" href="#" class="menu-open" name="menu-open" id="menu-open"/>
            <label class="menu-open-button" for="menu-open">
                <span class="menu-line menu-line-1"></span>
                <span class="menu-line menu-line-2"></span>
                <span class="menu-line menu-line-3"></span>
            </label>

            <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-bar-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-line-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-pie-chart"></i> </a>
            <a href="#" class="menu-item"> <i class="fa fa-table"></i> </a>
        </nav>

    </body>
</html>

```

Create  `3-styles.css`  and generate this layout/animation:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/252a25667dc7c65fe0e9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220606%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220606T041232Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0b467784041e63150deb663914c974ce9c6f10226ae3f15a5f01a5788a68fdc5)

You are not allowed to change the HTML

**Repo:**

-   GitHub repository:  `Fun-with-CSS`
-   File:  `3-styles.css`
