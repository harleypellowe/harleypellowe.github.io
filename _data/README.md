## Creating a new project
1. In **_posts** create a new folder with the title of the project.
1. In the project folder create files for each part.
1. In the front matter of Part 1:
    * Add `start_here: true`.
    * Add a brief `description` of the project. This will appear on the project list page.
    * (Optional) Add `top_image` (a link to an image that will appear in the project list).
1. In each part, set `permalink` to this format: `/projects/<project_name>/part-<num>`.
1. Each part should also have a `title` and `subtitle`.
1. Set `published: false` on all parts until the project is ready to launch.
    * View these in local mode by adding `--unpublished` property to `jekyll serve`.