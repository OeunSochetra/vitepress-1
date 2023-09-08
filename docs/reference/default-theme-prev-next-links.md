# Prev Next Links

You can customize the text and link for the previous and next pages (shown in the doc footer). This is helpful if you want a different text there than what you have on your sidebar. You may also find it useful to disable the footer or link to a page not included in your sidebar.

## prev

- Type: `string | false | { text?: string; link?: string }`

- Details:

  Specifies the text/link to show on the link to the previous page. The text/link will be inferred from the sidebar config if you don't set this in frontmatter.

- Examples:

  - To customize only the text:

    ```yaml
    ---
    prev: 'Get Started | Markdown'
    ---
    ```

  - To customize both text and link:

    ```yaml
    ---
    prev:
      text: 'Markdown'
      link: '/guide/markdown'
    ---
    ```

  - To hide the previous page:

    ```yaml
    ---
    prev: false
    ---
    ```

## next

Same as `prev` but for the next page.
