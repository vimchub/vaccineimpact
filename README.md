![VIMC logo](img/logo/VIMC_landscape_logo_transparent.png)

Development on server 104.236.120.87 `bundle exec jekyll serve -H 0.0.0.0`

r the website itself, go to: http://www.repidemicsconsortium.org

Please address requests via email to Thibaut Jombart ([thibautjombart@gmail.com](thibautjombart@gmail.com)).

# Instructions for editing the website

## Editing the existing pages


## Editing the navigation menu


## Editing the footer

## How to edit the style of the website

The general layout of the pages can't be changed easily.  But things like colour, spacing, fonts, and any other CSS style can easily be changed by adding CSS rules to the [`vimc.css`](./css/vimc.css) file. For example, you can change the size of the text, or the background colour of the navigation bar, or the colour of the text in the footer.

Note that the template was designed in a way such that it changes drastically when you view it on a big screen (laptop) vs a small screen (phone)

## How to add new pages

To add a new page at the URL `http://vimchub.github.io/example`:

- Add a file named `example.md` to the root directory of this repo
- The file **must** begin with two lines of three dashes (aka YAML front matter) in order for this new page to use the template. In other words, each file must begin with the following two lines

    ```
    ---
    ---
    ```
- You can write either in markdown or in pure HTML
- If you want to add images, I suggest you place all the images inside the [`img`](./img) folder and refer to images from there.
- In between the YAML front matter (between the two lines of dashes), you can specify a few parameters:
  - `title`: Gives a nice big title to the page
  - `subtitle`: A subtitle to the page
  - `bigimg`: The path to an image that will be used as a big wide "header image". This path has to point to a local file in this repository, it cannot point to an image on the web

## How to add new blog posts (aka news)

The pages described above should be added in the root directory. But any page you create inside the `_posts` folder will be treated as a blog post. The nice thing about blog post-type pages is that they will automatically be shown chronologically at `https://vimchub.github.io/blog/`, with all the pagination to previous/next posts taken care of.

Posts are created in exactly the same way as regular pages: you still need to make them `.md` file, they have to have YAML front matter, they can support the `title`/`subtitle`/`bigimg` parameters, you can add lists into them, etc. The only difference is that the name of the file must begin with the date of the post. For example, `2016-08-20-some-news.md`. It's vital that the name of each post contain the date in such a format, followed by whatever name you want, followed by `.md`.
